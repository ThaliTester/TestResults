#### Test 5644966031ce140_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 267837730107; DSPS: 8917679; Offset : -4321398749
,D/AndroidRuntime( 7167): 
D/AndroidRuntime( 7167): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7167): CheckJNI is OFF
D/AndroidRuntime( 7167): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1047): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1924): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1047): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1047): setTaskToReturnTo : TaskRecord{129ee0ea #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1047): setTaskToReturnTo : TaskRecord{129ee0ea #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1047): AppWindowTokenEx init.. 
E/GBMv2   (  351): DFP En is all cleared set to be enabled
I/ActivityManager( 1047): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7187 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7167): Shutting down VM
V/ActivityManager( 1047): Display changed displayId=0
D/DSDPConnection( 1835): Display #0 changed.
D/SplitWindowPolicy( 1924): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1924): topRunningActivity=ActivityInfo{2512110b co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1924): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1924): topRunningActivity=ActivityInfo{364cbe8 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7187): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7187): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7187): Loading: webviewchromium
I/LibraryLoader( 7187): Time to load native libraries: 5 ms (timestamps 4170-4175)
,I/LibraryLoader( 7187): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7187): Binding Chromium to main looper Looper (main, tid 1) {2461537b}
,I/LibraryLoader( 7187): Expected native library version number "",actual native library version number ""
I/chromium( 7187): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7187): Initializing chromium process, renderers=0
,W/art     ( 7187): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  331): registerClient() client 0xb14fd880, uid 10311
,W/chromium( 7187): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7187): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
D/BluetoothManagerService( 1047): Message: 20
D/BluetoothManagerService( 1047): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42f6624:true
I/chromium( 7187): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7187): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7187): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7187): Build Date: 12/12/14 금
I/Adreno-EGL( 7187): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7187): Remote Branch: 
I/Adreno-EGL( 7187): Local Patches: 
I/Adreno-EGL( 7187): Reconstruct Branch: 
,W/chromium( 7187): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7187): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7187): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7187): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7187): CordovaWebView is running on device made by: LGE
,W/art     ( 7187): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7187): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1047): Activity pause timeout for ActivityRecord{35293fdb u0 com.test.thalitest/.MainActivity t4}
,D/OpenGLRenderer( 7187): Render dirty regions requested: true
I/OpenGLRenderer( 7187): Initialized EGL, version 1.4
D/OpenGLRenderer( 7187): Enabling debug mode 0
,D/Atlas   ( 7187): Validating map...
,D/SplitWindow( 1047): check instance of lgWin Window{3e619a3e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7187): LgDataFeature() Constructor: none
,D/LgDataFeature( 7187): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1047): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1047): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1047): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1047): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1be3ee39,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1456): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1456): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1456):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1456): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/ActivityManager( 1047): Displayed com.test.thalitest/.MainActivity: +688ms (total +781ms)
I/Timeline( 1047): Timeline: Activity_windows_visible id: ActivityRecord{35293fdb u0 com.test.thalitest/.MainActivity t4} time:274648
I/Timeline( 7187): Timeline: Activity_idle id: android.os.BinderProxy@6ea116b time:274665
,D/JsMessageQueue( 7187): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7187): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7187): 
,D/jxcore_app_log( 7187): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435098880
,I/chromium( 7187): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7187): 
,I/chromium( 7187): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  351): DFP En is all cleared set to be enabled
E/GBMv2   (  351): Set value is all cleared set the max
I/GBMv2   (  351): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7187): Initializing JXcore engine
W/jxcore-log( 7187): JXcore engine is ready
,W/Thread-839( 7248): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7458]" dev="sockfs" ino=7458 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-839( 7248): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-839( 7248): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8921]" dev="sockfs" ino=8921 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-839( 7248): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-839( 7248): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[34831]" dev="sockfs" ino=34831 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 7187): Starting JXcore engine
W/jxcore-log( 7187): Platform android
W/jxcore-log( 7187): 
W/jxcore-log( 7187): Process ARCH arm
W/jxcore-log( 7187): 
,I/art     ( 7187): Background sticky concurrent mark sweep GC freed 136524(13MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 40MB/56MB, paused 1.842ms total 160.318ms
I/jxcore-log( 7187): JXcore Cordova bridge is ready!
I/jxcore-log( 7187): 
W/jxcore-log( 7187): JXcore engine is started
I/jxcore-log( 7187): Toggling radios to true
I/jxcore-log( 7187): 
D/BluetoothAdapter( 7187): enable(): BT is already enabled..!
D/WifiService( 1047): New client listening to asynchronous messages
D/WifiServiceImplEx( 1047): setWifiEnabled: true pid=7187, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1047): setWifiEnabled: true pid=7187, uid=10311
E/WifiService( 1047): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1047): disconnect pid=7187, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1047): reconnect pid=7187, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1047):  ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 7187): Radios toggled
I/jxcore-log( 7187): 
I/jxcore-log( 7187): My device name is: LGE-LG-D855
I/jxcore-log( 7187): 
E/WifiStateMachine( 1047):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1047): [277,121,652 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1047): doBoolean: DISCONNECT
I/wpa_supplicant( 2690): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1047): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1047): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1047): InitialState.processMessage what=4
D/Tethering( 1047): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1047): DISCONNECT: returned true
E/WifiStateMachine( 1047): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1047): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1047): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1047): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1047): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1047): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1047): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2690): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1047): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1047): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1047): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1047): doBoolean: SET ps 1
D/WifiNative-wlan0( 1047): SET ps 1: returned true
D/CommandListener(  326): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1047): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2054): Read error: ssl=0xaf498400: I/O error during system call, Connection timed out
V/NativeCrypto( 2054): SSL shutdown failed: ssl=0xaf498400: I/O error during system call, Broken pipe
I/art     (  362): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 192us total 10.953ms
I/ActivityManager( 1047): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7258 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/ConnectivityService( 1047): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1047): ignoring duplicate network state non-change
E/WifiStateMachine( 1047): Start Disconnecting Watchdog 1
D/ConnectivityService( 1047): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1047):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_RECONNECT 0 0
D/WifiHS20( 1047): hidePasspointNotification off =false
E/WifiNative: ( 1047): [277,252,800 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1047): doBoolean: RECONNECT
I/wpa_supplicant( 2690): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1047): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1047): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1047): RECONNECT: returned true
E/WifiStateMachine( 1047):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=277259
E/WifiStateMachine( 1047):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=277259
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService( 1047): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1047): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1047): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2690): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
I/art     (  362): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 10.999ms
D/WifiHS20( 1047): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/art     (  362): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 11.775ms
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1047): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1047): doBoolean: SET ps 1
D/ConnectivityService( 1047): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1924): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1047): SET ps 1: returned true
D/CommandListener(  326): Clearing all IP addresses on wlan0
D/libc-netbsd(  326): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1047): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1047): disableDataServiceNotify
D/DSQN    ( 1047): stop dsqn bin
D/DSQN    ( 1047): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiHS20( 1047): hidePasspointNotification off =false
E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=277308  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=277309  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1047):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1047):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1047):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1047): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1047):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1047): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1047):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/Nat464Xlat( 1047): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Disconnected - quitting
D/CSLegacyTypeTracker( 1047): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1047): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524292
D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiNetworkAgent( 1047): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=277317  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1047): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1047): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1047): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1047): Removing idletimer
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=277318  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1047): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WIFI    ( 1047): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1047):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1047): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/TelephonyNetworkFactory-1( 1835): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1835):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1047): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1047): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1047): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1047): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1047): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1047): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1047): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1047): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1047): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1047): ignore wifi update if we are not in OPENING or CLOSING
D/WifiHS20( 1047): hidePasspointNotification off =false
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateSCANNING
D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7258): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7258): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7258): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7258): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7258): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7258): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7258): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7258): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7258): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7258): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7258): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7258): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7258): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7258): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7258): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7258): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7258): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/DhcpStateMachine( 1047): StoppedState
D/DhcpStateMachine( 1047): StoppedState{ when=-201ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1047): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7295 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1047): Killing 6646:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1047): failed to open /acct/uid_10008/pid_6646/cgroup.procs: No such file or directory
I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 7258): LgDataFeature() Constructor: none
D/LgDataFeature( 7258): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7258): MCCMNC not supported: null
D/QRemote ( 6987): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6987): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6987): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7258): MCCMNC not supported: null
D/QRemote ( 6987): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6987): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6987): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7258): MCCMNC not supported: null
D/QRemote ( 6987): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6987): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6987): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7295): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7258): MCCMNC not supported: null
D/QRemote ( 6987): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6987): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6987): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7258): MCCMNC not supported: null
D/QRemote ( 6987): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6987): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6987): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/ActivityManager( 1047): Killing 6668:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1047): failed to open /acct/uid_10011/pid_6668/cgroup.procs: No such file or directory
,I/wpa_supplicant( 2690): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1047): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1047): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1047): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1047):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1047):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1047):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1047):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1047): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=279367  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=279371  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7258): MCCMNC not supported: null
D/QRemote ( 6987): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6987): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6987): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7258): MCCMNC not supported: null
D/QRemote ( 6987): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6987): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6987): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2690): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1047): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=279471  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=279471  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1047):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=279472
E/WifiStateMachine( 1047):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=279472
E/WifiStateMachine( 1047):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=279472
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=279473
E/WifiStateMachine( 1047):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=279473
E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=279473  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/Tethering( 1047): sendTetherStateChangedBroadcast 1, 0, 0
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7258): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7258): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7258): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7258): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=279477  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/UsbSettingsReceiver( 7258): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
E/WifiStateMachine( 1047):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1047): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1047):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsControl( 7258): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7258): [AUTORUN] onReceive() : availableList=[wlan0]
E/WifiStateMachine( 1047):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsReceiver( 7258): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7258): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7258): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceive,r( 7258): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7258): [AUTORUN] setTetherStatus() : status=false
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateFOUR_WAY_HANDSHAKE
I/wpa_supplicant( 2690): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2690): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1047): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1047): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1047): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=279484  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=279484  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1047):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=279485
E/WifiStateMachine( 1047):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=279485
D/WifiNative-wlan0( 1047): doString: [STATUS]
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1047):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1047): setVHTCapabilityType  : false
I/WifiServerServiceExt( 1047): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1047): setKeepAlivePacketInterval msec : 60
,V/WiFiOffLoadBroadcast( 7258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/ConnectivityService( 1047): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1047): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1047): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1047): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1047): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1047): NetworkAgent connected
D/WifiNative-wlan0( 1047): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1047): doBoolean: SAVE_CONFIG
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7258): MCCMNC not supported: null
,I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/QRemote ( 6987): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6987): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6987): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1047): SAVE_CONFIG: returned true
E/WifiConfigStore( 1047): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1047): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1047): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1047): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1047): SAVE_CONFIG: returned true
D/CommandListener(  326): Setting iface cfg
E/WifiStateMachine( 1047): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1047): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1047): WaitBeforeStartState
E/WifiStateMachine( 1047):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=279524  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=279525  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=279525  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=279526  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1047):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=279526  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=279526  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/WiFiOffLoadBroadcast( 7258): MCCMNC not supported: null
E/WifiStateMachine( 1047):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1047): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1047):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1047):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1047): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 6987): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6987): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6987): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7258): MCCMNC not supported: null
,D/QRemote ( 6987): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6987): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6987): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2690): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1047): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1047): doBoolean: SET ps 0
V/WiFiOffLoadBroadcast( 7258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1047): SET ps 0: returned true
,D/WifiNative-wlan0( 1047): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2690): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1047): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1047): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1047): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1047): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1eb50281 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1047): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1047): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1eb50281 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1047): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1047): DHCP Start wake lock is acquired.
D/CommandListener(  326): Setting iface cfg
D/CommandListener(  326): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper( 1047): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1047):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1047): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1047):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1047):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1047): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1047): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2690): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1047): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1047): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1047): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2690): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1047): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1047): doBoolean: SET ps 1
D/WifiNative-wlan0( 1047): SET ps 1: returned true
D/ConnectivityService( 1047): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1047):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1047):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1047): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1047): ignoring duplicate network state non-change
,I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WiFiOffLoadBroadcast( 7258): MCCMNC not supported: null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1047): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1047): Adding iface wlan0 to network 101
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1047): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
V/WfdStateTracker( 1924): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1047): [PASSPOINT] passpointNotification: hs20AP list is checked
E/WifiStateMachine( 1047): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/QRemote ( 6987): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6987): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6987): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1456): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1456): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1047): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1047): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1047): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  326): netlink response contains error (File exists)
D/ConnectivityService( 1047): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1047): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1047): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1047): Setting Dns servers for network 101 to [/192.168.1.1]
V/WiFiOffLoadBroadcast( 7258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/Nat464Xlat( 1047): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1047): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1047): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1047): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Connected
D/ConnectivityService( 1047):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1047):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1047):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1047):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1047): currentScore = 0, newScore = 20
D/ConnectivityService( 1047):    accepting network in place of null
D/ConnectivityService( 1047): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1835): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1835):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1047): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1047):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  326): res_queryN name = clients3.google.com, class = 1, type = 28
E/ConnectivityService( 1047): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySe,lected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1047): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WiFiOffLoadBroadcast( 7258): MCCMNC not supported: null
D/ConnectivityService( 1047): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1047): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1047): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1047): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1047): getAGpsConnectionInfo connType - 4
D/ConnectivityService( 1047): validation of new default Network = false
D/ConnectivityService( 1047): Default network via Wi-Fi connected. start DSQN
D/LocSvc_java( 1047): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/DSQN    ( 1047): enableDataServiceNotify 
D/DSQN    ( 1047): start dsqn bin
D/LocSvc_java( 1047): ignore wifi update if we are not in OPENING or CLOSING
D/QRemote ( 6987): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6987): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1047): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524290
I/QRemote ( 6987): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
W/dsqn    ( 7351): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7351): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/NetworkPolicy( 1047): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 7351): DSQN ssw
V/WiFiOffLoadBroadcast( 7258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7258): MCCMNC not supported: null
D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 6987): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6987): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6987): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/libc-netbsd(  326): res_queryN name = clients3.google.com, class = 1, type = 1
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7258): MCCMNC not supported: null
D/QRemote ( 6987): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6987): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6987): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6987): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6987): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7295): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7295): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7258): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7258): MCCMNC not supported: null
D/QRemote ( 6987): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6987): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6987): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6987): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6987): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/libc-netbsd(  326): res_queryN name = clients3.google.com succeed
D/LGDataListener(  326): argv[0]=dsqncommand
D/LGDataListener(  326): argv[1]=wlan0
D/LGDataListener(  326): argv[2]=1
D/LGDataListener(  326): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1047): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1047): start to monitor internet connection
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 19 Jan 2016 12:06:30 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453205190169], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453205190152]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Validated
D/ConnectivityService( 1047): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1047): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1047):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1047):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1047): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1047): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524290
D/WIFI    ( 1047): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1047):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1835): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1835):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/DhcpStateMachine( 1047): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1047): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1047): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,D/TelephonyIcons( 1456): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1456): refreshViews: Data not connected!! Set no data type icon / Roaming
W/dhcpcd  ( 7357): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7357): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7357): version 5.5.6 starting
,E/dhcpcd  ( 7357): get_duid: m
D/dhcpcd  ( 7357): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7357): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7357): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7357): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7357): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 7357): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7357): wlan0: sending REQUEST (xid 0xe98d24c0), next in 3.66 seconds
D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1047): MasterInitialState.processMessage what=3
D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/Tethering( 1047): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5557): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1047): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1047): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5557): type=WIFI subType= reason=null isConnected=true
W/ContextImpl( 6612): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/ActivityManager( 1047): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7383 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1047): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
D/GpsLocationProvider( 1047): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7383): onCreate
,W/AppUp4:DB( 7383):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7383):  setFingerPrint start
I/AppUp4:DB( 7383):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7383):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7383):  SDK version = 21
I/AppUp4:DB( 7383):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7383): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7383): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7383): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7383): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7383): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7383): onReceive
,D/LgDataFeature( 7383): LgDataFeature() Constructor: none
D/LgDataFeature( 7383): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7383): Context : android.app.ReceiverRestrictedContext@15d551f1
D/AppUp4:CustFacade( 7383): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7383): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7383): begin check event
I/AppUp4:CustModeStarterReceiver( 7383): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7383): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7383): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7383): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7383): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1047): Killing 6692:com.android.contacts/u0a19 (adj 15): empty #17
,E/WifiStateMachine( 1047):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1047):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1047):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1047):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1047):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1047): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1047): identical MTU - not setting
D/Nat464Xlat( 1047): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1047): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1456): CM callback handler got msg 524295
D/LGDMClient( 4363): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4363): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/libprocessgroup( 1047): failed to open /acct/uid_10019/pid_6692/cgroup.procs: No such file or directory
,W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3451): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3451): DownloadService onCreate
,D/LGDMClient( 4363): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4363): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3451): DownloadService onStartCommand
V/DownloadManager( 3451): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3451): in removeSpuriousFiles
V/DownloadManager( 3451): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 4363): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1,
V/DownloadManager( 3451): created cursor android.database.sqlite.SQLiteCursor@23b4a14b on behalf of 3451
I/LGDMClient( 4363): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3451): created cursor android.database.sqlite.SQLiteCursor@80fb728 on behalf of 3451
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3451): in trimDatabase
V/DownloadManager( 3451): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3451): created cursor android.database.sqlite.SQLiteCursor@96f5c41 on behalf of 3451
,V/DownloadManager( 3451): processing inserted download 1
V/DownloadManager( 3451): processing inserted download 4
V/DownloadManager( 3451): processing inserted download 7
V/DownloadManager( 3451): processing inserted download 8
V/DownloadManager( 3451): processing inserted download 9
V/DownloadManager( 3451): processing inserted download 10
V/DownloadManager( 3451): processing inserted download 16
V/DownloadManager( 3451): processing inserted download 17
V/DownloadManager( 3451): processing inserted download 18
D/eas_req ( 6716): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4363): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4363): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4363): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3451): processing inserted download 21
V/DownloadManager( 3451): processing inserted download 22
V/DownloadManager( 3451): DownloadService onDestroy
I/ActivityManager( 1047): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7418 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 6716): JNI_OnLoad()
I/HubEmail( 6716): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6716): registerNatives()
I/HubEmail( 6716): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6716): registerNativeMethods()
,I/HubEmail( 6716): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6716): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6716): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6716): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/dhcpcd  ( 7357): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/LgeMiscReceiver( 3386): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3386): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3386): networkInfo.isConnected() = false
I/dhcpcd  ( 7357): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7357): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7357): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7357): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7357): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7357): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7357): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7357): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,I/ActivityManager( 1047): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7444 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  326): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  326): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,D/libc-netbsd(  326): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1047): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7482 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1047): Killing 6740:com.android.gallery3d/u0a27 (adj 15): empty #17
,V/FormManager( 7418): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7418): Alarm would be updated, because LastCheckTime has been updated.
D/DhcpStateMachine( 1047): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1047): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1047): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
W/libprocessgroup( 1047): failed to open /acct/uid_10027/pid_6740/cgroup.procs: No such file or directory
D/LgDhcpStateMachineHelper( 1047): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1047): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1047): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1047): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1047): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1047): RunningState
I/ActivityManager( 1047): Killing 6815:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1047): failed to open /acct/uid_10061/pid_6815/cgroup.procs: No such file or directory
,I/ActivityManager( 1047): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7500 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1047): Killing 6860:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/jxcore-log( 7187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7187): 
,W/libprocessgroup( 1047): failed to open /acct/uid_10080/pid_6860/cgroup.procs: No such file or directory
,I/art     ( 7500): Almond Protected OAT
,D/WeatherApplication( 7500): removeAccount
,D/WeatherApplication( 7500): Account.length = 0
E/WeatherApplication( 7500): OPERATOR:OPEN
D/WeatherAncestor( 7500): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:6:32
D/Weather.Utils( 7500): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7500): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7500): 2 : This is isUpdating : false
D/WeatherAncestor( 7500): connectivity changed - connection : true
,D/WeatherService( 7500): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7500): 2 : lastUpdatedTime: 1430558561343
,D/ForecastDataCache( 7500): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7500): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7500): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7500): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:6:32
,I/ActivityManager( 1047): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7521 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1047): Killing 6906:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1047): failed to open /acct/uid_1000/pid_6906/cgroup.procs: No such file or directory
,E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7521): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7521): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7521): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  279): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  279): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7521): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 7187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7187): 
,I/jxcore-log( 7187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7187): 
,E/WifiStateMachine( 1047):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1047):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1047):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1047):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1047):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/jxcore-log( 7187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7187): 
,I/jxcore-log( 7187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7187): 
,I/jxcore-log( 7187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7187): 
I/WebViewFactory( 7521): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/jxcore-log( 7187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7187): 
I/LibraryLoader( 7521): Loading: webviewchromium
,I/LibraryLoader( 7521): Time to load native libraries: 4 ms (timestamps 2359-2363)
I/LibraryLoader( 7521): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7521): Binding Chromium to main looper Looper (main, tid 1) {7c0d4e0}
I/LibraryLoader( 7521): Expected native library version number "",actual native library version number ""
,I/chromium( 7521): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7521): Initializing chromium process, renderers=0
,W/art     ( 7521): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7521): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7521): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7521): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  331): registerClient() client 0xb558a5a0, uid 10093
W/AudioManagerAndroid( 7521): Requires BLUETOOTH permission
I/Adreno-EGL( 7521): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7521): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7521): Build Date: 12/12/14 금
I/Adreno-EGL( 7521): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7521): Remote Branch: 
I/Adreno-EGL( 7521): Local Patches: 
I/Adreno-EGL( 7521): Reconstruct Branch: 
,I/NSApplication( 7521): Starting up...
,I/ActivityManager( 1047): Killing 6956:com.lge.bnr/1000 (adj 15): empty #17
,V/WifiInternetCheck( 1047): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1047): failed to open /acct/uid_1000/pid_6956/cgroup.procs: No such file or directory
,D/Tethering( 1047): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5557): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1047): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1047): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ChimeraCfgMgr( 2332): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2332): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6612): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7383): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7383): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7383): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7383): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7383): onReceive
I/GLSUser ( 2054): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2054): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2054): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2054): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2054): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AppUp4:CustFacade( 7383): Context : android.app.ReceiverRestrictedContext@15d551f1
D/AppUp4:CustFacade( 7383): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7383): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7383): begin check event
I/AppUp4:CustModeStarterReceiver( 7383): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 4363): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4363): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4363): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/LGDMClient( 4363): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4363): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4363): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3451): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3451): DownloadService onCreate
W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4363): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4363): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4363): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/DownloadManager( 3451): in removeSpuriousFiles
V/DownloadManager( 3451): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3451): created cursor android.database.sqlite.SQLiteCursor@132a0727 on behalf of 3451
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Settings( 6716): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/DownloadManager( 3451): in trimDatabase
W/Kids    ( 2332): [AccountUtils] Account not ready
W/Kids    ( 2332): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2332): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2332): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2332): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2332): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3451): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,W/Settings( 6716): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3451): created cursor android.database.sqlite.SQLiteCursor@263d1dd4 on behalf of 3451
I/LgeMiscReceiver( 3386): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3386): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3386): networkInfo.isConnected() = false
W/ResourcesManager( 1406): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1406): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/WeatherAncestor( 7500): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:6:33
D/Weather.Utils( 7500): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7500): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7500): 2 : This is isUpdating : false
D/WeatherAncestor( 7500): connectivity changed - connection : true
D/WeatherService( 7500): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1827ac57
D/ForecastDataCache( 7500): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7500): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7500): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7500): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7500): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:6:33
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
W/ResourcesManager( 1406): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1406): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{38f25279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3451): DownloadService onStartCommand
V/DownloadManager( 3451): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3451): created cursor android.database.sqlite.SQLiteCursor@22a5eec3 on behalf of 3451
V/DownloadManager( 3451): processing inserted download 1
V/DownloadManager( 3451): processing inserted download 4
,V/DownloadManager( 3451): processing inserted download 7
V/DownloadManager( 3451): processing inserted download 8
V/DownloadManager( 3451): processing inserted download 9
D/ChimeraCfgMgr( 2332): Loading module com.google.android.gms.kids from APK com.google.android.gms
V/DownloadManager( 3451): processing inserted download 10
V/DownloadManager( 3451): processing inserted download 16
V/DownloadManager( 3451): processing inserted download 17
V/DownloadManager( 3451): processing inserted download 18
,V/DownloadManager( 3451): processing inserted download 21
,V/DownloadManager( 3451): processing inserted download 22
V/DownloadManager( 3451): DownloadService onDestroy
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6612): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,V/FormManager( 7418): There are no updated forms. The schedule will be deleted.
V/FormManager( 7418): Alarm would be updated, because LastCheckTime has been updated.
I/art     ( 1047): Explicit concurrent mark sweep GC freed 93167(4MB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 1.572ms total 98.370ms
,I/NetworkStateForAutoUpdateMonitor( 7383): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7383): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7383): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7383): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7383): onReceive
D/AppUp4:CustFacade( 7383): Context : android.app.ReceiverRestrictedContext@15d551f1
,D/AppUp4:CustFacade( 7383): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7383): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7383): begin check event
I/AppUp4:CustModeStarterReceiver( 7383): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4363): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4363): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2054): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2054): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2054): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2054): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3451): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/GLSActivity( 2054): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3451): DownloadService onCreate
I/DownloadManager( 3451): in removeSpuriousFiles
V/DownloadManager( 3451): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3451): created cursor android.database.sqlite.SQLiteCursor@38f25279 on behalf of 3451
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3451): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3451): in trimDatabase
V/DownloadManager( 3451): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3451): created cursor android.database.sqlite.SQLiteCursor@16e42bbe on behalf of 3451
D/LGDMClient( 4363): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4363): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMClient( 4363): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4363): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3451): DownloadService onStartCommand
W/Settings( 6716): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3451): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3451): created cursor android.database.sqlite.SQLiteCursor@23c9d35 on behalf of 3451
I/LgeMiscReceiver( 3386): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3386): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3386): networkInfo.isConnected() = true
D/PhoneState( 3386): setPdpRejectCasuse : false
W/Settings( 6716): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 4363): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4363): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4363): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3451): processing inserted download 1
V/DownloadManager( 3451): processing inserted download 4
V/DownloadManager( 3451): processing inserted download 7
V/DownloadManager( 3451): processing inserted download 8
V/DownloadManager( 3451): processing inserted download 9
V/DownloadManager( 3451): processing inserted download 10
V/DownloadManager( 3451): processing inserted download 16
V/DownloadManager( 3451): processing inserted download 17
V/DownloadManager( 3451): processing inserted download 18
V/DownloadManager( 3451): processing inserted download 21
V/DownloadManager( 3451): processing inserted download 22
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
W/Kids    ( 2332): [AccountUtils] Account not ready
W/Kids    ( 2332): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2332): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2332): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2332): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2332): 	at java.lang.Thread.run(Thread.java:818)
D/WeatherAncestor( 7500): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:6:33
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
V/DownloadManager( 3451): DownloadService onDestroy
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/Weather.Utils( 7500): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7500): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7500): 2 : This is isUpdating : false
D/WeatherAncestor( 7500): connectivity changed - connection : true
D/WeatherService( 7500): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@1827ac57
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/ForecastDataCache( 7500): 2 : lastUpdatedTime: 1430558561343
,D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
D/ForecastDataCache( 7500): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7500): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7500): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7500): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:6:33
,D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{38f25279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2332): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2054): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2054): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2054): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2054): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/FormManager( 7418): There are no updated forms. The schedule will be deleted.
V/GLSActivity( 2054): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/FormManager( 7418): Alarm would be updated, because LastCheckTime has been updated.
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2332): [AccountUtils] Account not ready
W/Kids    ( 2332): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2332): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2332): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2332): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2332): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2332): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2332): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1406): onNotificationPosted
D/SmartCoverUpdateMonitor( 1406): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1406): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1406): handleNotificationPosted(true)
D/QuickCircle( 1406): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1406): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): post do just update job
D/LgeQuickCoverNotificationData( 1406): showAll3
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1406): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1406): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1406): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1406): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1406): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1406): Notification difference=198
D/QuickStatusbarLayout( 1406): child = android.widget.LinearLayout{38f25279 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  326): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  326): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  326): res_queryN name = www.google.com succeed
,D/libc-netbsd(  326): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  326): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  326): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1047): isHttpConnectionAvailable - We got a valid response : 204
,I/jxcore-log( 7187): Test app app.js loaded
I/jxcore-log( 7187): 
,I/chromium( 7187): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7187): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7187): BLE advertisement is supported
I/jxcore-log( 7187): 
I/jxcore-log( 7187): --= Surplus to requirements =--
I/jxcore-log( 7187): 
I/jxcore-log( 7187): ****TEST TOOK:  ms ****
I/jxcore-log( 7187): 
I/jxcore-log( 7187): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7187): 
,D/PowerManagerServiceEx( 1047): acquireWakeLockInternal: lock=219978324, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1047
,V/AlarmManager( 1047): ELAPSED_WAKEUP set : Alarm{253a470e type 2 when 286012 com.google.android.gms} when 286012
,D/[Concierge]Service( 2575): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1047): releaseWakeLockInternal: lock=219978324 [*alarm*], flags=0x0
,D/libc-netbsd(  326): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  326): res_queryN name = mtalk.google.com, class = 1, type = 1
,D/libc-netbsd(  326): res_queryN name = mtalk.google.com succeed
,D/AndroidRuntime( 7634): 
D/AndroidRuntime( 7634): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7634): CheckJNI is OFF
D/AndroidRuntime( 7634): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1047): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1047): Killing 7187:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,W/PackageSettings( 1047): Skipping PackageSetting{129f410e com.example.hello/10319} due to missing metadata
,D/WifiService( 1047): Client connection lost with reason: 4
,I/WindowState( 1047): WIN DEATH: Window{3e619a3e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher( 1047): Window went away: Window{3e619a3e u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1047):   Force finishing activity ActivityRecord{35293fdb u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  351): DFP En is all cleared set to be enabled
,W/ActivityManager( 1047): Spurious death for ProcessRecord{1e4ab52f 7187:com.test.thalitest/u0a311}, curProc for 7187: null
I/ActivityManager( 1047): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
D/SplitWindowPolicy( 1924): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1924): topRunningActivity=ActivityInfo{57bb201 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1924): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1924): topRunningActivity=ActivityInfo{33ad48a6 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/ActivityManager( 1047):   Force finishing activity ActivityRecord{35293fdb u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1047): Duplicate finish request for ActivityRecord{35293fdb u0 com.test.thalitest/.MainActivity t4 f}
,D/KeyguardModel( 1456): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_MrGDBLogger_PackageInfoDetector( 3791): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/GeofencerStateMachine( 1800): Ignoring removeGeofence because network location is disabled.
E/LGBluetoothAvrcpQcomAdapter( 3877): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3877): [BTUI] [+] updateMediaPlayerInfo
,D/LIA_Service_RemotePackageHandler( 1979): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/[LGHome]EVENT( 2016): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2016): [Launcher.java:903:onResume()]onResume
I/art     ( 4624): Explicit concurrent mark sweep GC freed 15076(878KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 566us total 62.847ms
,V/SIM_STK ( 1047): Menu title from STK is T-Mobile
D/PostponalbeReceiver( 6612): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,I/InputReader( 1047): Reconfiguring input devices.  changes=0x00000010
D/GCM     ( 2054): Connected
,W/System.err( 4577): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4577): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4577): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4577): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4577): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4577): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4577): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4577): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4577): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4577): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4577): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4577): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/administrator( 1047): Handling package changes for user 0
,I/ActivityManager( 1047): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7678 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 2016): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2016): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/[SystemUI]QSlideListController( 1456): onReceive = android.intent.action.PACKAGE_REMOVED
,D/SplitUIManager( 1852): split_name #11 / not available #0
D/SplitUIService( 1852): removed split : 
V/SIM_STK ( 1047): Menu title from STK is T-Mobile
V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,D/GCM     ( 2054): Message class com.google.f.a.a.p
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1456): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1456): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/[LGHome]GBoardWebView( 2016): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1889): notifyUserLog: 1000003
I/[LGHome]LGActivityUtil( 2016): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2016): [Launcher.java:1056:onResume()]onResume end
D/LIA_Informant_ActionManagerMessageHandler( 3791): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]EVENT( 2016): [Launcher.java:1114:onPause()]onPause
,I/[LGHome]GBoardWebView( 2016): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1889): notifyUserLog: 1000004
V/BoardContentProvider( 3791): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_ActionManagerMessageHandler( 3791): handleMessage: what(1000) actionID(0x1000004)
D/SplitUIManager( 1852): split_name #11 / not available #0
I/SplitUIService( 1852): split app #11
I/GBoardWebViewUtils( 2016): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2016): , create_time: 1430558575574
I/GBoardWebViewUtils( 2016): , expire_time: 0
I/GBoardWebViewUtils( 2016): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2016): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2016): , display: false
I/GBoardWebViewUtils( 2016): , animation: false }
I/GBoardWebViewUtils( 2016): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2016): , create_time: 1430558575600
I/GBoardWebViewUtils( 2016): , expire_time: 0
I/GBoardWebViewUtils( 2016): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2016): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2016): , display: false
I/GBoardWebViewUtils( 2016): , animation: false }
I/GBoardWebViewUtils( 2016): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452774038448
I/GBoardWebViewUtils( 2016): , create_time: 1452774039338
I/GBoardWebViewUtils( 2016): , expire_time: 0
I/GBoardWebViewUtils( 2016): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2016): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2016): , display: false
I/GBoardWebViewUtils( 2016): , animation: false }
D/WallpaperManager( 2016): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1047): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1047): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1047): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1047): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1be3ee39,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[LGHome]EVENT( 2016): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]GBoardWebView( 2016): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/LockScreenSettings( 7678): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,W/ActivityManager( 1047): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3877): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3877): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3877): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3877): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3877): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3877): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3877): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3877): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3877): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3877): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3877): [BTUI] [-] updateMediaPlayerInfo
D/KeyguardModel( 1456): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1456): createShortcutInfo...
D/KeyguardModel( 1456): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1456): createShortcutInfo...
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1456): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1456): createShortcutInfo...
,W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1456): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1456): createShortcutInfo...
W/ResourcesManager( 1456): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1456): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 2016): [Launcher.java:5349:onStop()]onStop
D/KeyguardModel( 1456): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1456): createShortcutInfo...
I/NotificationService( 1047): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1047): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1047): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1047): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1456): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1456): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1456):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1456): , Keyguard show=false, IME shown=false, Panel expanded=false
D/AppUp4:PreloadHelper( 7383): added Exclude : com.test.thalitest
D/KeyguardModel( 1456): handleShortcutListChanged...
,I/ActivityManager( 1047): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7698 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/KeyguardModel( 1456): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1456): createShortcutInfo...
D/KeyguardModel( 1456): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1456): createShortcutInfo...
W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1456): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1456): createShortcutInfo...
W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1456): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1456): createShortcutInfo...
,W/ResourceType( 1456): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1456): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1456): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1456): createShortcutInfo...
I/ActivityManager( 1047): Killing 6936:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/Thermal-Lib( 3015): Thermal-Lib-Client: Client request sent
I/ThermalEngine(  345): Thermal-Server: Thermal received msg from  override
,I/[LGHome]Launcher.Model( 2016): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2016): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2016): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2016): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2016): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2016): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/art     ( 1047): Explicit concurrent mark sweep GC freed 26333(1665KB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 2.135ms total 305.701ms
W/libprocessgroup( 1047): failed to open /acct/uid_10005/pid_6936/cgroup.procs: No such file or directory
D/KeyguardModel( 1456): handleShortcutListChanged...
I/[LGHome]Launcher.Model( 2016): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2016): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 1047): Timeline: Activity_windows_visible id: ActivityRecord{1072922 u0 com.lge.launcher2/.Launcher t3} time:287158
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2016): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2016): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
W/ResourcesManager( 7698): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7698): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7698): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,I/[LGHome]EVENT( 2016): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/ResourcesManager( 7698): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7698): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]Launcher.Model( 2016): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2016): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/GAV4    ( 7521): Thread[GAThread,5,main]: No campaign data found.
I/[Concierge]WidgetView( 2016): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2575): onStartCommand(). Type : 8
D/[Concierge]Service( 2575): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2575): Update widget ID : 11
D/[Concierge]WidgetView( 2016): change position of spinner
,D/[Concierge]Service( 2575): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2016): initWebView(). Time : 1453205197605
I/[Concierge]WebView( 2016): Return exist ConciergeWebView. Reuse : 1028674171
D/[Concierge]WidgetView( 2016): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2016): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2016): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@352814a0
I/[LGHome]EVENT( 2016): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 2016): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2016): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2016): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2016): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2016): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2016): Widget kill message received. Destory myself. My : 1453204937842, New one : 1453205197605
,D/[Concierge]WidgetView( 2016): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2016): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/ResourcesManager( 1047): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 2016): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2016): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2016): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/SystemConfig( 7698): BUILD Country: EU
I/[LGHome]EVENT( 2016): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/SystemConfig( 7698): BUILD Operator: OPEN
W/ResourceType( 1047): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2016): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2016): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]EVENT( 2016): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2016): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2016): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2016): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2016): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2016): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
D/AndroidRuntime( 7634): Shutting down VM
I/[LGHome]Launcher( 2016): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2016): Timeline: Activity_idle id: android.os.BinderProxy@2890b57a time:287286
,I/ActivityManager( 1047): Killing 7072:com.google.android.apps.books/u0a54 (adj 15): empty #17
W/libprocessgroup( 1047): failed to open /acct/uid_10054/pid_7072/cgroup.procs: No such file or directory
,I/SystemConfig( 7698): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7698): existFile = false
I/SystemConfig( 7698): canReadFile = false
I/SystemConfig( 7698): systemFeature RCS result false
D/SystemConfig( 7698): refreshRcsSupport() :false
I/PackageChangeReceiver( 6716): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2351): Cleaning up data for package: com.test.thalitest
I/chromium( 2016): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/ActivityManager( 1047): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7723 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/GBoardtInterface( 2016): onReloaded()
,I/GBoardWebViewClient( 2016): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3791): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3791): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
W/ResourcesManager( 7723): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7723): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7723): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7723): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,D/ActionManagerService( 1889): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3791): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3791): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1889): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3791): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3791): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3791): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3791): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3791): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2016): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2016): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2016): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2016): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,D/GBoardUriUtils( 2016): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2016): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/AppConfig( 7723): Total System Memory = 2995761152
,D/SystemHelper( 7723): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1047): Killing 6270:com.android.vending/u0a44 (adj 15): empty #17
,D/LIA_Service_NativeEventReceiver( 1979): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 1979): startLIAService() : Trying to start LIA service ...
W/libprocessgroup( 1047): failed to open /acct/uid_10044/pid_6270/cgroup.procs: No such file or directory
,D/LIA_Service_LIAService( 1979): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
D/PostponalbeReceiver( 6612): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/ActivityManager( 1047): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7745 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/art     (  362): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 9.426ms
I/art     (  362): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 189us total 9.095ms

```
