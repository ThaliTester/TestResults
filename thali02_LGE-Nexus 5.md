#### Test 58135655812b57f_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3078): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3078):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3078):   adb logcat -s GAv4
W/GAv4    ( 3078): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3078): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3078): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3078): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2677): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3078): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3078): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  759): Killing 2392:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
V/JNIHelp ( 3078): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3078): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3078): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2392/cgroup.procs: No such file or directory
V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1711): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1711): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1711): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1711): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3151): 
D/AndroidRuntime( 3151): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3151): CheckJNI is OFF
D/AndroidRuntime( 3151): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 3151): Shutting down VM
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3172 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/MicrophoneInputStream( 1371): mic_close gfk@107c3646
D/audio_hw_primary(  184): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  184): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1371): Hotword detection finished
I/HotwordRecognitionRnr( 1371): Stopping hotword detection.
I/WebViewFactory( 3172): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3172): Time to load native libraries: 2 ms (timestamps 5987-5989)
,I/LibraryLoader( 3172): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3172): Binding Chromium to main looper Looper (main, tid 1) {2aab5720}
I/LibraryLoader( 3172): Expected native library version number "",actual native library version number ""
I/chromium( 3172): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3172): Initializing chromium process, singleProcess=true
,W/art     ( 3172): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3172): ApplicationContext is null in ApplicationStatus
,W/chromium( 3172): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3172): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3172): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3172): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/PowerManagerService(  759): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  759): Sleeping (uid 1000)...
,I/Adreno-EGL(  759): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/PermissionCache(  177): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (113 us)
,D/audio_hw_primary(  184): adev_set_parameters: enter: screen_state=on
E/audio_a2dp_hw(  184): adev_set_parameters: ERROR: set param called even when stream out is null
,E/native  (  759): do suspend false
,D/BluetoothManagerService(  759): Message: 20
,D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5508d28:true
,W/art     ( 3172): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3172): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3172): CordovaWebView is running on device made by: LGE
,W/art     ( 3172): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3172): Attempt to remove local handle scope entry from IRT, ignoring
,D/SurfaceFlinger(  177): shader cache generated - 24 shaders in 158.537338 ms
,D/OpenGLRenderer( 3172): Render dirty regions requested: true
,D/Atlas   ( 3172): Validating map...
,D/audio_hw_primary(  184): adev_set_parameters: enter: screen_state=off
,E/audio_a2dp_hw(  184): adev_set_parameters: ERROR: set param called even when stream out is null
,E/native  (  759): do suspend true
,W/chromium( 3172): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3172): Initialized EGL, version 1.4
D/OpenGLRenderer( 3172): Enabling debug mode 0
,I/Keyboard.Facilitator( 1088): onFinishInput()
,W/IInputConnectionWrapper( 3172): showStatusIcon on inactive InputConnection
,W/BindingManager( 3172): Cannot call determinedVisibility() - never saw a connection for the pid: 3172
,D/JsMessageQueue( 3172): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3172): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
,I/chromium( 3172): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/Sensors (  191): sns_acm_mr.c(432):Transport error -45
,I/DisplayManagerService(  759): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  759): Display changed displayId=0
,D/SurfaceFlinger(  177): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  177): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  177): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  759): Excessive delay in setPowerMode(): 297ms
,I/ActivityManager(  759): Killing 2486:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10080/pid_2486/cgroup.procs: No such file or directory
,W/jxcore-log( 3172): Initializing JXcore engine
W/jxcore-log( 3172): JXcore engine is ready
,W/Thread-302( 3243): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7998]" dev="sockfs" ino=7998 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-302( 3243): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-302( 3243): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8427]" dev="sockfs" ino=8427 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-302( 3243): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17355]" dev="sockfs" ino=17355 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3172): Starting JXcore engine
,W/jxcore-log( 3172): Platform android
W/jxcore-log( 3172): 
W/jxcore-log( 3172): Process ARCH arm
W/jxcore-log( 3172): 
,I/jxcore-log( 3172): JXcore Cordova bridge is ready!
I/jxcore-log( 3172): 
W/jxcore-log( 3172): JXcore engine is started
,I/jxcore-log( 3172): Toggling radios to true
I/jxcore-log( 3172): 
,D/BluetoothAdapter( 3172): enable(): BT is already enabled..!
,D/WifiService(  759): New client listening to asynchronous messages
D/WifiService(  759): setWifiEnabled: true pid=3172, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3172): Radios toggled
I/jxcore-log( 3172): 
,I/jxcore-log( 3172): My device name is: LGE-Nexus 5
I/jxcore-log( 3172): 
,I/wpa_supplicant(  979): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  759): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1668): Read error: ssl=0x9dd49e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1668): SSL shutdown failed: ssl=0x9dd49e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiStateMachine(  759): Start Disconnecting Watchdog 1
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,I/wpa_supplicant(  979): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  759): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Disconnected - quitting
D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1272): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityManager.CallbackHandler( 1711): CM callback handler got msg 524292
,I/ActivityManager(  759): Killing 2091:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10038/pid_2091/cgroup.procs: No such file or directory
,I/wpa_supplicant(  979): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  979): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  979): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  979): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  759): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
E/WifiStateMachine(  759): Start Dhcp Watchdog 2
,E/native  (  759): do suspend false
,E/WifiStateMachine(  759): scanCount==0 - aborting
,I/dhcpcd  ( 3287): version 5.5.6 starting
E/dhcpcd  ( 3287): get_duid: Read-only file system
,I/dhcpcd  ( 3287): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3287): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3287): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
D/Tethering(  759): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2789): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1711): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1711): onCreate
,D/SystemUpdateService( 1711): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1711): active receiver: enabled
,E/GpsLocationProvider(  759): No APN found to select.
,I/SystemUpdateService( 1711): showing system update notification
,I/iu.Environment( 1711): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ValidateNoPeople(  759): skipping global notification
,E/GpsLocationProvider(  759): No APN found to select.
,V/SystemUpdateService( 1711): retry (wakeup: false) in 3599987 ms
,I/iu.UploadsManager( 1711): num queued entries: 0
I/iu.UploadsManager( 1711): num updated entries: 0
I/iu.SyncManager( 1711): NEXT; no task
,I/Babel   ( 1923): connection state changed from CONNECTED to DISCONNECTED
,E/native  (  759): do suspend true
,I/ActivityManager(  759): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3346 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  759): Adding iface wlan0 to network 101
E/WifiStateMachine(  759): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  759): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  759): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  759): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  759): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/SystemUpdateService( 1711): onDestroy
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1711): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 16:23:59 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454948639799], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454948639785]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Validated
D/ConnectivityService(  759): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1272): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1711): CM callback handler got msg 524290
,I/GAv4    ( 3346): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3346):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3346):   adb logcat -s GAv4
,W/GAv4    ( 3346): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3346): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3346): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Finsky  ( 2677): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1668): Explicit concurrent mark sweep GC freed 31890(1979KB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 21MB/35MB, paused 678us total 31.080ms
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 3346): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3346): Time to load native libraries: 3 ms (timestamps 1949-1952)
I/LibraryLoader( 3346): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3346): Binding Chromium to main looper Looper (main, tid 1) {23c66212}
,I/LibraryLoader( 3346): Expected native library version number "",actual native library version number ""
,I/chromium( 3346): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3346): Initializing chromium process, singleProcess=true
W/art     ( 3346): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3346): ApplicationContext is null in ApplicationStatus
,W/chromium( 3346): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3346): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3346): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3346): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3346): Requires BLUETOOTH permission
,I/NSApplication( 3346): Starting up...
,V/MusicLeanback( 2789): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1711): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/art     (  759): Explicit concurrent mark sweep GC freed 46845(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 1.095ms total 91.660ms
,D/SystemUpdateService( 1711): onCreate
,D/SystemUpdateService( 1711): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1711): active receiver: enabled
I/iu.Environment( 1711): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1711): num queued entries: 0
,I/iu.UploadsManager( 1711): num updated entries: 0
,I/iu.SyncManager( 1711): NEXT; no task
,I/SystemUpdateService( 1711): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1711): retry (wakeup: false) in 3599970 ms
,D/SystemUpdateService( 1711): onDestroy
,I/Babel   ( 1923): connection state changed from DISCONNECTED to CONNECTED
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2677): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2677): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2677): untagSocket(37) failed with errno -22
,D/Finsky  ( 2677): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3172): 
,I/ActivityManager(  759): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3434 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/ConnectivityService(  759): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3434): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3434): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3434): VM with version 2.1.0 has multidex support
I/MultiDex( 3434): install
I/MultiDex( 3434): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3434): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3434): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3434): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b5a1c62: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3434): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1668): callingUid 10008, callindPid: 1668
,E/MDM     ( 1668): [229] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1668): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 1711): Restart initialization of location
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 3434): Reading stored module config
W/GCoreFlp( 1668): No location to return for getLastLocation()
W/FusedLocationProvider( 1668): location=null
,D/ChimeraCfgMgr( 3434): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/qtaguid ( 2677): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2677): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2677): untagSocket(37) failed with errno -22
,D/NativeLibraryUtils( 3434): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 3434): Connecting to CarCallService...
,I/art     ( 3434): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3434): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3434): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3434): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 3434): Creating a new PhoneAdapter instance
,W/ActivityManager(  759): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3434): setListener: com.google.android.gms.car.dn@516b699
,W/ActivityManager(  759): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3434): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3434): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3434): Package validated; name: com.android.vending
,V/Finsky  ( 2677): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3172): 
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3172): 
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3172): 
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3172): 
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3172): 
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3172): 
,I/jxcore-log( 3172): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3172): 
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2677): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2677): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2677): untagSocket(37) failed with errno -22
,W/ResourcesManager( 2677): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2677): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2677): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2677): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1668): client connected with version: 8296000
,D/Finsky  ( 2677): [270] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2677): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2677): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  759): Killing 2596:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/ActivityManager(  759): Killing 2641:com.google.android.gm.exchange/u0a69 (adj 15): empty #18
,W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_2596/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10069/pid_2641/cgroup.procs: No such file or directory
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2789): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2789): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1711): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1711): onCreate
,D/SystemUpdateService( 1711): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1711): active receiver: enabled
,I/SystemUpdateService( 1711): showing system update notification
,E/GpsLocationProvider(  759): No APN found to select.
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1711): retry (wakeup: false) in 3599973 ms
,D/SystemUpdateService( 1711): onDestroy
,I/jxcore-log( 3172): Test app app.js loaded
I/jxcore-log( 3172): 
,I/chromium( 3172): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3172): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@247d4f62 added. We now have 1 listener(s)
,I/jxcore-log( 3172): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3172): 
,D/CAR.SERVICE( 3434): mConnectedToCar = false, abort
,E/ActivityThread( 3434): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@747dc61 that was originally bound here
E/ActivityThread( 3434): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@747dc61 that was originally bound here
E/ActivityThread( 3434): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3434): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3434): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3434): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3434): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3434): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3434): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3434): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3434): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3434): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3434): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3434): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3434): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3434): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3434): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3434): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3434): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3434): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3434): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3434): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3434): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3434): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3434): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3434): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@a9d23e0 that was originally bound here
E/ActivityThread( 3434): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@a9d23e0 that was originally bound here
E/ActivityThread( 3434): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3434): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3434): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3434): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3434): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3434): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3434): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3434): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3434): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3434): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3434): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3434): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3434): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3434): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3434): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3434): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3434): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3434): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3434): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3434): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3434): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3434): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  759): Unbind failed: could not find connection for android.os.BinderProxy@4c92438
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2677): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2677): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1668): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1668): Vacuum at: now=1454948671398 tag=VacuumService
,I/PhenotypeConfigurator( 1668): Scheduling Phenotype for one-off execution 9084 seconds from now (1454948671871)
,D/GetConfigurationSnapshotOperation( 1668): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1668): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1668): Using platform SSLCertificateSocketFactory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1088): run()
I/Keyboard.Facilitator( 1088): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1668): disconnect managed GoogleApiClient
,I/jxcore-log( 3172): --= Surplus to requirements =--
I/jxcore-log( 3172): 
I/jxcore-log( 3172): ****TEST TOOK:  ms ****
I/jxcore-log( 3172): 
I/jxcore-log( 3172): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3172): 
,D/AndroidRuntime( 3594): 
D/AndroidRuntime( 3594): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3594): CheckJNI is OFF
,D/AndroidRuntime( 3594): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 3172:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,D/WifiService(  759): Client connection lost with reason: 4
I/WindowState(  759): WIN DEATH: Window{34bf5a04 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  759):   Force finishing activity ActivityRecord{1cb383f u0 com.test.thalitest/.MainActivity t216}
,W/PackageSettings(  759): Skipping PackageSetting{3c76efb4 com.example.hello/10278} due to missing metadata
,V/ActivityManager(  759): Display changed displayId=0
,W/ActivityManager(  759): Spurious death for ProcessRecord{2a7859b9 3172:com.test.thalitest/u0a270}, curProc for 3172: null
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1371): Explicit concurrent mark sweep GC freed 7751(552KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 315us total 20.229ms
,I/art     ( 1316): Explicit concurrent mark sweep GC freed 7261(546KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 540us total 16.689ms
,I/art     ( 1711): Explicit concurrent mark sweep GC freed 3932(206KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 26.256ms total 54.564ms
,I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1668): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1088): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1088): run()
,I/Decoder ( 1088): createOrResetDecoder
,D/VoicemailCleanupService( 1384): Cleaning up data for package: com.test.thalitest
I/LibraryLoader( 1467): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,I/art     (  759): Explicit concurrent mark sweep GC freed 37979(1920KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.549ms total 84.601ms
,I/art     (  759): WaitForGcToComplete blocked for 13.600ms for cause Explicit
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1088): run()
I/LibraryLoader( 1467): Time to load native libraries: 68 ms (timestamps 2642-2710)
I/LibraryLoader( 1467): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1467): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1467): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1467): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  759): Explicit concurrent mark sweep GC freed 2409(128KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.385ms total 84.408ms
,I/art     (  759): WaitForGcToComplete blocked for 109.574ms for cause Explicit
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1088): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1088): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1088): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1088): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1088): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1088): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1088): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1088): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1088): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1088): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1088): run()
I/StatsUtilsManager( 1088): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1088): shouldRecordStats() = Too Soon
,I/OpenGLRenderer(  946): Initialized EGL, version 1.4
D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
,D/OpenGLRenderer(  946): Enabling debug mode 0
,I/UpdateIcingCorporaServi( 1371): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1316): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@224008d9 new=com.google.android.velvet.VelvetApplication@224008d9
,I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3638 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  759): removeObsoleteFile: deleting file=216_task.xml
,I/art     (  759): Explicit concurrent mark sweep GC freed 5093(301KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.159ms total 97.325ms
,W/art     (  946): Attempt to remove local handle scope entry from IRT, ignoring
,W/InputMethodManagerService(  759): Got RemoteException sending setActive(false) notification to pid 3172 uid 10270
,I/Keyboard.Facilitator( 1088): onFinishInput()
,I/UpdateIcingCorporaServi( 1371): UpdateCorporaTask done [took 117 ms] updated apps [took 117 ms] 
,W/ContextImpl( 3638): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1711): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1711): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1711): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1711): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1711): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1711): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1668): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1668): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Keyboard.Facilitator( 1088): onFinishInput()
,I/LocationSettingsChecker( 1711): Removing dialog suppression flag for package com.test.thalitest
,I/ActivityManager(  759): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3672 uid=10039 gids={50039, 9997} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1711): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1711): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1711): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1711): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1711): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1711): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1711): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/AndroidRuntime( 3594): Shutting down VM
,I/GMPM-SVC( 1711): App measurement is starting up, version: 8489
I/GMPM-SVC( 1711): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Launcher( 1316): Deferring update until onResume
,D/gH_CompatibleDatabase( 1711): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1711): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1711): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1711): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1711): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1711): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 1711): Using Auth Proxy for data requests.
I/ActivityManager(  759): Killing 2769:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/ResourcesManager( 1316): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1316): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1316): Deferring update until onResume
,W/IInputConnectionWrapper(  946): showStatusIcon on inactive InputConnection
,W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2769/cgroup.procs: No such file or directory
,W/BaseAppContext( 1711): Using Auth Proxy for data requests.
,I/Icing   ( 1711): doRemovePackageData com.test.thalitest
,I/ActivityManager(  759): Killing 2743:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  759): Client connection lost with reason: 4
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2743/cgroup.procs: No such file or directory
,I/ActivityManager(  759): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3701 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 2615:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2615/cgroup.procs: No such file or directory
,D/ExternalStorage( 3701): After updating volumes, found 1 active roots
,W/ResourcesManager( 3078): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3078): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3672): Update found 7 roots in 318ms

```
