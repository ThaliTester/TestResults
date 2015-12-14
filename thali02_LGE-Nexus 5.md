#### Test 5065027870036d7_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
V/JNIHelp ( 3257): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3257): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3257): Installed default security provider GmsCore_OpenSSL
--------- beginning of system
W/libprocessgroup(  759): failed to open /acct/uid_10038/pid_2060/cgroup.procs: No such file or directory
V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CAR.SERVICE( 3136): mConnectedToCar = false, abort
E/ActivityThread( 3136): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@33e81c20 that was originally bound here
E/ActivityThread( 3136): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@33e81c20 that was originally bound here
E/ActivityThread( 3136): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3136): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3136): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3136): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3136): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3136): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3136): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3136): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3136): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3136): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3136): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3136): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3136): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3136): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3136): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3136): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3136): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3136): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3136): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3136): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3136): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3136): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3136): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 3136): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@35f44f9b that was originally bound here
E/ActivityThread( 3136): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@35f44f9b that was originally bound here
E/ActivityThread( 3136): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3136): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3136): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3136): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3136): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3136): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3136): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3136): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3136): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3136): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3136): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3136): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3136): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3136): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3136): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3136): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3136): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3136): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3136): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3136): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3136): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3136): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  759): Unbind failed: could not find connection for android.os.BinderProxy@b059c07
I/Icing   ( 1628): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1628): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1628): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1628): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3311): 
D/AndroidRuntime( 3311): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3311): CheckJNI is OFF
I/ActivityManager(  759): Killing 2614:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
D/AndroidRuntime( 3311): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  759): failed to open /acct/uid_10069/pid_2614/cgroup.procs: No such file or directory
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3325 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3311): Shutting down VM
V/ActivityManager(  759): Display changed displayId=0
I/WebViewFactory( 3325): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3325): Time to load native libraries: 1 ms (timestamps 9634-9635)
I/LibraryLoader( 3325): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3325): Binding Chromium to main looper Looper (main, tid 1) {107dcfdb}
I/LibraryLoader( 3325): Expected native library version number "",actual native library version number ""
I/chromium( 3325): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3325): Initializing chromium process, singleProcess=true
W/art     ( 3325): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3325): ApplicationContext is null in ApplicationStatus
W/chromium( 3325): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3325): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3325): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3325): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  759): Message: 20
,D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@370e7fb8:true
,W/art     ( 3325): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3325): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3325): CordovaWebView is running on device made by: LGE
,W/art     ( 3325): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3325): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3325): Render dirty regions requested: true
,D/Atlas   ( 3325): Validating map...
,W/chromium( 3325): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3325): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3325): Enabling debug mode 0
,I/Keyboard.Facilitator( 1103): onFinishInput()
,W/BindingManager( 3325): Cannot call determinedVisibility() - never saw a connection for the pid: 3325
,W/IInputConnectionWrapper( 3325): showStatusIcon on inactive InputConnection
,I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +402ms (total +57s769ms)
,D/JsMessageQueue( 3325): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3325): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1405526272
D/JX-Cordova( 3325): jxcore cordova android initializing
,W/jxcore-log( 3325): Initializing JXcore engine
W/jxcore-log( 3325): JXcore engine is ready
,W/jxcore-log( 3325): Starting JXcore engine
,W/.test.thalitest( 3325): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8303]" dev="sockfs" ino=8303 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3325): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3325): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8459]" dev="sockfs" ino=8459 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3325): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19157]" dev="sockfs" ino=19157 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3325): Platform android
W/jxcore-log( 3325): 
W/jxcore-log( 3325): Process ARCH arm
W/jxcore-log( 3325): 
,I/jxcore-log( 3325): JXcore Cordova bridge is ready!
I/jxcore-log( 3325): 
,W/jxcore-log( 3325): JXcore engine is started
I/Choreographer( 3325): Skipped 108 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3325): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3325): Toggling radios to true
I/jxcore-log( 3325): 
,D/BluetoothAdapter( 3325): enable(): BT is already enabled..!
,D/WifiService(  759): New client listening to asynchronous messages
D/WifiService(  759): setWifiEnabled: true pid=3325, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3325): Radios toggled
I/jxcore-log( 3325): 
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3325): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Perf Test app loaded loaded
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): check test folder
I/jxcore-log( 3325): 
I/wpa_supplicant(  984): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
I/jxcore-log( 3325): found test : ./testFindPeers.js
I/jxcore-log( 3325): 
,E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  759): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/jxcore-log( 3325): found test : ./testSendData.js
I/jxcore-log( 3325): 
,V/NativeCrypto( 1601): Read error: ssl=0xb4028e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1601): SSL shutdown failed: ssl=0xb4028e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): ValidatedState{ when=-6ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-6ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  759): Start Disconnecting Watchdog 1
I/wpa_supplicant(  984): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  759): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524292
D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Disconnected - quitting
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1271): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/Choreographer( 3325): Skipped 64 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3325): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityManager.CallbackHandler( 1628): CM callback handler got msg 524292
,I/wpa_supplicant(  984): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  984): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  984): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  984): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  759): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  179): Setting iface cfg
E/WifiStateMachine(  759): Start Dhcp Watchdog 2
,E/native  (  759): do suspend false
,E/WifiStateMachine(  759): scanCount==0 - aborting
,I/dhcpcd  ( 3410): version 5.5.6 starting
,E/dhcpcd  ( 3410): get_duid: Read-only file system
,I/dhcpcd  ( 3410): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2785): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1628): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1628): onCreate
,D/SystemUpdateService( 1628): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1628): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1628): num queued entries: 0
,I/iu.UploadsManager( 1628): num updated entries: 0
I/iu.SyncManager( 1628): NEXT; no task
,I/SystemUpdateService( 1628): active receiver: enabled
I/Babel   ( 1922): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1628): showing system update notification
,I/ActivityManager(  759): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3432 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  759): No APN found to select.
,E/GpsLocationProvider(  759): No APN found to select.
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1628): retry (wakeup: false) in 3599953 ms
,D/SystemUpdateService( 1628): onDestroy
,I/GAv4    ( 3432): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3432):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3432):   adb logcat -s GAv4
,W/GAv4    ( 3432): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3432): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3432): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3432): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3432): Time to load native libraries: 1 ms (timestamps 6523-6524)
I/LibraryLoader( 3432): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3432): Binding Chromium to main looper Looper (main, tid 1) {a678a7f}
,I/LibraryLoader( 3432): Expected native library version number "",actual native library version number ""
,I/chromium( 3432): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3432): Initializing chromium process, singleProcess=true
,W/art     ( 3432): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3432): ApplicationContext is null in ApplicationStatus
,W/chromium( 3432): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3432): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3432): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3432): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/dhcpcd  ( 3410): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,W/AudioManagerAndroid( 3432): Requires BLUETOOTH permission
,I/NSApplication( 3432): Starting up...
,I/dhcpcd  ( 3410): wlan0: leased 192.168.1.114 for 86400 seconds
,I/ActivityManager(  759): Killing 2569:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_2569/cgroup.procs: No such file or directory
,V/MusicLeanback( 2785): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1628): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1628): onCreate
,D/SystemUpdateService( 1628): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1628): active receiver: enabled
,I/SystemUpdateService( 1628): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1628): retry (wakeup: false) in 3599973 ms
,D/SystemUpdateService( 1628): onDestroy
,E/native  (  759): do suspend true
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiStateMachine(  759): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  759): Adding iface wlan0 to network 101
,E/ConnectivityService(  759): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  759): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  759): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  759): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1628): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 14 Dec 2015 21:16:23 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450127783198], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450127783179]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Validated
,D/ConnectivityService(  759): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1271): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1628): CM callback handler got msg 524290
,W/NetworkUtils( 1408): OkHttp exception
,W/EventLoggerService( 1408): Unable to send logs Error code: 262146
,I/jxcore-log( 3325): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3325): 
,D/ConnectivityService(  759): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2785): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2785): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1628): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1628): onCreate
,D/SystemUpdateService( 1628): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1628): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1628): num queued entries: 0
,I/iu.UploadsManager( 1628): num updated entries: 0
I/iu.SyncManager( 1628): NEXT; no task
,I/SystemUpdateService( 1628): active receiver: enabled
,I/SystemUpdateService( 1628): showing system update notification
,W/ResourcesManager( 3257): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3257): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1628): retry (wakeup: false) in 3599977 ms
,D/SystemUpdateService( 1628): onDestroy
,E/GpsLocationProvider(  759): No APN found to select.
,E/ActivityThread( 1628): Failed to find provider info for com.android.contacts.metadata
,I/art     (  759): Explicit concurrent mark sweep GC freed 43603(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.004ms total 55.736ms
,D/SyncManager(  759): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 70164, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  759): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 122344, reason: UserStart
,I/Babel   ( 1922): connection state changed from DISCONNECTED to CONNECTED
,D/Finsky  ( 2648): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2648): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1601): Vacuum at: now=1450127799469 tag=VacuumService
,I/PhenotypeConfigurator( 1601): Scheduling Phenotype for one-off execution 11525 seconds from now (1450127799723)
,D/GetConfigurationSnapshotOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1601): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1601): Using platform SSLCertificateSocketFactory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1103): run()
I/Keyboard.Facilitator( 1103): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1601): disconnect managed GoogleApiClient
,I/jxcore-log( 3325): Connected to the server!
I/jxcore-log( 3325): 
,I/chromium( 3325): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3325): --- start :testFindPeers.js---
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): testFindPeers created [object Object]
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): serverPort is 8876
I/jxcore-log( 3325): 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT4198
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3325): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): setState: INITIALIZED
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3325): start: OK
I/jxcore-log( 3325): StartBroadcasting started ok
I/jxcore-log( 3325): 
I/chromium( 3325): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 3325): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 3325): onConnectionManagerStateChanged: RUNNING
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3325): Ignored { when=-10ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT7626"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT7626 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT7626"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 34:FC:EF:11:B1:66, peer name: LGE-Nexus 5_PT7626, peer ID: 34:FC:EF:11:B1:66, Wi-Fi Direct device name: Android_2dc2, Wi-Fi Direct address: 52:55:27:f0:ff:f0
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:11:B1:66
I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:B1:66","peerName":"LGE-Nexus 5_PT7626","peerAvailable":true}]
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): Found peer : 34:FC:EF:11:B1:66, peerAvailable: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): weAreDoneNow
I/jxcore-log( 3325): 
I/jxcore-log( 3325): done, now sending data to server
I/jxcore-log( 3325): 
,W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT7626"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT7626"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT7626"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT7626"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT9882 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT9882, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: Thali Test's G2, Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:9D:93:0B
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3325): Ignored { when=-11ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7395","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7395 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7395","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7395","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7395","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7395","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT7395, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 3325): --- start :testFindPeers.js---
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): testFindPeers created [object Object]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): serverPort is 8876
I/jxcore-log( 3325): 
I/jxcore-log( 3325): weAreDoneNow
I/jxcore-log( 3325): 
I/jxcore-log( 3325): done, now sending data to server
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): done, now sending data to server
I/jxcore-log( 3325): 
,I/chromium( 3325): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3325): teardown
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): testFindPeers stopped
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): setState: NOT_INITIALIZED
I/jxcore-log( 3325): StopBroadcasting went ok
I/jxcore-log( 3325): 
I/chromium( 3325): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3325): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 3325): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/jxcore-log( 3325): --- start :testSendData.js---
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":23}bt-address length : 0
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): daya100000
I/jxcore-log( 3325): 
I/jxcore-log( 3325): check server
I/jxcore-log( 3325): 
I/jxcore-log( 3325): serverPort is 38748
I/jxcore-log( 3325): 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT4198
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3325): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): setState: INITIALIZED
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): setState: RUNNING
I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:B1:66","peerName":"LGE-Nexus 5_PT7626","peerAvailable":true},{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"LGE-LG-D802_PT9882","peerAvailable":true},{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT7395","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : LGE-Nexus 5_PT7626, Available: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : LGE-LG-D802_PT9882, Available: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : samsung-SM-A500FU_PT7395, Available: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
I/jxcore-log( 3325): device[1]: 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:15.811Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:15.811Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:22:15.811Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
,I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: Android_2dc2
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
I/io.jxcore.node.ConnectionHelper( 3325): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 314)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): Waiting for incoming connections...
,I/jxcore-log( 3325): StartBroadcasting started ok
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): null
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:22:15.828Z SendDataTCPServer.js: TCP/IP server is bound to port: 38748
I/jxcore-log( 3325): 
,I/chromium( 3325): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 3325): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 3325): onConnectionManagerStateChanged: RUNNING
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
,E/bt-btif ( 2086): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2086): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 2086): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT7626 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 314)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 315)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 314)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 315)
,I/BluetoothBondStateMachine( 2086): StableState(): Entering Off State
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 77 bytes successfully (thread ID: 315)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [34:FC:EF:11:B1:66 LGE-Nexus 5_PT7626 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT7626 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 315)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT7626 34:FC:EF:11:B1:66]
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: 34:FC:EF:11:B1:66, name: LGE-Nexus 5_PT7626, Bluetooth address: 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:11:B1:66 already in the list
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID 34:FC:EF:11:B1:66, created successfully
D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 316)
,D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 54066
I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,W/bt-btif ( 2086): invalid rfc slot id: 6
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 54066 (peer ID: 34:FC:EF:11:B1:66)
I/jxcore-log( 3325): 2015-12-14T21:22:17.887Z SendDataConnector.js: CLIENT connected to 54066, error: null
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:22:17.887Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:22:17.894Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 54066
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 316)
I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 317, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 318, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 318, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3325): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:11:B1:66 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:B1:66
I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 318
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 317
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 317, thread name: Sender): Socket closed
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 318, name: Receiver)
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:11:B1:66 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 317, name: Sender)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e2a887c:true
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Nexus 5
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3325): Ignored { when=-10ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3325): Ignored { when=-10ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/jxcore-log( 3325): 2015-12-14T21:22:28.326Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:28.327Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:22:28.334Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:28.334Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:28.336Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT452"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT452"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT452"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT452"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT452, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"HTC-HTC Desire 820_PT452","peerAvailable":true}]
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): Found peer : HTC-HTC Desire 820_PT452, Available: true
I/jxcore-log( 3325): 
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 3325): teardown
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): testSendData stopped
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): setState: NOT_INITIALIZED
,I/jxcore-log( 3325): StopBroadcasting went ok
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:22:32.250Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:32.250Z SendDataConnector.js: Stop retry timer
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:32.250Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:32.250Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
,I/jxcore-log( 3325): 2015-12-14T21:22:32.252Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:22:32.254Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3325): 
I/chromium( 3325): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 3325): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 3325): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/jxcore-log( 3325): --- start :testSendData.js---
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":23}bt-address length : 0
I/jxcore-log( 3325): 
I/jxcore-log( 3325): daya100000
I/jxcore-log( 3325): 
I/jxcore-log( 3325): check server
I/jxcore-log( 3325): 
I/jxcore-log( 3325): serverPort is 59068
I/jxcore-log( 3325): 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT4198
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3325): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): setState: INITIALIZED
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): setState: RUNNING
,I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:B1:66","peerName":"LGE-Nexus 5_PT7626","peerAvailable":true},{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"LGE-LG-D802_PT9882","peerAvailable":true},{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT7395","peerAvailable":true},{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"HTC-HTC Desire 820_PT452","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : LGE-Nexus 5_PT7626, Available: true
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): Found peer : LGE-LG-D802_PT9882, Available: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : samsung-SM-A500FU_PT7395, Available: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : HTC-HTC Desire 820_PT452, Available: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
I/jxcore-log( 3325): device[1]: 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:32.279Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:22:32.280Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:32.280Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: Android_2dc2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
I/io.jxcore.node.ConnectionHelper( 3325): start: OK
I/jxcore-log( 3325): StartBroadcasting started ok
I/jxcore-log( 3325): 
I/jxcore-log( 3325): null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:32.283Z SendDataTCPServer.js: TCP/IP server is bound to port: 59068
I/jxcore-log( 3325): 
I/chromium( 3325): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 3325): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 3325): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 320)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): Waiting for incoming connections...
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 8
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 9
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 320)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 320)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 10
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 11
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 320)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 320)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 12
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 13
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 320)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 320)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 14
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 15
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 320)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 320)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 16
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 17
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 320)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Maximum number of retries (5) reached, giving up... (thread ID: 320)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 320)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 LGE-Nexus 5_PT7626 34:FC:EF:11:B1:66]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
I/jxcore-log( 3325): 2015-12-14T21:22:40.593Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:40.593Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:40.594Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 3 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3325): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Nexus 5
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/jxcore-log( 3325): 2015-12-14T21:22:45.596Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:22:45.605Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
,I/jxcore-log( 3325): 2015-12-14T21:22:50.613Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:22:50.614Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:50.614Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:50.615Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: Android_2dc2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 321)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 18
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 19
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 321)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 321)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 20
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 21
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 321)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 321)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 22
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 23
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 321)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 321)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 24
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 25
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 321)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 321)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 26
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 27
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 321)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Maximum number of retries (5) reached, giving up... (thread ID: 321)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 321)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 LGE-Nexus 5_PT7626 34:FC:EF:11:B1:66]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
I/jxcore-log( 3325): 2015-12-14T21:22:57.991Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:57.992Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:22:57.993Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3325): 2015-12-14T21:23:02.994Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:23:02.994Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
,I/jxcore-log( 3325): 2015-12-14T21:23:08.003Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:08.003Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:08.004Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:08.004Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: Android_2dc2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 28
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 29
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 322)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 30
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 31
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 32
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 33
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 34
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 35
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 322)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 36
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 37
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Maximum number of retries (5) reached, giving up... (thread ID: 322)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 322)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 LGE-Nexus 5_PT7626 34:FC:EF:11:B1:66]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
I/jxcore-log( 3325): 2015-12-14T21:23:11.245Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:11.245Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:11.246Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3325): 2015-12-14T21:23:16.248Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:16.248Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3325): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:23:21.253Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:21.253Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:21.254Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:21.254Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: Android_2dc2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 323)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 38
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 39
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 323)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 323)
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 40
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 41
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 42
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 43
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 44
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 45
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 323)
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 46
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 47
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 323)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Maximum number of retries (5) reached, giving up... (thread ID: 323)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 323)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 LGE-Nexus 5_PT7626 34:FC:EF:11:B1:66]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
,I/jxcore-log( 3325): 2015-12-14T21:23:24.009Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:23:24.016Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:24.016Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3325): 2015-12-14T21:23:29.019Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:29.020Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:23:34.025Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:34.026Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:34.027Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:34.027Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
,I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: Android_2dc2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 324)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 48
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 49
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 50
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 51
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 52
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 53
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 54
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 55
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 56
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 57
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Maximum number of retries (5) reached, giving up... (thread ID: 324)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 324)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 LGE-Nexus 5_PT7626 34:FC:EF:11:B1:66]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
I/jxcore-log( 3325): 2015-12-14T21:23:37.581Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:37.582Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): oneRoundDownNow
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:37.585Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
,I/jxcore-log( 3325): 2015-12-14T21:23:37.596Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3325): 
I/jxcore-log( 3325): ---- round done--------
I/jxcore-log( 3325): 
I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
I/jxcore-log( 3325): device[2]: 34:FC:EF:9D:93:0B
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:37.600Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:37.601Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:37.601Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 325)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd6ebc rs_disc_pending=1
,W/bt-btif ( 2086): bta_dm_check_av:0
W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd7084 rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd7084 rs_disc_pending=0
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Nexus 5
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 2086): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2086): Entering PendingCommandState State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 2086): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2086): StableState(): Entering Off State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [34:FC:EF:9D:93:0B LGE-LG-D802_PT9882 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 325)
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 326)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 325)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 77 bytes successfully (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [34:FC:EF:9D:93:0B LGE-LG-D802_PT9882 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT9882 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 326)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT9882 34:FC:EF:9D:93:0B],
,I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: 34:FC:EF:9D:93:0B, name: LGE-LG-D802_PT9882, Bluetooth address: 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
,I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
,I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID 34:FC:EF:9D:93:0B, created successfully
D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 327)
,D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 56467
,I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 56467 (peer ID: 34:FC:EF:9D:93:0B)
I/jxcore-log( 3325): 2015-12-14T21:23:42.513Z SendDataConnector.js: CLIENT connected to 56467, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:42.513Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 56467
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 327)
,I/jxcore-log( 3325): 2015-12-14T21:23:42.543Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 328, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 329, name: Receiver)
,I/jxcore-log( 3325): 2015-12-14T21:23:44.348Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:23:44.665Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3325): 
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3325): 2015-12-14T21:23:45.205Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:23:45.523Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:23:46.067Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:23:46.283Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:23:46.901Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:23:47.265Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:23:47.777Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:23:48.092Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:48.093Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3325): 
I/jxcore-log( 3325): oneRoundDownNow
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:48.094Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:48.095Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:9D:93:0B
,I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 329
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 328
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 328, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:9D:93:0B disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 329, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:9D:93:0B disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:9D:93:0B
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 329, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 328, name: Sender)
,I/jxcore-log( 3325): 2015-12-14T21:23:48.154Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3325): 
I/jxcore-log( 3325): ---- round done--------
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
I/jxcore-log( 3325): device[3]: 7C:F9:0E:51:18:22
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:48.156Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:23:48.156Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:48.156Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 330)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd7084 rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd7084 rs_disc_pending=0
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2086): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2086): Entering PendingCommandState State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2086): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2086): StableState(): Entering Off State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7395 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 330)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 331)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 330),
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 331)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 83 bytes successfully (thread ID: 331)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7395 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7395 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7395 7C:F9:0E:51:18:22]
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT7395, Bluetooth address: 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:51:18:22, created successfully
D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 331)
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 332)
,D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 53028
I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 53028 (peer ID: 7C:F9:0E:51:18:22)
,I/jxcore-log( 3325): 2015-12-14T21:23:53.762Z SendDataConnector.js: CLIENT connected to 53028, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:53.763Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 53028
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 332)
,I/jxcore-log( 3325): 2015-12-14T21:23:53.784Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 333, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 334, name: Receiver)
,D/        ( 2086): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,D/        ( 2086): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11836
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd724c rs_disc_pending=0
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3325): 2015-12-14T21:23:57.834Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:23:57.836Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:23:57.838Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:23:57.843Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3325): 
I/jxcore-log( 3325): oneRoundDownNow
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:57.845Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:57.845Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 334
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 333
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 333, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 334, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 333, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 334, name: Receiver)
,I/jxcore-log( 3325): 2015-12-14T21:23:57.893Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3325): 
I/jxcore-log( 3325): ---- round done--------
I/jxcore-log( 3325): 
I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
I/jxcore-log( 3325): device[4]: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:57.893Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:57.893Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:23:57.893Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 335)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd724c rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd724c rs_disc_pending=0
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 60
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 61
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 335)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 335)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Connection timeout
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 62
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 63
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 335)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 335)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): cancel: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Cancelled: Connection timeout [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
,I/jxcore-log( 3325): 2015-12-14T21:24:19.474Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:24:19.475Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:24:19.476Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 335)
,I/jxcore-log( 3325): 2015-12-14T21:24:24.477Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:24:24.479Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: B4:CE:F6:AB:A4:6A), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:24:29.484Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:24:29.484Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:24:29.485Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:24:29.485Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 336)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 64
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 65
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 336)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 336)
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Connection timeout
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 66
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x8  CID 0x42
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 67
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 336)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 336)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5357 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT7658 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Cancelled: Connection timeout [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
,I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT5357, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 92:b6:86:43:73:1c
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:14:E2:C0
I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT5357","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : samsung-SM-N910C_PT5357, Available: true
I/jxcore-log( 3325): 
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT7658, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"samsung-SM-G800F_PT7658","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : samsung-SM-G800F_PT7658, Available: true
I/jxcore-log( 3325): 
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
I/jxcore-log( 3325): 2015-12-14T21:25:15.895Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:25:15.895Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:25:15.895Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 336)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 3325): 2015-12-14T21:25:20.896Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:25:20.897Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: B4:CE:F6:AB:A4:6A), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:25:25.906Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:25:25.906Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:25:25.914Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:25:25.915Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 337)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 68
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 69
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 337)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 337)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ActivityManager(  759): Killing 2756:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2756/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Connection timeout
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x8  CID 0x44
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 70
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
E/bt-btif ( 2086): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2086): Entering PendingCommandState State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 2086): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2086): StableState(): Entering Off State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using system decided port, total number of attempts: 2 (thread ID: 337)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 337)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8913 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT8658 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5394 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Cancelled: Connection timeout [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT8913, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:85:54
,I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT8913","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : LGE-LG-D722_PT8913, Available: true
I/jxcore-log( 3325): 
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT8658, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: , Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"motorola-XT1039_PT8658","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : motorola-XT1039_PT8658, Available: true
I/jxcore-log( 3325): 
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT5394, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:6f:c9:5d
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:3C:51
,I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT5394","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : LGE-LG-H815_PT5394, Available: true
I/jxcore-log( 3325): 
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/jxcore-log( 3325): 2015-12-14T21:26:11.967Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:26:11.967Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:26:11.967Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd7414 rs_disc_pending=0
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: HTC Desire 820
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3325): 2015-12-14T21:26:16.972Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:26:16.973Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3325): Ignored { when=-8ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: B4:CE:F6:AB:A4:6A), either no such connection or failed to close the connection
,I/jxcore-log( 3325): 2015-12-14T21:26:21.990Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:26:21.991Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:26:21.992Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:26:21.993Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: HTC Desire 820 B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 338)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT7658 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT7658, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x1f  CID 0x49
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 72
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,W/bt-btif ( 2086): invalid rfc slot id: 73
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 338)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 338)
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using port (1), total number of attempts: 2 (thread ID: 338)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 339)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 339)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 338)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 339)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 83 bytes successfully (thread ID: 339)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 339)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: B4:CE:F6:AB:A4:6A, name: HTC-HTC Desire 820_PT452, Bluetooth address: B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
,I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
,I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID B4:CE:F6:AB:A4:6A, created successfully
D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 340)
D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 33763
I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 33763 (peer ID: B4:CE:F6:AB:A4:6A)
I/jxcore-log( 3325): 2015-12-14T21:26:30.187Z SendDataConnector.js: CLIENT connected to 33763, error: null
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:26:30.187Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 33763
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 340)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 342, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 341, name: Sender)
,I/jxcore-log( 3325): 2015-12-14T21:26:30.230Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:26:31.440Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:26:32.139Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:26:32.345Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:26:32.732Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:26:33.292Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:26:33.431Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:26:34.046Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:26:34.847Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3325): 
,W/bt-btif ( 2086): dm_pm_timer expires
W/bt-btif ( 2086): dm_pm_timer expires 0
,W/bt-btif ( 2086): proc dm_pm_timer expires
,I/jxcore-log( 3325): 2015-12-14T21:26:44.849Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:26:44.850Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:26:44.852Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:26:44.871Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:26:44.873Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3325): 
,E/io.jxcore.node.StreamCopyingThread( 3325): Input stream got -1 on read (thread ID: 341, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 3325): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID B4:CE:F6:AB:A4:6A disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 342
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 341
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 342, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID B4:CE:F6:AB:A4:6A disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 342, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 341, name: Sender)
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3325): 2015-12-14T21:26:49.872Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:26:49.873Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: B4:CE:F6:AB:A4:6A), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:26:54.874Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:26:54.874Z SendDataConnector.js: Connect (retry count 4) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:26:54.875Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:26:54.875Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: HTC Desire 820 B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 343)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0xd  CID 0x4d
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 75
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback,
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 343)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 343)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 344)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 83 bytes successfully (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: B4:CE:F6:AB:A4:6A, name: HTC-HTC Desire 820_PT452, Bluetooth address: B4:CE:F6:AB:A4:6A
,D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
,I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID B4:CE:F6:AB:A4:6A, created successfully
,D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 344)
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 345)
,D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 45729
I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 45729 (peer ID: B4:CE:F6:AB:A4:6A)
I/jxcore-log( 3325): 2015-12-14T21:27:01.853Z SendDataConnector.js: CLIENT connected to 45729, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:01.853Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 45729
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 345)
,I/jxcore-log( 3325): 2015-12-14T21:27:01.857Z SendDataConnector.js: CLIENT now sending 20000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 347, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 346, name: Sender)
,I/jxcore-log( 3325): 2015-12-14T21:27:02.304Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:27:02.499Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:02.500Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3325): 
I/jxcore-log( 3325): oneRoundDownNow
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:02.502Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:02.502Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 347
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 346
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 346, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID B4:CE:F6:AB:A4:6A disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 347, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID B4:CE:F6:AB:A4:6A disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Successfully disconnected (peer ID: B4:CE:F6:AB:A4:6A
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 346, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 347, name: Receiver)
,I/jxcore-log( 3325): 2015-12-14T21:27:02.552Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3325): 
I/jxcore-log( 3325): ---- round done--------
I/jxcore-log( 3325): 
I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
I/jxcore-log( 3325): device[5]: E0:DB:10:14:E2:C0
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:02.553Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:02.553Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:02.553Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 348)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2086): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2086): Entering PendingCommandState State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2086): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2086): StableState(): Entering Off State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5357 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 348)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 349)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 348)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 349)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 82 bytes successfully (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5357 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5357 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 349)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5357 E0:DB:10:14:E2:C0]
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: E0:DB:10:14:E2:C0, name: samsung-SM-N910C_PT5357, Bluetooth address: E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID E0:DB:10:14:E2:C0, created successfully
D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 350)
D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 46659
I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 46659 (peer ID: E0:DB:10:14:E2:C0)
I/jxcore-log( 3325): 2015-12-14T21:27:04.773Z SendDataConnector.js: CLIENT connected to 46659, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:04.773Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:27:04.775Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 46659
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 350)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 352, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 351, name: Sender)
,I/jxcore-log( 3325): 2015-12-14T21:27:05.749Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:27:06.586Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:27:06.987Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3325): 
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3325): 2015-12-14T21:27:07.278Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:27:07.569Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:27:07.662Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:27:07.903Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:27:08.050Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:27:08.331Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:27:08.539Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:08.539Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): oneRoundDownNow
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:08.541Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:08.541Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 352
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 351
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 351, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID E0:DB:10:14:E2:C0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 352, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID E0:DB:10:14:E2:C0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 352, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 351, name: Sender)
,I/jxcore-log( 3325): 2015-12-14T21:27:08.593Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3325): 
I/jxcore-log( 3325): ---- round done--------
I/jxcore-log( 3325): 
I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): device[6]: 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:08.597Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:08.597Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:27:08.605Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
,I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: S5mini-1
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 353)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd75dc rs_disc_pending=0
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x43
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 78
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 79
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 353)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 353)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x44
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 80
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x45
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 81
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 353)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 353)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x47
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 82
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Connection timeout
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x46
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 83
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 353)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 353)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Cancelled: Connection timeout [00:F4:6F:30:E0:6C samsung-SM-G800F_PT7658 00:F4:6F:30:E0:6C]
,I/jxcore-log( 3325): 2015-12-14T21:27:24.663Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:24.664Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:24.666Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 353)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3309","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3309 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT3309, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: Note3-1, Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:1F:C9:5E
I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"samsung-SM-N9005_PT3309","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : samsung-SM-N9005_PT3309, Available: true
I/jxcore-log( 3325): 
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3309","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3309","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3309","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT2105 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT2105, peer ID: 44:80:EB:7B:5A:05, Wi-Fi Direct device name: XT1072_23d5, Wi-Fi Direct address: 44:80:eb:7b:5a:07
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID 44:80:EB:7B:5A:05
,I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"motorola-XT1072_PT2105","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : motorola-XT1072_PT2105, Available: true
I/jxcore-log( 3325): 
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 3325): 2015-12-14T21:27:29.667Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:29.668Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3309","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3309 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3309","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3309","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3309","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT3309, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: Note3-1, Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5394 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT5394, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:27:34.673Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:34.674Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:34.675Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:34.675Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: S5mini-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 354)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x48
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 84
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x49
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 85
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 354)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 354)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x4a
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:86, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 86
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x4c
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:87, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 87
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 354)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 354)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x4b
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:88, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 88
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x4d
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 89
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 354)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 354)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x4e
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:90, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 90
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x4f
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 91
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 354)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 354)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x40
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:92, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 92
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Connection timeout
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:93, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 93
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 354)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Maximum number of retries (5) reached, giving up... (thread ID: 354)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 354)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Cancelled: Connection timeout [00:F4:6F:30:E0:6C samsung-SM-G800F_PT7658 00:F4:6F:30:E0:6C]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C samsung-SM-G800F_PT7658 00:F4:6F:30:E0:6C]
,I/jxcore-log( 3325): 2015-12-14T21:27:54.497Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:54.498Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:54.499Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT9882 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT9882, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: , Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7209 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT7209, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: , Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID 80:01:84:8A:B3:68
I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"HTC-HTC Desire 820_PT7209","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : HTC-HTC Desire 820_PT7209, Available: true
I/jxcore-log( 3325): 
,W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3325): 2015-12-14T21:27:59.500Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:27:59.501Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7395","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7395 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7395","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7395","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7395","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT7395, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
,W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5995","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5995 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5995","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5995","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5995","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 7C:F9:0E:34:8A:A0, peer name: samsung-SM-G900F_PT5995, peer ID: 7C:F9:0E:34:8A:A0, Wi-Fi Direct device name: S5-1, Wi-Fi Direct address: ee:1f:72:63:11:86
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:34:8A:A0
I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT5995","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : samsung-SM-G900F_PT5995, Available: true
I/jxcore-log( 3325): 
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:28:04.506Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:28:04.507Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:28:04.507Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:28:04.512Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
,I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: S5mini-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 355)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:94, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 94
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x41
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:95, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 95
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 355)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 355)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x44
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:96, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 96
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x45
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:97, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 97
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 355)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Cancelled: Connection timeout [00:F4:6F:30:E0:6C samsung-SM-G800F_PT7658 00:F4:6F:30:E0:6C]
,I/jxcore-log( 3325): 2015-12-14T21:28:19.534Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:28:19.535Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:28:19.535Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 355)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3325): 2015-12-14T21:28:24.537Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:28:24.539Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:28:29.545Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:28:29.546Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:28:29.547Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:28:29.547Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
,I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
,D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: S5mini-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 356)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:98, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 98
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x46
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:99, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 99
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 356)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 356)
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8378","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT8378 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT8378, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: A5-1, Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:37:96:AB
I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT8378","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : samsung-SM-A500FU_PT8378, Available: true
I/jxcore-log( 3325): 
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Connection timeout
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x22  CID 0x48
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:100, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 100
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:101, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 101
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 356)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 356)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT7658 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Cancelled: Connection timeout [00:F4:6F:30:E0:6C samsung-SM-G800F_PT7658 00:F4:6F:30:E0:6C]
,I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT7658, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
I/jxcore-log( 3325): 2015-12-14T21:29:16.616Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:29:16.617Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:29:16.623Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 356)
,I/jxcore-log( 3325): 2015-12-14T21:29:21.649Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:29:21.649Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:29:26.653Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:29:26.654Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:29:26.655Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:29:26.655Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: S5mini-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 357)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2086): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2086): Entering PendingCommandState State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2086): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2086): StableState(): Entering Off State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:255
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): Incoming connection initialized (thread ID: 358)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 358)
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:102, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 102
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd796c rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:104, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 104
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 357)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 357)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd796c rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Connection timeout
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x43
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:105, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 105
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd796c rs_disc_pending=1
,W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x46
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:106, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 106
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 357)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 357)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Cancelled: Connection timeout [00:F4:6F:30:E0:6C samsung-SM-G800F_PT7658 00:F4:6F:30:E0:6C]
,I/jxcore-log( 3325): 2015-12-14T21:29:43.771Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:29:43.772Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): oneRoundDownNow
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3325): 2015-12-14T21:29:43.787Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:29:43.791Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3325): 
I/jxcore-log( 3325): ---- round done--------
I/jxcore-log( 3325): 
I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
I/jxcore-log( 3325): device[7]: F8:95:C7:87:85:54
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:29:43.794Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:29:43.794Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:29:43.795Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: G3s-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 359)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 357)
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd796c rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3325): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Connection timeout
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  759): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3811 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3811): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3811):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3811):   adb logcat -s GAv4
,W/GAv4    ( 3811): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3811): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3811): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  759): Killing 2587:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2587/cgroup.procs: No such file or directory
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED ,
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x22  CID 0x4c
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:107, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 107
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Cancelled: Connection timeout
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7395","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7395 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT61","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT61 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6801","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6801 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT9882 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Cancelled: Connection timeout [F8:95:C7:87:85:54 LGE-LG-D722_PT8913 F8:95:C7:87:85:54]
,I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT7395, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: Thali Test (Galaxy A5), Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT61, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:76:27
I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT61","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : samsung-SM-A300FU_PT61, Available: true
I/jxcore-log( 3325): 
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: B0:C5:59:3F:75:69, peer name: samsung-SM-G900F_PT6801, peer ID: B0:C5:59:3F:75:69, Wi-Fi Direct device name: , Wi-Fi Direct address: ee:1f:72:18:8b:78
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID B0:C5:59:3F:75:69
I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT6801","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : samsung-SM-G900F_PT6801, Available: true
I/jxcore-log( 3325): 
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT9882, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: , Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
I/jxcore-log( 3325): 2015-12-14T21:30:16.511Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:95:C7:87:85:54 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:30:16.511Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:95:C7:87:85:54 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:30:16.512Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd796c rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3325): 2015-12-14T21:30:21.513Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:30:21.514Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3325): 
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x10  CID 0x41
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:108, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 108
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 359)
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:85:54), either no such connection or failed to close the connection
,I/jxcore-log( 3325): 2015-12-14T21:30:26.517Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:30:26.523Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:30:26.526Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:30:26.527Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
,I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: G3s-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 360)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd796c rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x9  CID 0x40
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:109, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 109
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd796c rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3781","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3781 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT3781, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: Android_50a5, Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID F8:CF:C5:D9:E5:61
,I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"motorola-Nexus 6_PT3781","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : motorola-Nexus 6_PT3781, Available: true
I/jxcore-log( 3325): 
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:110, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 110
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 360)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 360)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd796c rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/HeadsetStateMachine( 2086): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2086): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 2086): Disconnected process message: 11, size: 0
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED ,
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Connection timeout
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2086): invalid rfc slot id: 7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Disconnected: bt socket closed, read return: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): removeThreadFromList: Removing thread with ID 358
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3325): Handshake failed (thread ID: 358)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 358)
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: A3-1
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x22  CID 0x42
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:111, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 111
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:112, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2086): invalid rfc slot id: 112
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 360)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 360)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true,
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Cancelled: Connection timeout [F8:95:C7:87:85:54 LGE-LG-D722_PT8913 F8:95:C7:87:85:54]
,W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/jxcore-log( 3325): 2015-12-14T21:31:13.913Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:95:C7:87:85:54 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:31:13.913Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:95:C7:87:85:54 failed
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:31:13.914Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 360)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/jxcore-log( 3325): 2015-12-14T21:31:18.914Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:31:18.915Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:85:54), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:31:23.921Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:31:23.922Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:31:23.922Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:31:23.923Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: G3s-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 361)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:113, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 113
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:114, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 114
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 361)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 361)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Connection timeout
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:115, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 115
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:116, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2086): invalid rfc slot id: 116
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 361)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 361)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Cancelled: Connection timeout [F8:95:C7:87:85:54 LGE-LG-D722_PT8913 F8:95:C7:87:85:54]
I/jxcore-log( 3325): 2015-12-14T21:31:44.846Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:95:C7:87:85:54 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:31:44.846Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:95:C7:87:85:54 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:31:44.847Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 361)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT452"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT452"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT452, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3325): 2015-12-14T21:31:49.847Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:31:49.849Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT8658 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT8658, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: , Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5394 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT5394, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:85:54), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:31:54.853Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:31:54.854Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:31:54.854Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:31:54.855Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: G3s-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 362)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:117, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2086): invalid rfc slot id: 117
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2086): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2086): Entering PendingCommandState State
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2086): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2086): StableState(): Entering Off State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [F8:95:C7:87:85:54 LGE-LG-D722_PT8913 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 362)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 363)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 363)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 362)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 363)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 77 bytes successfully (thread ID: 363)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT8913 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [F8:95:C7:87:85:54 LGE-LG-D722_PT8913 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT8913 F8:95:C7:87:85:54]
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: F8:95:C7:87:85:54, name: LGE-LG-D722_PT8913, Bluetooth address: F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID F8:95:C7:87:85:54, created successfully
D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 363)
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 364)
,D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 55875
I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 55875 (peer ID: F8:95:C7:87:85:54)
I/jxcore-log( 3325): 2015-12-14T21:32:02.524Z SendDataConnector.js: CLIENT connected to 55875, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:32:02.525Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 55875
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 364)
,I/jxcore-log( 3325): 2015-12-14T21:32:02.553Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 365, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 366, name: Receiver)
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2086): dm_pm_timer expires
W/bt-btif ( 2086): dm_pm_timer expires 0
,W/bt-btif ( 2086): proc dm_pm_timer expires
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3325): 2015-12-14T21:32:12.966Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:32:12.966Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:32:12.975Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:32:12.976Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:32:12.977Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3325): 
,E/io.jxcore.node.StreamCopyingThread( 3325): Input stream got -1 on read (thread ID: 365, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 3325): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:85:54 disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 366
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 365
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 366, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 366, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 365, name: Sender)
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3325): 2015-12-14T21:32:17.978Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:32:17.979Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: G3s-1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:85:54), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:32:22.979Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:32:22.979Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:32:22.979Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:32:22.980Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: G3s-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to G3s-1 in address F8:95:C7:87:85:54
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: G3s-1 F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to G3s-1 in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 367)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Connection timeout
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x8  CID 0x46
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:119, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 119
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:120, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 120
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 367)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 367)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Cancelled: Connection timeout [F8:95:C7:87:85:54 LGE-LG-D722_PT8913 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/jxcore-log( 3325): 2015-12-14T21:33:21.508Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:95:C7:87:85:54 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:21.508Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:95:C7:87:85:54 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): oneRoundDownNow
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:21.509Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:21.509Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3325): 
D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:85:54), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:33:21.509Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3325): 
I/jxcore-log( 3325): ---- round done--------
I/jxcore-log( 3325): 
I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
I/jxcore-log( 3325): device[8]: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:21.510Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:33:21.512Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:21.512Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 368)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 367)
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd7cfc rs_disc_pending=0
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 2086): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2086): Entering PendingCommandState State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 2086): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2086): StableState(): Entering Off State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT8658 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 368)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 369)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 369)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 368)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 81 bytes successfully (thread ID: 369)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT8658 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT8658 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 369)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT8658 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT8658, Bluetooth address: F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
,I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID F4:F1:E1:5C:3B:E2, created successfully
D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 370)
D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 56827
I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 56827 (peer ID: F4:F1:E1:5C:3B:E2)
I/jxcore-log( 3325): 2015-12-14T21:33:29.573Z SendDataConnector.js: CLIENT connected to 56827, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:29.574Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 56827
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 370)
,I/jxcore-log( 3325): 2015-12-14T21:33:29.600Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 372, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 371, name: Sender)
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/        ( 2086): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,D/        ( 2086): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11836
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8913 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT8913, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3325): 2015-12-14T21:33:35.062Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:33:35.136Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:33:35.158Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:33:35.285Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:35.285Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3325): 
I/jxcore-log( 3325): oneRoundDownNow
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:35.285Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:35.285Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 372
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 371
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 371, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 372, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Successfully disconnected (peer ID: F4:F1:E1:5C:3B:E2
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 371, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 372, name: Receiver)
,I/jxcore-log( 3325): 2015-12-14T21:33:35.292Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3325): 
I/jxcore-log( 3325): ---- round done--------
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
I/jxcore-log( 3325): device[9]: F8:95:C7:87:3C:51
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:35.293Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:35.293Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:35.293Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
,I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 373)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5357 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT5357, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: Note4-1, Wi-Fi Direct address: 92:b6:86:43:73:1c
,I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list,
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd7cfc rs_disc_pending=1
E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: XT1039
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2086): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2086): Entering PendingCommandState State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2086): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2086): StableState(): Entering Off State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5394 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 373)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 374)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 374)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 373)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 374)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 77 bytes successfully (thread ID: 374)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT5394 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5394 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 374)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5394 F8:95:C7:87:3C:51]
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT5394, Bluetooth address: F8:95:C7:87:3C:51
,D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
,I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID F8:95:C7:87:3C:51, created successfully
,D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 375)
D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 36261
,I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 36261 (peer ID: F8:95:C7:87:3C:51)
I/jxcore-log( 3325): 2015-12-14T21:33:47.204Z SendDataConnector.js: CLIENT connected to 36261, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:47.205Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 36261
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 375)
,I/jxcore-log( 3325): 2015-12-14T21:33:47.230Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 376, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 377, name: Receiver)
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5394 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT5394, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
,I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3325): 2015-12-14T21:33:53.582Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:33:53.640Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:33:53.687Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:33:53.692Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3325): 
I/jxcore-log( 3325): oneRoundDownNow
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:53.693Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:53.694Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 377
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 376
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 376, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:3C:51 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 377, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:3C:51 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 377, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 376, name: Sender)
,I/jxcore-log( 3325): 2015-12-14T21:33:53.739Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3325): 
I/jxcore-log( 3325): ---- round done--------
I/jxcore-log( 3325): 
I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
I/jxcore-log( 3325): device[10]: E0:DB:10:1F:C9:5E
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:53.743Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:53.744Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:53.744Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: Note3-1
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null E0:DB:10:1F:C9:5E
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: E0:DB:10:1F:C9:5E)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address E0:DB:10:1F:C9:5E (thread ID: 378)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd7ec4 rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd808c rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd808c rs_disc_pending=0
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 2086): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2086): Entering PendingCommandState State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 2086): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2086): StableState(): Entering Off State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3309 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 378)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 379)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 379)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 378)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 379)
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd808c rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 82 bytes successfully (thread ID: 379)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3309 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3309 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 379)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3309 E0:DB:10:1F:C9:5E]
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: E0:DB:10:1F:C9:5E, name: samsung-SM-N9005_PT3309, Bluetooth address: E0:DB:10:1F:C9:5E
,D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
,I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID E0:DB:10:1F:C9:5E, created successfully
D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 380)
D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 33176
,I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 33176 (peer ID: E0:DB:10:1F:C9:5E)
I/jxcore-log( 3325): 2015-12-14T21:33:57.546Z SendDataConnector.js: CLIENT connected to 33176, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:33:57.547Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 33176
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 380)
,I/jxcore-log( 3325): 2015-12-14T21:33:57.581Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 381, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 382, name: Receiver)
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 1408): Bluetooth Device Name: G4-1
,I/art     (  759): Explicit concurrent mark sweep GC freed 99222(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 1.024ms total 70.247ms
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd808c rs_disc_pending=0
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3325): 2015-12-14T21:33:58.662Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:33:58.962Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:33:59.165Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:33:59.223Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:33:59.420Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:33:59.593Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:33:59.819Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:33:59.826Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:34:00.199Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:34:00.430Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:00.431Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3325): 
I/jxcore-log( 3325): oneRoundDownNow
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:00.434Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:00.434Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:1F:C9:5E
I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 382
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 381
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 381, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID E0:DB:10:1F:C9:5E disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 382, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID E0:DB:10:1F:C9:5E disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:1F:C9:5E
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 381, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 382, name: Receiver)
,I/jxcore-log( 3325): 2015-12-14T21:34:00.493Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): ---- round done--------
I/jxcore-log( 3325): 
I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
I/jxcore-log( 3325): device[11]: 44:80:EB:7B:5A:05
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:00.494Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:00.494Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:00.494Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
,I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: XT1072_23d5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 384)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd808c rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd808c rs_disc_pending=0
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd808c rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd8254 rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Note3-1
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2086): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2086): Entering PendingCommandState State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2086): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2086): StableState(): Entering Off State
,E/BluetoothEventManager( 2730): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [44:80:EB:7B:5A:05 motorola-XT1072_PT2105 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 384)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 385)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 385)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 384)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 385)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 81 bytes successfully (thread ID: 385)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT2105 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [44:80:EB:7B:5A:05 motorola-XT1072_PT2105 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT2105 44:80:EB:7B:5A:05]
,I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: 44:80:EB:7B:5A:05, name: motorola-XT1072_PT2105, Bluetooth address: 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
,I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 44:80:EB:7B:5A:05 already in the list
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID 44:80:EB:7B:5A:05, created successfully
D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 385)
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 386)
,D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 49081
I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 49081 (peer ID: 44:80:EB:7B:5A:05)
I/jxcore-log( 3325): 2015-12-14T21:34:06.012Z SendDataConnector.js: CLIENT connected to 49081, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:06.013Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 49081
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 386)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 388, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 387, name: Sender)
,I/jxcore-log( 3325): 2015-12-14T21:34:06.063Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7209 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT7209, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: Android_63cc, Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,D/        ( 2086): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3325): 2015-12-14T21:34:07.801Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/        ( 2086): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18766
,I/jxcore-log( 3325): 2015-12-14T21:34:08.321Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3325): 
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3325): 2015-12-14T21:34:09.307Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7395","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7395 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7395","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT7395, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: Thali Test (Galaxy A5), Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,D/        ( 2086): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 3325): 2015-12-14T21:34:09.596Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3325): 2015-12-14T21:34:10.422Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3325): 2015-12-14T21:34:11.604Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3325): 2015-12-14T21:34:13.227Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3325): 2015-12-14T21:34:14.917Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3325): 2015-12-14T21:34:15.940Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:34:17.029Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:17.030Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): oneRoundDownNow
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:17.043Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:17.044Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 388
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 387
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 387, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 44:80:EB:7B:5A:05 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 388, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 44:80:EB:7B:5A:05 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 387, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 388, name: Receiver)
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,I/jxcore-log( 3325): 2015-12-14T21:34:17.093Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3325): 
I/jxcore-log( 3325): ---- round done--------
I/jxcore-log( 3325): 
I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
I/jxcore-log( 3325): device[12]: 80:01:84:8A:B3:68
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:17.094Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:17.094Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:17.094Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 80:01:84:8A:B3:68
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 80:01:84:8A:B3:68)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 80:01:84:8A:B3:68 (thread ID: 389)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd8254 rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive,
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: XT1072
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 2086): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2086): Entering PendingCommandState State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 2086): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2086): StableState(): Entering Off State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7209 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 389)
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 390)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 390)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 389)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 390)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 84 bytes successfully (thread ID: 390)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7209 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7209 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 390)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7209 80:01:84:8A:B3:68]
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: 80:01:84:8A:B3:68, name: HTC-HTC Desire 820_PT7209, Bluetooth address: 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID 80:01:84:8A:B3:68, created successfully
D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 391)
,D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 49011
,I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 49011 (peer ID: 80:01:84:8A:B3:68)
I/jxcore-log( 3325): 2015-12-14T21:34:27.665Z SendDataConnector.js: CLIENT connected to 49011, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:27.666Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 49011
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 391)
,I/jxcore-log( 3325): 2015-12-14T21:34:27.690Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 392, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 393, name: Receiver)
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2,
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd841c rs_disc_pending=0
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/jxcore-log( 3325): 2015-12-14T21:34:38.123Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:38.124Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:38.125Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:38.126Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:38.127Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3325): 
,E/io.jxcore.node.StreamCopyingThread( 3325): Input stream got -1 on read (thread ID: 392, thread name: Sender)
,E/io.jxcore.node.OutgoingSocketThread( 3325): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 80:01:84:8A:B3:68 disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 80:01:84:8A:B3:68
,I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 393
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 392
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 393, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 80:01:84:8A:B3:68 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 392, name: Sender)
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 393, name: Receiver)
,D/WifiP2pManager( 3325): Ignored { when=-33ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5394 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT5394, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: HTC Desire 820
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/jxcore-log( 3325): 2015-12-14T21:34:43.126Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:43.127Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT334","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT334 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT334","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT334, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: , Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Adding peer with ID 90:E7:C4:F6:69:77
I/jxcore-log( 3325): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT334","peerAvailable":true}]
I/jxcore-log( 3325): 
I/jxcore-log( 3325): Found peer : HTC-HTC One M8s_PT334, Available: true
I/jxcore-log( 3325): 
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 80:01:84:8A:B3:68
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 80:01:84:8A:B3:68), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:34:48.134Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:48.135Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:48.135Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:48.136Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: HTC Desire 820 80:01:84:8A:B3:68
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 80:01:84:8A:B3:68)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 80:01:84:8A:B3:68 (thread ID: 394)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7209 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 394)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 395)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 395)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 394)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 395)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 84 bytes successfully (thread ID: 395)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7209 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7209 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 395)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7209 80:01:84:8A:B3:68]
,I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: 80:01:84:8A:B3:68, name: HTC-HTC Desire 820_PT7209, Bluetooth address: 80:01:84:8A:B3:68
,D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
,I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID 80:01:84:8A:B3:68, created successfully
D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 396)
,D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 48341
I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 48341 (peer ID: 80:01:84:8A:B3:68)
I/jxcore-log( 3325): 2015-12-14T21:34:54.496Z SendDataConnector.js: CLIENT connected to 48341, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:34:54.496Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 48341
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 396)
,I/jxcore-log( 3325): 2015-12-14T21:34:54.526Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 398, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 397, name: Sender)
,I/jxcore-log( 3325): 2015-12-14T21:34:56.552Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:34:59.468Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:34:59.547Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:34:59.594Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:35:01.599Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:35:01.700Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:35:01.775Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:35:01.874Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:35:01.946Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:35:02.023Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:35:02.037Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): oneRoundDownNow
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:35:02.047Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:35:02.048Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 80:01:84:8A:B3:68
I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 398
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 397
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 397, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 80:01:84:8A:B3:68 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 398, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 80:01:84:8A:B3:68 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Successfully disconnected (peer ID: 80:01:84:8A:B3:68
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 397, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 398, name: Receiver)
,I/jxcore-log( 3325): 2015-12-14T21:35:02.100Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): ---- round done--------
I/jxcore-log( 3325): 
I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): device[13]: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:02.106Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:02.106Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:02.106Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: S5-1
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 399)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd841c rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd841c rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd85e4 rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2086): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2086): Entering PendingCommandState State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2086): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2086): StableState(): Entering Off State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd841c rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5995 7C:F9:0E:34:8A:A0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 399)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 400)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 400)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 399)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 400)
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 82 bytes successfully (thread ID: 400)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5995 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5995 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5995 7C:F9:0E:34:8A:A0]
,I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: 7C:F9:0E:34:8A:A0, name: samsung-SM-G900F_PT5995, Bluetooth address: 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:34:8A:A0 already in the list
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:34:8A:A0, created successfully
,D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,I/BluetoothClassifier( 1408): Bluetooth Device Name: HTC Desire 820
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 401)
D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 40942
I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 40942 (peer ID: 7C:F9:0E:34:8A:A0)
I/jxcore-log( 3325): 2015-12-14T21:35:07.606Z SendDataConnector.js: CLIENT connected to 40942, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:07.606Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 40942
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 401)
,I/jxcore-log( 3325): 2015-12-14T21:35:07.624Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 403, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 402, name: Sender)
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2086): dm_pm_timer expires
W/bt-btif ( 2086): dm_pm_timer expires 0
W/bt-btif ( 2086): proc dm_pm_timer expires
,I/UsageStatsService(  759): User[0] Flushing usage stats to disk
,I/jxcore-log( 3325): 2015-12-14T21:35:18.031Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:18.032Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:18.033Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:18.033Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:35:18.034Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3325): 
,E/io.jxcore.node.StreamCopyingThread( 3325): Input stream got -1 on read (thread ID: 402, thread name: Sender)
,E/io.jxcore.node.OutgoingSocketThread( 3325): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:34:8A:A0 disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
,I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 403
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 402
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 403, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:34:8A:A0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 403, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 402, name: Sender)
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,I/jxcore-log( 3325): 2015-12-14T21:35:23.034Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:23.035Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3325): 
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: S5-1
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:34:8A:A0), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:35:28.039Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:28.040Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:35:28.041Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:35:28.041Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
,I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
,D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: S5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to S5-1 in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: S5-1 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to S5-1 in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 404)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [7c:f9:0e:34:8a:a0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5995 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 404)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 405)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 405)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 404)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 405)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 82 bytes successfully (thread ID: 405)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5995 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5995 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 405)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5995 7C:F9:0E:34:8A:A0]
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: 7C:F9:0E:34:8A:A0, name: samsung-SM-G900F_PT5995, Bluetooth address: 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:34:8A:A0 already in the list
,I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:34:8A:A0, created successfully
D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 406)
,D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 57318
,I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 57318 (peer ID: 7C:F9:0E:34:8A:A0)
I/jxcore-log( 3325): 2015-12-14T21:35:30.276Z SendDataConnector.js: CLIENT connected to 57318, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:30.277Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 57318
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 406)
,I/jxcore-log( 3325): 2015-12-14T21:35:30.301Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 408, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 407, name: Sender)
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2086): dm_pm_timer expires
W/bt-btif ( 2086): dm_pm_timer expires 0
W/bt-btif ( 2086): proc dm_pm_timer expires
,I/jxcore-log( 3325): 2015-12-14T21:35:36.810Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2086): invalid rfc slot id: 128
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 408, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3325): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:34:8A:A0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 408
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 407
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 407, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:34:8A:A0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,D/BluetoothMapService( 2086): onReceive
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 407, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 408, name: Receiver)
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: S5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3325): Ignored { when=-10ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3325): 2015-12-14T21:35:46.811Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:46.812Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:46.812Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:46.813Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:35:46.814Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT7658 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT7658, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5394 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT5394, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/jxcore-log( 3325): 2015-12-14T21:35:51.813Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:51.814Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:51.815Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8913 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT8913, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
,W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3309","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3309 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3309","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT3309, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: Note3-1, Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7395","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7395 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7395","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT7395, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: Thali Test (Galaxy A5), Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:34:8A:A0), either no such connection or failed to close the connection
,I/jxcore-log( 3325): 2015-12-14T21:35:56.825Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:56.826Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:56.826Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:56.827Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
,I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: S5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to S5-1 in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: S5-1 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to S5-1 in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 409)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5995 7C:F9:0E:34:8A:A0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 409)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 410)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 410)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 409)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 410)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 82 bytes successfully (thread ID: 410)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5995 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5995 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 410)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5995 7C:F9:0E:34:8A:A0]
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: 7C:F9:0E:34:8A:A0, name: samsung-SM-G900F_PT5995, Bluetooth address: 7C:F9:0E:34:8A:A0
,D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:34:8A:A0 already in the list
,I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:34:8A:A0, created successfully
,D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 411)
,D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 46631
I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 46631 (peer ID: 7C:F9:0E:34:8A:A0)
,I/jxcore-log( 3325): 2015-12-14T21:35:59.504Z SendDataConnector.js: CLIENT connected to 46631, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:35:59.505Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 46631
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 411)
,I/jxcore-log( 3325): 2015-12-14T21:35:59.543Z SendDataConnector.js: CLIENT now sending 70000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 412, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 413, name: Receiver)
,I/jxcore-log( 3325): 2015-12-14T21:36:00.492Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3325): 
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3325): 2015-12-14T21:36:01.051Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:36:01.735Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:36:01.742Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:36:01.922Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:36:01.934Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:36:01.976Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:36:01.976Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3325): 
I/jxcore-log( 3325): oneRoundDownNow
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:36:01.976Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:36:01.976Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 413
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 412
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 412, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:34:8A:A0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 413, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:34:8A:A0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 412, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 413, name: Receiver)
,I/jxcore-log( 3325): 2015-12-14T21:36:01.982Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3325): 
I/jxcore-log( 3325): ---- round done--------
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
I/jxcore-log( 3325): device[14]: 7C:F9:0E:37:96:AB
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:36:01.983Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:36:01.983Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:36:01.983Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: A5-1
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 414)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd85e4 rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd87ac rs_disc_pending=1
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd87ac rs_disc_pending=0
,W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT61","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT61 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT61","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT61, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: Thali Test (Galaxy A3), Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd85e4 rs_disc_pending=0
E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: S5-1
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2086): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2086): Entering PendingCommandState State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2086): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2086): StableState(): Entering Off State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT8378 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 414)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 415)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 415)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 414)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 415)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 83 bytes successfully (thread ID: 415)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT8378 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT8378 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT8378 7C:F9:0E:37:96:AB]
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: 7C:F9:0E:37:96:AB, name: samsung-SM-A500FU_PT8378, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 415)
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 416)
D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 36667
I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 36667 (peer ID: 7C:F9:0E:37:96:AB)
I/jxcore-log( 3325): 2015-12-14T21:36:07.873Z SendDataConnector.js: CLIENT connected to 36667, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:36:07.874Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 36667
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 416)
,I/jxcore-log( 3325): 2015-12-14T21:36:07.896Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 417, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 418, name: Receiver)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/        ( 2086): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3325): 2015-12-14T21:36:08.881Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:36:08.912Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3325): 
,D/        ( 2086): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3325): 2015-12-14T21:36:08.992Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:36:09.035Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3325): 
,D/        ( 2086): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3325): 2015-12-14T21:36:09.086Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:36:09.132Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:36:09.165Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:36:09.208Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:36:09.216Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:36:09.322Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:36:09.323Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3325): 
I/jxcore-log( 3325): oneRoundDownNow
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:36:09.324Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:36:09.324Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 418
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 417
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 417, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 418, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 417, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 418, name: Receiver)
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0x1d):jv handle:0x0 not FOUND
,I/jxcore-log( 3325): 2015-12-14T21:36:09.392Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): ---- round done--------
I/jxcore-log( 3325): 
I/jxcore-log( 3325): startWithNextDevice
I/jxcore-log( 3325): 
I/jxcore-log( 3325): device[15]: 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:36:09.402Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:36:09.403Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:36:09.403Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 419)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd87ac rs_disc_pending=1
E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2086): bta_dm_check_av:0
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: A5-1
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT452"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT452"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT452, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Connection timeout
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x8  CID 0x45
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:131, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 131
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x8  CID 0x47
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:132, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 132
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 419)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 419)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5995","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5995 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5995","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 samsung-SM-A300FU_PT61 08:EC:A9:50:76:27]
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 7C:F9:0E:34:8A:A0, peer name: samsung-SM-G900F_PT5995, peer ID: 7C:F9:0E:34:8A:A0, Wi-Fi Direct device name: , Wi-Fi Direct address: ee:1f:72:63:11:86
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:34:8A:A0 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
I/jxcore-log( 3325): 2015-12-14T21:37:17.809Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:37:17.810Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:37:17.810Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 419)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3325): 2015-12-14T21:37:22.818Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:37:22.819Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7209 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT7209, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: Android_63cc, Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5394 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5394","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT5394, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:37:27.825Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:37:27.826Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:37:27.826Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:37:27.826Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
,I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 420)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT7658 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT7658, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
,W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT61","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT61 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 4 services discovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT61","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT61","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT61","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT61, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: Thali Test (Galaxy A3), Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
,W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Connection timeout
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x43
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:133, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 133
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Cancelled: Connection timeout
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 samsung-SM-A300FU_PT61 08:EC:A9:50:76:27]
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/jxcore-log( 3325): 2015-12-14T21:38:43.960Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:38:43.960Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:38:43.960Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,I/jxcore-log( 3325): Connected to the server!
I/jxcore-log( 3325): 
,I/chromium( 3325): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3325): 2015-12-14T21:38:48.960Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:38:48.961Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:38:53.964Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:38:53.965Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:38:53.966Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:38:53.966Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
,D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 421)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): Connection timeout
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x48
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:134, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 134
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 420)
,E/bt-btm  ( 2086): tBTM_SEC_DEV:0xa3dd8974 rs_disc_pending=0
,E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:135, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 135
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2086): bta_dm_check_av:0
,W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-btif ( 2086): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,W/bt-smp  ( 2086): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2086): Plain text(LSB ~ MSB) = 2a 1b 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2086): Encrypted text(LSB ~ MSB) = 9e 75 0a d0 d6 b9 ee 65 2a c9 55 be 41 2b 42 6f 
W/bt-btm  ( 2086): Stopping oneshot timer
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x8  CID 0x41
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:136, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 136
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 421)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect again in 300 ms... (thread ID: 421)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onConnectionFailed: Cancelled: Connection timeout
,I/jxcore-log( 3325): timeout now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): weAreDoneNow, resultArray.length: 14
I/jxcore-log( 3325): 
I/jxcore-log( 3325): sendReportNow
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): done, now sending data to server
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:40:52.953Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:40:52.957Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 samsung-SM-A300FU_PT61 08:EC:A9:50:76:27]
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/jxcore-log( 3325): 2015-12-14T21:40:52.982Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:40:52.982Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:40:52.982Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3325): 
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 421)
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 3325): 2015-12-14T21:40:57.982Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:40:57.983Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 7: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 7: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 7: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 11 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 10: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 11: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 3325): 2015-12-14T21:41:02.987Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:41:02.988Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:41:02.992Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:41:02.995Z SendDataConnector.js: do connect now
I/jxcore-log( 3325): 
,I/io.jxcore.node.ConnectionHelper( 3325): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3325): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 422)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3325): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7209 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local.",
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local.",
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT7209, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: Android_63cc, Wi-Fi Direct address: 82:01:84:6b:e8:5d
,I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
,W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,W/bt-sdp  ( 2086): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2086): DISCOVERY_COMP_EVT slot id:137, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2086): invalid rfc slot id: 137
W/BluetoothAdapter( 3325): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2086): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8913 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8913","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT8913, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
,I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT7658 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT7658, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT2105 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2105","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT2105, peer ID: 44:80:EB:7B:5A:05, Wi-Fi Direct device name: XT1072_23d5, Wi-Fi Direct address: 44:80:eb:7b:5a:07
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 44:80:EB:7B:5A:05 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,W/bt-btif ( 2086): info:x10
,D/        ( 2086): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2086): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2086): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 2086): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2086): Entering PendingCommandState State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 2086): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2086): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2086): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2086): StableState(): Entering Off State
,W/BluetoothEventManager( 2730): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2730): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,W/bt-btif ( 2086): new conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2086): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onSocketConnected: Authenticating next: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT61 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 422)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesWritten: 77 bytes successfully written (thread ID: 423)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Outgoing connection initialized (*handshake* thread ID: 423)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Exiting thread (thread ID: 422)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Entering thread (ID: 423)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): onBytesRead: Read 81 bytes successfully (thread ID: 423)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3325): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT61 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3325): onAuthenticated: Fully connected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT61 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3325): Exiting thread (ID: 423)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT61 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT61, Bluetooth address: 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3325): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
I/io.jxcore.node.ConnectionHelper( 3325): onConnected: Outgoing socket thread, for peer with ID 08:EC:A9:50:76:27, created successfully
D/io.jxcore.node.ConnectionHelper( 3325): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3325): Entering thread (ID: 424)
D/io.jxcore.node.OutgoingSocketThread( 3325): Server socket local port: 44540
I/io.jxcore.node.OutgoingSocketThread( 3325): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3325): onListeningForIncomingConnections: Outgoing connection is using port 44540 (peer ID: 08:EC:A9:50:76:27)
I/jxcore-log( 3325): 2015-12-14T21:41:12.875Z SendDataConnector.js: CLIENT connected to 44540, error: null
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:41:12.875Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3325): 
,I/io.jxcore.node.OutgoingSocketThread( 3325): Incoming data from address: /127.0.0.1, port: 44540
D/io.jxcore.node.OutgoingSocketThread( 3325): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3325): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3325): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3325): Exiting thread (ID: 424)
,I/jxcore-log( 3325): 2015-12-14T21:41:12.903Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3325): 
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 425, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3325): Entering thread (ID: 426, name: Receiver)
,D/        ( 2086): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3325): 2015-12-14T21:41:13.766Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:41:14.046Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3325): 
,D/        ( 2086): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3325): 2015-12-14T21:41:14.387Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:41:14.456Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3325): 
,D/        ( 2086): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926
,I/jxcore-log( 3325): 2015-12-14T21:41:14.833Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:41:15.029Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:41:15.237Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:41:15.348Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:41:15.462Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3325): 
,I/jxcore-log( 3325): 2015-12-14T21:41:15.989Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:41:15.989Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3325): 
I/jxcore-log( 3325): oneRoundDownNow
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:41:15.990Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3325): 
I/jxcore-log( 3325): 2015-12-14T21:41:15.991Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3325): 
D/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 3325): close
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 426
I/io.jxcore.node.OutgoingSocketThread( 3325): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3325): doStop: Thread ID: 425
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 425, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:76:27 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3325): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3325): Either failed to read from the output stream or write to the input stream (thread ID: 426, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3325): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3325): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:76:27 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 3325): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 425, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3325): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3325): Exiting thread (ID: 426, name: Receiver)
,I/jxcore-log( 3325): 2015-12-14T21:41:16.037Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3325): 
,W/bt-btif ( 2086): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,D/btif_config_util( 2086): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2086): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2086): onReceive
,I/BTConnectionReceiver( 1408): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1408): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 3325): Connected to the server!
I/jxcore-log( 3325): 
,I/chromium( 3325): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3325): Ignored { when=-20ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=-12ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 7: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 7: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 7: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 7: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6801","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6801 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6801","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6801","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6801","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6801","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6801","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6801","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: B0:C5:59:3F:75:69, peer name: samsung-SM-G900F_PT6801, peer ID: B0:C5:59:3F:75:69, Wi-Fi Direct device name: Thali Test (Galaxy S5), Wi-Fi Direct address: ee:1f:72:18:8b:78
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID B0:C5:59:3F:75:69 already in the list
,W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7209 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT7209, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: Android_63cc, Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
,W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5357 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT5357, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: Note4-1, Wi-Fi Direct address: 92:b6:86:43:73:1c
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 7: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 7: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 7: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 7: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3325): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 12 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 7: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 10: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 11: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,D/WifiP2pManager( 3325): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT8658 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8658"}", service type: "Cordovap2p._tcp.local.",
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers,
,I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT8658, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: XT1039_8c05, Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list,
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT9882 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT9882"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT9882, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: Thali Test's G2, Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5357 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5357","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT5357, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name,: Note4-1, Wi-Fi Direct address: 92:b6:86:43:73:1c
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3325): Ignored { when=-11ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,D/WifiP2pManager( 3325): Ignored { when=-8ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT452"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT452 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT452"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT452, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: Android_1950, Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT7658 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT7658, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/EventLogService( 1628): Aggregate from 1450127495146 (log), 1450127495146 (data)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): stopServiceDiscovery
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4198","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3325): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery stopped successfully
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): start: Starting peer discovery...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3325): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3325): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 5: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 6: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3325): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
D/WifiP2pManager( 3325): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service request added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: Got empty list
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7209 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT7209, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: Android_63cc, Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7209"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT7658 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT7658, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
,I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6801","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6801 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6801","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6801","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6801","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6801","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6801","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6801","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: B0:C5:59:3F:75:69, peer name: samsung-SM-G900F_PT6801, peer ID: B0:C5:59:3F:75:69, Wi-Fi Direct device name: Thali Test (Galaxy S5), Wi-Fi Direct address: ee:1f:72:18:8b:78
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID B0:C5:59:3F:75:69 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3781","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3781 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3325): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3325): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3781","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3781","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3781","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3781","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3781","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3781","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3325): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3325): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT3781, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: , Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 3325): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 3325): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/ActivityManager(  759): Killing 1990:com.google.android.calendar/u0a31 (adj 15): empty for 1819s
,I/ProcessStatsService(  759): Prepared write state in 3ms
,W/libprocessgroup(  759): failed to open /acct/uid_10031/pid_1990/cgroup.procs: No such file or directory
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  759): Pruning old procstats: /data/system/procstats/state-2015-12-14-08-40-18.bin
,TIME-OUT KILL (timeout was 1800000ms),I/ActivityManager(  759): Killing 2785:com.google.android.music:main/u0a60 (adj 13): empty for 1800s
I/ActivityManager(  759): Killing 3113:com.android.defcontainer/u0a5 (adj 13): empty for 1811s
I/ActivityManager(  759): Killing 3136:com.google.android.gms:car/u0a8 (adj 13): empty for 1812s
I/ActivityManager(  759): Killing 3224:com.android.musicfx/u0a15 (adj 13): empty for 1813s
I/ActivityManager(  759): Killing 1494:com.google.android.partnersetup/u0a13 (adj 15): empty for 1813s
I/ActivityManager(  759): Killing 2864:com.android.providers.calendar/u0a2 (adj 15): empty for 1816s
W/libprocessgroup(  759): failed to open /acct/uid_10060/pid_2785/cgroup.procs: No such file or directory
W/libprocessgroup(  759): failed to open /acct/uid_10005/pid_3113/cgroup.procs: No such file or directory
W/libprocessgroup(  759): failed to open /acct/uid_10008/pid_3136/cgroup.procs: No such file or directory
W/libprocessgroup(  759): failed to open /acct/uid_10015/pid_3224/cgroup.procs: No such file or directory
W/libprocessgroup(  759): failed to open /acct/uid_10013/pid_1494/cgroup.procs: No such file or directory
W/libprocessgroup(  759): failed to open /acct/uid_10002/pid_2864/cgroup.procs: No such file or directory
D/AndroidRuntime( 4078): 
D/AndroidRuntime( 4078): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4078): CheckJNI is OFF
D/AndroidRuntime( 4078): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 3325:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  759): WIN DEATH: Window{23fd46e8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  759): Client connection lost with reason: 4
W/PackageSettings(  759): Skipping PackageSetting{168b2bf com.example.hello/10277} due to missing metadata
I/ActivityManager(  759):   Force finishing activity ActivityRecord{1b57c134 u0 com.test.thalitest/.MainActivity t214}
W/ActivityManager(  759): Spurious death for ProcessRecord{15b90858 3325:com.test.thalitest/u0a270}, curProc for 3325: null
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  759):   Force finishing activity ActivityRecord{1b57c134 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  759): Duplicate finish request for ActivityRecord{1b57c134 u0 com.test.thalitest/.MainActivity t214 f}
I/art     ( 1293): Explicit concurrent mark sweep GC freed 4056(299KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 223us total 16.143ms
I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1103): resetDictionaries() : en_US
W/GeofencerStateMachine( 1601): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1103): run()
I/Adreno-EGL(  942): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  942): Initialized EGL, version 1.4
D/OpenGLRenderer(  942): Enabling debug mode 0
I/art     (  759): Explicit concurrent mark sweep GC freed 109720(5MB) AllocSpace objects, 10(240KB) LOS objects, 33% free, 28MB/42MB, paused 1.366ms total 77.416ms
I/art     ( 1408): Explicit concurrent mark sweep GC freed 71355(3MB) AllocSpace objects, 15(240KB) LOS objects, 24% free, 18MB/25MB, paused 308us total 118.596ms
D/VoicemailCleanupService( 1369): Cleaning up data for package: com.test.thalitest
I/art     ( 1628): Explicit concurrent mark sweep GC freed 13734(728KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 22MB/30MB, paused 523us total 128.551ms
I/Decoder ( 1103): createOrResetDecoder
I/ActivityManager(  759): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=4115 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
I/Keyboard.Facilitator.MainLanguageModelLoader( 1103): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1103): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1103): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1103): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1103): run()
I/StatsUtilsManager( 1103): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1103): shouldRecordStats() = Too Soon
D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  759): removeObsoleteFile: deleting file=214_task.xml
I/UpdateIcingCorporaServi( 1408): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/InputMethodManagerService(  759): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@34d59639 (uid=10034 pid=942)
W/InputMethodManagerService(  759): Got RemoteException sending setActive(false) notification to pid 3325 uid 10270
W/Launcher( 1293): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@39486a78 new=com.google.android.velvet.VelvetApplication@39486a78
I/Keyboard.Facilitator( 1103): onFinishInput()
I/art     (  759): Explicit concurrent mark sweep GC freed 10876(561KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 5.133ms total 153.418ms
I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4140 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  759): Killing 3432:com.google.android.apps.magazines/u0a61 (adj 15): empty for 1803s
D/AndroidRuntime( 4078): Shutting down VM
I/Launcher( 1293): Deferring update until onResume
W/libprocessgroup(  759): failed to open /acct/uid_10061/pid_3432/cgroup.procs: No such file or directory
W/ContextImpl( 4140): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/PackageBroadcastService( 1628): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1628): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1628): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1628): Module APK com.google.android.play.games already loaded
W/ResourcesManager( 1293): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/LocationSettingsChecker( 1628): Removing dialog suppression flag for package com.test.thalitest
W/ResourcesManager( 1293): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/GMPM-SVC( 1628): App measurement is starting up, version: 8489
I/GMPM-SVC( 1628): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/Launcher( 1293): Deferring update until onResume
I/art     ( 1601): Explicit concurrent mark sweep GC freed 89584(4MB) AllocSpace objects, 32(535KB) LOS objects, 39% free, 23MB/38MB, paused 928us total 82.421ms
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@58d53b)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@de709b1)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@393e96)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@7758a17)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@21e8fe04)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@28b18fed)
D/ChimeraCfgMgr( 1628): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1628): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1601): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1601): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  759): Delay finish: com.google.android.gms/.gcm.nts.SchedulerReceiver
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3818a6e)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3569a50f)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@26e0099c)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1af9cfa5)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@183fdf7a)
E/SQLiteLog( 1628): (3850) statement aborts at 151: [DELETE FROM FileContent163 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
E/DocListDatabase( 1628): Failed to delete from FileContent163 table
E/DocListDatabase( 1628): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1628): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1628): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1628): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1628): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1628): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1628): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 1628): 	at com.google.android.gms.drive.database.f.a(SourceFile:987)
E/DocListDatabase( 1628): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/DocListDatabase( 1628): 	at com.google.android.gms.drive.j.ah.run(SourceFile:51)
E/DocListDatabase( 1628): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 1628): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 1628): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1628): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process ( 1628): Sending signal. PID: 1628 SIG: 9
D/ConnectivityService(  759): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@31ae0689)
D/ConnectivityService(  759): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  759): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/AppDataSearchClient( 1408): Request indexing failed.
E/AppDataSearchClient( 1408): android.os.DeadObjectException
E/AppDataSearchClient( 1408): 	at android.os.BinderProxy.transactNative(Native Method)
E/AppDataSearchClient( 1408): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AppDataSearchClient( 1408): 	at bkp.a(Unknown Source)
E/AppDataSearchClient( 1408): 	at bbt.a(Unknown Source)
E/AppDataSearchClient( 1408): 	at beg.i(PG:330)
E/AppDataSearchClient( 1408): 	at beh.call(PG:215)
E/AppDataSearchClient( 1408): 	at beg.a(PG:299)
E/AppDataSearchClient( 1408): 	at beg.c(PG:222)
E/AppDataSearchClient( 1408): 	at cun.b(PG:660)
E/AppDataSearchClient( 1408): 	at cun.a(PG:651)
E/AppDataSearchClient( 1408): 	at cun.g(PG:597)
E/AppDataSearchClient( 1408): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/AppDataSearchClient( 1408): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AppDataSearchClient( 1408): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AppDataSearchClient( 1408): 	at cuw.Tg(PG:368)
E/AppDataSearchClient( 1408): 	at cuy.ub(PG:301)
E/AppDataSearchClient( 1408): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/AppDataSearchClient( 1408): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/AppDataSearchClient( 1408): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchClient( 1408): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchClient( 1408): 	at android.os.Looper.loop(Looper.java:135)
E/AppDataSearchClient( 1408): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/IcingCorporaProvider( 1408): Table change notification failed for TableStorageSpec[applications]
I/UpdateIcingCorporaServi( 1408): UpdateCorporaTask done [took 477 ms] updated apps [took 477 ms] 
I/ActivityManager(  759): Process com.google.android.gms (pid 1628) has died
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 1000ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 11000ms
I/ActivityManager(  759): Resuming delayed broadcast
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10997ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20997ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 20997ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 30997ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 30996ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 30996ms

```
