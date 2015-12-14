#### Test 50650278ec2c976_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 277614656128; DSPS: 9237749; Offset : -4313271431
,D/AndroidRuntime( 7011): 
D/AndroidRuntime( 7011): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7011): CheckJNI is OFF
D/AndroidRuntime( 7011): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1040): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1968): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1040): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1040): setTaskToReturnTo : TaskRecord{31e7336 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1040): setTaskToReturnTo : TaskRecord{31e7336 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1040): AppWindowTokenEx init.. 
E/GBMv2   (  345): DFP En is all cleared set to be enabled
I/ActivityManager( 1040): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7031 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7011): Shutting down VM
V/ActivityManager( 1040): Display changed displayId=0
D/DSDPConnection( 1872): Display #0 changed.
D/SplitWindowPolicy( 1968): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1968): topRunningActivity=ActivityInfo{1f86c9ac co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1968): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1968): topRunningActivity=ActivityInfo{24de7675 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7031): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7031): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7031): Loading: webviewchromium
I/LibraryLoader( 7031): Time to load native libraries: 4 ms (timestamps 6868-6872)
,I/LibraryLoader( 7031): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7031): Binding Chromium to main looper Looper (main, tid 1) {37f0645c}
,I/LibraryLoader( 7031): Expected native library version number "",actual native library version number ""
I/chromium( 7031): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7031): Initializing chromium process, renderers=0
W/art     ( 7031): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  322): registerClient() client 0xb57be8c0, uid 10311
,W/chromium( 7031): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7031): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7031): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1040): Message: 20
D/BluetoothManagerService( 1040): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@284c8610:true
,I/Adreno-EGL( 7031): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7031): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7031): Build Date: 12/12/14 금
I/Adreno-EGL( 7031): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7031): Remote Branch: 
I/Adreno-EGL( 7031): Local Patches: 
I/Adreno-EGL( 7031): Reconstruct Branch: 
W/chromium( 7031): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7031): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7031): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7031): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7031): CordovaWebView is running on device made by: LGE
W/art     ( 7031): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7031): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 7031): Render dirty regions requested: true
I/OpenGLRenderer( 7031): Initialized EGL, version 1.4
D/OpenGLRenderer( 7031): Enabling debug mode 0
D/Atlas   ( 7031): Validating map...
W/ActivityManager( 1040): Activity pause timeout for ActivityRecord{2cd5b237 u0 com.test.thalitest/.MainActivity t4}
D/SplitWindow( 1040): check instance of lgWin Window{4e615ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 7031): LgDataFeature() Constructor: none
D/LgDataFeature( 7031): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1040): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1040): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1040): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1040): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@e921a68,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1040): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1469): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1469): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1469):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1469): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1040): Displayed com.test.thalitest/.MainActivity: +641ms (total +739ms)
I/Timeline( 1040): Timeline: Activity_windows_visible id: ActivityRecord{2cd5b237 u0 com.test.thalitest/.MainActivity t4} time:287325
I/Timeline( 7031): Timeline: Activity_idle id: android.os.BinderProxy@9c39c8c time:287336
I/chromium( 7031): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7031): 
D/JsMessageQueue( 7031): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7031): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435083520
D/JX-Cordova( 7031): jxcore cordova android initializing
E/GBMv2   (  345): DFP En is all cleared set to be enabled
E/GBMv2   (  345): Set value is all cleared set the max
I/GBMv2   (  345): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7031): Initializing JXcore engine
W/jxcore-log( 7031): JXcore engine is ready
,W/jxcore-log( 7031): Starting JXcore engine
W/.test.thalitest( 7031): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8338]" dev="sockfs" ino=8338 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7031): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7031): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9934]" dev="sockfs" ino=9934 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7031): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7031): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[34319]" dev="sockfs" ino=34319 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/art     ( 7031): Background sticky concurrent mark sweep GC freed 123909(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 4.229ms total 143.284ms
,W/jxcore-log( 7031): Platform android
W/jxcore-log( 7031): 
W/jxcore-log( 7031): Process ARCH arm
W/jxcore-log( 7031): 
,I/jxcore-log( 7031): JXcore Cordova bridge is ready!
I/jxcore-log( 7031): 
W/jxcore-log( 7031): JXcore engine is started
,I/jxcore-log( 7031): Toggling radios to true
I/jxcore-log( 7031): 
,D/BluetoothAdapter( 7031): enable(): BT is already enabled..!
D/WifiService( 1040): New client listening to asynchronous messages
D/WifiServiceImplEx( 1040): setWifiEnabled: true pid=7031, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1040): setWifiEnabled: true pid=7031, uid=10311
E/WifiService( 1040): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1040): disconnect pid=7031, uid=10311, packageName=com.test.thalitest
,E/WifiStateMachine( 1040):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1040): [290,833,305 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1040): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1040): reconnect pid=7031, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7031): Radios toggled
I/jxcore-log( 7031): 
D/BluetoothManagerService( 1040): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 7031): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7031): 
I/jxcore-log( 7031): Perf Test app loaded loaded
I/jxcore-log( 7031): 
I/jxcore-log( 7031): check test folder
I/jxcore-log( 7031): 
I/jxcore-log( 7031): found test : ./testFindPeers.js
I/jxcore-log( 7031): 
,I/wpa_supplicant( 2642): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1040): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1040): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1040): InitialState.processMessage what=4
D/Tethering( 1040): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1040): DISCONNECT: returned true
E/WifiStateMachine( 1040): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
I/jxcore-log( 7031): found test : ./testSendData.js
I/jxcore-log( 7031): 
,D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2642): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1040): SET ps 1: returned true
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1040): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7104 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/DhcpStateMachine( 1040): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  317): Clearing all IP addresses on wlan0
V/NativeCrypto( 2128): Read error: ssl=0xaf4d0200: I/O error during system call, Connection timed out
V/NativeCrypto( 2128): SSL shutdown failed: ssl=0xaf4d0200: I/O error during system call, Broken pipe
,D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/WifiHS20( 1040): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1968): handleWifiStateChangedEvent: 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1040): hidePasspointNotification off =false
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1040): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/WifiStateMachine( 1040): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1040):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1040): [290,962,910 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1040): doBoolean: RECONNECT
I/wpa_supplicant( 2642): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1040): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1040): RECONNECT: returned true
E/WifiStateMachine( 1040):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=290966
E/WifiStateMachine( 1040):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=290966
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/LGWifiP2pService( 1040): InactiveState{ when=-19ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-19ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2642): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/WifiNative-wlan0( 1040): SET ps 1: returned true
W/ResourcesManager( 7104): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7104): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 7104): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7104): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7104): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7104): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/CommandListener(  317): Clearing all IP addresses on wlan0
D/ConnectivityService( 1040): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1040): disableDataServiceNotify
D/DSQN    ( 1040): stop dsqn bin
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1040): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=291015  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=291015  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1040): hidePasspointNotification off =false
E/WifiStateMachine( 1040):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1040): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=291022  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1040): hidePasspointNotification off =false
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1040): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1040): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=291025  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateSCANNING
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524292
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1040): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1040): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Disconnected - quitting
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1040): Checking for replacement network to handle request NetworkRequest, [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1040): Removing idletimer
D/TelephonyNetworkFactory-1( 1872): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/Settings( 1040): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1040): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1040): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WIFI    ( 1040): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1040): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1040): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1040): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
,D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/chromium( 7031): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7031): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7031): 
D/UsbSettingsReceiver( 7104): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7104): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7104): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7104): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7104): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/chromium( 7031): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/UsbSettingsControl( 7104): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7104): [AUTORUN] onReceive() : availableList=[]
,D/UsbSettingsReceiver( 7104): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7104): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7104): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7104): [AUTORUN] setTetherStatus() : status=false
D/DhcpStateMachine( 1040): StoppedState
D/DhcpStateMachine( 1040): StoppedState{ when=-133ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1040): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7141 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1040): Killing 6583:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1040): failed to open /acct/uid_10008/pid_6583/cgroup.procs: No such file or directory
,I/PCSuite ( 7141): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7141): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7141): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7104): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7104): LgDataFeature() Constructor: none
D/LgDataFeature( 7104): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7104): MCCMNC not supported: null
,I/ActivityManager( 1040): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7168 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1040): Killing 6104:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10011/pid_6104/cgroup.procs: No such file or directory
,W/ResourcesManager( 7168): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7168): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7168): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7168): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7168): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7168): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7168): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7168): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7168): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7168): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7168): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7168): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/QRemote ( 7168): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 7168): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/PCSuite ( 7141): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7141): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7141): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7104): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7104): MCCMNC not supported: null
D/QRemote ( 7168): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7168): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7168): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7141): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7141): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7141): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7104): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7104): MCCMNC not supported: null
D/QRemote ( 7168): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7168): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7168): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7141): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7141): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7141): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7104): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7104): MCCMNC not supported: null
D/QRemote ( 7168): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7168): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7168): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7104): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7104): MCCMNC not supported: null
D/QRemote ( 7168): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7168): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7168): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,V/QRemote ( 7168): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7168): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7168): LgDataFeature() Constructor: none
D/LgDataFeature( 7168): LgDataFeature() Constructor Done, null
,V/SoundPool( 7168): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,V/SoundPool( 7168): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7168): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7168): doLoad: loading sample sampleID=1
I/QRemote ( 7168): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7168): Start decode
V/MediaPlayer[Native]( 7168): decode(31, 10857164, 17813)
,V/MediaPlayerService(  322): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  322): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  322): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  322): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  322): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  322): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  322): player type = 3
V/AwesomePlayer(  322): AwesomePlayer create()
D/UEI.SmartControl( 6748): QS Service created
V/AwesomePlayer(  322): reset_l() 
V/AwesomePlayer(  322): cancelPlayerEvents
D/QRemote ( 7168): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/AwesomePlayer(  322): setAudioSink() 
V/AwesomePlayer(  322): reset_l() 
V/AudioCache(  322): notify(0xb5474780, 8, 0, 0)
V/AudioCache(  322): ignored
V/AwesomePlayer(  322): cancelPlayerEvents
D/Utils   (  322): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  322): setDataSource_l dataSource
V/LGParserOSAL(  322): SniffLGParser start
V/LGParserOSAL(  322): MainType:5, SubType=0
V/LGParserOSAL(  322): #### check Mime : application/ogg
V/LGParserOSAL(  322): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  322): Use LGExtractor :application/ogg 
E/QRemote ( 7168): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/UEI.SmartControl( 6748): Service initServices...
D/UEI.SmartControl( 6748): QS start get config
,V/LGMDMManager( 7168): Create singleton instance
,V/LGParserOSAL(  322): supported mime: application/ogg
V/AwesomePlayer(  322): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  322): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  322): mBitrate = -1 bits/sec
V/AwesomePlayer(  322): AudioTrack Setting
V/AwesomePlayer(  322): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  322): setAudioSource() 
V/MediaPlayerService(  322): prepare
V/AwesomePlayer(  322): prepareAsync_l() 
V/MediaPlayerService(  322): wait for prepare
V/AwesomePlayer(  322): onPrepareAsyncEvent() 
V/AwesomePlayer(  322): initAudioDecoder() 
W/Utils   (  322): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  322): isOffloadSupported()
V/AudioPolicyManager(  322): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  322): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  322): isAudioPlaybackHookOn() false
V/AwesomePlayer(  322): getUseOffload() = 0 
V/OMXCodec(  322): OMXCodec::Create
V/OMXCodec(  322): findMatchingCodecs()
V/OMXCodec(  322): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  322): matchingCodecs.size()=1
V/OMXCodec(  322): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  322): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  322): LG Codec Adapter start
V/OMXCodec(  322): OMXCodec Createtor
V/OMXCodec(  322): setComponentRole
V/OMXCodec(  322): configureCodec protected=0
V/LGCodecAdapter(  322): called getLGCodecSpecificData
V/LGCodecOSAL(  322): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  322): Called LGconfigureCodecMETA
V/LGCodecOSAL(  322): Called LGconfigureCodecMSG
,V/LGCodecOSAL(  322): Not support LGCodec
V/OMXCodec(  322): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  322): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  322): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  322): Could not offload audio decode, try pcm offload
W/Utils   (  322): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  322): isOffloadSupported()
V/AudioPolicyManager(  322): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  322): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  322): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  322): init()
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  322): allocateBuffers
V/OMXCodec(  322): allocateBuffersOnPort portIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
,V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  322): allocateBuffersOnPort portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
V/OMXCodec(  322): init() mAsyncCompletion wait!!! 
V/OMXCodec(  322): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  322): init() mAsyncCompletion wait!!! 
V/OMXCodec(  322): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  322): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  322): finishAsyncPrepare_l() 
V/AudioCache(  322): notify(0xb5474780, 5, 0, 0)
V/AudioCache(  322): ignored
V/AudioCache(  322): notify(0xb5474780, 1, 0, 0)
V/AudioCache(  322): prepared
V/AudioCache(  322): wait - success
V/MediaPlayerService(  322): start
V/AwesomePlayer(  322): play_l() 
V/AwesomePlayer(  322): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  322): createAudioPlayer_l
V/AwesomePlayer(  322): seekAudioIfNecessary_l() 
V/AwesomePlayer(  322): startAudioPlayer_l() 
D/AudioPlayer(  322): start of Playback, useOffload 0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  322): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  322): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  322): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  322): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885328
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  322): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  322): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  322): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  322): allocateBuffersOnPort portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb57c47e0 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  322): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  322): notify(0xb5474780, 6, 0, 0)
V/AudioCache(  322): ignored
V/MediaPlayerService(  322): wait for playback complete
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab700000, 0xb57e9000, 4096)
,V/AudioCache(  322): write(0xb57e9000, 4096)
,V/AudioCache(  322): memcpy(0xab701000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab702000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab703000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab704000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab705000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab706000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab707000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab708000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
,V/AudioCache(  322): memcpy(0xab709000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab70a000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab70b000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab70c000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab70d000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab70e000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab70f000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab710000, 0xb57e9000, 4096)
,V/AudioCache(  322): write(0xb57e9000, 4096)
,V/AudioCache(  322): memcpy(0xab711000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab712000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab713000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab714000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
,V/AudioCache(  322): memcpy(0xab715000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab716000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab717000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab718000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
,V/AudioCache(  322): memcpy(0xab719000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab71a000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab71b000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab71c000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
,V/AudioCache(  322): memcpy(0xab71d000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab71e000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab71f000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab720000, 0xb57e9000, 4096)
,V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab721000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab722000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab723000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab724000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab725000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab726000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab727000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab728000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab729000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab72a000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab72b000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab72c000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab72d000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab72e000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab72f000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab730000, 0xb57e9000, 4096)
V/AudioCache(  322): write(0xb57e9000, 4096)
V/AudioCache(  322): memcpy(0xab731000, 0xb57e9000, 4096)
V/OMXCodec(  322): [OMX.google.vorbis.decoder] No more output data.
,V/OMXCodec(  322): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  322): postAudioEOS() 
V/AudioCache(  322): write(0xb57e9000, 280)
V/AudioCache(  322): memcpy(0xab732000, 0xb57e9000, 280)
V/AwesomePlayer(  322): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  322): onStreamDone
V/AwesomePlayer(  322): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  322): notify(0xb5474780, 2, 0, 0)
V/AudioCache(  322): playback complete
V/AwesomePlayer(  322): pause_l() 
V/AudioCache(  322): notify(0xb5474780, 7, 0, 0)
V/AudioCache(  322): ignored
V/AwesomePlayer(  322): cancelPlayerEvents
D/AudioPlayer(  322): Pause Playback at 1068125
V/AudioCache(  322): wait - success
V/MediaPlayerService(  322): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  322): reset_l() 
V/AudioCache(  322): notify(0xb5474780, 8, 0, 0)
V/AudioCache(  322): ignored
V/AwesomePlayer(  322): cancelPlayerEvents
D/AudioPlayer(  322): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  322): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  322): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  322): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb57c47e0 on port 1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  322): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  322): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  322): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  322): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  322): AudioPlayer releasing audio source
D/AudioPlayer(  322): AudioPlayer done releasing audio source
V/AwesomePlayer(  322): reset_l() 
V/AwesomePlayer(  322): cancelPlayerEvents
V/AwesomePlayer(  322): ~AwesomePlayer call
V/AwesomePlayer(  322): reset_l() 
V/AwesomePlayer(  322): cancelPlayerEvents
V/SoundPool( 7168): close(31)
V/SoundPool( 7168): pointer = 0x9fe3e,000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4423
I/UEI.SmartControl( 6748): Supports setup maps: true
D/UEI.SmartControl( 6748): QS start statue = true Error code = 0
I/UEI.SmartControl( 6748): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6748): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6748): ### init IR Blaster...
D/serial_port( 6748): Configuring serial port
E/UEI.SmartControl( 6748): UEIBLaster setting for 616
I/UEI.SmartControl( 6748): Setting serial record hearder size = 2
I/UEI.SmartControl( 6748): configuring settings for MAXQ616
I/UEI.SmartControl( 6748): Get version...
,D/UEI.SmartControl( 6748): serial port data available: 21,
,D/UEI.SmartControl( 6748): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6748): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6748): QS saving settings...
D/UEI.SmartControl( 6748): IR Blaster version: 25672567
,D/UEI.SmartControl( 6748): serial port data available: 4
,W/ContextImpl( 6748): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 6748): Device manager: loading config....
D/UEI.SmartControl( 6748): ----------- loading internal config...
E/UEI.SmartControl( 6748): Services init done
D/UEI.SmartControl( 6748): QS Service init finished
D/UEI.SmartControl( 6748): QS Service version name: 2.1.91
D/UEI.SmartControl( 6748): QS Service version code: 201091
D/UEI.SmartControl( 6748): Service requested: Control
E/UEI.SmartControl( 6748): Loading SETTINGS...
,D/UEI.SmartControl( 6748): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6748): -- Open brand translation xml: brands_translations_ko
D/UEI.SmartControl( 6748): Internal service binding...
I/QRemote ( 7168): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6748): ------ IControl API: 11
,D/UEI.SmartControl( 6748): File observer start...
E/UEI.SmartControl( 6748): IR Port is disabled: false
D/UEI.SmartControl( 6748): Starting file observer...
I/UEI.SmartControl( 6748): Registering callback...
I/UEI.SmartControl( 6748): ------ IControl API: 19
,I/UEI.SmartControl( 6748): Registering Services Ready callback...
I/UEI.SmartControl( 6748): Notify client services are ready...
I/QRemote ( 7168): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
I/UEI.SmartControl( 6748): Notify AllClients services are ready: 0
I/QRemote ( 7168): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6748): -----service ready thread exits
D/QRemote ( 7168): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7168): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7168): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7168): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7168): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7168): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6748): ------ IControl API: 8
D/QRemote ( 7168): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7168): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7168): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7168): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7168): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7168): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7168): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,D/QRemote ( 7168): [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
V/QRemote ( 7168): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7168): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7168): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1450109572056]
D/QRemote ( 7168): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1040): Killing 6124:com.android.contacts/u0a19 (adj 15): empty #17
D/QRemote ( 7168): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1040): failed to open /acct/uid_10019/pid_6124/cgroup.procs: No such file or directory
,V/QRemote ( 7168): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7168): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2642): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1040): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1040): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1040):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1040):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1040):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
,E/WifiStateMachine( 1040):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1040): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=293043  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=293075  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7104): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7104): MCCMNC not supported: null
D/QRemote ( 7168): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7168): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7168): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7104): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2642): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1040): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2642): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2642): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=293151  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=293153  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1040): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1040): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1040): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1040):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=293158
E/WifiStateMachine( 1040):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=293158
,D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1040):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=293162
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=293162
E/WifiStateMachine( 1040):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=293163
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=293163  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=293172  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1040):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=293174  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,D/Tethering( 1040): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=293180  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1040):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=293182
E/WifiStateMachine( 1040):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=293184
D/WifiNative-wlan0( 1040): doString: [STATUS]
D/WifiMonitor( 1040): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1040): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1040):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServiceExtension( 1040): setVHTCapabilityType  : false
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,D/WiFiOffLoadBroadcast( 7104): MCCMNC not supported: null
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateASSOCIATED
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/WifiServerServiceExt( 1040): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1040): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7168): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7168): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1040): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1040): Got NetworkAgent Messenger
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1040): NetworkAgent connected
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
I/QRemote ( 7168): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
E/WifiConfigStore( 1040): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1040): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1040): SET_NETWORK 0 bssid any: returned true
,D/WifiNative-wlan0( 1040): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7104): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7104): MCCMNC not supported: null
D/WifiNative-wlan0( 1040): SAVE_CONFIG: returned true
D/CommandListener(  317): Setting iface cfg
E/WifiStateMachine( 1040): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1040): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): WaitBeforeStartState
E/WifiStateMachine( 1040):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=293241  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 7168): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1040):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=293241  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 7168): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7168): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=293242  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1040): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1040):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=293247  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1040):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=293247  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=293247  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1040):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1040):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
V/WiFiOffLoadBroadcast( 7104): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1040):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1040): doBoolean: DRIVER SETSUSPENDMODE 0
D/WiFiOffLoadBroadcast( 7104): MCCMNC not supported: null
D/QRemote ( 7168): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7168): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7168): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/UsbSettingsReceiver( 7104): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7104): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7104): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7104): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7104): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7104): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7104): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7104): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7104): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7104): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7104): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7104): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/wpa_supplicant( 2642): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1040): DRIVER SETSUSPENDMODE 0: returned true
,D/WifiNative-wlan0( 1040): doBoolean: SET ps 0
D/WifiNative-wlan0( 1040): SET ps 0: returned true
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2642): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1040): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1040): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1040): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1040): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1c4b0719 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1c4b0719 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  317): Setting iface cfg
D/CommandListener(  317): Trying to bring up wlan0
D/DhcpStateMachine( 1040): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1040): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper( 1040): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.125/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/WiFiOffLoadBroadcast( 7104): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1040): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1040): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1040):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WiFiOffLoadBroadcast( 7104): MCCMNC not supported: null
E/WifiStateMachine( 1040):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1040):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1040): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2642): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1040): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1040): doBoolean: DRIVER SETSUSPENDMODE 1
D/LGWifiP2pService( 1040): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1040): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2642): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1040): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1040): doBoolean: SET ps 1
D/QRemote ( 7168): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7168): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7168): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7104): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7104): MCCMNC not supported: null
D/WifiNative-wlan0( 1040): SET ps 1: returned true
E/WifiStateMachine( 1040):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1040):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1040): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService( 1040): ignoring duplicate network state non-change
,W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7168): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7168): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7168): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1040): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1040): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1040): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1469): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1968): handleWifiStateChangedEvent: 1
D/WifiHS20( 1040): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1040): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1040): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1040): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1040): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/ConnectivityService( 1040): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1040): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService( 1040): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  317): netlink response contains error (File exists)
D/ConnectivityService( 1040): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1040): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1040): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
,D/ConnectivityService( 1040): Setting Dns servers for network 101 to [/192.168.1.1]
V/WiFiOffLoadBroadcast( 7104): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1040): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1040):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Connected
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1040): currentScore = 0, newScore = 20
D/ConnectivityService( 1040):    accepting network in place of null
D/ConnectivityService( 1040): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc-netbsd(  317): res_queryN name = clients3.google.com, class = 1, type = 28
,I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = true, mWifiLevel = 0
D/WIFI    ( 1040): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1040): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1040): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1040): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1040): [e] list.add(nai) empty : false size: 1
D/TelephonyNetworkFactory-1( 1872): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1040): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1040): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1040): getAGpsConnectionInfo connType - 4
,D/LocSvc_java( 1040): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1040): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1040): validation of new default Network = false
D/ConnectivityService( 1040): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1040): enableDataServiceNotify 
D/DSQN    ( 1040): start dsqn bin
D/ConnectivityService( 1040): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7245): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524290
W/dsqn    ( 7245): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WiFiOffLoadBroadcast( 7104): MCCMNC not supported: null
D/QRemote ( 7168): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7168): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,E/DSQN    ( 7245): DSQN ssw
,V/NetworkPolicy( 1040): [LG_RESTRICTED] checkMobilePolicy_type()
I/QRemote ( 7168): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7104): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7104): MCCMNC not supported: null
D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7168): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7168): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7168): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  317): res_queryN name = clients3.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7141): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7141): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7104): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7104): MCCMNC not supported: null
D/QRemote ( 7168): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7168): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7168): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7168): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7168): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  317): res_queryN name = clients3.google.com succeed
,I/PCSuite ( 7141): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7141): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7104): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7104): MCCMNC not supported: null
D/LGDataListener(  317): argv[0]=dsqncommand
D/LGDataListener(  317): argv[1]=wlan0
D/LGDataListener(  317): argv[2]=1
D/LGDataListener(  317): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1040): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1040): start to monitor internet connection
D/QRemote ( 7168): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7168): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7168): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7168): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7168): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 14 Dec 2015 16:12:53 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450109573176], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450109573156]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1040): Validated
D/ConnectivityService( 1040): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1040): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1040):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1040): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1040): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524290
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1040): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1872): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    ( 1040):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1872):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/DhcpStateMachine( 1040): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1040): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1040): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7251): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7251): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/dhcpcd  ( 7251): version 5.5.6 starting
E/dhcpcd  ( 7251): get_duid: m
D/dhcpcd  ( 7251): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
,D/dhcpcd  ( 7251): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 7251): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7251): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7251): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7251): wlan0: rebinding lease of 192.168.1.125
D/dhcpcd  ( 7251): wlan0: sending REQUEST (xid 0x80fa14b2), next in 3.13 seconds
,D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1040): MasterInitialState.processMessage what=3
D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1040): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5450): type=WIFI subType= reason=null isConnected=true
W/ContextImpl( 6547): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5450): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1040): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7268 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7268): onCreate
W/AppUp4:DB( 7268):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7268):  setFingerPrint start
I/AppUp4:DB( 7268):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7268):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7268):  SDK version = 21
I/AppUp4:DB( 7268):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7268): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7268): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7268): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7268): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7268): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7268): onReceive
,D/LgDataFeature( 7268): LgDataFeature() Constructor: none
D/LgDataFeature( 7268): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7268): Context : android.app.ReceiverRestrictedContext@1c0c983a
D/AppUp4:CustFacade( 7268): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7268): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7268): begin check event
I/AppUp4:CustModeStarterReceiver( 7268): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7268): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7268): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7268): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 7268): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1040): Killing 6611:com.lge.email/u0a23 (adj 15): empty #17
,D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/libprocessgroup( 1040): failed to open /acct/uid_10023/pid_6611/cgroup.procs: No such file or directory
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3377): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4317): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3377): DownloadService onCreate
I/LGDMClient( 4317): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3377): in removeSpuriousFiles
,V/DownloadManager( 3377): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3377): created cursor android.database.sqlite.SQLiteCursor@1f3f8d3e on behalf of 3377
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3377): in trimDatabase
,V/DownloadManager( 3377): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3377): created cursor android.database.sqlite.SQLiteCursor@3d2050ec on behalf of 3377
I/ActivityManager( 1040): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7313 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3377): DownloadService onStartCommand
,V/DownloadManager( 3377): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3377): created cursor android.database.sqlite.SQLiteCursor@24233f4a on behalf of 3377
E/LGDMClient( 4317): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3377): processing inserted download 1
V/DownloadManager( 3377): processing inserted download 4
D/LGDMClient( 4317): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3377): processing inserted download 7
D/LGDMClient( 4317): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3377): processing inserted download 8
,V/DownloadManager( 3377): processing inserted download 9
V/DownloadManager( 3377): processing inserted download 10
V/DownloadManager( 3377): processing inserted download 16
V/DownloadManager( 3377): processing inserted download 17
V/DownloadManager( 3377): processing inserted download 18
V/DownloadManager( 3377): processing inserted download 21
V/DownloadManager( 3377): DownloadService onDestroy
E/WifiStateMachine( 1040):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1040):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1040):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1040): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1040): identical MTU - not setting
D/Nat464Xlat( 1040): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1040): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1040):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1040): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524295
W/ResourcesManager( 7313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7313): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7313): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7313): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/dhcpcd  ( 7251): wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,I/LGEmail ( 7313): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/dhcpcd  ( 7251): wlan0: leased 192.168.1.125 for 86400 seconds
,D/dhcpcd  ( 7251): wlan0: adding IP address 192.168.1.125/24
D/dhcpcd  ( 7251): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7251): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7251): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7251): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7251): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7251): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
D/LGEmail ( 7313): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7313): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7313): LgDataFeature() Constructor: none
,D/LgDataFeature( 7313): LgDataFeature() Constructor Done, null
,D/eas_req ( 7313): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1040): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7357 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7313): JNI_OnLoad()
,I/HubEmail( 7313): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 7313): registerNatives()
I/HubEmail( 7313): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7313): registerNativeMethods()
I/HubEmail( 7313): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7313): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/art     (  349): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 481us total 40.547ms
I/ActivityManager( 1040): Killing 6641:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/DhcpStateMachine( 1040): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1040): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1040): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1040): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.125
V/LgDhcpStateMachineHelper( 1040): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1040): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1040): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1040): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1040): RunningState
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 443us total 20.755ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 450us total 20.756ms
,W/libprocessgroup( 1040): failed to open /acct/uid_10027/pid_6641/cgroup.procs: No such file or directory
,W/Settings( 7313): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7313): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3340): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3340): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3340): networkInfo.isConnected() = false
,I/ActivityManager( 1040): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7380 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1040): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7400 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1040): Killing 6497:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_10004/pid_6497/cgroup.procs: No such file or directory
,D/libc-netbsd(  317): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1040): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7420 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 6668:com.google.android.apps.docs/u0a61 (adj 15): empty #17
V/FormManager( 7357): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7357): Alarm would be updated, because LastCheckTime has been updated.
W/libprocessgroup( 1040): failed to open /acct/uid_10061/pid_6668/cgroup.procs: No such file or directory
,I/ActivityManager( 1040): Killing 6700:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/art     ( 7420): Almond Protected OAT
,I/jxcore-log( 7031): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 7031): 
,W/libprocessgroup( 1040): failed to open /acct/uid_10080/pid_6700/cgroup.procs: No such file or directory
,D/WeatherApplication( 7420): removeAccount
D/WeatherApplication( 7420): Account.length = 0
E/WeatherApplication( 7420): OPERATOR:OPEN
,D/WeatherAncestor( 7420): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:55
D/Weather.Utils( 7420): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7420): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7420): 2 : This is isUpdating : false
,D/WeatherAncestor( 7420): connectivity changed - connection : true
D/WeatherService( 7420): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7420): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7420): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7420): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7420): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7420): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:55
,E/WifiStateMachine( 1040):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1040):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1040):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/ActivityManager( 1040): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7440 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1040): Killing 6781:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_6781/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7440): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7440): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7440): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7440): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1040): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1040): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1040): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1040): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5450): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1040): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=463241613, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
V/AlarmManager( 1040): ELAPSED_WAKEUP set : Alarm{12912d71 type 2 when 296347 com.google.android.gms} when 296347
D/[Concierge]Service( 2643): onStartCommand(). Type : 9
,I/WebViewFactory( 7440): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7440): Loading: webviewchromium
,I/LibraryLoader( 7440): Time to load native libraries: 10 ms (timestamps 6562-6572)
I/LibraryLoader( 7440): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7440): Binding Chromium to main looper Looper (main, tid 1) {392dd48d}
I/LibraryLoader( 7440): Expected native library version number "",actual native library version number ""
I/chromium( 7440): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7440): Initializing chromium process, renderers=0
,W/art     ( 7440): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7440): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7440): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7440): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,I/Adreno-EGL( 7440): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7440): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7440): Build Date: 12/12/14 금
I/Adreno-EGL( 7440): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7440): Remote Branch: 
I/Adreno-EGL( 7440): Local Patches: 
I/Adreno-EGL( 7440): Reconstruct Branch: 
,V/AudioPolicyService(  322): registerClient() client 0xb57bea20, uid 10093
W/AudioManagerAndroid( 7440): Requires BLUETOOTH permission
I/NSApplication( 7440): Starting up...
,I/ActivityManager( 1040): Killing 6805:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1040): failed to open /acct/uid_1000/pid_6805/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2328): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2328): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6547): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7268): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7268): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7268): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7268): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7268): onReceive
,D/AppUp4:CustFacade( 7268): Context : android.app.ReceiverRestrictedContext@1c0c983a
D/AppUp4:CustFacade( 7268): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7268): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7268): begin check event
I/AppUp4:CustModeStarterReceiver( 7268): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4317): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/DownloadManager( 3377): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 4317): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3377): DownloadService onCreate
,W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4317): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/DownloadManager( 3377): in removeSpuriousFiles
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LGDMClient( 4317): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4317): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3377): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3377): created cursor android.database.sqlite.SQLiteCursor@3b378fd8 on behalf of 3377
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3377): in trimDatabase
V/DownloadManager( 3377): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3377): created cursor android.database.sqlite.SQLiteCursor@de0616 on behalf of 3377
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3377): DownloadService onStartCommand
V/DownloadManager( 3377): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3377): created cursor android.database.sqlite.SQLiteCursor@481d184 on behalf of 3377
V/DownloadManager( 3377): processing inserted download 1
I/LgeMiscReceiver( 3340): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3340): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3340): networkInfo.isConnected() = false
,V/DownloadManager( 3377): processing inserted download 4
V/DownloadManager( 3377): processing inserted download 7
V/DownloadManager( 3377): processing inserted download 8
V/DownloadManager( 3377): processing inserted download 9
V/DownloadManager( 3377): processing inserted download 10
W/Settings( 7313): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3377): processing inserted download 16
V/DownloadManager( 3377): processing inserted download 17
V/DownloadManager( 3377): processing inserted download 18
V/DownloadManager( 3377): processing inserted download 21
,D/WeatherAncestor( 7420): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:56
V/DownloadManager( 3377): DownloadService onDestroy
W/Settings( 7313): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Weather.Utils( 7420): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7420): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7420): 2 : This is isUpdating : false
D/WeatherAncestor( 7420): connectivity changed - connection : true
D/WeatherService( 7420): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@314d6a48
D/ForecastDataCache( 7420): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7420): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7420): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7420): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7420): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:56
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2328): [AccountUtils] Account not ready
W/Kids    ( 2328): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2328): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2328): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2328): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2328): 	at java.lang.Thread.run(Thread.java:818)
V/FormManager( 7357): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7357): Alarm would be updated, because LastCheckTime has been updated.
D/ChimeraCfgMgr( 2328): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6547): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6547): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7268): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7268): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7268): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7268): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7268): onReceive
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AppUp4:CustFacade( 7268): Context : android.app.ReceiverRestrictedContext@1c0c983a
,D/AppUp4:CustFacade( 7268): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7268): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7268): begin check event
I/AppUp4:CustModeStarterReceiver( 7268): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3377): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3377): DownloadService onCreate
D/LGDMClient( 4317): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3377): in removeSpuriousFiles
V/DownloadManager( 3377): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4317): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 3377): DownloadService onStartCommand
V/DownloadManager( 3377): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4317): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3377): created cursor android.database.sqlite.SQLiteCursor@2b0c81f0 on behalf of 3377
I/art     ( 1040): Explicit concurrent mark sweep GC freed 85551(4MB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 1.756ms total 133.881ms
V/DownloadManager( 3377): created cursor android.database.sqlite.SQLiteCursor@138aa369 on behalf of 3377
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
,I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3377): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
V/DownloadManager( 3377): processing inserted download 1
V/DownloadManager( 3377): processing inserted download 4
I/DownloadManager( 3377): in trimDatabase
V/DownloadManager( 3377): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3377): processing inserted download 7
V/DownloadManager( 3377): processing inserted download 8
V/DownloadManager( 3377): processing inserted download 9
V/DownloadManager( 3377): processing inserted download 10
V/DownloadManager( 3377): processing inserted download 16
V/DownloadManager( 3377): processing inserted download 17
V/DownloadManager( 3377): created cursor android.database.sqlite.SQLiteCursor@1c07c1ee on behalf of 3377
V/DownloadManager( 3377): processing inserted download 18
I/LgeMiscReceiver( 3340): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3340): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3340): networkInfo.isConnected() = true
D/PhoneState( 3340): setPdpRejectCasuse : false
V/DownloadManager( 3377): processing inserted download 21
,W/Settings( 7313): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 4317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/LGDMClient( 4317): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4317): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4317): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/WeatherAncestor( 7420): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:56
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
I/art     ( 2128): Explicit concurrent mark sweep GC freed 38313(2MB) AllocSpace objects, 10(1440KB) LOS objects, 51% free, 30MB/62MB, paused 1.677ms total 70.909ms
D/Weather.Utils( 7420): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7420): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7420): 2 : This is isUpdating : false
D/WeatherAncestor( 7420): connectivity changed - connection : true
D/WeatherService( 7420): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@314d6a48
V/DownloadManager( 3377): DownloadService onDestroy
W/Settings( 7313): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ForecastDataCache( 7420): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7420): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7420): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7420): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7420): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:12:56
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{22ac6da2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
W/Kids    ( 2328): [AccountUtils] Account not ready
W/Kids    ( 2328): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2328): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2328): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2328): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2328): 	at java.lang.Thread.run(Thread.java:818)
V/FormManager( 7357): There are no updated forms. The schedule will be deleted.
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
,V/FormManager( 7357): Alarm would be updated, because LastCheckTime has been updated.
D/UEI.SmartControl( 6748): Internal timer expired: 4
D/UEI.SmartControl( 6748): unbind internal service
D/ChimeraCfgMgr( 2328): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PowerManagerServiceEx( 1040): releaseWakeLockInternal: lock=463241613 [*alarm*], flags=0x0
D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = mtalk.google.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{22ac6da2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  317): res_queryN name = mtalk.google.com succeed
,V/NotificationService( 1040): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1040): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1040): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1040): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1040): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2328): [AccountUtils] Account not ready
W/Kids    ( 2328): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2328): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2328): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2328): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2328): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2328): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2328): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{22ac6da2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/serial_port( 6748): close(fd = 24)
,I/UEI.SmartControl( 6748): Serial port is closed.
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  317): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  317): res_queryN name = www.google.com succeed
,D/libc-netbsd(  317): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  317): res_queryN name = clients3.google.com, class = 1, type = 1
,D/libc-netbsd(  317): res_queryN name = clients3.google.com succeed
D/GCM     ( 2128): Connected
,D/sensors_hal_Time( 1040): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1040): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1040): tsOffsetIs: Apps: 297615835252; DSPS: 9893148; Offset : -4313282285
,V/WifiInternetCheck( 1040): isHttpConnectionAvailable - We got a valid response : 204
D/GCM     ( 2128): Message class com.google.f.a.a.p
,D/PowerManagerServiceEx( 1040): acquireWakeLockInternal: lock=463241613, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1040
D/[Concierge]Service( 2643): onStartCommand(). Type : 9
I/[SystemUI]TimeTickManager( 1469): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1469): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1469): called onTimeUpdated()
I/[SystemUI]Clock( 1469): called onTimeUpdated()
I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
V/QRemote ( 7168): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7168): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4423

```
