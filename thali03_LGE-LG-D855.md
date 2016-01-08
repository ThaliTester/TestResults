#### Test 549702613245198_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 257676205534; DSPS: 8584706; Offset : -4322004354
,D/AndroidRuntime( 7232): 
D/AndroidRuntime( 7232): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7232): CheckJNI is OFF
D/AndroidRuntime( 7232): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1031): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1959): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1031): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{864c60 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1031): setTaskToReturnTo : TaskRecord{864c60 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1031): AppWindowTokenEx init.. 
E/GBMv2   (  344): DFP En is all cleared set to be enabled
I/ActivityManager( 1031): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7251 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7232): Shutting down VM
V/ActivityManager( 1031): Display changed displayId=0
D/DSDPConnection( 1870): Display #0 changed.
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{25746fb3 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{40e4970 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7251): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7251): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7251): Loading: webviewchromium
I/LibraryLoader( 7251): Time to load native libraries: 5 ms (timestamps 5831-5836)
I/LibraryLoader( 7251): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7251): Binding Chromium to main looper Looper (main, tid 1) {304adc23}
I/LibraryLoader( 7251): Expected native library version number "",actual native library version number ""
I/chromium( 7251): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7251): Initializing chromium process, renderers=0
W/art     ( 7251): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  319): registerClient() client 0xb57bf840, uid 10311
D/BluetoothManagerService( 1031): Message: 20
W/chromium( 7251): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7251): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7251): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7251): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7251): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7251): Build Date: 12/12/14 금
I/Adreno-EGL( 7251): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7251): Remote Branch: 
I/Adreno-EGL( 7251): Local Patches: 
I/Adreno-EGL( 7251): Reconstruct Branch: 
W/chromium( 7251): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7251): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7251): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7251): onDetachedFromWindow called when already detached. Ignoring
I/art     ( 1031): Explicit concurrent mark sweep GC freed 25695(1133KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 2.402ms total 151.395ms
D/BluetoothManagerService( 1031): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@120dd245:true
D/SystemWebViewEngine( 7251): CordovaWebView is running on device made by: LGE
W/art     ( 7251): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7251): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1031): Activity pause timeout for ActivityRecord{16b3f519 u0 com.test.thalitest/.MainActivity t4}
D/OpenGLRenderer( 7251): Render dirty regions requested: true
I/OpenGLRenderer( 7251): Initialized EGL, version 1.4
D/OpenGLRenderer( 7251): Enabling debug mode 0
D/Atlas   ( 7251): Validating map...
D/SplitWindow( 1031): check instance of lgWin Window{2367dd54 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 7251): LgDataFeature() Constructor: none
D/LgDataFeature( 7251): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1031): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1031): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1031): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1031): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@243252,  pkg=WindowManager.LayoutParams
D/PhoneStatusBar( 1478): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/SystemUI[Framework]( 1031): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1478): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1478):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1478): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1031): Displayed com.test.thalitest/.MainActivity: +673ms (total +754ms)
I/Timeline( 1031): Timeline: Activity_windows_visible id: ActivityRecord{16b3f519 u0 com.test.thalitest/.MainActivity t4} time:276299
I/Timeline( 7251): Timeline: Activity_idle id: android.os.BinderProxy@28bb1413 time:276299
I/chromium( 7251): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7251): 
D/JsMessageQueue( 7251): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 7251): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7251): 
D/jxcore_app_log( 7251): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435075840
D/JX-Cordova( 7251): jxcore cordova android initializing
E/GBMv2   (  344): DFP En is all cleared set to be enabled
E/GBMv2   (  344): Set value is all cleared set the max
I/GBMv2   (  344): DFP Enabled. Ignore VFP set
,D/sensors_hal_Time( 1031): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1031): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1031): tsOffsetIs: Apps: 277677624950; DSPS: 9240113; Offset : -4322017025
W/jxcore-log( 7251): Initializing JXcore engine
W/jxcore-log( 7251): JXcore engine is ready
W/jxcore-log( 7251): Starting JXcore engine
I/art     ( 7251): Background sticky concurrent mark sweep GC freed 124657(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.813ms total 134.426ms
,W/.test.thalitest( 7251): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8413]" dev="sockfs" ino=8413 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7251): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7251): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7667]" dev="sockfs" ino=7667 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7251): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7251): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33665]" dev="sockfs" ino=33665 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7251): Platform android
W/jxcore-log( 7251): 
W/jxcore-log( 7251): Process ARCH arm
W/jxcore-log( 7251): 
,I/jxcore-log( 7251): JXcore Cordova bridge is ready!
I/jxcore-log( 7251): 
W/jxcore-log( 7251): JXcore engine is started
,I/Choreographer( 7251): Skipped 138 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 7251): Toggling radios to true
I/jxcore-log( 7251): 
,D/BluetoothAdapter( 7251): enable(): BT is already enabled..!
D/WifiService( 1031): New client listening to asynchronous messages
D/WifiServiceImplEx( 1031): setWifiEnabled: true pid=7251, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService( 1031): setWifiEnabled: true pid=7251, uid=10311,
E/WifiService( 1031): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1031): disconnect pid=7251, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1031):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1031): [279,095,908 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1031): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1031): reconnect pid=7251, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7251): Radios toggled
I/jxcore-log( 7251): 
I/wpa_supplicant( 2706): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1031): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1031): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1031): InitialState.processMessage what=4
D/WifiNative-wlan0( 1031): DISCONNECT: returned true
E/WifiStateMachine( 1031): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1031): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1031): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2706): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
D/WifiNative-wlan0( 1031): SET ps 1: returned true
D/DhcpStateMachine( 1031): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 1031): sendTetherStateChangedBroadcast 0, 0, 0
D/CommandListener(  314): Clearing all IP addresses on wlan0
I/ActivityManager( 1031): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7324 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/NativeCrypto( 2131): Read error: ssl=0xaa6d8e00: I/O error during system call, Connection timed out
V/NativeCrypto( 2131): SSL shutdown failed: ssl=0xaa6d8e00: I/O error during system call, Broken pipe
E/WifiStateMachine( 1031): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1031):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_RECONNECT 0 0
,E/WifiNative: ( 1031): [279,219,251 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1031): doBoolean: RECONNECT
I/wpa_supplicant( 2706): wlan0: CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1031): ignoring duplicate network state non-change
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService( 1031): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1031): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1031): hidePasspointNotification off =false
,D/WifiNative-wlan0( 1031): RECONNECT: returned true
E/WifiStateMachine( 1031):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=279246
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WfdStateTracker( 1959): handleWifiStateChangedEvent: 0
E/WifiStateMachine( 1031):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=279265
D/WifiHS20( 1031): hidePasspointNotification off =false
D/LGWifiP2pService( 1031): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2706): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
D/WifiNative-wlan0( 1031): SET ps 1: returned true
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  314): Clearing all IP addresses on wlan0
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1031): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1031): disableDataServiceNotify
D/DSQN    ( 1031): stop dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1031): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/WifiHS20( 1031): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=279302  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=279302  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1031):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/ConnectivityService( 1031): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine( 1031):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/Nat464Xlat( 1031): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/CSLegacyTypeTracker( 1031): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
E/WifiStateMachine( 1031):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/CSLegacyTypeTracker( 1031): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Disconnected - quitting
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524292
E/WifiStateMachine( 1031):  DisconnectedState CMD_UPDATE_LINKPR,OPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1031): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
V/NetworkPolicy( 1031): [LG_RESTRICTED] !!!isConnected  type  :1
,D/WifiNetworkAgent( 1031): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=279309  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/LocSvc_java( 1031): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1031): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1031): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1031): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1031): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1031): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1031): Removing idletimer
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=279314  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1031): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1031): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
V/NetworkPolicy( 1031): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1870): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1031): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1031): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1031): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1031): ignore wifi update if we are not in OPENING or CLOSING
D/WifiHS20( 1031): hidePasspointNotification off =false
,W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,D/WIFI    ( 1031): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateDISCONNECTED
D/WIFI    ( 1031):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateSCANNING
W/ResourcesManager( 7324): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7324): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7324): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7324): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7324): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7324): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1031): StoppedState
D/DhcpStateMachine( 1031): StoppedState{ when=-143ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7324): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7324): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7324): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7324): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7324): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7324): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7324): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7324): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7324): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7324): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsControl( 7324): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1031): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7361 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 6629:com.android.defcontainer/u0a4 (adj 15): empty #17
I/art     (  348): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 459us total 25.466ms
,I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 401us total 19.072ms
,I/art     (  348): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 355us total 17.094ms
,W/libprocessgroup( 1031): failed to open /acct/uid_10004/pid_6629/cgroup.procs: No such file or directory
,I/PCSuite ( 7361): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7361): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7361): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7324): LgDataFeature() Constructor: none
D/LgDataFeature( 7324): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7324): MCCMNC not supported: null
I/ActivityManager( 1031): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7382 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1031): Killing 6776:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10008/pid_6776/cgroup.procs: No such file or directory
,W/ResourcesManager( 7382): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7382): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7382): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7382): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7382): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7382): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7382): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 7382): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7382): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7382): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7382): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7382): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7382): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7361): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7361): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7361): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7382): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 7324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7324): MCCMNC not supported: null
D/QRemote ( 7382): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7382): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7382): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7361): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7361): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7361): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7324): MCCMNC not supported: null
D/QRemote ( 7382): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7382): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7382): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7361): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7361): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7361): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7324): MCCMNC not supported: null
D/QRemote ( 7382): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7382): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7382): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7324): MCCMNC not supported: null
D/QRemote ( 7382): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7382): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7382): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7382): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7382): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7382): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7382): LgDataFeature() Constructor: none
D/LgDataFeature( 7382): LgDataFeature() Constructor Done, null
,V/SoundPool( 7382): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7382): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7382): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7382): doLoad: loading sample sampleID=1
V/SoundPool( 7382): Start decode
V/MediaPlayer[Native]( 7382): decode(31, 10857164, 17813)
V/MediaPlayerService(  319): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  319): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  319): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  319): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  319): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  319): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  319): player type = 3
V/AwesomePlayer(  319): AwesomePlayer create()
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/AwesomePlayer(  319): setAudioSink() 
V/AwesomePlayer(  319): reset_l() 
V/AudioCache(  319): notify(0xb5474c40, 8, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
D/Utils   (  319): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  319): setDataSource_l dataSource
V/LGParserOSAL(  319): SniffLGParser start
V/LGParserOSAL(  319): MainType:5, SubType=0
V/LGParserOSAL(  319): #### check Mime : application/ogg
V/LGParserOSAL(  319): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  319): Use LGExtractor :application/ogg 
I/QRemote ( 7382): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,D/UEI.SmartControl( 6921): QS Service created
D/QRemote ( 7382): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7382): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7382): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGParserOSAL(  319): supported mime: application/ogg
V/AwesomePlayer(  319): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  319): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  319): mBitrate = -1 bits/sec
V/AwesomePlayer(  319): AudioTrack Setting
V/AwesomePlayer(  319): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  319): setAudioSource() 
V/MediaPlayerService(  319): prepare
V/AwesomePlayer(  319): prepareAsync_l() 
V/MediaPlayerService(  319): wait for prepare
V/AwesomePlayer(  319): onPrepareAsyncEvent() 
V/AwesomePlayer(  319): initAudioDecoder() 
W/Utils   (  319): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  319): isOffloadSupported()
V/AudioPolicyManager(  319): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  319): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  319): isAudioPlaybackHookOn() false
V/AwesomePlayer(  319): getUseOffload() = 0 
V/OMXCodec(  319): OMXCodec::Create
V/OMXCodec(  319): findMatchingCodecs()
V/OMXCodec(  319): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  319): matchingCodecs.size()=1
V/OMXCodec(  319): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  319): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  319): LG Codec Adapter start
V/OMXCodec(  319): OMXCodec Createtor
V/OMXCodec(  319): setComponentRole
V/OMXCodec(  319): configureCodec protected=0
V/LGCodecAdapter(  319): called getLGCodecSpecificData
V/LGCodecOSAL(  319): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  319): Called LGconfigureCodecMETA
V/LGCodecOSAL(  319): Called LGconfigureCodecMSG
V/LGCodecOSAL(  319): Not support LGCodec
V/OMXCodec(  319): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  319): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  319): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  319): Could not offload audio decode, try pcm offload
W/Utils   (  319): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
,V/AudioSystem(  319): isOffloadSupported()
V/AudioPolicyManager(  319): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  319): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  319): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  319): init()
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  319): allocateBuffers
V/OMXCodec(  319): allocateBuffersOnPort portIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7880 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on input port
V/OMXCodec(  319): allocateBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57c2060 on output port
V/OMXCodec(  319): init() mAsyncCompletion wait!!! 
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  319): init() mAsyncCompletion wait!!! 
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  319): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  319): finishAsyncPrepare_l() 
V/AudioCache(  319): notify(0xb5474c40, 5, 0, 0)
V/AudioCache(  319): ignored
V/AudioCache(  319): notify(0xb5474c40, 1, 0, 0)
V/AudioCache(  319): prepared
V/AudioCache(  319): wait - success
V/MediaPlayerService(  319): start
V/AwesomePlayer(  319): play_l() 
V/AwesomePlayer(  319): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  319): createAudioPlayer_l
V/AwesomePlayer(  319): seekAudioIfNecessary_l() 
V/AwesomePlayer(  319): startAudioPlayer_l() 
D/AudioPlayer(  319): start of Playback, useOffload 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  319): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  319): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  319): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885488
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044810848
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_DISA,BLED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  319): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  319): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  319): allocateBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d30 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57c25b0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  319): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  319): notify(0xb5474c40, 6, 0, 0)
V/AudioCache(  319): ignored
V/MediaPlayerService(  319): wait for playback complete
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac700000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac701000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac702000, 0xb14b9000, 4096)
V/LGMDMManager( 7382): Create singleton instance
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac703000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac704000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac705000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac706000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac707000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac708000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac709000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac70a000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac70b000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac70c000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac70d000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac70e000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac70f000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac710000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac711000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac712000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac713000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac714000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac715000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac716000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac717000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac718000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac719000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac71a000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac71b000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac71c000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac71d000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac71e000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac71f000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac720000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac721000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac722000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac723000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac724000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac725000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac726000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac727000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac728000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac729000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac72a000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac72b000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac72c000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac72d000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac72e000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac72f000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac730000, 0xb14b9000, 4096)
V/AudioCache(  319): write(0xb14b9000, 4096)
V/AudioCache(  319): memcpy(0xac731000, 0xb14b9000, 4096)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  319): postAudioEOS() 
V/AudioCache(  319): write(0xb14b9000, 280)
V/AudioCache(  319): memcpy(0xac732000, 0xb14b9000, 280)
I/UEI.SmartControl( 6921): Service initServices...
D/UEI.SmartControl( 6921): QS start get config
V/AwesomePlayer(  319): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  319): onStreamDone
V/AwesomePlayer(  319): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  319): notify(0xb5474c40, 2, 0, 0)
V/AudioCache(  319): playback complete
V/AwesomePlayer(  319): pause_l() 
V/AudioCache(  319): notify(0xb5474c40, 7, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
D/AudioPlayer(  319): Pause Playback at 1068125
,V/AudioCache(  319): wait - success
V/MediaPlayerService(  319): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  319): reset_l() 
V/AudioCache(  319): notify(0xb5474c40, 8, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
D/AudioPlayer(  319): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  319): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7880 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb57c25b0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d30 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  319): AudioPlayer releasing audio source
D/AudioPlayer(  319): AudioPlayer done releasing audio source
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/AwesomePlayer(  319): ~AwesomePlayer call
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/SoundPool( 7382): close(31)
V/SoundPool( 7382): pointer = 0x9ff3a000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7382): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 7382): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7382): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:190
,I/UEI.SmartControl( 6921): Supports setup maps: true
,D/UEI.SmartControl( 6921): QS start statue = true Error code = 0
I/UEI.SmartControl( 6921): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6921): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6921): ### init IR Blaster...
D/serial_port( 6921): Configuring serial port
E/UEI.SmartControl( 6921): UEIBLaster setting for 616
I/UEI.SmartControl( 6921): Setting serial record hearder size = 2
I/UEI.SmartControl( 6921): configuring settings for MAXQ616
I/UEI.SmartControl( 6921): Get version...
D/UEI.SmartControl( 6921): serial port data available: 21
,D/UEI.SmartControl( 6921): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6921): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 6921): QS saving settings...
D/UEI.SmartControl( 6921): IR Blaster version: 25672567
D/UEI.SmartControl( 6921): serial port data available: 4
,I/UEI.SmartControl( 6921): Device manager: loading config....
W/ContextImpl( 6921): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
D/UEI.SmartControl( 6921): ----------- loading internal config...
,E/UEI.SmartControl( 6921): Services init done
D/UEI.SmartControl( 6921): QS Service init finished
D/UEI.SmartControl( 6921): QS Service version name: 2.1.91
D/UEI.SmartControl( 6921): QS Service version code: 201091
E/UEI.SmartControl( 6921): Loading SETTINGS...
D/UEI.SmartControl( 6921): Service requested: Control
D/UEI.SmartControl( 6921): Internal service binding...
,I/QRemote ( 7382): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6921): ------ IControl API: 11
D/UEI.SmartControl( 6921): File observer start...
E/UEI.SmartControl( 6921): IR Port is disabled: false
D/UEI.SmartControl( 6921): Starting file observer...
I/UEI.SmartControl( 6921): Registering callback...
I/UEI.SmartControl( 6921): ------ IControl API: 19
I/UEI.SmartControl( 6921): Registering Services Ready callback...
D/UEI.SmartControl( 6921): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6921): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6921): -----service ready thread exits
I/QRemote ( 7382): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7382): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7382): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7382): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7382): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,I/UEI.SmartControl( 6921): ------ IControl API: 8
D/QRemote ( 7382): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7382): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7382): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7382): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7382): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7382): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7382): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7382): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7382): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7382): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7382): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7382): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 7382): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7382): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7382): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452283886856]
D/QRemote ( 7382): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1031): Killing 6204:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/QRemote ( 7382): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1031): failed to open /acct/uid_10011/pid_6204/cgroup.procs: No such file or directory
,V/QRemote ( 7382): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7382): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7382): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7382): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7382): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7382): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7382): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7382): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
I/wpa_supplicant( 2706): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1031): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,D/WifiMonitor( 1031): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1031): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1031):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1031):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1031):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1031):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1031): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=281347  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=281368  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7324): MCCMNC not supported: null
D/QRemote ( 7382): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7382): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7382): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2706): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1031): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=281442  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=281443  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,D/Tethering( 1031): sendTetherStateChangedBroadcast 1, 0, 0
I/wpa_supplicant( 2706): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2706): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1031):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281444
E/WifiStateMachine( 1031):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281448
E/WifiStateMachine( 1031):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281448
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281448
E/WifiStateMachine( 1031):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281448
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=281448  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1031): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WiFiOffLoadBroadcast( 7324): MCCMNC not supported: null
W/WifiMonitor( 1031): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1031): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=281452  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1031):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=281453  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=281458  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1031):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=281458
E/WifiStateMachine( 1031):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=281459
D/WifiNative-wlan0( 1031): doString: [STATUS]
,D/WifiMonitor( 1031): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1031): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateASSOCIATED
D/WifiNative-wlan0( 1031):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1031): setVHTCapabilityType  : false
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7382): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7382): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7382): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/WifiServerServiceExt( 1031): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1031): setKeepAlivePacketInterval msec : 60
,I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/UsbSettingsReceiver( 7324): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7324): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7324): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7324): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7324): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7324): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7324): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7324): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7324): [AUTORUN] onReceive() : errorList=[]
,D/UsbSettingsControl( 7324): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7324): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7324): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1031): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1031): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1031): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1031): NetworkAgent connected
,D/WiFiOffLoadBroadcast( 7324): MCCMNC not supported: null
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
E/WifiConfigStore( 1031): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1031): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1031): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1031): doBoolean: SAVE_CONFIG
D/QRemote ( 7382): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7382): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7382): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1031): SAVE_CONFIG: returned true
D/CommandListener(  314): Setting iface cfg
E/WifiStateMachine( 1031): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1031): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1031): WaitBeforeStartState
E/WifiStateMachine( 1031):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281509  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281510  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281510  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1031):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateFOUR_WAY_HANDSHAKE
,V/WiFiOffLoadBroadcast( 7324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1031):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281519  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281520  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1031):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281520  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1031): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WiFiOffLoadBroadcast( 7324): MCCMNC not supported: null
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1031):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1031):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 7382): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7382): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7382): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7324): MCCMNC not supported: null
D/QRemote ( 7382): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7382): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7382): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2706): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 0
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1031): SET ps 0: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2706): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1031): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1031): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1031): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@340c8e98 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@340c8e98 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1031): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1031): DHCP Start wake lock is acquired.
D/CommandListener(  314): Setting iface cfg
D/CommandListener(  314): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1031): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
E/WifiStateMachine( 1031):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
E/WifiStateMachine( 1031):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1031): doBoolean: DRIVER BTCOEXMODE 2
D/WifiServerServiceExt( 1031): SUPPLICANT_STATE_CHANGED_ACTION
D/LGWifiP2pService( 1031): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt( 1031): setSupplicantStateCOMPLETED
I/wpa_supplicant( 2706): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1031): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1031): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1031): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2706): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1031): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1031): doBoolean: SET ps 1
V/WiFiOffLoadBroadcast( 7324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7324): MCCMNC not supported: null
D/QRemote ( 7382): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7382): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7382): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1031): SET ps 1: returned true
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine( 1031):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1031):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1031):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1031): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1031): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1031): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1031): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1031): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1031): [PASSPOINT] passpointNotification: hs20AP list is checked
V/WfdStateTracker( 1959): handleWifiStateChangedEvent: 1
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1031): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1031): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1031): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1031): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/ConnectivityService( 1031): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1031): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1031): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  314): netlink response contains error (File exists)
D/ConnectivityService( 1031): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
I/StatusBar.NetworkController( 1478): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1478): mWifiConnected = true, mWifiLevel = 0
D/ConnectivityService( 1031): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1031): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1031): Setting Dns servers for network 101 to [/192.168.1.1]
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Nat464Xlat( 1031): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1031): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1031): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1031): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1031):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1031):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Connected
D/ConnectivityService( 1031):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1031): currentScore = 0, newScore = 20
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1031):    accepting network in place of null
D/ConnectivityService( 1031): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Checking http://clients3.google.com/generate_204 on "NG700"
D/WIFI    ( 1031): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1031):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1031): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1031): Sending connecte,d broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/WiFiOffLoadBroadcast( 7324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1031): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1031): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1031): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1031): validation of new default Network = false
D/ConnectivityService( 1031): Default network via Wi-Fi connected. start DSQN
D/TelephonyNetworkFactory-1( 1870): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/DSQN    ( 1031): enableDataServiceNotify 
D/DSQN    ( 1031): start dsqn bin
D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1031): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1031): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1031): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1031): ignore wifi update if we are not in OPENING or CLOSING
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
V/NetworkPolicy( 1031): [LG_RESTRICTED] checkMobilePolicy_type()
D/WiFiOffLoadBroadcast( 7324): MCCMNC not supported: null
,D/ConnectivityService( 1031): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524290
W/dsqn    ( 7447): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7447): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/QRemote ( 7382): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7382): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/DSQN    ( 7447): DSQN ssw
,D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 7382): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7324): MCCMNC not supported: null
D/QRemote ( 7382): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7382): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7382): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7361): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7361): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7324): MCCMNC not supported: null
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
D/QRemote ( 7382): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7382): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7382): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7382): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 7382): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7361): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7361): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDataListener(  314): argv[0]=dsqncommand
D/LGDataListener(  314): argv[1]=wlan0
D/LGDataListener(  314): argv[2]=1
D/LGDataListener(  314): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1031): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1031): start to monitor internet connection
,D/WiFiOffLoadBroadcast( 7324): MCCMNC not supported: null
D/QRemote ( 7382): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7382): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7382): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7382): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7382): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 20:11:27 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452283887634], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452283887614]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1031): Validated
,D/ConnectivityService( 1031): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1031): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1031):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1031):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1031): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1031): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1031): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1031):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1870): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/TelephonyIcons( 1478): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1478): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1031): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1031): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1031): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7453): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7453): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7453): version 5.5.6 starting
,E/dhcpcd  ( 7453): get_duid: m
,D/dhcpcd  ( 7453): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7453): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7453): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7453): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7453): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7453): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7453): wlan0: sending REQUEST (xid 0xbe9b0807), next in 4.37 seconds
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1031): MasterInitialState.processMessage what=3
D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1031): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1031): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6736): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5956): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5956): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1031): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7479 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1031): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1031): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1031): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7479): onCreate
W/AppUp4:DB( 7479):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7479):  setFingerPrint start
I/AppUp4:DB( 7479):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7479):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7479):  SDK version = 21
I/AppUp4:DB( 7479):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7479): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7479): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7479): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7479): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7479): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7479): onReceive
D/LgDataFeature( 7479): LgDataFeature() Constructor: none
D/LgDataFeature( 7479): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7479): Context : android.app.ReceiverRestrictedContext@3f236ed9
D/AppUp4:CustFacade( 7479): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7479): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7479): begin check event
I/AppUp4:CustModeStarterReceiver( 7479): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7479): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7479): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7479): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7479): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1031): Killing 6226:com.android.contacts/u0a19 (adj 15): empty #17
D/LGDMClient( 4353): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4353): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1031): failed to open /acct/uid_10019/pid_6226/cgroup.procs: No such file or directory
W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3421): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3421): DownloadService onCreate
D/LGDMClient( 4353): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/LGDMClient( 4353): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/eas_req ( 6804): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/DownloadManager( 3421): in removeSpuriousFiles
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/LGDMClient( 4353): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4353): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@1446552d on behalf of 3421
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
,I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
E/LGDMClient( 4353): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4353): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4353): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3421): in trimDatabase
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@1db42a62 on behalf of 3421
,V/DownloadManager( 3421): DownloadService onStartCommand
V/DownloadManager( 3421): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@28601729 on behalf of 3421
,V/DownloadManager( 3421): processing inserted download 1
V/DownloadManager( 3421): processing inserted download 4
V/DownloadManager( 3421): processing inserted download 7
V/DownloadManager( 3421): processing inserted download 8
V/DownloadManager( 3421): processing inserted download 9
V/DownloadManager( 3421): processing inserted download 10
V/DownloadManager( 3421): processing inserted download 16
V/DownloadManager( 3421): processing inserted download 17
V/DownloadManager( 3421): processing inserted download 18
,V/DownloadManager( 3421): processing inserted download 21
I/ActivityManager( 1031): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7514 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3421): DownloadService onDestroy
I/HubEmail( 6804): JNI_OnLoad()
I/HubEmail( 6804): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6804): registerNatives()
I/HubEmail( 6804): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6804): registerNativeMethods()
I/HubEmail( 6804): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6804): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
E/WifiStateMachine( 1031):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1031):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1031):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1031):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1031):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1031): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1031): identical MTU - not setting
D/Nat464Xlat( 1031): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1031): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1031):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1031): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1478): CM callback handler got msg 524295
W/Settings( 6804): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 6804): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3362): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3362): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3362): networkInfo.isConnected() = false
,I/ActivityManager( 1031): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7537 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 7453): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/dhcpcd  ( 7453): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7453): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 7453): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7453): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7453): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7453): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7453): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7453): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/ActivityManager( 1031): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7570 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6830:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10027/pid_6830/cgroup.procs: No such file or directory
,D/DhcpStateMachine( 1031): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1031): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1031): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1031): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1031): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1031): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1031): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1031): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1031): RunningState
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1031): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7594 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1031): Killing 6861:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,V/FormManager( 7514): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7514): Alarm would be updated, because LastCheckTime has been updated.
W/libprocessgroup( 1031): failed to open /acct/uid_10061/pid_6861/cgroup.procs: No such file or directory
,I/art     ( 7594): Almond Protected OAT
,D/WeatherApplication( 7594): removeAccount
,D/WeatherApplication( 7594): Account.length = 0
E/WeatherApplication( 7594): OPERATOR:OPEN
D/WeatherAncestor( 7594): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:11:29
D/Weather.Utils( 7594): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7594): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7594): 2 : This is isUpdating : false
D/WeatherAncestor( 7594): connectivity changed - connection : true
D/WeatherService( 7594): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7594): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7594): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7594): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7594): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7594): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:11:29
I/ActivityManager( 1031): Killing 6894:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1031): failed to open /acct/uid_10080/pid_6894/cgroup.procs: No such file or directory
,I/ActivityManager( 1031): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7613 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1031): Killing 6974:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_6974/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7613): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7613): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7613): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7613): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/WifiStateMachine( 1031):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1031):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1031):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1031):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1031):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1031):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/WebViewFactory( 7613): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7613): Loading: webviewchromium
,I/LibraryLoader( 7613): Time to load native libraries: 3 ms (timestamps 4306-4309)
I/LibraryLoader( 7613): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7613): Binding Chromium to main looper Looper (main, tid 1) {2e95cf68}
,I/LibraryLoader( 7613): Expected native library version number "",actual native library version number ""
I/chromium( 7613): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7613): Initializing chromium process, renderers=0
,W/art     ( 7613): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7613): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7613): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7613): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  319): registerClient() client 0xb57bf060, uid 10093
W/AudioManagerAndroid( 7613): Requires BLUETOOTH permission
I/Adreno-EGL( 7613): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7613): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7613): Build Date: 12/12/14 금
I/Adreno-EGL( 7613): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7613): Remote Branch: 
I/Adreno-EGL( 7613): Local Patches: 
I/Adreno-EGL( 7613): Reconstruct Branch: 
,I/NSApplication( 7613): Starting up...
,I/ActivityManager( 1031): Killing 7003:com.lge.bnr/1000 (adj 15): empty #17
,V/WifiInternetCheck( 1031): Single check msg out of sync, ignoring.
,W/libprocessgroup( 1031): failed to open /acct/uid_1000/pid_7003/cgroup.procs: No such file or directory
,D/ConnectivityService( 1031): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1031): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1031): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5956): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1031): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6736): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7479): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7479): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7479): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7479): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7479): onReceive
D/AppUp4:CustFacade( 7479): Context : android.app.ReceiverRestrictedContext@3f236ed9
D/AppUp4:CustFacade( 7479): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7479): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7479): begin check event
I/AppUp4:CustModeStarterReceiver( 7479): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4353): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4353): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3421): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4353): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4353): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMClient( 4353): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4353): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3421): DownloadService onCreate
I/GLSUser ( 2131): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2131): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2131): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2131): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DownloadManager( 3421): in removeSpuriousFiles
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@2b26404f on behalf of 3421
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3421): in trimDatabase
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@1939fce5 on behalf of 3421
,V/DownloadManager( 3421): DownloadService onStartCommand
E/LGDMClient( 4353): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4353): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4353): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3421): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 6804): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6804): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3362): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3362): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3362): networkInfo.isConnected() = false
,V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@21b0926b on behalf of 3421
V/DownloadManager( 3421): processing inserted download 1
V/DownloadManager( 3421): processing inserted download 4
V/DownloadManager( 3421): processing inserted download 7
V/DownloadManager( 3421): processing inserted download 8
V/DownloadManager( 3421): processing inserted download 9
V/DownloadManager( 3421): processing inserted download 10
V/DownloadManager( 3421): processing inserted download 16
V/DownloadManager( 3421): processing inserted download 17
V/DownloadManager( 3421): processing inserted download 18
D/WeatherAncestor( 7594): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:11:30
V/DownloadManager( 3421): processing inserted download 21
,D/Weather.Utils( 7594): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7594): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7594): 2 : This is isUpdating : false
D/WeatherAncestor( 7594): connectivity changed - connection : true
D/WeatherService( 7594): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2165177f
D/ForecastDataCache( 7594): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7594): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7594): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7594): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7594): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:11:30
V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3421): DownloadService onDestroy
W/Kids    ( 2350): [AccountUtils] Account not ready
W/Kids    ( 2350): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2350): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2350): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
V/FormManager( 7514): There are no updated forms. The schedule will be deleted.
D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/FormManager( 7514): Alarm would be updated, because LastCheckTime has been updated.
,W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b128261 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6736): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7479): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7479): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7479): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7479): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7479): onReceive
D/AppUp4:CustFacade( 7479): Context : android.app.ReceiverRestrictedContext@3f236ed9
,D/AppUp4:CustFacade( 7479): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7479): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7479): begin check event
I/AppUp4:CustModeStarterReceiver( 7479): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 4353): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4353): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2131): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2131): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2131): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2131): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3421): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4353): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3421): DownloadService onCreate
V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DownloadManager( 3421): in removeSpuriousFiles
I/LGDMClient( 4353): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@1b128261 on behalf of 3421
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3421): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3421): in trimDatabase
V/DownloadManager( 3421): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@22a14186 on behalf of 3421
D/LGDMClient( 4353): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4353): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4353): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4353): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4353): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3421): DownloadService onStartCommand
V/DownloadManager( 3421): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/Settings( 6804): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3421): created cursor android.database.sqlite.SQLiteCursor@d93e39d on behalf of 3421
W/Settings( 6804): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3421): processing inserted download 1
V/DownloadManager( 3421): processing inserted download 4
W/Kids    ( 2350): [AccountUtils] Account not ready
W/Kids    ( 2350): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2350): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2350): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3421): processing inserted download 7
V/DownloadManager( 3421): processing inserted download 8
V/DownloadManager( 3421): processing inserted download 9
I/LgeMiscReceiver( 3362): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3362): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3362): networkInfo.isConnected() = true
D/PhoneState( 3362): setPdpRejectCasuse : false
V/DownloadManager( 3421): processing inserted download 10
V/DownloadManager( 3421): processing inserted download 16
,D/LgeQuickCoverNLService( 1419): onNotificationPosted
V/DownloadManager( 3421): processing inserted download 17
V/DownloadManager( 3421): processing inserted download 18
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
V/DownloadManager( 3421): processing inserted download 21
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/WeatherAncestor( 7594): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:11:30
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
V/DownloadManager( 3421): DownloadService onDestroy
D/Weather.Utils( 7594): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7594): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7594): 2 : This is isUpdating : false
D/WeatherAncestor( 7594): connectivity changed - connection : true
D/WeatherService( 7594): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2165177f
D/ForecastDataCache( 7594): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7594): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7594): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7594): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7594): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 21:11:30
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b128261 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2350): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/FormManager( 7514): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7514): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2131): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2131): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2131): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2131): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2131): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1031): Explicit concurrent mark sweep GC freed 85381(4MB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 2.320ms total 139.341ms
,V/NotificationService( 1031): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1031): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1031): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1031): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1031): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2350): [AccountUtils] Account not ready
W/Kids    ( 2350): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2350): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2350): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2350): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2350): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2350): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{1b128261 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/PowerManagerServiceEx( 1031): acquireWakeLockInternal: lock=375122027, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1031
,D/[Concierge]Service( 2613): onStartCommand(). Type : 9
,V/QRemote ( 7382): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7382): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:190
,D/PowerManagerServiceEx( 1031): releaseWakeLockInternal: lock=375122027 [*alarm*], flags=0x0
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  314): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = www.google.com succeed
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
,D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
D/UEI.SmartControl( 6921): Internal timer expired: 3
D/UEI.SmartControl( 6921): unbind internal service
,V/WifiInternetCheck( 1031): isHttpConnectionAvailable - We got a valid response : 204
,D/serial_port( 6921): close(fd = 24)
,I/UEI.SmartControl( 6921): Serial port is closed.
V/AlarmManager( 1031): ELAPSED_WAKEUP set : Alarm{3d5a2b1a type 2 when 286275 com.google.android.gms} when 286275
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  314): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2131): Connected
,D/GCM     ( 2131): Message class com.google.f.a.a.p
I/jxcore-log( 7251): Test app app.js loaded
I/jxcore-log( 7251): 
,I/chromium( 7251): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7251): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 7251): --= Surplus to requirements =--
I/jxcore-log( 7251): 
I/jxcore-log( 7251): ****TEST TOOK:  ms ****
I/jxcore-log( 7251): 
,I/jxcore-log( 7251): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7251): 
I/GAV4    ( 7613): Thread[GAThread,5,main]: No campaign data found.
,D/AndroidRuntime( 7753): 
D/AndroidRuntime( 7753): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7753): CheckJNI is OFF
,D/AndroidRuntime( 7753): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1031): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1031): Killing 7251:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,W/PackageSettings( 1031): Skipping PackageSetting{167950f1 com.example.hello/10319} due to missing metadata
I/WindowState( 1031): WIN DEATH: Window{2367dd54 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1031): Client connection lost with reason: 4
,D/InputDispatcher( 1031): Window went away: Window{2367dd54 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1031):   Force finishing activity ActivityRecord{16b3f519 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  344): DFP En is all cleared set to be enabled
,W/ActivityManager( 1031): Spurious death for ProcessRecord{b1db941 7251:com.test.thalitest/u0a311}, curProc for 7251: null
,I/ActivityManager( 1031): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1031):   Force finishing activity ActivityRecord{16b3f519 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1031): Duplicate finish request for ActivityRecord{16b3f519 u0 com.test.thalitest/.MainActivity t4 f}
I/[LGHome]EVENT( 2085): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{111594e9 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{2ec5956e co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]EVENT( 2085): [Launcher.java:903:onResume()]onResume
D/KeyguardModel( 1478): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_MrGDBLogger_PackageInfoDetector( 3724): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,D/LIA_Service_RemotePackageHandler( 2032): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
E/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] [+] updateMediaPlayerInfo
W/GeofencerStateMachine( 1828): Ignoring removeGeofence because network location is disabled.
I/InputReader( 1031): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 4644): Explicit concurrent mark sweep GC freed 15850(890KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 606us total 120.766ms
,W/System.err( 4592): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 4592): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
,W/System.err( 4592): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4592): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4592): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4592): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4592): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4592): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4592): 	at java.lang.reflect.Method.invoke(Native Method)
D/administrator( 1031): Handling package changes for user 0
I/[LGHome]EVENT( 2085): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2085): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
W/System.err( 4592): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4592): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4592): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,I/[SystemUI]QSlideListController( 1478): onReceive = android.intent.action.PACKAGE_REMOVED
D/ActionManagerService( 1922): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3724): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2085): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/PostponalbeReceiver( 6736): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/[LGHome]LGActivityUtil( 2085): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 2085): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2085): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1922): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2085): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,D/LIA_Informant_ActionManagerMessageHandler( 3724): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3724): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2085): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2085): , create_time: 1430558575574
I/GBoardWebViewUtils( 2085): , expire_time: 0
I/GBoardWebViewUtils( 2085): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2085): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2085): , display: false
I/GBoardWebViewUtils( 2085): , animation: false }
I/GBoardWebViewUtils( 2085): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2085): , create_time: 1430558575600
I/GBoardWebViewUtils( 2085): , expire_time: 0
I/GBoardWebViewUtils( 2085): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2085): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2085): , display: false
I/GBoardWebViewUtils( 2085): , animation: false }
I/GBoardWebViewUtils( 2085): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2085): , create_time: 1452175675684
I/GBoardWebViewUtils( 2085): , expire_time: 0
I/GBoardWebViewUtils( 2085): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2085): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2085): , display: false
I/GBoardWebViewUtils( 2085): , animation: false }
D/WallpaperManager( 2085): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1478): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1478): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/SplitUIManager( 1887): split_name #11 / not available #0
D/SplitUIService( 1887): removed split : 
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,I/SystemUI[Framework]( 1031): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1031): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1031): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1031): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@243252,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1031): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
V/SIM_STK ( 1031): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2085): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]GBoardWebView( 2085): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/ActivityManager( 1031): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7789 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,D/SplitUIManager( 1887): split_name #11 / not available #0
I/SplitUIService( 1887): split app #11
,W/ActivityManager( 1031): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3811): [BTUI] [-] updateMediaPlayerInfo
,V/SIM_STK ( 1031): Menu title from STK is T-Mobile
,D/AppUp4:PreloadHelper( 7479): added Exclude : com.test.thalitest
I/LockScreenSettings( 7789): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/art     ( 1031): Explicit concurrent mark sweep GC freed 14056(1080KB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 1.477ms total 312.089ms
,I/NotificationService( 1031): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
I/ActivityManager( 1031): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7807 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/BackupManagerService( 1031): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1031): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2085): [Launcher.java:5349:onStop()]onStop
,D/TaskPersister( 1031): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1478): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
D/KeyguardModel( 1478): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1478): createShortcutInfo...
I/[SystemUI]NavigationThemeResource( 1478): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1478):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1478): , Keyguard show=false, IME shown=false, Panel expanded=false
D/KeyguardModel( 1478): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1478): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1478): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1478): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1478): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourcesManager( 7807): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7807): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7807): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7807): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7807): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1478): handleShortcutListChanged...
D/KeyguardModel( 1478): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1478): createShortcutInfo...
,D/KeyguardModel( 1478): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1478): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1478): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1478): createShortcutInfo...
W/ResourceType( 1478): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1478): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]Launcher.Model( 2085): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
D/KeyguardModel( 1478): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1478): createShortcutInfo...
I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ThermalEngine(  332): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3152): Thermal-Lib-Client: Client request sent
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/ActivityManager( 1031): Killing 7029:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/[LGHome]Launcher.Model( 2085): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2085): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2085): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2085): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2085): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,W/ResourcesManager( 1031): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/AndroidRuntime( 7753): Shutting down VM
,W/ResourceType( 1031): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/KeyguardModel( 1478): handleShortcutListChanged...
,D/[Concierge]Service( 2613): onStartCommand(). Type : 8
D/[Concierge]Service( 2613): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
W/libprocessgroup( 1031): failed to open /acct/uid_10005/pid_7029/cgroup.procs: No such file or directory
D/[Concierge]Service( 2613): Update widget ID : 11
I/Timeline( 1031): Timeline: Activity_windows_visible id: ActivityRecord{4c5b670 u0 com.lge.launcher2/.Launcher t3} time:290494
D/[Concierge]WidgetView( 2085): change position of spinner
I/[Concierge]WidgetView( 2085): initWebView(). Time : 1452283896424
D/[Concierge]Service( 2613): onStartCommand(). Type : 0
,I/SystemConfig( 7807): BUILD Country: EU
I/SystemConfig( 7807): BUILD Operator: OPEN
I/[Concierge]WebView( 2085): Return exist ConciergeWebView. Reuse : 781765681
D/[Concierge]WidgetView( 2085): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2085): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2085): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@36954727
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 2085): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2085): isWidgetUpdateSkippable ? true
I/[LGHome]EVENT( 2085): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/[Concierge]WidgetBroadcastReceiver( 2085): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/ActivityManager( 1031): Killing 7111:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/[Concierge]WidgetView( 2085): Widget kill message received. Destory myself. My : 1452283634438, New one : 1452283896424
D/[Concierge]WidgetView( 2085): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2085): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/libprocessgroup( 1031): failed to open /acct/uid_10054/pid_7111/cgroup.procs: No such file or directory
I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/SystemConfig( 7807): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7807): existFile = false
,I/SystemConfig( 7807): canReadFile = false
I/SystemConfig( 7807): systemFeature RCS result false
D/SystemConfig( 7807): refreshRcsSupport() :false
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/PackageChangeReceiver( 6804): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/VoicemailCleanupService( 2194): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1031): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7830 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2085): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2085): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2085): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,I/[LGHome]Launcher( 2085): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7830): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7830): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7830): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/Timeline( 2085): Timeline: Activity_idle id: android.os.BinderProxy@30c40310 time:290671
I/AppConfig( 7830): Total System Memory = 2995761152
,D/SystemHelper( 7830): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1031): Killing 6341:com.android.vending/u0a44 (adj 15): empty #17
,I/chromium( 2085): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/GBoardtInterface( 2085): onReloaded()
,I/GBoardWebViewClient( 2085): onPageFinished url:file:///android_asset/www/main.html
W/libprocessgroup( 1031): failed to open /acct/uid_10044/pid_6341/cgroup.procs: No such file or directory
D/LIA_Service_NativeEventReceiver( 2032): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2032): startLIAService() : Trying to start LIA service ...

```
