#### Test 5753124374916c2_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2635): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  762): Killing 2383:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
W/ResourcesManager( 3051): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3051): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  762): failed to open /acct/uid_1000/pid_2383/cgroup.procs: No such file or directory
V/JNIHelp ( 3051): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3051): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3051): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1628): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1628): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1628): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1628): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3123): 
D/AndroidRuntime( 3123): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3123): CheckJNI is OFF
D/AndroidRuntime( 3123): Calling main entry com.android.commands.am.Am
I/ActivityManager(  762): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  762): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3144 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3123): Shutting down VM
I/art     (  193): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 192us total 16.877ms
I/art     (  193): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.485ms
I/art     (  193): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 8.244ms
V/ActivityManager(  762): Display changed displayId=0
I/WebViewFactory( 3144): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3144): Time to load native libraries: 3 ms (timestamps 7229-7232)
I/LibraryLoader( 3144): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3144): Binding Chromium to main looper Looper (main, tid 1) {269db611}
I/LibraryLoader( 3144): Expected native library version number "",actual native library version number ""
I/chromium( 3144): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3144): Initializing chromium process, singleProcess=true
W/art     ( 3144): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3144): ApplicationContext is null in ApplicationStatus
W/chromium( 3144): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3144): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3144): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3144): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  762): Message: 20
D/BluetoothManagerService(  762): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@152f677a:true
,W/art     ( 3144): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3144): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3144): CordovaWebView is running on device made by: LGE
,W/art     ( 3144): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3144): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3144): Render dirty regions requested: true
,D/Atlas   ( 3144): Validating map...
,W/chromium( 3144): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3144): Initialized EGL, version 1.4
D/OpenGLRenderer( 3144): Enabling debug mode 0
,I/Keyboard.Facilitator( 1082): onFinishInput()
,W/IInputConnectionWrapper( 3144): showStatusIcon on inactive InputConnection
,I/ActivityManager(  762): Displayed com.test.thalitest/.MainActivity: +421ms (total +45s901ms)
,W/BindingManager( 3144): Cannot call determinedVisibility() - never saw a connection for the pid: 3144
,D/JsMessageQueue( 3144): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3144): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3144): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  762): Killing 2465:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10080/pid_2465/cgroup.procs: No such file or directory
,W/jxcore-log( 3144): Initializing JXcore engine
W/jxcore-log( 3144): JXcore engine is ready
,W/Thread-296( 3192): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8481]" dev="sockfs" ino=8481 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-296( 3192): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-296( 3192): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8553]" dev="sockfs" ino=8553 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-296( 3192): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19141]" dev="sockfs" ino=19141 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3144): Starting JXcore engine
,W/jxcore-log( 3144): Platform android
W/jxcore-log( 3144): 
W/jxcore-log( 3144): Process ARCH arm
W/jxcore-log( 3144): 
,I/ActivityManager(  762): Killing 2082:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10038/pid_2082/cgroup.procs: No such file or directory
,I/jxcore-log( 3144): JXcore Cordova bridge is ready!
I/jxcore-log( 3144): 
,W/jxcore-log( 3144): JXcore engine is started
,I/jxcore-log( 3144): Toggling radios to true
I/jxcore-log( 3144): 
,D/BluetoothAdapter( 3144): enable(): BT is already enabled..!
,D/WifiService(  762): New client listening to asynchronous messages
,D/WifiService(  762): setWifiEnabled: true pid=3144, uid=10270
E/WifiService(  762): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3144): Radios toggled
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): My device name is: LGE-Nexus 5
I/jxcore-log( 3144): 
,I/wpa_supplicant(  982): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  762): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  762): do suspend true
D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1603): Read error: ssl=0xaffd2e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1603): SSL shutdown failed: ssl=0xaffd2e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  762): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  762): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  982): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  762): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
D/ConnectivityService(  762): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1628): CM callback handler got msg 524292
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  762): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Disconnected - quitting
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  762): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1224): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  762): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  762): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  982): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  982): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  982): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  982): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  762): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  178): Setting iface cfg
E/WifiStateMachine(  762): Start Dhcp Watchdog 2
,E/native  (  762): do suspend false
,E/WifiStateMachine(  762): scanCount==0 - aborting
,I/dhcpcd  ( 3236): version 5.5.6 starting
,E/dhcpcd  ( 3236): get_duid: Read-only file system
,I/dhcpcd  ( 3236): wlan0: rebinding lease of 192.168.1.114
,D/Finsky  ( 2635): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2635): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  762): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3258 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dhcpcd  ( 3236): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,W/Finsky  ( 2635): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/ResourcesManager( 3258): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3258): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/dhcpcd  ( 3236): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  762): MasterInitialState.processMessage what=3
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  762): MasterInitialState.processMessage what=3
,I/MultiDex( 3258): VM with version 2.1.0 has multidex support
I/MultiDex( 3258): install
I/MultiDex( 3258): VM has multidex support, MultiDex support library is disabled.
,V/MusicLeanback( 2773): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1628): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1628): onCreate
,D/SystemUpdateService( 1628): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1628): active receiver: enabled
,I/SystemUpdateService( 1628): showing system update notification
,I/iu.Environment( 1628): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/Babel   ( 1941): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1628): num queued entries: 0
I/iu.UploadsManager( 1628): num updated entries: 0
I/iu.SyncManager( 1628): NEXT; no task
,I/ActivityManager(  762): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3288 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  762): No APN found to select.
,V/JNIHelp ( 3258): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ValidateNoPeople(  762): skipping global notification
,E/GpsLocationProvider(  762): No APN found to select.
,V/SystemUpdateService( 1628): retry (wakeup: false) in 3599892 ms
,D/SystemUpdateService( 1628): onDestroy
,E/native  (  762): do suspend true
,W/ActivityThread( 3258): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3258): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3658386b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3258): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 3258): Reading stored module config
,D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  762): Adding iface wlan0 to network 101
D/ChimeraCfgMgr( 3258): Loading module com.google.android.gms.car from APK com.google.android.gms
,E/WifiStateMachine(  762): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  762): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  762): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  762): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  762): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  762): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  762): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  762): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  762): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  762): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1628): CM callback handler got msg 524290
,I/GAv4    ( 3288): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3288):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3288):   adb logcat -s GAv4
,W/GAv4    ( 3288): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/NativeLibraryUtils( 3258): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 3258): Connecting to CarCallService...
,I/art     ( 3258): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3258): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/GAv4    ( 3288): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3288): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/CAR.SERVICE( 3258): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3258): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 3258): Creating a new PhoneAdapter instance
,W/ActivityManager(  762): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3258): setListener: com.google.android.gms.car.dn@846f636
W/ActivityManager(  762): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3258): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3258): Starting CarCallService with initial phone null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Feb 2016 14:14:30 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454681670534], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454681670495]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Validated
,D/ConnectivityService(  762): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1628): CM callback handler got msg 524290
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1224): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CAR.SERVICE( 3258): Package validated; name: com.android.vending
,I/art     (  762): Explicit concurrent mark sweep GC freed 40737(2010KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 973us total 54.217ms
,V/Finsky  ( 2635): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/WebViewFactory( 3288): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3288): Time to load native libraries: 3 ms (timestamps 3043-3046)
,I/LibraryLoader( 3288): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3288): Binding Chromium to main looper Looper (main, tid 1) {39c125b}
I/LibraryLoader( 3288): Expected native library version number "",actual native library version number ""
I/chromium( 3288): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3288): Initializing chromium process, singleProcess=true
W/art     ( 3288): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3288): ApplicationContext is null in ApplicationStatus
,W/chromium( 3288): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3288): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3288): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3288): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AudioManagerAndroid( 3288): Requires BLUETOOTH permission
,I/NSApplication( 3288): Starting up...
,V/MusicLeanback( 2773): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1628): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1628): onCreate
D/SystemUpdateService( 1628): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1628): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1628): num queued entries: 0
,I/iu.UploadsManager( 1628): num updated entries: 0
I/SystemUpdateService( 1628): active receiver: enabled
,I/iu.SyncManager( 1628): NEXT; no task
,I/SystemUpdateService( 1628): showing system update notification
,I/ValidateNoPeople(  762): skipping global notification
V/SystemUpdateService( 1628): retry (wakeup: false) in 3599978 ms
,D/SystemUpdateService( 1628): onDestroy
,D/WearableService( 1603): callingUid 10008, callindPid: 1603
,E/MDM     ( 1603): [230] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1603): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1628): Restart initialization of location
,I/Babel   ( 1941): connection state changed from DISCONNECTED to CONNECTED
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1603): No location to return for getLastLocation()
,W/FusedLocationProvider( 1603): location=null
,I/jxcore-log( 3144): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3144): 
,W/ResourcesManager( 2635): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2635): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2635): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ConnectivityService(  762): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/Finsky  ( 2635): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1603): client connected with version: 8296000
,D/Finsky  ( 2635): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2635): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2635): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  762): Killing 2562:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/jxcore-log( 3144): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3144): 
,I/jxcore-log( 3144): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3144): 
,I/ActivityManager(  762): Killing 2606:com.google.android.gm.exchange/u0a69 (adj 15): empty #18
,W/libprocessgroup(  762): failed to open /acct/uid_10045/pid_2562/cgroup.procs: No such file or directory
,W/libprocessgroup(  762): failed to open /acct/uid_10069/pid_2606/cgroup.procs: No such file or directory
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  762): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2773): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2773): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/SystemUpdateService( 1628): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1628): onCreate
,D/SystemUpdateService( 1628): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1628): active receiver: enabled
,I/SystemUpdateService( 1628): showing system update notification
,E/GpsLocationProvider(  762): No APN found to select.
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1628): retry (wakeup: false) in 3599973 ms
,D/SystemUpdateService( 1628): onDestroy
,D/CAR.SERVICE( 3258): mConnectedToCar = false, abort
,E/ActivityThread( 3258): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@307195e that was originally bound here
E/ActivityThread( 3258): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@307195e that was originally bound here
E/ActivityThread( 3258): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3258): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3258): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3258): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3258): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3258): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3258): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3258): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3258): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3258): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3258): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3258): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3258): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3258): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3258): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3258): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3258): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3258): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3258): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3258): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3258): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3258): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3258): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3258): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@5805bd1 that was originally bound here
E/ActivityThread( 3258): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@5805bd1 that was originally bound here
E/ActivityThread( 3258): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3258): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3258): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3258): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3258): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3258): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3258): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3258): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3258): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3258): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3258): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3258): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3258): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3258): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3258): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3258): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3258): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3258): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3258): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3258): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3258): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3258): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  762): Unbind failed: could not find connection for android.os.BinderProxy@1e383003
,I/jxcore-log( 3144): Test app app.js loaded
I/jxcore-log( 3144): 
,I/chromium( 3144): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3144): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3717c4f added. We now have 1 listener(s)
,I/jxcore-log( 3144): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3144): 
,D/Finsky  ( 2635): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2635): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  762): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3439 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3439): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3439):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3439):   adb logcat -s GAv4
,W/GAv4    ( 3439): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3439): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3439): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  762): Killing 2745:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10003/pid_2745/cgroup.procs: No such file or directory
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1603): Vacuum at: now=1454681701394 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1082): run()
I/Keyboard.Facilitator( 1082): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1603): disconnect managed GoogleApiClient
,I/ActivityManager(  762): Killing 2724:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  762): Client connection lost with reason: 4
,W/libprocessgroup(  762): failed to open /acct/uid_1000/pid_2724/cgroup.procs: No such file or directory
,W/bt-smp  ( 2147): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2147): Plain text(LSB ~ MSB) = 71 1f 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2147): Encrypted text(LSB ~ MSB) = 43 d0 b7 87 c7 b6 8d 2f 1d 47 fb 14 1c 25 99 a3 
,W/bt-btm  ( 2147): Stopping oneshot timer
,I/PhenotypeConfigurator( 1603): Scheduling Phenotype for one-off execution 3697 seconds from now (1454682571457)
,D/GetConfigurationSnapshotOperation( 1603): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1603): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1603): Using platform SSLCertificateSocketFactory
,I/art     ( 1603): Explicit concurrent mark sweep GC freed 51052(2MB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 21MB/36MB, paused 837us total 58.646ms
,E/DataBuffer( 1603): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@16ebf3cd)
,E/DataBuffer( 1603): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@44d7482)
,E/DataBuffer( 1603): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d066793)
E/DataBuffer( 1603): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2dfb13d0)
E/DataBuffer( 1603): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@36d0ffc9)
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  762): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
