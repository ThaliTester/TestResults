#### Test 58259810381ca4f_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1686): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1686): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3124): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3124):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3124):   adb logcat -s GAv4
W/GAv4    ( 3124): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3124): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3124): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3124): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2638): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  761): Killing 2388:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
W/ResourcesManager( 3124): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3124): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2388/cgroup.procs: No such file or directory
V/JNIHelp ( 3124): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3124): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3124): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1686): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1686): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1686): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1686): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3203): 
D/AndroidRuntime( 3203): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3203): CheckJNI is OFF
D/AndroidRuntime( 3203): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 3203): Shutting down VM
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3224 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/MicrophoneInputStream( 1402): mic_close gfk@46b627d
D/audio_hw_primary(  184): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  184): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1402): Hotword detection finished
I/HotwordRecognitionRnr( 1402): Stopping hotword detection.
I/WebViewFactory( 3224): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3224): Time to load native libraries: 1 ms (timestamps 5647-5648)
I/LibraryLoader( 3224): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3224): Binding Chromium to main looper Looper (main, tid 1) {1c89c3d5}
,I/LibraryLoader( 3224): Expected native library version number "",actual native library version number ""
,I/chromium( 3224): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3224): Initializing chromium process, singleProcess=true
,W/art     ( 3224): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3224): ApplicationContext is null in ApplicationStatus
,W/chromium( 3224): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3224): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3224): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3224): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
,D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19246bd6:true
,W/art     ( 3224): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3224): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3224): CordovaWebView is running on device made by: LGE
,W/art     ( 3224): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3224): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3224): Render dirty regions requested: true
,D/Atlas   ( 3224): Validating map...
,W/chromium( 3224): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3224): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3224): Enabling debug mode 0
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +466ms (total +43s809ms)
,I/Keyboard.Facilitator( 1103): onFinishInput()
,W/BindingManager( 3224): Cannot call determinedVisibility() - never saw a connection for the pid: 3224
,D/JsMessageQueue( 3224): Set native->JS mode to OnlineEventsBridgeMode
,I/PowerManagerService(  761): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  761): Sleeping (uid 1000)...
,I/Adreno-EGL(  761): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/PermissionCache(  176): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (124 us)
,D/audio_hw_primary(  184): adev_set_parameters: enter: screen_state=on
E/audio_a2dp_hw(  184): adev_set_parameters: ERROR: set param called even when stream out is null
,E/native  (  761): do suspend false
,D/jxcore_app_log( 3224): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3224): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Keyboard.Facilitator( 1103): onFinishInput()
,D/audio_hw_primary(  184): adev_set_parameters: enter: screen_state=off
E/audio_a2dp_hw(  184): adev_set_parameters: ERROR: set param called even when stream out is null
,E/native  (  761): do suspend true
,E/Sensors (  191): sns_acm_mr.c(432):Transport error -45
,I/DisplayManagerService(  761): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  761): Display changed displayId=0
D/SurfaceFlinger(  176): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  176): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  176): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  761): Excessive delay in setPowerMode(): 284ms
,I/ActivityManager(  761): Killing 2470:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/jxcore-log( 3224): Initializing JXcore engine
W/jxcore-log( 3224): JXcore engine is ready
,W/Thread-301( 3282): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8357]" dev="sockfs" ino=8357 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-301( 3282): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-301( 3282): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9460]" dev="sockfs" ino=9460 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-301( 3282): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17976]" dev="sockfs" ino=17976 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3224): Starting JXcore engine
,W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_2470/cgroup.procs: No such file or directory
,W/jxcore-log( 3224): Platform android
W/jxcore-log( 3224): 
W/jxcore-log( 3224): Process ARCH arm
W/jxcore-log( 3224): 
,I/jxcore-log( 3224): JXcore Cordova bridge is ready!
I/jxcore-log( 3224): 
W/jxcore-log( 3224): JXcore engine is started
,I/jxcore-log( 3224): Toggling radios to true
I/jxcore-log( 3224): 
,D/BluetoothAdapter( 3224): enable(): BT is already enabled..!
,D/WifiService(  761): New client listening to asynchronous messages
,D/WifiService(  761): setWifiEnabled: true pid=3224, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3224): Radios toggled
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): My device name is: LGE-Nexus 5
I/jxcore-log( 3224): 
,I/wpa_supplicant(  986): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  761): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1647): Read error: ssl=0xa4242e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1647): SSL shutdown failed: ssl=0xa4242e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  761): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  986): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  761): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1686): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1256): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  986): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  986): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  986): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  986): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
,E/WifiStateMachine(  761): Start Dhcp Watchdog 2
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/ActivityManager(  761): Killing 2127:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2127/cgroup.procs: No such file or directory
,I/dhcpcd  ( 3327): version 5.5.6 starting
E/dhcpcd  ( 3327): get_duid: Read-only file system
,I/dhcpcd  ( 3327): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3327): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3327): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  761): do suspend true
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  761): Adding iface wlan0 to network 101
,E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  761): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1686): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 09:41:44 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454578904014], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454578904002]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1256): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1686): CM callback handler got msg 524290
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1686): CM callback handler got msg 524295
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2770): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 2770): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2770): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1686): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1686): onCreate
,D/SystemUpdateService( 1686): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1686): active receiver: enabled
,I/SystemUpdateService( 1686): showing system update notification
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3395 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  761): No APN found to select.
,I/ValidateNoPeople(  761): skipping global notification
,E/GpsLocationProvider(  761): No APN found to select.
,V/SystemUpdateService( 1686): retry (wakeup: false) in 3599937 ms
,D/SystemUpdateService( 1686): onDestroy
,I/GAv4    ( 3395): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3395):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3395):   adb logcat -s GAv4
,W/GAv4    ( 3395): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3395): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3395): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  761): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/WebViewFactory( 3395): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3395): Time to load native libraries: 2 ms (timestamps 1520-1522)
,I/LibraryLoader( 3395): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3395): Binding Chromium to main looper Looper (main, tid 1) {1bcc957f}
,I/LibraryLoader( 3395): Expected native library version number "",actual native library version number ""
,I/chromium( 3395): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3395): Initializing chromium process, singleProcess=true
W/art     ( 3395): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3395): ApplicationContext is null in ApplicationStatus
,W/chromium( 3395): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3395): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3395): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3395): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3395): Starting up...
,I/ActivityManager(  761): Killing 2610:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/AudioManagerAndroid( 3395): Requires BLUETOOTH permission
,W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2610/cgroup.procs: No such file or directory
,V/MusicLeanback( 2770): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1686): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1686): onCreate
,I/art     (  761): Explicit concurrent mark sweep GC freed 52113(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 945us total 75.234ms
,D/SystemUpdateService( 1686): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1686): active receiver: enabled
,I/SystemUpdateService( 1686): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1686): retry (wakeup: false) in 3599930 ms
,D/SystemUpdateService( 1686): onDestroy
,I/jxcore-log( 3224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3224): 
,D/Finsky  ( 2638): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3224): 
,I/art     ( 1647): Explicit concurrent mark sweep GC freed 35790(2MB) AllocSpace objects, 31(496KB) LOS objects, 39% free, 21MB/35MB, paused 1.261ms total 42.874ms
,V/GLSActivity( 1647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3224): 
,V/GLSActivity( 1647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2638): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2638): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2638): untagSocket(37) failed with errno -22
,D/Finsky  ( 2638): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3469 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3469): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3469): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3469): VM with version 2.1.0 has multidex support
I/MultiDex( 3469): install
I/MultiDex( 3469): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3469): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3469): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3469): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2655ea8f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3469): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1647): callingUid 10008, callindPid: 1647
E/MDM     ( 1647): [230] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 3469): Reading stored module config
I/qtaguid ( 2638): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2638): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2638): untagSocket(37) failed with errno -22
D/AuthorizationBluetoothService( 1647): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 1686): Restart initialization of location
,V/GLSActivity( 1647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1647): No location to return for getLastLocation()
,W/FusedLocationProvider( 1647): location=null
,D/ChimeraCfgMgr( 3469): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3,
,I/NetworkMonitor( 2770): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2770): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1686): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1686): onCreate
,E/GpsLocationProvider(  761): No APN found to select.
D/SystemUpdateService( 1686): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 1686): active receiver: enabled
,I/SystemUpdateService( 1686): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,D/NativeLibraryUtils( 3469): Install completed successfully. count=14 extracted=0
,V/SystemUpdateService( 1686): retry (wakeup: false) in 3599960 ms
,D/SystemUpdateService( 1686): onDestroy
,D/CAR.SERVICE( 3469): Connecting to CarCallService...
,I/art     ( 3469): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3469): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3469): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3469): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 3469): Creating a new PhoneAdapter instance
,W/ActivityManager(  761): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3469): setListener: com.google.android.gms.car.dn@b761eaa
,W/ActivityManager(  761): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3469): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3469): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3469): Package validated; name: com.android.vending
,V/Finsky  ( 2638): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2638): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2638): Untagging socket 37 failed errno=-22
,W/NetworkManagementSocketTagger( 2638): untagSocket(37) failed with errno -22
,D/Finsky  ( 2638): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.apps.magazines to true
,D/Finsky  ( 2638): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.apps.magazines from  to d_AAAAAAADF8w=
,W/ResourcesManager( 2638): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2638): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2638): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2638): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1647): client connected with version: 8296000
,D/Finsky  ( 2638): [270] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2638): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2638): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  761): Killing 2566:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_2566/cgroup.procs: No such file or directory
,I/jxcore-log( 3224): Test app app.js loaded
I/jxcore-log( 3224): 
,I/chromium( 3224): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be9378d added. We now have 1 listener(s)
,I/jxcore-log( 3224): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3224): 
,D/CAR.SERVICE( 3469): mConnectedToCar = false, abort
,E/ActivityThread( 3469): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2d3ef752 that was originally bound here
E/ActivityThread( 3469): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2d3ef752 that was originally bound here
E/ActivityThread( 3469): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3469): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3469): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3469): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3469): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3469): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3469): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3469): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3469): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3469): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3469): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3469): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3469): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3469): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3469): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3469): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3469): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3469): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3469): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3469): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3469): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3469): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3469): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3469): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2511cd95 that was originally bound here
E/ActivityThread( 3469): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2511cd95 that was originally bound here
E/ActivityThread( 3469): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3469): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3469): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3469): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3469): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3469): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3469): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3469): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3469): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3469): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3469): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3469): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3469): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3469): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3469): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3469): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3469): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3469): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3469): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3469): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3469): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3469): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  761): Unbind failed: could not find connection for android.os.BinderProxy@3ce4043
,V/GLSActivity( 1647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1686): Aggregate from 1454577115085 (log), 1454577115085 (data)
,D/Finsky  ( 2638): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2638): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1647): Vacuum at: now=1454578937348 tag=VacuumService
,I/art     (  761): Explicit concurrent mark sweep GC freed 30423(1377KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 936us total 115.083ms
,I/PhenotypeConfigurator( 1647): Scheduling Phenotype for one-off execution 12111 seconds from now (1454578937860)
,D/GetConfigurationSnapshotOperation( 1647): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1647): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1647): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1647): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1103): run()
I/Keyboard.Facilitator( 1103): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1647): disconnect managed GoogleApiClient
,I/ActivityManager(  761): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3641 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3641): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3641):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3641):   adb logcat -s GAv4
,W/GAv4    ( 3641): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3641): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3641): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  761): Killing 2736:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2736/cgroup.procs: No such file or directory
,I/jxcore-log( 3224): TAP version 13
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # multiplex can send data
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 1 String should be length:200
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # enqueue and run in order
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 2 firstPromise setTimeout
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 3 firstPromise result
I/jxcore-log( 3224): 
I/jxcore-log( 3224): ok 4 firstPromise testValue
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 5 secondPromise setTimeout
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 6 secondPromise result
I/jxcore-log( 3224): 
I/jxcore-log( 3224): ok 7 secondPromise testValue
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 8 thirdPromise in promise
I/jxcore-log( 3224): 
I/jxcore-log( 3224): ok 9 thirdPromise result
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 10 thirdPromise testValue
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # basic
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 11 sane
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # another
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 12 sane
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 13 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 14 null
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 15 (unnamed assert)
I/jxcore-log( 3224): 
I/jxcore-log( 3224): ok 16 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 17 should not throw
I/jxcore-log( 3224): 
I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 18 (unnamed assert)
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 19 (unnamed assert)
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 20 should not throw
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 21 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 22 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 23 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # failed to get mobile documents path
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 24 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 25 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 26 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 27 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # #init should register the networkChanged event
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 28 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # #startBroadcasting should throw on null device name
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 29 should throw
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 30 should throw
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 31 should throw
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 32 should throw
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # #startBroadcasting should throw on negative port
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 33 should throw
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # #startBroadcasting should throw on too large port
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 34 should throw
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 35 should be equal
I/jxcore-log( 3224): 
I/jxcore-log( 3224): ok 36 should be equal
I/jxcore-log( 3224): 
I/jxcore-log( 3224): ok 37 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 38 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 39 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 40 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 41 should be equal
I/jxcore-log( 3224): 
I/jxcore-log( 3224): ok 42 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 43 should be equal
I/jxcore-log( 3224): 
I/jxcore-log( 3224): ok 44 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 45 should be equal
I/jxcore-log( 3224): 
I/jxcore-log( 3224): ok 46 should be equal
I/jxcore-log( 3224): 
I/jxcore-log( 3224): ok 47 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 48 should be equal
I/jxcore-log( 3224): 
I/jxcore-log( 3224): ok 49 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 50 should be equal
I/jxcore-log( 3224): 
I/jxcore-log( 3224): ok 51 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): ok 52 should be equal
I/jxcore-log( 3224): 
I/jxcore-log( 3224): ok 53 should be equal
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # teardown
I/jxcore-log( 3224): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2547cd42 added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124270.3224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124270.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: OK
I/io.jxcore.node.ConnectionHelper( 3224): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124270.3224, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124270.3224","ra":"34:FC:EF:11:AE:67"}
,W/BluetoothAdapter( 3224): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124270.3224","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454579124270.3224","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124270.3224, mode: WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/io.jxcore.node.ConnectionHelper( 3224): start: OK
,I/jxcore-log( 3224): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 3224): 
I/io.jxcore.node.ConnectionHelper( 3224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3224): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  986): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3224): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3224): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3224): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 3224): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a897b8e added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124332.3224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124332.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: OK
I/io.jxcore.node.ConnectionHelper( 3224): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124332.3224, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124332.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124332.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454579124332.3224","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3224): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): start: Starting P2P device discovery...
I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124332.3224, mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local service added successfully
,I/io.jxcore.node.ConnectionHelper( 3224): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/wpa_supplicant(  986): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: RESTARTING
,I/jxcore-log( 3224): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 3224): 
,I/io.jxcore.node.ConnectionHelper( 3224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopForRestart
,I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3224): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3224): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3224): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3224): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 3224): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3725c29a added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124378.3224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124378.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: OK
I/io.jxcore.node.ConnectionHelper( 3224): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124378.3224, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): bind: Binding a new listener
,W/BluetoothAdapter( 3224): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Waiting for incoming connections...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124378.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124378.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454579124378.3224","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): start: Starting P2P device discovery...
,I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124378.3224, mode: WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/io.jxcore.node.ConnectionHelper( 3224): start: OK
,I/jxcore-log( 3224): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 3224): 
,I/io.jxcore.node.ConnectionHelper( 3224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: NOT_STARTED
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3224): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): stop: Stopping services
,I/wpa_supplicant(  986): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3224): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3224): Service requests cleared successfully
,I/jxcore-log( 3224): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 3224): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@370d6e66 added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124422.3224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124422.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: OK
I/io.jxcore.node.ConnectionHelper( 3224): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3224): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124422.3224, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124422.3224","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124422.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454579124422.3224","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/io.jxcore.node.ConnectionHelper( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124422.3224, mode: WIFI
I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3224): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 3224): 
I/io.jxcore.node.ConnectionHelper( 3224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: NOT_STARTED
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopForRestart
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3224): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: RUNNING_WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local services cleared successfully
I/wpa_supplicant(  986): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3224): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3224): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3224): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 3224): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12720af2 added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124461.3224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124461.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: OK
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 3224): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3224): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124461.3224, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124461.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124461.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454579124461.3224","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/io.jxcore.node.ConnectionHelper( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124461.3224, mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3224): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 3224): 
I/io.jxcore.node.ConnectionHelper( 3224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: NOT_STARTED
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopForRestart
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3224): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: RESTARTING
I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): release: No more listeners, de-initializing...
I/wpa_supplicant(  986): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3224): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
I/jxcore-log( 3224): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 3224): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3224): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2111e43e added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124500.3224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124500.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: OK
I/io.jxcore.node.ConnectionHelper( 3224): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3224): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124500.3224, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124500.3224","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124500.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454579124500.3224","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/io.jxcore.node.ConnectionHelper( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124500.3224, mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3224): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 3224): 
I/io.jxcore.node.ConnectionHelper( 3224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3224): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local service added successfully
I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): onServerStopped
I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi,.WifiP2pDeviceDiscoverer( 3224): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant(  986): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3224): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3224): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3224): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 3224): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2644064a added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124547.3224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124547.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: OK
I/io.jxcore.node.ConnectionHelper( 3224): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3224): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124547.3224, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124547.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124547.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454579124547.3224","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124547.3224, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3224): start: OK
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3224): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 3224): 
I/io.jxcore.node.ConnectionHelper( 3224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): shutdown
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant(  986): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3224): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3224): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3224): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3224): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 3224): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11c43d16 added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124607.3224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124607.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: OK
W/BluetoothAdapter( 3224): getBluetoothService() called with no BluetoothManagerCallback
I/io.jxcore.node.ConnectionHelper( 3224): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124607.3224, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124607.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124607.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454579124607.3224","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: RUNNING_WIFI
I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124607.3224, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3224): start: OK
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3224): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 3224): 
I/io.jxcore.node.ConnectionHelper( 3224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): shutdown
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3224): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): onServerStopped
I/wpa_supplicant(  986): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3224): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3224): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3224): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 3224): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13f14a2 added. We now have 10 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124666.3224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124666.3224","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: OK
I/io.jxcore.node.ConnectionHelper( 3224): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3224): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124666.3224, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124666.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124666.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454579124666.3224","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/io.jxcore.node.ConnectionHelper( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124666.3224, mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3224): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 3224): 
I/io.jxcore.node.ConnectionHelper( 3224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3224): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): release: No more listeners, de-initializing...
I/wpa_supplicant(  986): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3224): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
,I/jxcore-log( 3224): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 3224): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3224): Service requests cleared successfully
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3224): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9dd8ee added. We now have 11 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3224): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124722.3224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124722.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): start: OK
I/io.jxcore.node.ConnectionHelper( 3224): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3224): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124722.3224, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3224): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124722.3224","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454579124722.3224","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454579124722.3224","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454579124722.3224, mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 3224): start: OK
,I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3224): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 3224): 
I/io.jxcore.node.ConnectionHelper( 3224): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3224): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3224): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3224): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant(  986): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3224): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3224): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3224): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3224): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3224): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3224): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3224): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3224): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3224): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3224): Service requests cleared successfully
,I/jxcore-log( 3224): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 3224): 
,I/jxcore-log( 3224): # setup
I/jxcore-log( 3224): 
,I/ActivityManager(  761): Killing 2717:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  761): Client connection lost with reason: 4
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2717/cgroup.procs: No such file or directory
,W/bt-smp  ( 2151): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2151): Plain text(LSB ~ MSB) = dd ac 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2151): Encrypted text(LSB ~ MSB) = dd 03 04 89 37 87 e0 b8 90 f5 e7 d8 0c a4 ba 5a 
,W/bt-btm  ( 2151): Stopping oneshot timer
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3750): 
D/AndroidRuntime( 3750): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3750): CheckJNI is OFF
D/AndroidRuntime( 3750): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 3224:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  761): WIN DEATH: Window{d0d7686 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  761): Client connection lost with reason: 4
W/PackageSettings(  761): Skipping PackageSetting{4009b19 com.example.hello/10278} due to missing metadata
I/ActivityManager(  761):   Force finishing activity ActivityRecord{2babf38b u0 com.test.thalitest/.MainActivity t216}
V/ActivityManager(  761): Display changed displayId=0
W/ActivityManager(  761): Spurious death for ProcessRecord{18f7f43b 3224:com.test.thalitest/u0a270}, curProc for 3224: null
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1278): Explicit concurrent mark sweep GC freed 7258(546KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 1.937ms total 17.867ms
I/art     ( 1402): Explicit concurrent mark sweep GC freed 10166(698KB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 19MB/25MB, paused 532us total 33.917ms
I/art     ( 1686): Explicit concurrent mark sweep GC freed 6404(318KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 436us total 55.406ms
I/Keyboard.Facilitator( 1103): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1103): run()
W/GeofencerStateMachine( 1647): Ignoring removeGeofence because network location is disabled.
I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
I/LibraryLoader( 1538): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
I/OpenGLRenderer(  946): Initialized EGL, version 1.4
D/OpenGLRenderer(  946): Enabling debug mode 0
I/Decoder ( 1103): createOrResetDecoder
D/VoicemailCleanupService( 1369): Cleaning up data for package: com.test.thalitest
I/art     (  761): Explicit concurrent mark sweep GC freed 22381(1459KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.822ms total 121.291ms
I/art     (  761): WaitForGcToComplete blocked for 29.825ms for cause Explicit
I/UpdateIcingCorporaServi( 1402): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/art     (  946): Attempt to remove local handle scope entry from IRT, ignoring
W/Launcher( 1278): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2c1177ea new=com.google.android.velvet.VelvetApplication@2c1177ea
I/LibraryLoader( 1538): Time to load native libraries: 83 ms (timestamps 6764-6847)
I/LibraryLoader( 1538): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1538): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1538): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1538): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3793 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  761): removeObsoleteFile: deleting file=216_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1103): run()
W/InputMethodManagerService(  761): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@408c773 (uid=10034 pid=946)
I/UpdateIcingCorporaServi( 1402): UpdateCorporaTask done [took 131 ms] updated apps [took 131 ms] 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1103): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
W/ContextImpl( 3793): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = contacts
D/PackageBroadcastService( 1686): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1686): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1686): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1686): Module APK com.google.android.play.games already loaded
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
D/ChimeraCfgMgr( 1686): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1686): Module APK com.google.android.play.games already loaded
W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 3224 uid 10270
I/Keyboard.Facilitator( 1103): onFinishInput()
E/NetworkScheduler.SchedulerReceiver( 1647): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1647): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 1686): Removing dialog suppression flag for package com.test.thalitest
I/art     (  761): Explicit concurrent mark sweep GC freed 8476(412KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.634ms total 208.962ms
D/gH_CompatibleDatabase( 1686): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1686): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1686): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1686): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1686): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1686): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1686): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1686): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1686): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1686): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1686): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1686): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1686): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3833 uid=10039 gids={50039, 9997} abi=armeabi-v7a
I/Launcher( 1278): Deferring update until onResume
W/ResourcesManager( 1278): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/BaseAppContext( 1686): Using Auth Proxy for data requests.
W/BaseAppContext( 1686): Using Auth Proxy for data requests.
I/GMPM-SVC( 1686): App measurement is starting up, version: 8489
I/GMPM-SVC( 1686): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
D/AndroidRuntime( 3750): Shutting down VM
W/art     ( 3750): No such thread id for suspend: 13
W/ResourcesManager( 1278): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1278): Deferring update until onResume
I/Icing   ( 1686): doRemovePackageData com.test.thalitest
I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3859 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  761): Killing 2584:com.google.android.gm/u0a70 (adj 15): empty #17
W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2584/cgroup.procs: No such file or directory
I/ActivityManager(  761): Killing 2062:com.google.android.calendar/u0a31 (adj 15): empty #17
W/libprocessgroup(  761): failed to open /acct/uid_10031/pid_2062/cgroup.procs: No such file or directory
D/ExternalStorage( 3859): After updating volumes, found 1 active roots
W/ResourcesManager( 3124): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3124): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Documents( 3833): Update found 7 roots in 252ms
D/Documents( 3833): Update found 7 roots in 139ms

```
