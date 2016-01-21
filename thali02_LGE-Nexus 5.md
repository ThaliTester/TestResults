#### Test 56672827b6f75d5_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1718): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1718): Module APK com.google.android.play.games already loaded
V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GAv4    ( 3151): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3151):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3151):   adb logcat -s GAv4
W/GAv4    ( 3151): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3151): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3151): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3151): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
--------- beginning of system
I/ActivityManager(  758): Killing 2434:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
W/ResourcesManager( 3151): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3151): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  758): failed to open /acct/uid_1000/pid_2434/cgroup.procs: No such file or directory
I/qtaguid ( 2703): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2703): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2703): untagSocket(37) failed with errno -22
D/Finsky  ( 2703): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
V/JNIHelp ( 3151): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/WearableService( 1652): callingUid 10008, callindPid: 1652
D/LocationInitializer( 1718): Restart initialization of location
D/AuthorizationBluetoothService( 1652): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1652): [234] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1652): No location to return for getLastLocation()
W/FusedLocationProvider( 1652): location=null
W/System  ( 3151): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3151): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2703): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2703): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 2703): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/Finsky  ( 2703): [1] DailyHygiene.access$600: Logging device features
D/DeviceConnectionService( 1652): client connected with version: 8296000
D/Finsky  ( 2703): [270] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2703): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2703): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1718): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1718): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1718): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1718): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/ActivityManager(  758): Killing 2148:com.google.android.deskclock/u0a38 (adj 15): empty #17
I/ActivityManager(  758): Killing 2525:com.google.android.youtube/u0a80 (adj 15): empty #18
W/libprocessgroup(  758): failed to open /acct/uid_10038/pid_2148/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10080/pid_2525/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3225): 
D/AndroidRuntime( 3225): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3225): CheckJNI is OFF
I/ActivityManager(  758): Killing 2674:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
D/AndroidRuntime( 3225): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  758): failed to open /acct/uid_10069/pid_2674/cgroup.procs: No such file or directory
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  758): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3246 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3225): Shutting down VM
V/ActivityManager(  758): Display changed displayId=0
I/WebViewFactory( 3246): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3246): Time to load native libraries: 2 ms (timestamps 8644-8646)
I/LibraryLoader( 3246): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3246): Binding Chromium to main looper Looper (main, tid 1) {39da0779}
I/LibraryLoader( 3246): Expected native library version number "",actual native library version number ""
I/chromium( 3246): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3246): Initializing chromium process, singleProcess=true
W/art     ( 3246): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3246): ApplicationContext is null in ApplicationStatus
,W/chromium( 3246): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3246): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3246): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3246): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  758): Message: 20
,D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cbb8a75:true
,W/art     ( 3246): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3246): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3246): CordovaWebView is running on device made by: LGE
,W/art     ( 3246): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3246): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3246): Render dirty regions requested: true
,D/Atlas   ( 3246): Validating map...
,W/chromium( 3246): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3246): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3246): Enabling debug mode 0
,W/BindingManager( 3246): Cannot call determinedVisibility() - never saw a connection for the pid: 3246
,W/IInputConnectionWrapper( 3246): showStatusIcon on inactive InputConnection
,I/ActivityManager(  758): Displayed com.test.thalitest/.MainActivity: +471ms (total +57s55ms)
,D/JsMessageQueue( 3246): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3246): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258391296
,I/chromium( 3246): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3246): Initializing JXcore engine
W/jxcore-log( 3246): JXcore engine is ready
,W/Thread-306( 3294): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8160]" dev="sockfs" ino=8160 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3294): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-306( 3294): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6505]" dev="sockfs" ino=6505 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3294): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19733]" dev="sockfs" ino=19733 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3246): Starting JXcore engine
,W/jxcore-log( 3246): Platform android
W/jxcore-log( 3246): 
,W/jxcore-log( 3246): Process ARCH arm
W/jxcore-log( 3246): 
,I/jxcore-log( 3246): JXcore Cordova bridge is ready!
I/jxcore-log( 3246): 
,W/jxcore-log( 3246): JXcore engine is started
,I/jxcore-log( 3246): Toggling radios to true
I/jxcore-log( 3246): 
,D/BluetoothAdapter( 3246): enable(): BT is already enabled..!
,D/WifiService(  758): setWifiEnabled: true pid=3246, uid=10270
E/WifiService(  758): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3246): Radios toggled
I/jxcore-log( 3246): 
I/jxcore-log( 3246): My device name is: LGE-Nexus 5
I/jxcore-log( 3246): 
,I/wpa_supplicant(  980): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  758): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  758): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1652): Read error: ssl=0x9d753e00: I/O error during system call, Connection timed out
,I/art     (  758): Explicit concurrent mark sweep GC freed 19846(915KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.228ms total 71.768ms
D/WifiService(  758): New client listening to asynchronous messages
,V/NativeCrypto( 1652): SSL shutdown failed: ssl=0x9d753e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  758): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  980): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/ConnectivityService(  758): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/native  (  758): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService(  758): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  758): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1718): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Disconnected - quitting
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  758): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1233): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  758): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WifiNetworkAgent(  758): NetworkAgent: NetworkAgent channel lost
,D/CAR.SERVICE( 3113): mConnectedToCar = false, abort
E/ActivityThread( 3113): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@194739a6 that was originally bound here
E/ActivityThread( 3113): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@194739a6 that was originally bound here
E/ActivityThread( 3113): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3113): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3113): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3113): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3113): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3113): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3113): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3113): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3113): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3113): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3113): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3113): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3113): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3113): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3113): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3113): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3113): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3113): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3113): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3113): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3113): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3113): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3113): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3113): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@6205539 that was originally bound here
E/ActivityThread( 3113): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@6205539 that was originally bound here
E/ActivityThread( 3113): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3113): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3113): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3113): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3113): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3113): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3113): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3113): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3113): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3113): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3113): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3113): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3113): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3113): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3113): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3113): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3113): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3113): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3113): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3113): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3113): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3113): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  758): Unbind failed: could not find connection for android.os.BinderProxy@76fc786
,I/wpa_supplicant(  980): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  980): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  980): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  980): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  758): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  758): Start Dhcp Watchdog 2
,E/native  (  758): do suspend false
,E/WifiStateMachine(  758): scanCount==0 - aborting
,I/dhcpcd  ( 3329): version 5.5.6 starting
E/dhcpcd  ( 3329): get_duid: Read-only file system
,I/dhcpcd  ( 3329): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3329): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,I/dhcpcd  ( 3329): wlan0: leased 192.168.1.114 for 86400 seconds
,V/MusicLeanback( 2808): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1718): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1718): onCreate
,D/SystemUpdateService( 1718): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1718): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1718): num queued entries: 0
I/iu.UploadsManager( 1718): num updated entries: 0
I/iu.SyncManager( 1718): NEXT; no task
,I/SystemUpdateService( 1718): active receiver: enabled
,I/SystemUpdateService( 1718): showing system update notification
I/Babel   ( 1926): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  758): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3349 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/GpsLocationProvider(  758): No APN found to select.
,E/GpsLocationProvider(  758): No APN found to select.
,V/SystemUpdateService( 1718): retry (wakeup: false) in 3599912 ms
,D/SystemUpdateService( 1718): onDestroy
,I/ValidateNoPeople(  758): skipping global notification
,I/GAv4    ( 3349): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3349):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3349):   adb logcat -s GAv4
,W/GAv4    ( 3349): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3349): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3349): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  758): do suspend true
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  758): Adding iface wlan0 to network 101
,E/WifiStateMachine(  758): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  758): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  758): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  758): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  758): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  758): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  758): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  758): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  758): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1718): CM callback handler got msg 524290
,I/WebViewFactory( 3349): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3349): Time to load native libraries: 2 ms (timestamps 4787-4789)
I/LibraryLoader( 3349): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3349): Binding Chromium to main looper Looper (main, tid 1) {3ac3d23d}
I/LibraryLoader( 3349): Expected native library version number "",actual native library version number ""
I/chromium( 3349): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3349): Initializing chromium process, singleProcess=true
W/art     ( 3349): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3349): ApplicationContext is null in ApplicationStatus
,W/chromium( 3349): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3349): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3349): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3349): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 16:44:10 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453394650201], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453394650177]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Validated
D/ConnectivityService(  758): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1233): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1718): CM callback handler got msg 524290
,W/AudioManagerAndroid( 3349): Requires BLUETOOTH permission
,I/NSApplication( 3349): Starting up...
,I/jxcore-log( 3246): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3246): 
,I/ActivityManager(  758): Killing 2629:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10045/pid_2629/cgroup.procs: No such file or directory
,V/MusicLeanback( 2808): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1718): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1718): onCreate
D/SystemUpdateService( 1718): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1718): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1718): num queued entries: 0
I/iu.UploadsManager( 1718): num updated entries: 0
I/iu.SyncManager( 1718): NEXT; no task
,I/SystemUpdateService( 1718): active receiver: enabled
,I/SystemUpdateService( 1718): showing system update notification
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1718): retry (wakeup: false) in 3599986 ms
,D/SystemUpdateService( 1718): onDestroy
,I/Babel   ( 1926): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3246): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3246): 
,I/jxcore-log( 3246): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3246): 
,I/jxcore-log( 3246): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3246): 
,I/jxcore-log( 3246): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3246): 
,I/jxcore-log( 3246): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3246): 
,I/jxcore-log( 3246): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3246): 
,D/ConnectivityService(  758): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3246): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3246): 
,I/jxcore-log( 3246): Test app app.js loaded
I/jxcore-log( 3246): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3246): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3246): BLE advertisement is supported
I/jxcore-log( 3246): 
,I/chromium( 3246): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2808): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2808): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1718): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1718): onCreate
,D/SystemUpdateService( 1718): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1718): active receiver: enabled
,I/SystemUpdateService( 1718): showing system update notification
,E/GpsLocationProvider(  758): No APN found to select.
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1718): retry (wakeup: false) in 3599968 ms
,D/SystemUpdateService( 1718): onDestroy
,D/Finsky  ( 2703): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2703): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1652): Vacuum at: now=1453394672054 tag=VacuumService
,I/PhenotypeConfigurator( 1652): Scheduling Phenotype for one-off execution 9911 seconds from now (1453394672450)
,D/GetConfigurationSnapshotOperation( 1652): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1652): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1652): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1652): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  758): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3572 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3572): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3572):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3572):   adb logcat -s GAv4
,W/GAv4    ( 3572): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3572): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3572): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  758): Killing 2784:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10003/pid_2784/cgroup.procs: No such file or directory
,I/ClearcutLoggerApiImpl( 1652): disconnect managed GoogleApiClient
,I/EventLogService( 1718): Aggregate from 1453392901198 (log), 1453392901198 (data)
,I/jxcore-log( 3246): --= Surplus to requirements =--
I/jxcore-log( 3246): 
,I/jxcore-log( 3246): ****TEST TOOK:  ms ****
I/jxcore-log( 3246): 
I/jxcore-log( 3246): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3246): 
,D/AndroidRuntime( 3649): 
D/AndroidRuntime( 3649): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3649): CheckJNI is OFF
,D/AndroidRuntime( 3649): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  758): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  758): Killing 3246:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  758): WIN DEATH: Window{2504fae5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  758): Client connection lost with reason: 4
,W/PackageSettings(  758): Skipping PackageSetting{1af06c7d com.example.hello/10278} due to missing metadata
,I/ActivityManager(  758):   Force finishing activity ActivityRecord{9a10d81 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  758): Spurious death for ProcessRecord{cdb4985 3246:com.test.thalitest/u0a270}, curProc for 3246: null
,I/ActivityManager(  758): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1331): Explicit concurrent mark sweep GC freed 3987(295KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 481us total 19.920ms
,I/art     ( 1355): Explicit concurrent mark sweep GC freed 437(29KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 395us total 26.239ms
,I/InputReader(  758): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1067): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1652): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1718): Explicit concurrent mark sweep GC freed 8931(487KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 22MB/30MB, paused 582us total 58.653ms
,I/Keyboard.Facilitator.DecoderInitializer( 1067): run()
,I/Decoder ( 1067): createOrResetDecoder
,D/VoicemailCleanupService( 1391): Cleaning up data for package: com.test.thalitest
,W/Launcher( 1331): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@10b23cbe new=com.google.android.velvet.VelvetApplication@10b23cbe
,I/UpdateIcingCorporaServi( 1355): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/LibraryLoader( 1537): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,I/art     (  758): Explicit concurrent mark sweep GC freed 53682(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 1.481ms total 95.126ms
,I/ActivityManager(  758): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3688 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  758): WaitForGcToComplete blocked for 73.998ms for cause Explicit
,I/LibraryLoader( 1537): Time to load native libraries: 67 ms (timestamps 6801-6868)
I/LibraryLoader( 1537): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
,I/chromium( 1537): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/art     ( 1537): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1537): Attempt to remove local handle scope entry from IRT, ignoring
,I/OpenGLRenderer(  946): Initialized EGL, version 1.4
,D/OpenGLRenderer(  946): Enabling debug mode 0
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1067): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1067): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loading LM = contacts
,W/ContextImpl( 3688): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/BackupManagerService(  758): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  758): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loading LM = history
I/UpdateIcingCorporaServi( 1355): UpdateCorporaTask done [took 151 ms] updated apps [took 151 ms] 
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1067): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1067): run()
,D/PackageBroadcastService( 1718): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1718): Clearing selected account for com.test.thalitest
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1067): run()
I/StatsUtilsManager( 1067): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1067): shouldRecordStats() = Too Soon
,D/TaskPersister(  758): removeObsoleteFile: deleting file=216_task.xml
,D/ChimeraCfgMgr( 1718): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1718): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1718): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1718): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1718): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1652): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1652): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1718): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1718): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,W/InputMethodManagerService(  758): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3dcde97 (uid=10034 pid=946)
,D/gH_MetricsDatabase( 1718): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1718): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1718): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1718): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1718): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/ActivityManager(  758): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3732 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 1718): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1718): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1718): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1718): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1718): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1718): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/art     (  758): Explicit concurrent mark sweep GC freed 9150(447KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.552ms total 209.210ms
,W/BaseAppContext( 1718): Using Auth Proxy for data requests.
,W/BaseAppContext( 1718): Using Auth Proxy for data requests.
,I/ActivityManager(  758): Killing 2766:com.android.settings/1000 (adj 15): empty #17
,I/GMPM-SVC( 1718): App measurement is starting up, version: 8489
I/GMPM-SVC( 1718): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,D/WifiService(  758): Client connection lost with reason: 4
,D/AndroidRuntime( 3649): Shutting down VM
,W/libprocessgroup(  758): failed to open /acct/uid_1000/pid_2766/cgroup.procs: No such file or directory
,I/Launcher( 1331): Deferring update until onResume
,I/Icing   ( 1718): doRemovePackageData com.test.thalitest
,W/ResourcesManager( 1331): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1331): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  758): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3763 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  758): Killing 2647:com.google.android.gm/u0a70 (adj 15): empty #17
,I/Launcher( 1331): Deferring update until onResume
,W/libprocessgroup(  758): failed to open /acct/uid_10070/pid_2647/cgroup.procs: No such file or directory
,I/ActivityManager(  758): Killing 2084:com.google.android.calendar/u0a31 (adj 15): empty #17
,D/ExternalStorage( 3763): After updating volumes, found 1 active roots
,W/libprocessgroup(  758): failed to open /acct/uid_10031/pid_2084/cgroup.procs: No such file or directory
,W/ResourcesManager( 3151): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3151): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3732): Update found 7 roots in 143ms
,D/Documents( 3732): Update found 7 roots in 61ms

```
