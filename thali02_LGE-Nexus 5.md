#### Test 58380500fccea7e_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1695): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1695): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3071): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3071):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3071):   adb logcat -s GAv4
W/GAv4    ( 3071): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3071): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3071): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3071): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2641): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3071): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3071): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  764): Killing 2384:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
V/JNIHelp ( 3071): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3071): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3071): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  764): failed to open /acct/uid_1000/pid_2384/cgroup.procs: No such file or directory
V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1695): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1695): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1695): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1695): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3124): 
D/AndroidRuntime( 3124): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3124): CheckJNI is OFF
D/AndroidRuntime( 3124): Calling main entry com.android.commands.am.Am
I/ActivityManager(  764): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 3124): Shutting down VM
I/ActivityManager(  764): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3145 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/MicrophoneInputStream( 1383): mic_close gfk@1fdf42df
D/audio_hw_primary(  185): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  185): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1383): Hotword detection finished
I/HotwordRecognitionRnr( 1383): Stopping hotword detection.
I/WebViewFactory( 3145): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3145): Time to load native libraries: 1 ms (timestamps 4485-4486)
I/LibraryLoader( 3145): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3145): Binding Chromium to main looper Looper (main, tid 1) {171024f1}
I/LibraryLoader( 3145): Expected native library version number "",actual native library version number ""
I/chromium( 3145): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3145): Initializing chromium process, singleProcess=true
,W/art     ( 3145): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3145): ApplicationContext is null in ApplicationStatus
,W/chromium( 3145): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3145): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3145): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3145): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  764): Message: 20
D/BluetoothManagerService(  764): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@85f2b7a:true
,W/art     ( 3145): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3145): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3145): CordovaWebView is running on device made by: LGE
,W/art     ( 3145): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3145): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3145): Render dirty regions requested: true
,D/Atlas   ( 3145): Validating map...
,W/chromium( 3145): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/SurfaceFlinger(  173): shader cache generated - 24 shaders in 129.977386 ms
,I/OpenGLRenderer( 3145): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3145): Enabling debug mode 0
,I/ActivityManager(  764): Displayed com.test.thalitest/.MainActivity: +614ms (total +42s521ms)
,W/BindingManager( 3145): Cannot call determinedVisibility() - never saw a connection for the pid: 3145
,D/JsMessageQueue( 3145): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3145): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
,I/chromium( 3145): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  764): Killing 2468:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  764): failed to open /acct/uid_10080/pid_2468/cgroup.procs: No such file or directory
,I/PowerManagerService(  764): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  764): Sleeping (uid 1000)...
,I/Adreno-EGL(  764): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/PermissionCache(  173): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1244 us)
,D/audio_hw_primary(  185): adev_set_parameters: enter: screen_state=on
E/audio_a2dp_hw(  185): adev_set_parameters: ERROR: set param called even when stream out is null
,W/jxcore-log( 3145): Initializing JXcore engine
W/jxcore-log( 3145): JXcore engine is ready
,E/native  (  764): do suspend false
,D/audio_hw_primary(  185): adev_set_parameters: enter: screen_state=off
E/audio_a2dp_hw(  185): adev_set_parameters: ERROR: set param called even when stream out is null
I/Keyboard.Facilitator( 1107): onFinishInput()
,E/native  (  764): do suspend true
,W/Thread-301( 3215): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8045]" dev="sockfs" ino=8045 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-301( 3215): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-301( 3215): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8434]" dev="sockfs" ino=8434 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-301( 3215): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[15090]" dev="sockfs" ino=15090 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3145): Starting JXcore engine
,W/jxcore-log( 3145): Platform android
W/jxcore-log( 3145): 
W/jxcore-log( 3145): Process ARCH arm
W/jxcore-log( 3145): 
,E/Sensors (  192): sns_acm_mr.c(432):Transport error -45
,I/DisplayManagerService(  764): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  764): Display changed displayId=0
,D/SurfaceFlinger(  173): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  173): hwc_blank: Blanking display: 0
,I/jxcore-log( 3145): JXcore Cordova bridge is ready!
I/jxcore-log( 3145): 
W/jxcore-log( 3145): JXcore engine is started
,I/jxcore-log( 3145): Toggling radios to true
I/jxcore-log( 3145): 
,D/qdhwcomposer(  173): hwc_blank: Done blanking display: 0
D/BluetoothAdapter( 3145): enable(): BT is already enabled..!
D/SurfaceControl(  764): Excessive delay in setPowerMode(): 279ms
,D/WifiService(  764): New client listening to asynchronous messages
,D/WifiService(  764): setWifiEnabled: true pid=3145, uid=10270
E/WifiService(  764): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3145): Radios toggled
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): My device name is: LGE-Nexus 5
I/jxcore-log( 3145): 
,I/wpa_supplicant(  989): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  764): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  764): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1661): Read error: ssl=0xb4228e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1661): SSL shutdown failed: ssl=0xb4228e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  764): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Checking http://clients3.google.com/generate_204 on "NG7005g"
,E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  764): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  989): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  764): do suspend true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/ConnectivityService(  764): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524292
D/Nat464Xlat(  764): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  764): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1695): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Disconnected - quitting
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  764): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1258): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  764): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  989): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  989): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  989): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  989): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  764): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  764): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
E/WifiStateMachine(  764): Start Dhcp Watchdog 2
,E/native  (  764): do suspend false
,E/WifiStateMachine(  764): scanCount==0 - aborting
,I/dhcpcd  ( 3283): version 5.5.6 starting
E/dhcpcd  ( 3283): get_duid: Read-only file system
,I/dhcpcd  ( 3283): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3283): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3283): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  764): do suspend true
,D/ConnectivityService(  764): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  764): Adding iface wlan0 to network 101
,E/WifiStateMachine(  764): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  764): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  764): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  764): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  764): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  764): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  764): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  764): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  764): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  764): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  764): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  764): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1695): CM callback handler got msg 524290
,I/ActivityManager(  764): Killing 2111:com.google.android.deskclock/u0a38 (adj 15): empty #17
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 06 Feb 2016 00:13:23 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454717603230], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454717603210]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  764): Validated
D/ConnectivityService(  764): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  764): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1258): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1695): CM callback handler got msg 524290
,W/libprocessgroup(  764): failed to open /acct/uid_10038/pid_2111/cgroup.procs: No such file or directory
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  764): MasterInitialState.processMessage what=3
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 2760): type=WIFI subType= reason=null isConnected=true
,D/Tethering(  764): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2760): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 2760): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1695): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
E/GpsLocationProvider(  764): No APN found to select.
,D/SystemUpdateService( 1695): onCreate
,D/SystemUpdateService( 1695): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1695): active receiver: enabled
,I/SystemUpdateService( 1695): showing system update notification
,E/GpsLocationProvider(  764): No APN found to select.
,I/ValidateNoPeople(  764): skipping global notification
,V/SystemUpdateService( 1695): retry (wakeup: false) in 3599986 ms
,I/ActivityManager(  764): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3356 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Nat464Xlat(  764): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  764): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524295
,D/SystemUpdateService( 1695): onDestroy
,D/ConnectivityManager.CallbackHandler( 1695): CM callback handler got msg 524295
,I/GAv4    ( 3356): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3356):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3356):   adb logcat -s GAv4
,W/GAv4    ( 3356): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3356): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3356): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3356): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3356): Time to load native libraries: 2 ms (timestamps 674-676)
I/LibraryLoader( 3356): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3356): Binding Chromium to main looper Looper (main, tid 1) {23534e3b}
,I/LibraryLoader( 3356): Expected native library version number "",actual native library version number ""
,I/chromium( 3356): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3356): Initializing chromium process, singleProcess=true
,W/art     ( 3356): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3356): ApplicationContext is null in ApplicationStatus
,W/chromium( 3356): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3356): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3356): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3356): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/ConnectivityService(  764): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/NSApplication( 3356): Starting up...
,I/ActivityManager(  764): Killing 2612:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/AudioManagerAndroid( 3356): Requires BLUETOOTH permission
,W/libprocessgroup(  764): failed to open /acct/uid_10069/pid_2612/cgroup.procs: No such file or directory
,V/MusicLeanback( 2760): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1695): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1695): onCreate
,D/SystemUpdateService( 1695): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/art     (  764): Explicit concurrent mark sweep GC freed 52330(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 1.477ms total 78.418ms
,I/SystemUpdateService( 1695): active receiver: enabled
,I/SystemUpdateService( 1695): showing system update notification
,I/ValidateNoPeople(  764): skipping global notification
,V/SystemUpdateService( 1695): retry (wakeup: false) in 3599989 ms
,D/SystemUpdateService( 1695): onDestroy
,I/jxcore-log( 3145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3145): 
,D/ConnectivityService(  764): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  764): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2760): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  764): No APN found to select.
,V/MusicLeanback( 2760): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1695): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1695): onCreate
,D/SystemUpdateService( 1695): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1695): active receiver: enabled
,I/SystemUpdateService( 1695): showing system update notification
,I/ValidateNoPeople(  764): skipping global notification
,V/SystemUpdateService( 1695): retry (wakeup: false) in 3599984 ms
D/SystemUpdateService( 1695): onDestroy
,D/Finsky  ( 2641): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1661): Explicit concurrent mark sweep GC freed 32346(2011KB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 21MB/35MB, paused 927us total 53.347ms
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2641): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2641): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2641): untagSocket(37) failed with errno -22
,D/Finsky  ( 2641): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  764): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3465 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3465): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3465): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3465): VM with version 2.1.0 has multidex support
I/MultiDex( 3465): install
I/MultiDex( 3465): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3465): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3465): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3465): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@df6bc4b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3465): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1661): callingUid 10008, callindPid: 1661
,E/MDM     ( 1661): [225] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/qtaguid ( 2641): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2641): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2641): untagSocket(37) failed with errno -22
D/ChimeraCfgMgr( 3465): Reading stored module config
,D/AuthorizationBluetoothService( 1661): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1695): Restart initialization of location
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 3465): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1661): No location to return for getLastLocation()
W/FusedLocationProvider( 1661): location=null
,D/NativeLibraryUtils( 3465): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 3465): Connecting to CarCallService...
,I/art     ( 3465): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3465): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3465): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3465): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 3465): Creating a new PhoneAdapter instance
W/ActivityManager(  764): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3465): setListener: com.google.android.gms.car.dn@12ccb96
,W/ActivityManager(  764): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3465): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3465): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3465): Package validated; name: com.android.vending
,V/Finsky  ( 2641): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2641): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2641): Untagging socket 37 failed errno=-22
,W/NetworkManagementSocketTagger( 2641): untagSocket(37) failed with errno -22
,W/ResourcesManager( 2641): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2641): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2641): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2641): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1661): client connected with version: 8296000
,D/Finsky  ( 2641): [271] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2641): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2641): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  764): Killing 2566:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  764): failed to open /acct/uid_10045/pid_2566/cgroup.procs: No such file or directory
,I/jxcore-log( 3145): Test app app.js loaded
I/jxcore-log( 3145): 
,I/chromium( 3145): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3145): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3145): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3145): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3145): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3145): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3145): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3145): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3145): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3145): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3145): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1da8d493 added. We now have 1 listener(s)
,I/jxcore-log( 3145): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): TAP version 13
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # setup
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): ok 1 should be equal
I/jxcore-log( 3145): 
I/jxcore-log( 3145): ok 2 should be equal
I/jxcore-log( 3145): 
I/jxcore-log( 3145): ok 3 should be equal
I/jxcore-log( 3145): 
I/jxcore-log( 3145): ok 4 should be equal
I/jxcore-log( 3145): 
I/jxcore-log( 3145): # teardown
I/jxcore-log( 3145): 
I/jxcore-log( 3145): # setup
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): ok 5 should be equal
I/jxcore-log( 3145): 
I/jxcore-log( 3145): ok 6 should be equal
I/jxcore-log( 3145): 
I/jxcore-log( 3145): ok 7 should be equal
I/jxcore-log( 3145): 
I/jxcore-log( 3145): ok 8 should be equal
I/jxcore-log( 3145): 
I/jxcore-log( 3145): # teardown
I/jxcore-log( 3145): 
I/jxcore-log( 3145): # setup
I/jxcore-log( 3145): 
I/jxcore-log( 3145): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): ok 9 should throw
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # teardown
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # setup
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): ok 10 should throw
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # teardown
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # setup
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # #parseBeacons no beacons returns null
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): ok 11 should be equal
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # teardown
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # setup
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): ok 12 should throw
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # teardown
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # setup
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): ok 13 should be equal
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # teardown
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # setup
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # #parseBeacons addressBookCallback returns null for all
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): ok 14 (unnamed assert)
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): ok 15 should be equal
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # teardown
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # setup
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): ok 16 (unnamed assert)
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): ok 17 (unnamed assert)
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # teardown
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # setup
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 3145): 
,I/jxcore-log( 3145): ok 18 (unnamed assert)
I/jxcore-log( 3145): 
I/jxcore-log( 3145): # teardown
I/jxcore-log( 3145): 
,D/CAR.SERVICE( 3465): mConnectedToCar = false, abort
,E/ActivityThread( 3465): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@22a122be that was originally bound here
E/ActivityThread( 3465): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@22a122be that was originally bound here
E/ActivityThread( 3465): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3465): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3465): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3465): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3465): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3465): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3465): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3465): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3465): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3465): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3465): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3465): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3465): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3465): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3465): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3465): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3465): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3465): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3465): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3465): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3465): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3465): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3465): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3465): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@256caab1 that was originally bound here
E/ActivityThread( 3465): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@256caab1 that was originally bound here
E/ActivityThread( 3465): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3465): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3465): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3465): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3465): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3465): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3465): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3465): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3465): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3465): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3465): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3465): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3465): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3465): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3465): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3465): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3465): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3465): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3465): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3465): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3465): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3465): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  764): Unbind failed: could not find connection for android.os.BinderProxy@28703957
,D/Finsky  ( 2641): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2641): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1661): Vacuum at: now=1454717637721 tag=VacuumService
,I/GoogleURLConnFactory( 1661): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1661): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/PhenotypeConfigurator( 1661): Server returned 404
,I/art     (  764): Explicit concurrent mark sweep GC freed 31602(1393KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.144ms total 82.349ms
,I/PhenotypeConfigurator( 1661): Scheduling Phenotype for one-off execution 6819 seconds from now (1454717639057)
,D/GetConfigurationSnapshotOperation( 1661): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1661): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1661): Using platform SSLCertificateSocketFactory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1107): run()
I/Keyboard.Facilitator( 1107): flushDynamicLanguageModels()
,I/ActivityManager(  764): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3624 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3624): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3624):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3624):   adb logcat -s GAv4
,W/GAv4    ( 3624): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3624): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3624): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  764): Killing 2734:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  764): failed to open /acct/uid_10003/pid_2734/cgroup.procs: No such file or directory
,I/ClearcutLoggerApiImpl( 1661): disconnect managed GoogleApiClient
,I/jxcore-log( 3145): --= Surplus to requirements =--
I/jxcore-log( 3145): 
I/jxcore-log( 3145): ****TEST TOOK:  ms ****
I/jxcore-log( 3145): 
I/jxcore-log( 3145): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3145): 
,D/AndroidRuntime( 3673): 
D/AndroidRuntime( 3673): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3673): CheckJNI is OFF
,D/AndroidRuntime( 3673): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  764): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  764): Killing 3145:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  764): WIN DEATH: Window{1299672a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  764): Client connection lost with reason: 4
,I/ActivityManager(  764):   Force finishing activity ActivityRecord{105c1be u0 com.test.thalitest/.MainActivity t216}
,W/PackageSettings(  764): Skipping PackageSetting{14dea275 com.example.hello/10278} due to missing metadata
,V/ActivityManager(  764): Display changed displayId=0
,W/ActivityManager(  764): Spurious death for ProcessRecord{2b867899 3145:com.test.thalitest/u0a270}, curProc for 3145: null
I/ActivityManager(  764): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  764):   Force finishing activity ActivityRecord{105c1be u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  764): Duplicate finish request for ActivityRecord{105c1be u0 com.test.thalitest/.MainActivity t216 f}
,I/art     ( 1695): Explicit concurrent mark sweep GC freed 433(16KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 22MB/29MB, paused 451us total 36.139ms
I/art     ( 1383): Explicit concurrent mark sweep GC freed 10116(694KB) AllocSpace objects, 1(39KB) LOS objects, 25% free, 19MB/25MB, paused 340us total 21.035ms
,I/Keyboard.Facilitator( 1107): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1107): run()
,I/Decoder ( 1107): createOrResetDecoder
,I/InputReader(  764): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1661): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1307): Explicit concurrent mark sweep GC freed 7192(542KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 653us total 24.728ms
,I/LibraryLoader( 1517): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,I/art     (  764): Explicit concurrent mark sweep GC freed 11747(792KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 883us total 83.636ms
,I/art     (  764): WaitForGcToComplete blocked for 83.674ms for cause Explicit
,D/VoicemailCleanupService( 1395): Cleaning up data for package: com.test.thalitest
,I/OpenGLRenderer(  949): Initialized EGL, version 1.4
,I/UpdateIcingCorporaServi( 1383): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/OpenGLRenderer(  949): Enabling debug mode 0
W/Launcher( 1307): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@8758d6 new=com.google.android.velvet.VelvetApplication@8758d6
,I/ActivityManager(  764): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3713 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/LibraryLoader( 1517): Time to load native libraries: 78 ms (timestamps 6634-6712)
I/LibraryLoader( 1517): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1517): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1517): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1517): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     (  949): Attempt to remove local handle scope entry from IRT, ignoring
,D/BackupManagerService(  764): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  764): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1107): run()
,D/TaskPersister(  764): removeObsoleteFile: deleting file=216_task.xml
,W/InputMethodManagerService(  764): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@1a16fd64 (uid=10034 pid=949)
W/ContextImpl( 3713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1107): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = contacts
,D/ChimeraCfgMgr( 1695): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1695): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1695): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1695): Module APK com.google.android.play.games already loaded
I/UpdateIcingCorporaServi( 1383): UpdateCorporaTask done [took 137 ms] updated apps [took 137 ms] 
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1107): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1107): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1107): run()
I/StatsUtilsManager( 1107): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1107): shouldRecordStats() = Too Soon
,D/PackageBroadcastService( 1695): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1661): Invalid parameter app
D/AccountUtils( 1695): Clearing selected account for com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1661): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  764): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3748 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/art     (  764): Explicit concurrent mark sweep GC freed 7383(376KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.180ms total 232.386ms
,I/LocationSettingsChecker( 1695): Removing dialog suppression flag for package com.test.thalitest
,I/ActivityManager(  764): Killing 2714:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  764): Client connection lost with reason: 4
,D/gH_CompatibleDatabase( 1695): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1695): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1695): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1695): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1695): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1695): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1695): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1695): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1695): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1695): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1695): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1695): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1695): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/AndroidRuntime( 3673): Shutting down VM
,W/libprocessgroup(  764): failed to open /acct/uid_1000/pid_2714/cgroup.procs: No such file or directory
,I/Launcher( 1307): Deferring update until onResume
,W/ResourcesManager( 1307): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/BaseAppContext( 1695): Using Auth Proxy for data requests.
,W/ResourcesManager( 1307): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/BaseAppContext( 1695): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1695): App measurement is starting up, version: 8489
I/GMPM-SVC( 1695): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Launcher( 1307): Deferring update until onResume
,I/Icing   ( 1695): doRemovePackageData com.test.thalitest
,I/ActivityManager(  764): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3779 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  764): Killing 2586:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  764): failed to open /acct/uid_10070/pid_2586/cgroup.procs: No such file or directory
,I/ActivityManager(  764): Killing 2046:com.google.android.calendar/u0a31 (adj 15): empty #17
,D/ExternalStorage( 3779): After updating volumes, found 1 active roots
,W/libprocessgroup(  764): failed to open /acct/uid_10031/pid_2046/cgroup.procs: No such file or directory
,W/ResourcesManager( 3071): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3071): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3748): Update found 7 roots in 151ms
,D/Documents( 3748): Update found 7 roots in 61ms

```
