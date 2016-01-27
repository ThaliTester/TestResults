#### Test 57321924b5e4f25_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 237972752931; DSPS: 7938649; Offset : -4312864850
,D/AndroidRuntime( 7005): 
D/AndroidRuntime( 7005): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7005): CheckJNI is OFF
D/AndroidRuntime( 7005): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1036): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1959): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1036): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{1eed5105 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{1eed5105 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1036): AppWindowTokenEx init.. 
E/GBMv2   (  341): DFP En is all cleared set to be enabled
I/ActivityManager( 1036): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7020 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7005): Shutting down VM
V/ActivityManager( 1036): Display changed displayId=0
D/DSDPConnection( 1870): Display #0 changed.
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{2722fddd co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{92d9d52 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7020): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7020): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7020): Loading: webviewchromium
,I/LibraryLoader( 7020): Time to load native libraries: 4 ms (timestamps 4253-4257)
I/LibraryLoader( 7020): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7020): Binding Chromium to main looper Looper (main, tid 1) {1390d4cd}
,I/LibraryLoader( 7020): Expected native library version number "",actual native library version number ""
I/chromium( 7020): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7020): Initializing chromium process, renderers=0
,W/art     ( 7020): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  321): registerClient() client 0xb1427480, uid 10311
,W/chromium( 7020): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7020): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7020): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cc79d67:true
I/Adreno-EGL( 7020): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  (),
I/Adreno-EGL( 7020): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7020): Build Date: 12/12/14 금
I/Adreno-EGL( 7020): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7020): Remote Branch: 
I/Adreno-EGL( 7020): Local Patches: 
I/Adreno-EGL( 7020): Reconstruct Branch: 
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 46669(2005KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 2.572ms total 109.156ms
W/ActivityManager( 1036): Activity pause timeout for ActivityRecord{2899355a u0 com.test.thalitest/.MainActivity t4}
,W/chromium( 7020): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7020): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7020): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7020): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7020): CordovaWebView is running on device made by: LGE
,W/art     ( 7020): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7020): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7020): Render dirty regions requested: true
I/OpenGLRenderer( 7020): Initialized EGL, version 1.4
D/OpenGLRenderer( 7020): Enabling debug mode 0
,D/Atlas   ( 7020): Validating map...
D/SplitWindow( 1036): check instance of lgWin Window{38484029 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7020): LgDataFeature() Constructor: none
D/LgDataFeature( 7020): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/PhoneStatusBar( 1463): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@14a0d7e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1463): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1463):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1463): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1036): Displayed com.test.thalitest/.MainActivity: +718ms (total +816ms)
I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{2899355a u0 com.test.thalitest/.MainActivity t4} time:254747
,I/Timeline( 7020): Timeline: Activity_idle id: android.os.BinderProxy@28cd8b3d time:254757
I/chromium( 7020): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7020): 
,D/JsMessageQueue( 7020): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7020): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7020): 
,D/jxcore_app_log( 7020): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435200256
,I/chromium( 7020): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/GBMv2   (  341): DFP En is all cleared set to be enabled
E/GBMv2   (  341): Set value is all cleared set the max
I/GBMv2   (  341): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7020): Initializing JXcore engine
W/jxcore-log( 7020): JXcore engine is ready
,W/Thread-808( 7094): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9374]" dev="sockfs" ino=9374 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-808( 7094): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-808( 7094): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10793]" dev="sockfs" ino=10793 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-808( 7094): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-808( 7094): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33958]" dev="sockfs" ino=33958 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7020): Starting JXcore engine
,W/jxcore-log( 7020): Platform android
W/jxcore-log( 7020): 
W/jxcore-log( 7020): Process ARCH arm
W/jxcore-log( 7020): 
,I/jxcore-log( 7020): JXcore Cordova bridge is ready!
I/jxcore-log( 7020): 
W/jxcore-log( 7020): JXcore engine is started
,I/jxcore-log( 7020): Toggling radios to true
I/jxcore-log( 7020): 
,D/BluetoothAdapter( 7020): enable(): BT is already enabled..!
D/WifiService( 1036): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1036): setWifiEnabled: true pid=7020, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1036): setWifiEnabled: true pid=7020, uid=10311
E/WifiService( 1036): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1036): disconnect pid=7020, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1036):  ConnectedState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1036): reconnect pid=7020, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7020): Radios toggled
I/jxcore-log( 7020): 
E/WifiStateMachine( 1036):  L2ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 7020): My device name is: LGE-LG-D855
I/jxcore-log( 7020): 
E/WifiNative: ( 1036): [257,541,118 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1036): doBoolean: DISCONNECT
,I/wpa_supplicant( 2701): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering( 1036): InitialState.processMessage what=4
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1036): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1036): DISCONNECT: returned true
E/WifiStateMachine( 1036): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
,I/ActivityManager( 1036): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7096 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2701): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/CommandListener(  315): Clearing all IP addresses on wlan0
,D/DhcpStateMachine( 1036): RunningState{ when=-8ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2133): Read error: ssl=0xaa6d6600: I/O error during system call, Connection timed out
,V/NativeCrypto( 2133): SSL shutdown failed: ssl=0xaa6d6600: I/O error during system call, Broken pipe
D/ConnectivityService( 1036): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
,E/WifiStateMachine( 1036): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1036):  DisconnectingState CMD_RECONNECT 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Forcing reevaluation
E/WifiStateMachine( 1036):  ConnectModeState CMD_RECONNECT 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on "NG700"
E/WifiNative: ( 1036): [257,684,891 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1036): doBoolean: RECONNECT
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1036): ignoring duplicate network state non-change
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/wpa_supplicant( 2701): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1959): handleWifiStateChangedEvent: 0
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1036): RECONNECT: returned true
E/WifiStateMachine( 1036):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=257702
E/WifiStateMachine( 1036):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=257703
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGWifiP2pService( 1036): InactiveState{ when=-11ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-11ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2701): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
,D/CommandListener(  315): Clearing all IP addresses on wlan0
D/ConnectivityService( 1036): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1036): disableDataServiceNotify
D/DSQN    ( 1036): stop dsqn bin
D/libc-netbsd(  315): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=257726  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=257727  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
,E/WifiStateMachine( 1036):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1036): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=257736  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1036): hidePasspointNotification off =false
D/ConnectivityService( 1036): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
,D/CSLegacyTypeTracker( 1036): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1036): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityManager.CallbackHandler( 1463): CM callback handler got msg 524292
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Disconnected - quitting
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
W/ResourcesManager( 7096): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7096): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7096): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7096): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7096): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7096): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=257750  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkManagementService( 1036): Removing idletimer
D/WIFI    ( 1036): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings( 1036): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1036): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/TelephonyNetworkFactory-1( 1870): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateSCANNING
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
,D/TelephonyIcons( 1463): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1463): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1036): StoppedState
D/DhcpStateMachine( 1036): StoppedState{ when=-137ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7096): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 7096): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7096): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7096): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7096): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7096): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7096): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7096): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7096): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7096): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7096): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 257974342615; DSPS: 8594061; Offset : -4312861846
,I/ActivityManager( 1036): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7134 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 6591:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10008/pid_6591/cgroup.procs: No such file or directory
,I/PCSuite ( 7134): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7134): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7134): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7096): LgDataFeature() Constructor: none
D/LgDataFeature( 7096): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
I/ActivityManager( 1036): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7158 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1036): Killing 6082:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10011/pid_6082/cgroup.procs: No such file or directory
,W/ResourcesManager( 7158): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7158): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7158): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7158): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7158): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7158): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7158): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7158): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7158): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7158): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7158): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
I/PCSuite ( 7134): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7134): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7134): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7158): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7158): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7134): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7134): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7134): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7158): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7134): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7134): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7134): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
,D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7158): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7158): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7158): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7158): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7158): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7158): LgDataFeature() Constructor: none
D/LgDataFeature( 7158): LgDataFeature() Constructor Done, null
,V/SoundPool( 7158): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7158): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7158): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7158): doLoad: loading sample sampleID=1
I/QRemote ( 7158): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,V/SoundPool( 7158): Start decode
V/MediaPlayer[Native]( 7158): decode(31, 10857164, 17813)
D/UEI.SmartControl( 6736): QS Service created
D/QRemote ( 7158): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/MediaPlayerService(  321): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  321): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  321): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  321): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  321): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  321): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  321): player type = 3
V/AwesomePlayer(  321): AwesomePlayer create()
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/AwesomePlayer(  321): setAudioSink() 
V/AwesomePlayer(  321): reset_l() 
V/AudioCache(  321): notify(0xb1432280, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/Utils   (  321): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  321): setDataSource_l dataSource
V/LGParserOSAL(  321): SniffLGParser start
V/LGParserOSAL(  321): MainType:5, SubType=0
V/LGParserOSAL(  321): #### check Mime : application/ogg
V/LGParserOSAL(  321): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  321): Use LGExtractor :application/ogg 
E/QRemote ( 7158): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7158): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,I/UEI.SmartControl( 6736): Service initServices...
D/UEI.SmartControl( 6736): QS start get config
V/LGMDMManager( 7158): Create singleton instance
V/LGParserOSAL(  321): supported mime: application/ogg
V/AwesomePlayer(  321): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  321): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  321): mBitrate = -1 bits/sec
V/AwesomePlayer(  321): AudioTrack Setting
V/AwesomePlayer(  321): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  321): setAudioSource() 
V/MediaPlayerService(  321): prepare
V/AwesomePlayer(  321): prepareAsync_l() 
V/MediaPlayerService(  321): wait for prepare
V/AwesomePlayer(  321): onPrepareAsyncEvent() 
V/AwesomePlayer(  321): initAudioDecoder() 
W/Utils   (  321): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  321): isOffloadSupported()
V/AudioPolicyManager(  321): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  321): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  321): isAudioPlaybackHookOn() false
V/AwesomePlayer(  321): getUseOffload() = 0 
V/OMXCodec(  321): OMXCodec::Create
V/OMXCodec(  321): findMatchingCodecs()
V/OMXCodec(  321): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  321): matchingCodecs.size()=1
V/OMXCodec(  321): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  321): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  321): LG Codec Adapter start
V/OMXCodec(  321): OMXCodec Createtor
V/OMXCodec(  321): setComponentRole
V/OMXCodec(  321): configureCodec protected=0
V/LGCodecAdapter(  321): called getLGCodecSpecificData
V/LGCodecOSAL(  321): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMETA
V/LGCodecOSAL(  321): Called LGconfigureCodecMSG
V/LGCodecOSAL(  321): Not support LGCodec
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  321): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  321): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  321): Could not offload audio decode, try pcm offload
W/Utils   (  321): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  321): isOffloadSupported()
V/AudioPolicyManager(  321): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  321): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  321): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  321): init()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  321): allocateBuffers
V/OMXCodec(  321): allocateBuffersOnPort portIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434510 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on input port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on input port
V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434790 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434ce0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434d30 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434d80 on output port
V/OMXCodec(  321): init() mAsyncCompletion wait!!! 
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  321): init() mAsyncCompletion wait!!! 
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  321): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  321): finishAsyncPrepare_l() 
V/AudioCache(  321): notify(0xb1432280, 5, 0, 0)
V/AudioCache(  321): ignored
V/AudioCache(  321): notify(0xb1432280, 1, 0, 0)
V/AudioCache(  321): prepared
V/AudioCache(  321): wait - success
V/MediaPlayerService(  321): start
V/AwesomePlayer(  321): play_l() 
V/AwesomePlayer(  321): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  321): createAudioPlayer_l
V/AwesomePlayer(  321): seekAudioIfNecessary_l() 
V/AwesomePlayer(  321): startAudioPlayer_l() 
D/AudioPlayer(  321): start of Playback, useOffload 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  321): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  321): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OM,XCodec(  321): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  321): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976464
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977824
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977904
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977984
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  321): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  321): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  321): allocateBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434d30 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434ce0 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1434790 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] allocated buffer 0xb1453060 on output port
V/OMXCodec(  321): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  321): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  321): notify(0xb1432280, 6, 0, 0)
V/AudioCache(  321): ignored
V/MediaPlayerService(  321): wait for playback complete
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab700000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab701000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab702000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab703000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab704000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab705000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab706000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab707000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab708000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab709000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab70a000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab70b000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab70c000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab70d000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab70e000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab70f000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab710000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab711000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab712000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab713000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab714000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab715000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab716000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab717000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab718000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab719000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab71a000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab71b000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab71c000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab71d000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab71e000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab71f000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab720000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab721000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab722000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab723000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab724000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab725000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab726000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab727000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab728000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab729000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab72a000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab72b000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab72c000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab72d000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab72e000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab72f000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab730000, 0xb57ed000, 4096)
V/AudioCache(  321): write(0xb57ed000, 4096)
V/AudioCache(  321): memcpy(0xab731000, 0xb57ed000, 4096)
V/OMXCodec(  321): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  321): postAudioEOS() 
V/AudioCache(  321): write(0xb57ed000, 280)
V/AudioCache(  321): memcpy(0xab732000, 0xb57ed000, 280)
D/QRemote ( 7158): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 7158): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AwesomePlayer(  321): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  321): onStreamDone
V/AwesomePlayer(  321): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  321): notify(0xb1432280, 2, 0, 0)
V/AudioCache(  321): playback complete
V/AwesomePlayer(  321): pause_l() 
V/AudioCache(  321): wait - success
V/AudioCache(  321): notify(0xb1432280, 7, 0, 0)
V/MediaPlayerService(  321): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/AudioPlayer(  321): Pause Playback at 1068125
D/QRemote ( 7158): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2878
,V/AwesomePlayer(  321): reset_l() 
V/AudioCache(  321): notify(0xb1432280, 8, 0, 0)
V/AudioCache(  321): ignored
V/AwesomePlayer(  321): cancelPlayerEvents
D/AudioPlayer(  321): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14346a0 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb1434510 on port 0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb1453060 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb1434790 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb1434ce0 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeing buffer 0xb1434d30 on port 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  321): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  321): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  321): AudioPlayer releasing audio source
D/AudioPlayer(  321): AudioPlayer done releasing audio source
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/AwesomePlayer(  321): ~AwesomePlayer call
V/AwesomePlayer(  321): reset_l() 
V/AwesomePlayer(  321): cancelPlayerEvents
V/SoundPool( 7158): close(31)
V/SoundPool( 7158): pointer = 0x9ff3c000, size = 205080, sampleRate = 48000, numChannels = 2
I/UEI.SmartControl( 6736): Supports setup maps: true
D/UEI.SmartControl( 6736): QS start statue = true Error code = 0
I/UEI.SmartControl( 6736): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6736): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6736): ### init IR Blaster...
D/serial_port( 6736): Configuring serial port
E/UEI.SmartControl( 6736): UEIBLaster setting for 616
I/UEI.SmartControl( 6736): Setting serial record hearder size = 2
I/UEI.SmartControl( 6736): configuring settings for MAXQ616
I/UEI.SmartControl( 6736): Get version...
,D/UEI.SmartControl( 6736): serial port data available: 21
,D/UEI.SmartControl( 6736): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6736): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6736): QS saving settings...
D/UEI.SmartControl( 6736): IR Blaster version: 25672567
,D/UEI.SmartControl( 6736): serial port data available: 4
,W/ContextImpl( 6736): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6736): Services init done
D/UEI.SmartControl( 6736): QS Service init finished
D/UEI.SmartControl( 6736): QS Service version name: 2.1.91
D/UEI.SmartControl( 6736): QS Service version code: 201091
D/UEI.SmartControl( 6736): Service requested: Control
I/QRemote ( 7158): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6736): Internal service binding...
I/UEI.SmartControl( 6736): Device manager: loading config....
,D/UEI.SmartControl( 6736): ----------- loading internal config...
I/UEI.SmartControl( 6736): ------ IControl API: 11
D/UEI.SmartControl( 6736): File observer start...
E/UEI.SmartControl( 6736): IR Port is disabled: false
D/UEI.SmartControl( 6736): Starting file observer...
I/UEI.SmartControl( 6736): Registering callback...
I/UEI.SmartControl( 6736): ------ IControl API: 19
I/UEI.SmartControl( 6736): Registering Services Ready callback...
E/UEI.SmartControl( 6736): Loading SETTINGS...
D/UEI.SmartControl( 6736): -- Open brand translation xml: brands_translations_ko
,I/UEI.SmartControl( 6736): Notify AllClients services are ready: 0
,I/QRemote ( 7158): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6736): -----service ready thread exits
D/QRemote ( 7158): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7158): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7158): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7158): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6736): ------ IControl API: 8
D/QRemote ( 7158): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7158): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7158): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7158): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7158): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7158): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7158): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7158): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7158): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7158): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7158): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7158): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7158): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7158): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7158): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453879971309]
,D/QRemote ( 7158): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1036): Killing 6101:com.android.contacts/u0a19 (adj 15): empty #17
D/QRemote ( 7158): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1036): failed to open /acct/uid_10019/pid_6101/cgroup.procs: No such file or directory
,V/QRemote ( 7158): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7158): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7158): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7158): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7158): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7158): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7158): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7158): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2701): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1036): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1036): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1036):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1036):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1036):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
E/WifiStateMachine( 1036):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=2 known=0 got=2 bcn=0
D/WifiNative-wlan0( 1036): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=259777  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=259809  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7158): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7158): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1036): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1036): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5444): type=WIFI subType= reason=null isConnected=false
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6560): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/GpsLocationProvider( 1036): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1036): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5444): type=WIFI subType= reason=null isConnected=false
,I/ActivityManager( 1036): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7227 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7227): onCreate
,W/AppUp4:DB( 7227):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7227):  setFingerPrint start
I/AppUp4:DB( 7227):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7227):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 7227):  SDK version = 21
,I/AppUp4:DB( 7227):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7227): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7227): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7227): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7227): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7227): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7227): onReceive
D/LgDataFeature( 7227): LgDataFeature() Constructor: none
D/LgDataFeature( 7227): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7227): Context : android.app.ReceiverRestrictedContext@3e00b093
D/AppUp4:CustFacade( 7227): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7227): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7227): begin check event
I/AppUp4:CustModeStarterReceiver( 7227): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7227): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7227): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 7227): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7227): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1036): Killing 6616:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10023/pid_6616/cgroup.procs: No such file or directory
,D/LGDMClient( 4280): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4280): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4280): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4280): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 4280): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4280): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 4280): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/ActivityManager( 1036): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7254 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7254): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7254): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7254): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7254): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 7254): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7254): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7254): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7254): LgDataFeature() Constructor: none
D/LgDataFeature( 7254): LgDataFeature() Constructor Done, null
,D/eas_req ( 7254): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1036): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7275 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7254): JNI_OnLoad()
I/HubEmail( 7254): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7254): registerNatives()
I/HubEmail( 7254): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7254): registerNativeMethods()
I/HubEmail( 7254): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7254): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1036): Killing 6128:com.android.gallery3d/u0a27 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10027/pid_6128/cgroup.procs: No such file or directory
,W/Settings( 7254): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3344): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3344): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3344): networkInfo.isConnected() = false
I/ActivityManager( 1036): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7298 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  350): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 431us total 21.367ms
,W/FormManager( 7275): Network not available. Please check & try again.
I/wpa_supplicant( 2701): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
E/WifiStateMachine( 1036):  DisconnectedState ASSOCIATION_REJECTION_EVENT 27 1 c0:ff:d4:d3:aa:48 blacklist=false rt=261930
E/WifiStateMachine( 1036):  ConnectModeState ASSOCIATION_REJECTION_EVENT 27 1 c0:ff:d4:d3:aa:48 blacklist=false rt=261930
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=261931  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
I/art     (  350): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 396us total 21.038ms
,E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=261943  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
I/art     (  350): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 13.101ms
,D/WifiHS20( 1036): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateDISCONNECTED
V/FormManager( 7275): Network unavailable.
V/FormManager( 7275): Network unavailable.
,I/ActivityManager( 1036): Killing 6666:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,I/wpa_supplicant( 2701): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=262031  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiMonitor( 1036): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1036): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,W/libprocessgroup( 1036): failed to open /acct/uid_10061/pid_6666/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=262086  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateSCANNING
I/ActivityManager( 1036): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7323 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 6714:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
I/jxcore-log( 7020): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7020): 
,W/libprocessgroup( 1036): failed to open /acct/uid_10080/pid_6714/cgroup.procs: No such file or directory
,I/ActivityManager( 1036): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7344 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 2239:com.lge.music/u0a34 (adj 15): empty #17
,V/AudioFlinger(  321): 2239 died, releasing its sessions
V/AudioFlinger(  321):  pid 1870 @ 0
V/AudioFlinger(  321):  pid 3344 @ 1
V/AudioFlinger(  321):  pid 3344 @ 2
,W/libprocessgroup( 1036): failed to open /acct/uid_10034/pid_2239/cgroup.procs: No such file or directory
,I/art     ( 7344): Almond Protected OAT
,D/WeatherApplication( 7344): removeAccount
,D/WeatherApplication( 7344): Account.length = 0
E/WeatherApplication( 7344): OPERATOR:OPEN
D/WeatherAncestor( 7344): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:32:54
D/Weather.Utils( 7344): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7344): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7344): 2 : This is isUpdating : false
,D/WeatherAncestor( 7344): connectivity changed - connection : true
D/WeatherService( 7344): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7344): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7344): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7344): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7344): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7344): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:32:54
,I/ActivityManager( 1036): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7362 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6792:com.lge.eula/1000 (adj 15): empty #17
,E/WifiStateMachine( 1036):  DisconnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1036):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6792/cgroup.procs: No such file or directory
,E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7362): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7362): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7362): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7362): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/jxcore-log( 7020): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7020): 
,I/WebViewFactory( 7362): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7362): Loading: webviewchromium
I/LibraryLoader( 7362): Time to load native libraries: 4 ms (timestamps 3142-3146)
,I/LibraryLoader( 7362): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7362): Binding Chromium to main looper Looper (main, tid 1) {3176e22c}
I/LibraryLoader( 7362): Expected native library version number "",actual native library version number ""
I/chromium( 7362): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7362): Initializing chromium process, renderers=0
,W/art     ( 7362): Attempt to remove local handle scope entry from IRT, ignoring
I/jxcore-log( 7020): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7020): 
V/AudioPolicyService(  321): registerClient() client 0xb1427880, uid 10093
W/AudioManagerAndroid( 7362): Requires BLUETOOTH permission
W/chromium( 7362): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7362): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/jxcore-log( 7020): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7020): 
I/chromium( 7362): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,I/Adreno-EGL( 7362): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7362): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7362): Build Date: 12/12/14 금
I/Adreno-EGL( 7362): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7362): Remote Branch: 
I/Adreno-EGL( 7362): Local Patches: 
I/Adreno-EGL( 7362): Reconstruct Branch: 
I/jxcore-log( 7020): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7020): 
,I/jxcore-log( 7020): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7020): 
,I/jxcore-log( 7020): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7020): 
I/NSApplication( 7362): Starting up...
I/jxcore-log( 7020): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7020): 
I/ActivityManager( 1036): Killing 6840:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6840/cgroup.procs: No such file or directory
,I/iu.Environment( 2367): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2367): num queued entries: 0
I/iu.UploadsManager( 2367): num updated entries: 0
I/iu.SyncManager( 2367): NEXT; no task
D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6560): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkStateForAutoUpdateMonitor( 7227): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7227): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7227): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7227): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7227): onReceive
,D/AppUp4:CustFacade( 7227): Context : android.app.ReceiverRestrictedContext@3e00b093
D/AppUp4:CustFacade( 7227): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7227): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7227): begin check event
I/AppUp4:CustModeStarterReceiver( 7227): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4280): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4280): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4280): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4280): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/eas_req ( 7254): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 4280): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4280): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 4280): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
W/FormManager( 7275): Network not available. Please check & try again.
,I/LgeMiscReceiver( 3344): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3344): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3344): networkInfo.isConnected() = false
V/FormManager( 7275): Network unavailable.
D/WeatherAncestor( 7344): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:32:55
,V/FormManager( 7275): Network unavailable.
D/Weather.Utils( 7344): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7344): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7344): 2 : This is isUpdating : false
D/WeatherAncestor( 7344): connectivity changed - connection : true
D/WeatherService( 7344): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@f62f0c9
D/ForecastDataCache( 7344): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7344): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7344): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7344): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7344): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:32:55
W/Settings( 7254): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ChimeraCfgMgr( 2367): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7134): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7134): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7134): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7158): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7134): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7134): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7134): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
,D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7158): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7158): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/jxcore-log( 7020): Test app app.js loaded
I/jxcore-log( 7020): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7020): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 7020): BLE advertisement is supported
I/jxcore-log( 7020): 
I/chromium( 7020): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 2701): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1036): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1036): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1036):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1036):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1036):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1036):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1036): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=264112  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,D/UEI.SmartControl( 6736): Internal timer expired: 3
D/UEI.SmartControl( 6736): unbind internal service
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=264133  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7158): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2701): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1036): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,I/wpa_supplicant( 2701): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2701): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/Tethering( 1036): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=264241  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1036): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1036): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1036): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=264253  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1036):  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=264254
E/WifiStateMachine( 1036):  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=264254
E/WifiStateMachine( 1036):  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=264255
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=264258
E/WifiStateMachine( 1036):  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=264258
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=264259  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,D/serial_port( 6736): close(fd = 24)
D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7158): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=264277  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1036):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=264281  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=264282  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1036):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=264283
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=264284
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1036): doString: [STATUS]
,D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7096): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7096): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7096): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7096): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7096): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/UEI.SmartControl( 6736): Serial port is closed.
D/UsbSettingsControl( 7096): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7096): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7096): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7096): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7096): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7096): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7096): [AUTORUN] setTetherStatus() : status=false
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1036):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/WifiServiceExtension( 1036): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/WifiServerServiceExt( 1036): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1036): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1036): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1036): Got NetworkAgent Messenger
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1036): NetworkAgent connected
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7158): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
D/CommandListener(  315): Setting iface cfg
E/WifiStateMachine( 1036): Start Dhcp Watchdog 2
E/WifiStateMachine( 1036):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=264339  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,D/DhcpStateMachine( 1036): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): WaitBeforeStartState
,E/WifiStateMachine( 1036):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=264340  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=264341  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1036):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=264346  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=264346  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=264346  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1036):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1036):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1036): doBoolean: DRIVER SETSUSPENDMODE 0
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateGROUP_HANDSHAKE
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7158): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2701): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1036): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 0
D/WifiNative-wlan0( 1036): SET ps 0: returned true
,D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2701): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1036): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1036): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1036): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3521a5c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3521a5c target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1036): DHCP Start wake lock is acquired.
D/CommandListener(  315): Setting iface cfg
D/CommandListener(  315): Trying to bring up wlan0
D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
,V/LgDhcpStateMachineHelper( 1036): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
E/WifiStateMachine( 1036):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1036):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2701): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2701): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1036): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/LGWifiP2pService( 1036): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/QRemote ( 7158): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1036):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1036): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1036): ignoring duplicate network state non-change
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1036): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1036): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1959): handleWifiStateChangedEvent: 1
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1036): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/ConnectivityService( 1036): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1036): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1036): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  315): netlink response contains error (File exists)
D/ConnectivityService( 1036): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1036): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1036): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1036): Setting Dns servers for network 101 to [/192.168.1.1]
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1036): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1036):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1036): currentScore = 0, newScore = 20
D/ConnectivityService( 1036):    accepting network in place of null
D/ConnectivityService( 1036): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1036): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1036): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1870): new score 20 for exis,iting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1036): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1036): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1036): validation of new default Network = false
D/ConnectivityService( 1036): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1036): enableDataServiceNotify 
D/DSQN    ( 1036): start dsqn bin
D/LocSvc_java( 1036): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1036): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1463): CM callback handler got msg 524290
W/dsqn    ( 7465): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7465): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
I/StatusBar.NetworkController( 1463): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1463): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7158): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,E/DSQN    ( 7465): DSQN ssw
V/NetworkPolicy( 1036): [LG_RESTRICTED] checkMobilePolicy_type()
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/TelephonyIcons( 1463): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7158): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
D/libc-netbsd(  315): res_queryN name = clients3.google.com, class = 1, type = 1
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7158): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7134): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7134): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7158): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/libc-netbsd(  315): res_queryN name = clients3.google.com succeed
I/QRemote ( 7158): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7158): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7134): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7134): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDataListener(  315): argv[0]=dsqncommand
D/LGDataListener(  315): argv[1]=wlan0
D/LGDataListener(  315): argv[2]=1
D/LGDataListener(  315): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1036): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1036): start to monitor internet connection
,D/WiFiOffLoadBroadcast( 7096): MCCMNC not supported: null
D/QRemote ( 7158): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7158): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jan 2016 07:32:56 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453879976686], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453879976667]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Validated
D/ConnectivityService( 1036): Validated NetworkAgentInfo [WIFI () - 101]
D/QRemote ( 7158): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
D/ConnectivityService( 1036): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1036):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1036): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1036): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QRemote ( 7158): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
D/ConnectivityService( 1036): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1463): CM callback handler got msg 524290
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1036): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1870): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
I/QRemote ( 7158): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/TelephonyIcons( 1463): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1463): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/DhcpStateMachine( 1036): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1036): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1036): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7471): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7471): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 7471): version 5.5.6 starting
,E/dhcpcd  ( 7471): get_duid: m
D/dhcpcd  ( 7471): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7471): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7471): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7471): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7471): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7471): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7471): wlan0: sending REQUEST (xid 0xbba14b8b), next in 4.81 seconds
,I/jxcore-log( 7020): --= Surplus to requirements =--
I/jxcore-log( 7020): 
I/jxcore-log( 7020): ****TEST TOOK:  ms ****
I/jxcore-log( 7020): 
I/jxcore-log( 7020): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7020): 
,E/WifiStateMachine( 1036):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,D/ConnectivityService( 1036): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1036): identical MTU - not setting
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1036): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1463): CM callback handler got msg 524295
,D/AndroidRuntime( 7495): 
D/AndroidRuntime( 7495): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7495): CheckJNI is OFF
I/dhcpcd  ( 7471): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7471): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7471): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7471): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7471): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7471): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7471): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7471): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7471): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/AndroidRuntime( 7495): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1036): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
,I/ActivityManager( 1036): Killing 7020:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/PackageSettings( 1036): Skipping PackageSetting{e634248 com.example.hello/10319} due to missing metadata
I/WindowState( 1036): WIN DEATH: Window{38484029 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1036): Client connection lost with reason: 4
D/InputDispatcher( 1036): Window went away: Window{38484029 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/DhcpStateMachine( 1036): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1036): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1036): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1036): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1036): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1036): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1036): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1036): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1036): RunningState
I/ActivityManager( 1036):   Force finishing activity ActivityRecord{2899355a u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  341): DFP En is all cleared set to be enabled
W/ActivityManager( 1036): Spurious death for ProcessRecord{1e04e64 7020:com.test.thalitest/u0a311}, curProc for 7020: null
I/ActivityManager( 1036): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,I/ActivityManager( 1036):   Force finishing activity ActivityRecord{2899355a u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1036): Duplicate finish request for ActivityRecord{2899355a u0 com.test.thalitest/.MainActivity t4 f}
,I/[LGHome]EVENT( 2086): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2086): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{dc72823 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]EVENT( 2086): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
D/SplitWindowPolicy( 1959): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1959): topRunningActivity=ActivityInfo{3a18f120 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1923): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2086): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 3729): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2086): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1463): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1036): Reconfiguring input devices.  changes=0x00000010
E/LGBluetoothAvrcpQcomAdapter( 3788): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3788): [BTUI] [+] updateMediaPlayerInfo
,D/LIA_Service_RemotePackageHandler( 2024): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3729): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/GeofencerStateMachine( 1832): Ignoring removeGeofence because network location is disabled.
I/art     ( 4549): Explicit concurrent mark sweep GC freed 16106(914KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 684us total 70.891ms
,D/PostponalbeReceiver( 6560): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/[LGHome]EVENT( 2086): [Launcher.java:1056:onResume()]onResume end
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,W/System.err( 4496): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4496): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4496): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4496): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4496): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4496): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4496): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4496): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4496): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4496): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4496): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4496): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1036): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7547 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 2086): [Launcher.java:1114:onPause()]onPause
I/[SystemUI]QSlideListController( 1463): onReceive = android.intent.action.PACKAGE_REMOVED
D/ActionManagerService( 1923): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2086): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,D/LIA_Informant_ActionManagerMessageHandler( 3729): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3729): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2086): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2086): , create_time: 1430558575574
I/GBoardWebViewUtils( 2086): , expire_time: 0
I/GBoardWebViewUtils( 2086): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2086): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2086): , display: false
I/GBoardWebViewUtils( 2086): , animation: false }
I/GBoardWebViewUtils( 2086): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2086): , create_time: 1430558575600
I/GBoardWebViewUtils( 2086): , expire_time: 0
I/GBoardWebViewUtils( 2086): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2086): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2086): , display: false
I/GBoardWebViewUtils( 2086): , animation: false }
I/GBoardWebViewUtils( 2086): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453384801259
I/GBoardWebViewUtils( 2086): , create_time: 1453384801850
I/GBoardWebViewUtils( 2086): , expire_time: 0
I/GBoardWebViewUtils( 2086): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2086): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2086): , display: false
I/GBoardWebViewUtils( 2086): , animation: false }
D/SplitUIManager( 1887): split_name #11 / not available #0
D/SplitUIService( 1887): removed split : 
D/WallpaperManager( 2086): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@14a0d7e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[LGHome]GBoardWebView( 2086): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,D/SplitUIManager( 1887): split_name #11 / not available #0
I/SplitUIService( 1887): split app #11
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1463): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1463): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 100342(5MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 44MB/66MB, paused 1.942ms total 221.534ms
I/art     ( 1036): WaitForGcToComplete blocked for 202.373ms for cause Explicit
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
D/AppUp4:PreloadHelper( 7227): added Exclude : com.test.thalitest
,I/LockScreenSettings( 7547): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/ActivityManager( 1036): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7567 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ActivityManager( 1036): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3788): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3788): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3788): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3788): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3788): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3788): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3788): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3788): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3788): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3788): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3788): [BTUI] [-] updateMediaPlayerInfo
D/administrator( 1036): Handling package changes for user 0
D/KeyguardModel( 1463): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1463): createShortcutInfo...
I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1463): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1463): createShortcutInfo...
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,W/ResourcesManager( 1463): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2086): [Launcher.java:5349:onStop()]onStop
W/ResourceType( 1463): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1463): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1463): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1463): createShortcutInfo...
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1463): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1463): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1463): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1463): createShortcutInfo...
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
W/ResourcesManager( 1463): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1463): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1463): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1463): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1463): createShortcutInfo...
D/KeyguardModel( 1463): handleShortcutListChanged...
D/KeyguardModel( 1463): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1463): createShortcutInfo...
D/KeyguardModel( 1463): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1463): createShortcutInfo...
W/ResourceType( 1463): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1463): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1463): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1463): createShortcutInfo...
W/ResourceType( 1463): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1463): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1463): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1463): createShortcutInfo...
W/ResourceType( 1463): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1463): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1463): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1463): createShortcutInfo...
W/ResourcesManager( 7567): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7567): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7567): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7567): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7567): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager( 1036): Killing 6821:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/NotificationService( 1036): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1036): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1036): Receieved: android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1463): handleShortcutListChanged...
,W/libprocessgroup( 1036): failed to open /acct/uid_10005/pid_6821/cgroup.procs: No such file or directory
I/art     ( 1036): Explicit concurrent mark sweep GC freed 6936(387KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.029ms total 186.691ms
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/PhoneStatusBar( 1463): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
,I/[SystemUI]NavigationThemeResource( 1463): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1463):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1463): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1036): removeObsoleteFile: deleting file=4_task.xml
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2086): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{36f46923 u0 com.lge.launcher2/.Launcher t3} time:266713
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2086): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[Concierge]WidgetView( 2086): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2612): onStartCommand(). Type : 8
D/[Concierge]Service( 2612): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2612): Update widget ID : 11
D/[Concierge]WidgetView( 2086): change position of spinner
,I/[Concierge]WidgetView( 2086): initWebView(). Time : 1453879978865
D/[Concierge]Service( 2612): onStartCommand(). Type : 0
I/SystemConfig( 7567): BUILD Country: EU
,I/SystemConfig( 7567): BUILD Operator: OPEN
I/ActivityManager( 1036): Killing 6481:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/ResourcesManager( 1036): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1036): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/AndroidRuntime( 7495): Shutting down VM
,W/libprocessgroup( 1036): failed to open /acct/uid_10054/pid_6481/cgroup.procs: No such file or directory
,I/[Concierge]WebView( 2086): Return exist ConciergeWebView. Reuse : 357284994
D/[Concierge]WidgetView( 2086): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2086): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2086): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@fe435b5
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2086): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/VoicemailCleanupService( 2197): Cleaning up data for package: com.test.thalitest
I/PackageChangeReceiver( 7254): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/SystemConfig( 7567): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 7567): existFile = false
I/SystemConfig( 7567): canReadFile = false
I/SystemConfig( 7567): systemFeature RCS result false
D/SystemConfig( 7567): refreshRcsSupport() :false
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2086): isWidgetUpdateSkippable ? true
,D/[Concierge]WidgetBroadcastReceiver( 2086): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/ActivityManager( 1036): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7589 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/[Concierge]WidgetView( 2086): Widget kill message received. Destory myself. My : 1453879740611, New one : 1453879978865
D/[Concierge]WidgetView( 2086): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2086): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]EVENT( 2086): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2086): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
W/ResourcesManager( 7589): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7589): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7589): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7589): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2086): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2086): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2086): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2086): Timeline: Activity_idle id: android.os.BinderProxy@249bf554 time:267034
,I/AppConfig( 7589): Total System Memory = 2995761152
,D/SystemHelper( 7589): region [EU], country [EU], operator [OPEN], sub-operator []
E/SharedPreferencesImpl( 7589): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
I/ActivityManager( 1036): Killing 6204:com.android.vending/u0a44 (adj 15): empty #17
,I/chromium( 2086): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)

```
