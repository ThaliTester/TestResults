#### Test 5841644866d9c0e_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3100): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3100):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3100):   adb logcat -s GAv4
W/GAv4    ( 3100): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3100): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3100): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3100): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/ChimeraCfgMgr( 1646): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1646): Module APK com.google.android.play.games already loaded
D/Finsky  ( 2627): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3100): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3100): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  761): Killing 2356:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
V/JNIHelp ( 3100): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3100): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3100): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2356/cgroup.procs: No such file or directory
V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1646): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1646): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1646): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1646): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3158): 
D/AndroidRuntime( 3158): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3158): CheckJNI is OFF
D/AndroidRuntime( 3158): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 3158): Shutting down VM
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3179 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/MicrophoneInputStream( 1392): mic_close gfk@51e74c6
D/audio_hw_primary(  182): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  182): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1392): Stopping hotword detection.
I/HotwordRecognitionRnr( 1392): Hotword detection finished
I/WebViewFactory( 3179): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3179): Time to load native libraries: 2 ms (timestamps 3015-3017)
I/LibraryLoader( 3179): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3179): Binding Chromium to main looper Looper (main, tid 1) {381aa1a0}
I/LibraryLoader( 3179): Expected native library version number "",actual native library version number ""
I/chromium( 3179): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3179): Initializing chromium process, singleProcess=true
,W/art     ( 3179): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3179): ApplicationContext is null in ApplicationStatus
,W/chromium( 3179): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3179): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3179): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3179): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@222566f2:true
,W/art     ( 3179): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3179): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3179): CordovaWebView is running on device made by: LGE
,W/art     ( 3179): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3179): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3179): Render dirty regions requested: true
,D/Atlas   ( 3179): Validating map...
,W/chromium( 3179): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3179): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3179): Enabling debug mode 0
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +438ms (total +40s976ms)
,W/BindingManager( 3179): Cannot call determinedVisibility() - never saw a connection for the pid: 3179
,D/JsMessageQueue( 3179): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3179): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257335680
,I/chromium( 3179): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  761): Killing 2447:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_2447/cgroup.procs: No such file or directory
,I/PowerManagerService(  761): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  761): Sleeping (uid 1000)...
,I/Adreno-EGL(  761): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/PermissionCache(  175): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (111 us)
,D/audio_hw_primary(  182): adev_set_parameters: enter: screen_state=on
,E/audio_a2dp_hw(  182): adev_set_parameters: ERROR: set param called even when stream out is null
,E/native  (  761): do suspend false
,D/audio_hw_primary(  182): adev_set_parameters: enter: screen_state=off
E/audio_a2dp_hw(  182): adev_set_parameters: ERROR: set param called even when stream out is null
I/Keyboard.Facilitator( 1110): onFinishInput()
,E/native  (  761): do suspend true
,W/jxcore-log( 3179): Initializing JXcore engine
W/jxcore-log( 3179): JXcore engine is ready
,W/Thread-301( 3227): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7684]" dev="sockfs" ino=7684 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-301( 3227): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-301( 3227): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8577]" dev="sockfs" ino=8577 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-301( 3227): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20611]" dev="sockfs" ino=20611 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3179): Starting JXcore engine
,W/jxcore-log( 3179): Platform android
W/jxcore-log( 3179): 
,W/jxcore-log( 3179): Process ARCH arm
W/jxcore-log( 3179): 
,E/Sensors (  189): sns_acm_mr.c(432):Transport error -45
,D/SurfaceFlinger(  175): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  175): hwc_blank: Blanking display: 0
,I/DisplayManagerService(  761): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  761): Display changed displayId=0
,I/jxcore-log( 3179): JXcore Cordova bridge is ready!
I/jxcore-log( 3179): 
W/jxcore-log( 3179): JXcore engine is started
,D/qdhwcomposer(  175): hwc_blank: Done blanking display: 0
D/SurfaceControl(  761): Excessive delay in setPowerMode(): 283ms
,I/jxcore-log( 3179): Toggling radios to true
I/jxcore-log( 3179): 
,D/BluetoothAdapter( 3179): enable(): BT is already enabled..!
,D/WifiService(  761): New client listening to asynchronous messages
,D/WifiService(  761): setWifiEnabled: true pid=3179, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3179): Radios toggled
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): My device name is: LGE-Nexus 5
I/jxcore-log( 3179): 
,I/wpa_supplicant(  981): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  761): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,V/NativeCrypto( 1603): Read error: ssl=0x9bb60e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1603): SSL shutdown failed: ssl=0x9bb60e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  761): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  981): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  761): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1646): CM callback handler got msg 524292
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
,D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1299): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  761): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  981): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  981): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  981): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  981): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  178): Setting iface cfg
E/WifiStateMachine(  761): Start Dhcp Watchdog 2
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3298): version 5.5.6 starting
E/dhcpcd  ( 3298): get_duid: Read-only file system
,I/dhcpcd  ( 3298): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3298): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  761): MasterInitialState.processMessage what=3
,D/Tethering(  761): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2747): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/dhcpcd  ( 3298): wlan0: leased 192.168.1.114 for 86400 seconds
,I/SystemUpdateService( 1646): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,E/GpsLocationProvider(  761): No APN found to select.
,D/SystemUpdateService( 1646): onCreate
,D/SystemUpdateService( 1646): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1646): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1646): num queued entries: 0
,I/iu.UploadsManager( 1646): num updated entries: 0
I/iu.SyncManager( 1646): NEXT; no task
,I/SystemUpdateService( 1646): active receiver: enabled
,I/SystemUpdateService( 1646): showing system update notification
,I/Babel   ( 1923): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3343 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  761): No APN found to select.
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1646): retry (wakeup: false) in 3599929 ms
,D/SystemUpdateService( 1646): onDestroy
,I/GAv4    ( 3343): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3343):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3343):   adb logcat -s GAv4
,W/GAv4    ( 3343): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3343): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3343): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  761): do suspend true
,E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  761): Adding iface wlan0 to network 101
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  761): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1646): CM callback handler got msg 524290
,I/WebViewFactory( 3343): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3343): Time to load native libraries: 3 ms (timestamps 8913-8916)
I/LibraryLoader( 3343): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3343): Binding Chromium to main looper Looper (main, tid 1) {1eb8f0c7}
,I/LibraryLoader( 3343): Expected native library version number "",actual native library version number ""
,I/chromium( 3343): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3343): Initializing chromium process, singleProcess=true
,W/art     ( 3343): Attempt to remove local handle scope entry from IRT, ignoring
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 12:09:32 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455019772716], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455019772702]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1646): CM callback handler got msg 524290
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1299): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,E/SysUtils( 3343): ApplicationContext is null in ApplicationStatus
,W/chromium( 3343): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3343): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3343): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3343): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3343): Requires BLUETOOTH permission
,I/NSApplication( 3343): Starting up...
,I/ActivityManager(  761): Killing 2082:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2082/cgroup.procs: No such file or directory
,V/MusicLeanback( 2747): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1646): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1646): onCreate
,D/SystemUpdateService( 1646): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1646): active receiver: enabled
,I/SystemUpdateService( 1646): showing system update notification
,I/iu.Environment( 1646): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1646): num queued entries: 0
,I/iu.UploadsManager( 1646): num updated entries: 0
I/iu.SyncManager( 1646): NEXT; no task
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1646): retry (wakeup: false) in 3599958 ms
,I/art     (  761): Explicit concurrent mark sweep GC freed 48259(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 1.314ms total 62.144ms
,D/SystemUpdateService( 1646): onDestroy
,I/Babel   ( 1923): connection state changed from DISCONNECTED to CONNECTED
,I/ActivityManager(  761): Killing 2599:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/jxcore-log( 3179): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3179): 
,W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2599/cgroup.procs: No such file or directory
,I/GCM     ( 1646): Message from null null
,E/GCM     ( 1646): Dropping message from null
,D/ConnectivityService(  761): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3179): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3179): 
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2747): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2747): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  761): No APN found to select.
,I/SystemUpdateService( 1646): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1646): onCreate
D/SystemUpdateService( 1646): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1646): active receiver: enabled
,I/SystemUpdateService( 1646): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1646): retry (wakeup: false) in 3599978 ms
,D/SystemUpdateService( 1646): onDestroy
,D/Finsky  ( 2627): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2627): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2627): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2627): untagSocket(37) failed with errno -22
D/Finsky  ( 2627): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3467 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3467): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3467): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3467): VM with version 2.1.0 has multidex support
I/MultiDex( 3467): install
I/MultiDex( 3467): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3467): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3467): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3467): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@23975fad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3467): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1603): callingUid 10008, callindPid: 1603
,E/MDM     ( 1603): [172] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/qtaguid ( 2627): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2627): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2627): untagSocket(37) failed with errno -22
,D/AuthorizationBluetoothService( 1603): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1646): Restart initialization of location
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 3467): Reading stored module config
,D/ChimeraCfgMgr( 3467): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1603): No location to return for getLastLocation()
,W/FusedLocationProvider( 1603): location=null
,D/NativeLibraryUtils( 3467): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 3467): Connecting to CarCallService...
,I/art     ( 3467): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3467): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3467): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3467): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 3467): Creating a new PhoneAdapter instance
,W/ActivityManager(  761): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3467): setListener: com.google.android.gms.car.dn@3d9aee60
W/ActivityManager(  761): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3467): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3467): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3467): Package validated; name: com.android.vending
,V/Finsky  ( 2627): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2627): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2627): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2627): untagSocket(37) failed with errno -22
,W/ResourcesManager( 2627): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2627): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2627): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2627): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1603): client connected with version: 8296000
,D/Finsky  ( 2627): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2627): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2627): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3179): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3179): 
,I/jxcore-log( 3179): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3179): 
,I/ActivityManager(  761): Killing 2551:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_2551/cgroup.procs: No such file or directory
,I/jxcore-log( 3179): Test app app.js loaded
I/jxcore-log( 3179): 
,I/chromium( 3179): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3179): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3179): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3179): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3179): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3179): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3179): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3179): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3179): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3179): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3179): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c73f35c added. We now have 1 listener(s)
,I/jxcore-log( 3179): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3179): 
,D/CAR.SERVICE( 3467): mConnectedToCar = false, abort
,E/ActivityThread( 3467): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1e609e48 that was originally bound here
E/ActivityThread( 3467): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1e609e48 that was originally bound here
E/ActivityThread( 3467): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3467): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3467): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3467): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3467): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3467): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3467): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3467): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3467): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3467): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3467): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3467): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3467): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3467): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3467): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3467): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3467): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3467): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3467): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3467): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3467): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3467): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3467): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3467): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@6c9d263 that was originally bound here
E/ActivityThread( 3467): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@6c9d263 that was originally bound here
E/ActivityThread( 3467): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3467): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3467): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3467): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3467): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3467): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3467): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3467): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3467): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3467): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3467): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3467): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3467): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3467): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3467): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3467): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3467): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3467): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3467): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3467): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3467): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3467): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  761): Unbind failed: could not find connection for android.os.BinderProxy@3671a4c9
,D/Finsky  ( 2627): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2627): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1603): Vacuum at: now=1455019807649 tag=VacuumService
,I/PhenotypeConfigurator( 1603): Scheduling Phenotype for one-off execution 1135 seconds from now (1455019808126)
,D/GetConfigurationSnapshotOperation( 1603): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1603): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1603): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  761): Explicit concurrent mark sweep GC freed 32446(1439KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.081ms total 85.153ms
,I/Keyboard.Facilitator.LanguageModelFlusher( 1110): run()
I/Keyboard.Facilitator( 1110): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1603): disconnect managed GoogleApiClient
,I/jxcore-log( 3179): --= Surplus to requirements =--
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ****TEST TOOK:  ms ****
I/jxcore-log( 3179): 
I/jxcore-log( 3179): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3179): 
,D/AndroidRuntime( 3612): 
D/AndroidRuntime( 3612): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3612): CheckJNI is OFF
,D/AndroidRuntime( 3612): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 3179:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  761): WIN DEATH: Window{28170a2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  761): Client connection lost with reason: 4
,W/PackageSettings(  761): Skipping PackageSetting{3fe91107 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{17f65078 u0 com.test.thalitest/.MainActivity t216}
,V/ActivityManager(  761): Display changed displayId=0
,W/ActivityManager(  761): Spurious death for ProcessRecord{1cad0f71 3179:com.test.thalitest/u0a270}, curProc for 3179: null
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1646): Explicit concurrent mark sweep GC freed 3770(200KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 529us total 27.092ms
,I/art     ( 1392): Explicit concurrent mark sweep GC freed 7656(545KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 1.170ms total 38.432ms
,I/art     ( 1359): Explicit concurrent mark sweep GC freed 7264(547KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 664us total 17.570ms
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1110): resetDictionaries() : en_US
W/GeofencerStateMachine( 1603): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1110): run()
,I/Decoder ( 1110): createOrResetDecoder
,I/art     (  761): Explicit concurrent mark sweep GC freed 8119(611KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.090ms total 51.820ms
,D/VoicemailCleanupService( 1410): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1392): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1359): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@381aa1a0 new=com.google.android.velvet.VelvetApplication@381aa1a0
,I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3651 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  944): Initialized EGL, version 1.4
,D/OpenGLRenderer(  944): Enabling debug mode 0
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1110): run()
,I/art     (  761): Explicit concurrent mark sweep GC freed 2928(160KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.219ms total 90.443ms
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  761): removeObsoleteFile: deleting file=216_task.xml
,W/InputMethodManagerService(  761): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@119e4197 (uid=10034 pid=944)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1110): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1110): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1110): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1110): run()
I/StatsUtilsManager( 1110): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1110): shouldRecordStats() = Too Soon
,W/ContextImpl( 3651): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1392): UpdateCorporaTask done [took 121 ms] updated apps [took 121 ms] 
,D/PackageBroadcastService( 1646): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1646): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1646): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1646): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1646): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1646): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1603): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1603): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1646): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1646): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1646): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1646): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1646): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1646): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1646): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1646): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1646): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1646): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1646): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1646): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1646): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1646): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3684 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/AndroidRuntime( 3612): Shutting down VM
I/Launcher( 1359): Deferring update until onResume
,I/GMPM-SVC( 1646): App measurement is starting up, version: 8489
I/GMPM-SVC( 1646): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/ResourcesManager( 1359): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/BaseAppContext( 1646): Using Auth Proxy for data requests.
,I/ActivityManager(  761): Killing 2724:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/ResourcesManager( 1359): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1359): Deferring update until onResume
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2724/cgroup.procs: No such file or directory
,W/BaseAppContext( 1646): Using Auth Proxy for data requests.
,I/Icing   ( 1646): doRemovePackageData com.test.thalitest
,I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3709 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2701:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  761): Client connection lost with reason: 4
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2701/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 2572:com.google.android.gm/u0a70 (adj 15): empty #17
,D/ExternalStorage( 3709): After updating volumes, found 1 active roots
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2572/cgroup.procs: No such file or directory
,W/ResourcesManager( 3100): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3100): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3684): Update found 7 roots in 176ms
,D/Documents( 3684): Update found 7 roots in 87ms

```
