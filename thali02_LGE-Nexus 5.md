#### Test 58918757c0fcaf3_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1634): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1634): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3021): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3021):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3021):   adb logcat -s GAv4
W/GAv4    ( 3021): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3021): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3021): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3021): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
--------- beginning of system
W/ResourcesManager( 3021): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3021): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2616): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
V/JNIHelp ( 3021): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3021): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3021): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1608): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  760): Killing 2334:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2334/cgroup.procs: No such file or directory
I/Icing   ( 1634): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1634): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1634): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1634): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3078): 
D/AndroidRuntime( 3078): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3078): CheckJNI is OFF
D/AndroidRuntime( 3078): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 3078): Shutting down VM
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3099 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  196): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 180us total 8.303ms
I/art     (  196): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.478ms
I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 7.230ms
I/MicrophoneInputStream( 1420): mic_close gfk@31975e45
D/audio_hw_primary(  185): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  185): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1420): Hotword detection finished
I/HotwordRecognitionRnr( 1420): Stopping hotword detection.
I/WebViewFactory( 3099): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3099): Time to load native libraries: 2 ms (timestamps 3502-3504)
I/LibraryLoader( 3099): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3099): Binding Chromium to main looper Looper (main, tid 1) {275288ba}
,I/LibraryLoader( 3099): Expected native library version number "",actual native library version number ""
,I/chromium( 3099): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3099): Initializing chromium process, singleProcess=true
W/art     ( 3099): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3099): ApplicationContext is null in ApplicationStatus
,W/chromium( 3099): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3099): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3099): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3099): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3595101b:true
,W/art     ( 3099): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3099): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3099): CordovaWebView is running on device made by: LGE
,W/art     ( 3099): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3099): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3099): Render dirty regions requested: true
,D/Atlas   ( 3099): Validating map...
,W/chromium( 3099): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3099): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3099): Enabling debug mode 0
,D/SurfaceFlinger(  173): shader cache generated - 24 shaders in 131.327240 ms
,I/Keyboard.Facilitator( 1099): onFinishInput()
,W/BindingManager( 3099): Cannot call determinedVisibility() - never saw a connection for the pid: 3099
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +614ms (total +41s705ms)
,D/JsMessageQueue( 3099): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3099): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257331840
,I/chromium( 3099): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  760): Killing 2422:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10080/pid_2422/cgroup.procs: No such file or directory
,W/jxcore-log( 3099): Initializing JXcore engine
,W/jxcore-log( 3099): JXcore engine is ready
,W/Thread-296( 3158): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9480]" dev="sockfs" ino=9480 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-296( 3158): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-296( 3158): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8120]" dev="sockfs" ino=8120 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-296( 3158): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18263]" dev="sockfs" ino=18263 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3099): Starting JXcore engine
,W/jxcore-log( 3099): Platform android
W/jxcore-log( 3099): 
W/jxcore-log( 3099): Process ARCH arm
W/jxcore-log( 3099): 
,I/jxcore-log( 3099): JXcore Cordova bridge is ready!
I/jxcore-log( 3099): 
,W/jxcore-log( 3099): JXcore engine is started
,I/jxcore-log( 3099): Toggling radios to true
I/jxcore-log( 3099): 
,D/BluetoothAdapter( 3099): enable(): BT is already enabled..!
,D/WifiService(  760): New client listening to asynchronous messages
D/WifiService(  760): setWifiEnabled: true pid=3099, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3099): Radios toggled
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): My device name is: LGE-Nexus 5
I/jxcore-log( 3099): 
,I/wpa_supplicant(  985): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1608): Read error: ssl=0xa416be00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1608): SSL shutdown failed: ssl=0xa416be00: I/O error during system call, Broken pipe
D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=-2ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-2ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  760): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  985): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  181): Clearing all IP addresses on wlan0
D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
E/ConnectivityService(  760): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/TelephonyNetworkFactory( 1258): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityManager.CallbackHandler( 1634): CM callback handler got msg 524292
,I/PowerManagerService(  760): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  760): Sleeping (uid 1000)...
,I/Adreno-EGL(  760): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/PermissionCache(  173): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (115 us)
,D/audio_hw_primary(  185): adev_set_parameters: enter: screen_state=on
E/audio_a2dp_hw(  185): adev_set_parameters: ERROR: set param called even when stream out is null
,E/native  (  760): do suspend false
,I/Keyboard.Facilitator( 1099): onFinishInput()
,D/audio_hw_primary(  185): adev_set_parameters: enter: screen_state=off
E/audio_a2dp_hw(  185): adev_set_parameters: ERROR: set param called even when stream out is null
,E/native  (  760): do suspend true
,E/Sensors (  192): sns_acm_mr.c(432):Transport error -45
,D/SurfaceFlinger(  173): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  173): hwc_blank: Blanking display: 0
I/DisplayManagerService(  760): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  760): Display changed displayId=0
,D/qdhwcomposer(  173): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  760): Excessive delay in setPowerMode(): 282ms
,I/wpa_supplicant(  985): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  985): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  985): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  985): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
E/WifiStateMachine(  760): Start Dhcp Watchdog 2
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/dhcpcd  ( 3213): version 5.5.6 starting
,E/dhcpcd  ( 3213): get_duid: Read-only file system
,I/dhcpcd  ( 3213): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3213): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3213): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  760): Adding iface wlan0 to network 101
,E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  760): Setting Dns servers for network 101 to [/192.168.1.1]
,E/WifiStateMachine(  760): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1634): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Feb 2016 17:06:45 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455124005908], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455124005883]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
,D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1258): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1634): CM callback handler got msg 524290
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2740): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 2740): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2740): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  760): No APN found to select.
,E/GpsLocationProvider(  760): No APN found to select.
,I/SystemUpdateService( 1634): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1634): onCreate
,D/SystemUpdateService( 1634): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1634): active receiver: enabled
,I/SystemUpdateService( 1634): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3268 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/SystemUpdateService( 1634): retry (wakeup: false) in 3599953 ms
,D/SystemUpdateService( 1634): onDestroy
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1634): CM callback handler got msg 524295
,I/GAv4    ( 3268): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3268):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3268):   adb logcat -s GAv4
,W/GAv4    ( 3268): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3268): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3268): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  760): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/WebViewFactory( 3268): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3268): Time to load native libraries: 1 ms (timestamps 9359-9360)
I/LibraryLoader( 3268): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3268): Binding Chromium to main looper Looper (main, tid 1) {2d7c50f}
I/LibraryLoader( 3268): Expected native library version number "",actual native library version number ""
I/chromium( 3268): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3268): Initializing chromium process, singleProcess=true
,W/art     ( 3268): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3268): ApplicationContext is null in ApplicationStatus
,W/chromium( 3268): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3268): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3268): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3268): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3268): Requires BLUETOOTH permission
,I/NSApplication( 3268): Starting up...
,I/ActivityManager(  760): Killing 2060:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2060/cgroup.procs: No such file or directory
,V/MusicLeanback( 2740): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1634): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/art     (  760): Explicit concurrent mark sweep GC freed 49212(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.232ms total 72.895ms
,D/SystemUpdateService( 1634): onCreate
,D/SystemUpdateService( 1634): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1634): active receiver: enabled
,I/SystemUpdateService( 1634): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1634): retry (wakeup: false) in 3599973 ms
,D/SystemUpdateService( 1634): onDestroy
,I/ActivityManager(  760): Killing 2585:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/jxcore-log( 3099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3099): 
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2585/cgroup.procs: No such file or directory
,I/jxcore-log( 3099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3099): 
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2740): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2740): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1634): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1634): onCreate
,D/SystemUpdateService( 1634): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1634): active receiver: enabled
I/SystemUpdateService( 1634): showing system update notification
,E/GpsLocationProvider(  760): No APN found to select.
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1634): retry (wakeup: false) in 3599980 ms
D/SystemUpdateService( 1634): onDestroy
,D/Finsky  ( 2616): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1608): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1608): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1608): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1608): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2616): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2616): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2616): untagSocket(37) failed with errno -22
,D/Finsky  ( 2616): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1608): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3360 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3360): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3360): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3360): VM with version 2.1.0 has multidex support
I/MultiDex( 3360): install
I/MultiDex( 3360): VM has multidex support, MultiDex support library is disabled.
,I/qtaguid ( 2616): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2616): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2616): untagSocket(37) failed with errno -22
,V/JNIHelp ( 3360): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3360): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3360): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2fb7161f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3360): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1608): callingUid 10008, callindPid: 1608
,D/AuthorizationBluetoothService( 1608): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1608): [227] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1634): Restart initialization of location
,V/GLSActivity( 1608): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 3360): Reading stored module config
,W/GCoreFlp( 1608): No location to return for getLastLocation()
W/FusedLocationProvider( 1608): location=null
,D/ChimeraCfgMgr( 3360): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/NativeLibraryUtils( 3360): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 3360): Connecting to CarCallService...
,I/art     ( 3360): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3360): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3360): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3360): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 3360): Creating a new PhoneAdapter instance
,W/ActivityManager(  760): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3360): setListener: com.google.android.gms.car.dn@169c7f7a
,W/ActivityManager(  760): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3360): Returning an existing PhoneAdapter instance.
,D/CAR.TEL.Service( 3360): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3360): Package validated; name: com.android.vending
,V/Finsky  ( 2616): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1608): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2616): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2616): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2616): untagSocket(37) failed with errno -22
,W/ResourcesManager( 2616): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2616): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2616): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2616): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1608): client connected with version: 8296000
,D/Finsky  ( 2616): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1608): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2616): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2616): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  760): Killing 2529:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_2529/cgroup.procs: No such file or directory
,I/jxcore-log( 3099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): Test app app.js loaded
I/jxcore-log( 3099): 
,I/chromium( 3099): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3099): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3099): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3099): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3099): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3099): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3099): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3099): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3099): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3099): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3099): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7000ccc added. We now have 1 listener(s)
,I/jxcore-log( 3099): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3099): 
,D/CAR.SERVICE( 3360): mConnectedToCar = false, abort
,E/ActivityThread( 3360): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@29ab4e22 that was originally bound here
E/ActivityThread( 3360): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@29ab4e22 that was originally bound here
E/ActivityThread( 3360): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3360): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3360): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3360): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3360): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3360): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3360): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3360): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3360): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3360): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3360): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3360): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3360): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3360): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3360): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3360): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3360): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3360): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3360): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3360): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1c64efa5 that was originally bound here
E/ActivityThread( 3360): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1c64efa5 that was originally bound here
E/ActivityThread( 3360): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3360): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3360): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3360): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3360): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3360): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3360): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3360): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3360): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3360): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3360): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3360): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3360): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3360): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3360): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3360): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3360): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3360): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  760): Unbind failed: could not find connection for android.os.BinderProxy@20879d61
,D/Finsky  ( 2616): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2616): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1608): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1608): Vacuum at: now=1455124041872 tag=VacuumService
,I/PhenotypeConfigurator( 1608): Scheduling Phenotype for one-off execution 2403 seconds from now (1455124042245)
,D/GetConfigurationSnapshotOperation( 1608): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1608): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1608): Using platform SSLCertificateSocketFactory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1099): run()
I/Keyboard.Facilitator( 1099): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1608): disconnect managed GoogleApiClient
,I/jxcore-log( 3099): TAP version 13
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # multiplex can send data
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 1 String should be length:200
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # enqueue and run in order
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 2 firstPromise setTimeout
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 3 firstPromise result
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 4 firstPromise testValue
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 5 secondPromise setTimeout
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 6 secondPromise result
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 7 secondPromise testValue
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 8 thirdPromise in promise
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 9 thirdPromise result
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 10 thirdPromise testValue
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # basic
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 11 sane
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # another
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 12 sane
I/jxcore-log( 3099): 
I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 13 should be equal
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 14 null
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 15 (unnamed assert)
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 16 should be equal
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 17 should not throw
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 18 (unnamed assert)
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 19 (unnamed assert)
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 20 should not throw
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 21 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 22 should be equal
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 23 should be equal
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # failed to get mobile documents path
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 24 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 25 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 26 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 27 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # #init should register the networkChanged event
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 28 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # #startBroadcasting should throw on null device name
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 29 should throw
I/jxcore-log( 3099): 
I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 30 should throw
I/jxcore-log( 3099): 
I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 31 should throw
I/jxcore-log( 3099): 
I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 32 should throw
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # #startBroadcasting should throw on negative port
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 33 should throw
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # #startBroadcasting should throw on too large port
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 34 should throw
I/jxcore-log( 3099): 
I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 35 should be equal
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 36 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 37 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 38 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 39 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 40 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 41 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 42 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 43 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 44 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 45 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 46 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 47 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 48 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 49 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 50 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 51 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # teardown
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): ok 52 should be equal
I/jxcore-log( 3099): 
I/jxcore-log( 3099): ok 53 should be equal
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # setup
I/jxcore-log( 3099): 
,I/jxcore-log( 3099): # #start should fail if called twice in a row
I/jxcore-log( 3099): 
,I/ActivityManager(  760): Killing 2709:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2709/cgroup.procs: No such file or directory
,W/bt-smp  ( 2091): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2091): Plain text(LSB ~ MSB) = 4e 7d 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2091): Encrypted text(LSB ~ MSB) = 92 5a 3f 2a 06 f4 03 98 32 a4 3f 31 c1 58 63 f6 
W/bt-btm  ( 2091): Stopping oneshot timer
,I/art     (  760): Explicit concurrent mark sweep GC freed 35092(1572KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 811us total 69.087ms
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3539 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/EventLogService( 1634): Aggregate from 1455122880078 (log), 1455122880078 (data)
,I/GAv4    ( 3539): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3539):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3539):   adb logcat -s GAv4
,W/GAv4    ( 3539): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3539): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3539): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Killing 2679:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  760): Client connection lost with reason: 4
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2679/cgroup.procs: No such file or directory
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
