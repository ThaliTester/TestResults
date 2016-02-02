#### Test 575312431f256a6_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3197): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3197):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3197):   adb logcat -s GAv4
W/GAv4    ( 3197): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3197): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3197): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3197): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2680): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3197): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3197): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3197): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  764): Killing 2644:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/System  ( 3197): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3197): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  764): failed to open /acct/uid_10069/pid_2644/cgroup.procs: No such file or directory
V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1701): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1701): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1701): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1701): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3264): 
D/AndroidRuntime( 3264): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3264): CheckJNI is OFF
D/AndroidRuntime( 3264): Calling main entry com.android.commands.am.Am
I/ActivityManager(  764): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  764): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3285 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3264): Shutting down VM
V/ActivityManager(  764): Display changed displayId=0
I/WebViewFactory( 3285): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3285): Time to load native libraries: 1 ms (timestamps 2242-2243)
I/LibraryLoader( 3285): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3285): Binding Chromium to main looper Looper (main, tid 1) {d7ae8fc}
I/LibraryLoader( 3285): Expected native library version number "",actual native library version number ""
I/chromium( 3285): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3285): Initializing chromium process, singleProcess=true
W/art     ( 3285): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3285): ApplicationContext is null in ApplicationStatus
W/chromium( 3285): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3285): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3285): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3285): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  764): Message: 20
D/BluetoothManagerService(  764): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cbb57d1:true
,W/art     ( 3285): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3285): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3285): CordovaWebView is running on device made by: LGE
,W/art     ( 3285): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3285): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3285): Render dirty regions requested: true
,D/Atlas   ( 3285): Validating map...
,W/chromium( 3285): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3285): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3285): Enabling debug mode 0
,W/BindingManager( 3285): Cannot call determinedVisibility() - never saw a connection for the pid: 3285
,W/IInputConnectionWrapper( 3285): showStatusIcon on inactive InputConnection
I/ActivityManager(  764): Displayed com.test.thalitest/.MainActivity: +443ms (total +50s695ms)
,D/JsMessageQueue( 3285): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3285): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
,I/chromium( 3285): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  764): Killing 2599:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  764): failed to open /acct/uid_10045/pid_2599/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 3094): mConnectedToCar = false, abort
,E/ActivityThread( 3094): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@7d6918d that was originally bound here
E/ActivityThread( 3094): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@7d6918d that was originally bound here
E/ActivityThread( 3094): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3094): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3094): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3094): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3094): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3094): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3094): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3094): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3094): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3094): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3094): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3094): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3094): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3094): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3094): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3094): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3094): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3094): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3094): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3094): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3094): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3094): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3094): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@383ff1bc that was originally bound here
E/ActivityThread( 3094): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@383ff1bc that was originally bound here
E/ActivityThread( 3094): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3094): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3094): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3094): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3094): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3094): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3094): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3094): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3094): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3094): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3094): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3094): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3094): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3094): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3094): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3094): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3094): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3094): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3094): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3094): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3094): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  764): Unbind failed: could not find connection for android.os.BinderProxy@2a792972
,W/jxcore-log( 3285): Initializing JXcore engine
W/jxcore-log( 3285): JXcore engine is ready
,W/Thread-317( 3341): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8058]" dev="sockfs" ino=8058 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-317( 3341): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-317( 3341): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9505]" dev="sockfs" ino=9505 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-317( 3341): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19135]" dev="sockfs" ino=19135 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3285): Starting JXcore engine
,W/jxcore-log( 3285): Platform android
W/jxcore-log( 3285): 
W/jxcore-log( 3285): Process ARCH arm
W/jxcore-log( 3285): 
,I/jxcore-log( 3285): JXcore Cordova bridge is ready!
I/jxcore-log( 3285): 
,W/jxcore-log( 3285): JXcore engine is started
,I/jxcore-log( 3285): Toggling radios to true
I/jxcore-log( 3285): 
,D/BluetoothAdapter( 3285): enable(): BT is already enabled..!
,D/WifiService(  764): New client listening to asynchronous messages
,D/WifiService(  764): setWifiEnabled: true pid=3285, uid=10270
E/WifiService(  764): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3285): Radios toggled
I/jxcore-log( 3285): 
I/jxcore-log( 3285): My device name is: LGE-Nexus 5
I/jxcore-log( 3285): 
,I/wpa_supplicant( 1050): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  764): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  764): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1627): Read error: ssl=0xb5067e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1627): SSL shutdown failed: ssl=0xb5067e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  764): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): ValidatedState{ when=-5ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): DefaultState{ when=-5ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  764): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1050): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  764): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  764): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  764): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  764): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1701): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524292
D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  764): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  764): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory( 1218): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  764): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1050): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1050): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1050): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1050): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  764): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  178): Setting iface cfg
,E/WifiStateMachine(  764): Start Dhcp Watchdog 2
,E/native  (  764): do suspend false
,E/WifiStateMachine(  764): scanCount==0 - aborting
,I/dhcpcd  ( 3370): version 5.5.6 starting
E/dhcpcd  ( 3370): get_duid: Read-only file system
,I/dhcpcd  ( 3370): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  764): MasterInitialState.processMessage what=3
D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  764): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2787): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1701): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1701): onCreate
D/SystemUpdateService( 1701): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1701): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1701): active receiver: enabled
,I/dhcpcd  ( 3370): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/Babel   ( 1944): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  764): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3379 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/iu.UploadsManager( 1701): num queued entries: 0
I/iu.UploadsManager( 1701): num updated entries: 0
I/iu.SyncManager( 1701): NEXT; no task
,E/GpsLocationProvider(  764): No APN found to select.
,I/dhcpcd  ( 3370): wlan0: leased 192.168.1.114 for 86400 seconds
,I/SystemUpdateService( 1701): showing system update notification
,I/ValidateNoPeople(  764): skipping global notification
,E/GpsLocationProvider(  764): No APN found to select.
,V/SystemUpdateService( 1701): retry (wakeup: false) in 3599915 ms
,D/SystemUpdateService( 1701): onDestroy
,I/GAv4    ( 3379): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3379):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3379):   adb logcat -s GAv4
,W/GAv4    ( 3379): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3379): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3379): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  764): do suspend true
,D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiStateMachine(  764): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  764): Adding iface wlan0 to network 101
,E/ConnectivityService(  764): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  764): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  764): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  764): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  764): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  764): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  764): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  764): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  764): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  764): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1701): CM callback handler got msg 524290
,I/WebViewFactory( 3379): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 17:26:09 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454433969553], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454433969530]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Validated
,D/ConnectivityService(  764): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  764): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1218): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
,I/LibraryLoader( 3379): Time to load native libraries: 2 ms (timestamps 7943-7945)
I/LibraryLoader( 3379): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3379): Binding Chromium to main looper Looper (main, tid 1) {16759c90}
,I/LibraryLoader( 3379): Expected native library version number "",actual native library version number ""
I/chromium( 3379): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3379): Initializing chromium process, singleProcess=true
,W/art     ( 3379): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3379): ApplicationContext is null in ApplicationStatus
,W/chromium( 3379): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3379): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3379): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3379): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/ConnectivityManager.CallbackHandler( 1701): CM callback handler got msg 524290
,W/AudioManagerAndroid( 3379): Requires BLUETOOTH permission
,I/NSApplication( 3379): Starting up...
,I/ActivityManager(  764): Killing 2763:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  764): failed to open /acct/uid_10003/pid_2763/cgroup.procs: No such file or directory
,V/MusicLeanback( 2787): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1701): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1701): onCreate
,D/SystemUpdateService( 1701): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1701): active receiver: enabled
,I/iu.Environment( 1701): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1701): num queued entries: 0
I/iu.UploadsManager( 1701): num updated entries: 0
I/iu.SyncManager( 1701): NEXT; no task
I/SystemUpdateService( 1701): showing system update notification
,I/ValidateNoPeople(  764): skipping global notification
,V/SystemUpdateService( 1701): retry (wakeup: false) in 3599962 ms
,D/SystemUpdateService( 1701): onDestroy
,I/Babel   ( 1944): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3285): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3285): 
,D/ConnectivityService(  764): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3285): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3285): 
,I/jxcore-log( 3285): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3285): 
,I/jxcore-log( 3285): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3285): 
,I/jxcore-log( 3285): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3285): 
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  764): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2787): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2787): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1701): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1701): onCreate
,D/SystemUpdateService( 1701): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1701): active receiver: enabled
,E/GpsLocationProvider(  764): No APN found to select.
,I/SystemUpdateService( 1701): showing system update notification
,I/ValidateNoPeople(  764): skipping global notification
,V/SystemUpdateService( 1701): retry (wakeup: false) in 3599958 ms
,D/SystemUpdateService( 1701): onDestroy
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  764): Explicit concurrent mark sweep GC freed 45216(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 820us total 70.296ms
,I/jxcore-log( 3285): Test app app.js loaded
I/jxcore-log( 3285): 
,I/chromium( 3285): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3285): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3285): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3285): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3285): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3285): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3285): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3285): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3285): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3285): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3285): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@110d59e7 added. We now have 1 listener(s)
,I/jxcore-log( 3285): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3285): 
,D/Finsky  ( 2680): [265] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2680): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1627): Vacuum at: now=1454433990010 tag=VacuumService
,I/PhenotypeConfigurator( 1627): Scheduling Phenotype for one-off execution 1291 seconds from now (1454433990437)
,D/GetConfigurationSnapshotOperation( 1627): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1627): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1627): Using platform SSLCertificateSocketFactory
,I/ClearcutLoggerApiImpl( 1627): disconnect managed GoogleApiClient
,I/ActivityManager(  764): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3601 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3601): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3601):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3601):   adb logcat -s GAv4
,W/GAv4    ( 3601): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3601): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3601): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  764): Killing 2729:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  764): Client connection lost with reason: 4
,W/libprocessgroup(  764): failed to open /acct/uid_1000/pid_2729/cgroup.procs: No such file or directory
,I/ActivityManager(  764): Killing 2618:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  764): failed to open /acct/uid_10070/pid_2618/cgroup.procs: No such file or directory
,W/bt-smp  ( 2130): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2130): Plain text(LSB ~ MSB) = 3a f6 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2130): Encrypted text(LSB ~ MSB) = 21 6b ef 6b 1b 22 03 23 92 5e c4 f0 6c 9e 17 50 
W/bt-btm  ( 2130): Stopping oneshot timer
,I/EventLogService( 1701): Aggregate from 1454432401225 (log), 1454432401225 (data)
,I/UsageStatsService(  764): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
