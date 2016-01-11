#### Test 549702617cfd775_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/[SystemUI]Clock( 1469): called onTimeUpdated()
I/LgeClockWidgetControlView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
I/[SystemUI]DateView( 1469): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1469): handleTimeUpdate
,D/AndroidRuntime( 7022): 
D/AndroidRuntime( 7022): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7022): CheckJNI is OFF
D/AndroidRuntime( 7022): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1970): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{3a89056d #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{3a89056d #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  345): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7042 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7022): Shutting down VM
V/ActivityManager( 1038): Display changed displayId=0
D/DSDPConnection( 1873): Display #0 changed.
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{26fdc471 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{c4d4256 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7042): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7042): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7042): Loading: webviewchromium
I/LibraryLoader( 7042): Time to load native libraries: 5 ms (timestamps 3778-3783)
,I/LibraryLoader( 7042): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7042): Binding Chromium to main looper Looper (main, tid 1) {35710061}
I/LibraryLoader( 7042): Expected native library version number "",actual native library version number ""
I/chromium( 7042): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7042): Initializing chromium process, renderers=0
,W/art     ( 7042): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7042): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,V/AudioPolicyService(  329): registerClient() client 0xb15231c0, uid 10311
I/chromium( 7042): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7042): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e96e8f:true
I/Adreno-EGL( 7042): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7042): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7042): Build Date: 12/12/14 금
I/Adreno-EGL( 7042): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7042): Remote Branch: 
I/Adreno-EGL( 7042): Local Patches: 
I/Adreno-EGL( 7042): Reconstruct Branch: 
,W/chromium( 7042): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7042): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7042): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7042): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7042): CordovaWebView is running on device made by: LGE
,W/art     ( 7042): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7042): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7042): Render dirty regions requested: true
I/OpenGLRenderer( 7042): Initialized EGL, version 1.4
D/OpenGLRenderer( 7042): Enabling debug mode 0
,D/Atlas   ( 7042): Validating map...
,D/SplitWindow( 1038): check instance of lgWin Window{1d071211 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/ActivityManager( 1038): Activity pause timeout for ActivityRecord{b4cb5a2 u0 com.test.thalitest/.MainActivity t4}
,D/LgDataFeature( 7042): LgDataFeature() Constructor: none
,D/LgDataFeature( 7042): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1469): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@31282935,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1469): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1469):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1469): , Keyguard show=false, IME shown=false, Panel expanded=false
,I/ActivityManager( 1038): Displayed com.test.thalitest/.MainActivity: +647ms (total +727ms)
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{b4cb5a2 u0 com.test.thalitest/.MainActivity t4} time:284234
I/Timeline( 7042): Timeline: Activity_idle id: android.os.BinderProxy@3e9c3d1 time:284238
D/JsMessageQueue( 7042): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7042): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7042): 
,D/jxcore_app_log( 7042): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435052800
D/JX-Cordova( 7042): jxcore cordova android initializing
,I/chromium( 7042): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7042): 
E/GBMv2   (  345): DFP En is all cleared set to be enabled
E/GBMv2   (  345): Set value is all cleared set the max
I/GBMv2   (  345): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7042): Initializing JXcore engine
W/jxcore-log( 7042): JXcore engine is ready
W/jxcore-log( 7042): Starting JXcore engine
W/.test.thalitest( 7042): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10384]" dev="sockfs" ino=10384 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7042): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7042): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9898]" dev="sockfs" ino=9898 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7042): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7042): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33767]" dev="sockfs" ino=33767 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7042): Platform android
W/jxcore-log( 7042): 
W/jxcore-log( 7042): Process ARCH arm
W/jxcore-log( 7042): 
I/jxcore-log( 7042): JXcore Cordova bridge is ready!
I/jxcore-log( 7042): 
W/jxcore-log( 7042): JXcore engine is started
I/Choreographer( 7042): Skipped 124 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 7042): Toggling radios to true
I/jxcore-log( 7042): 
D/BluetoothAdapter( 7042): enable(): BT is already enabled..!
D/WifiService( 1038): New client listening to asynchronous messages
D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=7042, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: true pid=7042, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1038): disconnect pid=7042, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1038): [286,794,836 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1038): reconnect pid=7042, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7042): Radios toggled
I/jxcore-log( 7042): 
I/jxcore-log( 7042): My device name is: LGE-LG-D855
I/jxcore-log( 7042): 
I/wpa_supplicant( 2732): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038): DISCONNECT: returned true
D/Tethering( 1038): InitialState.processMessage what=4
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2732): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/CommandListener(  325): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1038): RunningState{ when=-6ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2142): Read error: ssl=0xaf4d5e00: I/O error during system call, Connection timed out
V/NativeCrypto( 2142): SSL shutdown failed: ssl=0xaf4d5e00: I/O error during system call, Broken pipe
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/art     (  360): Background concurrent mark sweep GC freed 808(34KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 5.257ms total 31.945ms
I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7139 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
E/WifiStateMachine( 1038): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1038):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1038): [286,924,917 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
I/wpa_supplicant( 2732): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1038): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1970): handleWifiStateChangedEvent: 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1038): RECONNECT: returned true
E/WifiStateMachine( 1038):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=286945
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=286946
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2732): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/CommandListener(  325): Clearing all IP addresses on wlan0
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=286973  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=286973  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/DSQN    ( 1038): Dns fail occured do internet check.
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/DSQN    ( 1038): EVENT_INTERNET_CHECK_REQUEST received
D/DSQN    ( 1038): try Internet connection check
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=286986  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1038): hidePasspointNotification off =false
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/DSQN    ( 1038): ThreadTCPConnectionCheck DNS fail internet is not possible
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=286989  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/DSQN    ( 1038): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1038): L3_DATA_SERVICE_QUALITY STATUS 0 DataEnabled: false
W/ContextImpl( 1038): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 com.android.server.DataServiceQualityMonitor.sendDSqualityIntent:1103 com.android.server.DataServiceQualityMonitor.access$200:55 com.android.server.DataServiceQualityMonitor$ThreadInternetCheck.run:921 <bottom of call stack> 
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524292
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
D/WifiDataContinuityService( 1038): L3_DATA_SERVICE_QUALITY_ACTION, resultStatus : 0
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1038): Removing idletimer
D/TelephonyNetworkFactory-1( 1873): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1038): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WifiServiceExtension( 1970): isInternetCheckAvailable return false
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
W/ResourcesManager( 7139): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7139): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7139): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7139): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7139): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7139): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-129ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7139): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7139): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7139): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7139): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7139): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7139): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7139): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7139): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7139): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7139): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7139): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7176 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6623:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10008/pid_6623/cgroup.procs: No such file or directory
,I/PCSuite ( 7176): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7176): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7176): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7139): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7139): LgDataFeature() Constructor: none
D/LgDataFeature( 7139): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7139): MCCMNC not supported: null
,I/ActivityManager( 1038): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7198 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1038): Killing 6180:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/art     (  360): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 309us total 15.392ms
,I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 296us total 13.136ms
,I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 249us total 12.032ms
,W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_6180/cgroup.procs: No such file or directory
,W/ResourcesManager( 7198): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7198): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7198): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7198): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7198): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7198): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7198): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7198): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 7198): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7198): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7198): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7198): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 7198): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7198): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/PCSuite ( 7176): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7176): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7176): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7139): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7139): MCCMNC not supported: null
,D/QRemote ( 7198): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7198): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7198): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7176): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7176): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7176): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7139): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7139): MCCMNC not supported: null
D/QRemote ( 7198): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7198): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7198): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7176): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7176): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7176): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7139): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7139): MCCMNC not supported: null
D/QRemote ( 7198): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7198): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7198): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7139): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7139): MCCMNC not supported: null
D/QRemote ( 7198): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7198): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7198): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7198): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7198): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7198): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7198): LgDataFeature() Constructor: none
,D/LgDataFeature( 7198): LgDataFeature() Constructor Done, null
V/SoundPool( 7198): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7198): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7198): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7198): doLoad: loading sample sampleID=1
I/QRemote ( 7198): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/DSQN    ( 1038): EVENT_INTERNET_CHECK_ENABLE received
V/SoundPool( 7198): Start decode
V/MediaPlayer[Native]( 7198): decode(31, 10857164, 17813)
D/QRemote ( 7198): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/UEI.SmartControl( 6760): QS Service created
V/MediaPlayerService(  329): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  329): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  329): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  329): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  329): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  329): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  329): player type = 3
V/AwesomePlayer(  329): AwesomePlayer create()
V/AwesomePlayer(  329): reset_l() 
V/AwesomePlayer(  329): cancelPlayerEvents
V/AwesomePlayer(  329): setAudioSink() 
V/AwesomePlayer(  329): reset_l() 
V/AudioCache(  329): notify(0xb11638c0, 8, 0, 0)
V/AudioCache(  329): ignored
V/AwesomePlayer(  329): cancelPlayerEvents
D/Utils   (  329): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  329): setDataSource_l dataSource
V/LGParserOSAL(  329): SniffLGParser start
V/LGParserOSAL(  329): MainType:5, SubType=0
V/LGParserOSAL(  329): #### check Mime : application/ogg
V/LGParserOSAL(  329): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  329): Use LGExtractor :application/ogg 
E/QRemote ( 7198): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7198): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGMDMManager( 7198): Create singleton instance
V/LGParserOSAL(  329): supported mime: application/ogg
V/AwesomePlayer(  329): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  329): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  329): mBitrate = -1 bits/sec
V/AwesomePlayer(  329): AudioTrack Setting
V/AwesomePlayer(  329): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  329): setAudioSource() 
V/MediaPlayerService(  329): prepare
V/AwesomePlayer(  329): prepareAsync_l() 
V/MediaPlayerService(  329): wait for prepare
,V/AwesomePlayer(  329): onPrepareAsyncEvent() 
V/AwesomePlayer(  329): initAudioDecoder() 
W/Utils   (  329): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  329): isOffloadSupported()
V/AudioPolicyManager(  329): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,D/AudioPolicyManager(  329): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  329): isAudioPlaybackHookOn() false
V/AwesomePlayer(  329): getUseOffload() = 0 
V/OMXCodec(  329): OMXCodec::Create
V/OMXCodec(  329): findMatchingCodecs()
V/OMXCodec(  329): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  329): matchingCodecs.size()=1
V/OMXCodec(  329): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/UEI.SmartControl( 6760): Service initServices...
,D/UEI.SmartControl( 6760): QS start get config
D/OMXCodec(  329): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  329): LG Codec Adapter start
V/OMXCodec(  329): OMXCodec Createtor
V/OMXCodec(  329): setComponentRole
V/OMXCodec(  329): configureCodec protected=0
V/LGCodecAdapter(  329): called getLGCodecSpecificData
V/LGCodecOSAL(  329): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  329): Called LGconfigureCodecMETA
V/LGCodecOSAL(  329): Called LGconfigureCodecMSG
V/LGCodecOSAL(  329): Not support LGCodec
V/OMXCodec(  329): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  329): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  329): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  329): Could not offload audio decode, try pcm offload
W/Utils   (  329): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  329): isOffloadSupported()
V/AudioPolicyManager(  329): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  329): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  329): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  329): init()
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  329): allocateBuffers
V/OMXCodec(  329): allocateBuffersOnPort portIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on input port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on input port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1434790 on input port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1434830 on input port
V/OMXCodec(  329): allocateBuffersOnPort portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1434880 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1434e70 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1434f10 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb15270b0 on output port
V/OMXCodec(  329): init() mAsyncCompletion wait!!! 
V/OMXCodec(  329): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  329): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
,V/OMXCodec(  329): init() mAsyncCompletion wait free! ,
V/AwesomePlayer(  329): finishAsyncPrepare_l() 
V/AudioCache(  329): notify(0xb11638c0, 5, 0, 0)
V/AudioCache(  329): ignored
V/AudioCache(  329): notify(0xb11638c0, 1, 0, 0)
V/AudioCache(  329): prepared
V/AudioCache(  329): wait - success
V/MediaPlayerService(  329): start
V/AwesomePlayer(  329): play_l() 
V/AwesomePlayer(  329): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  329): createAudioPlayer_l
V/AwesomePlayer(  329): seekAudioIfNecessary_l() 
V/AwesomePlayer(  329): startAudioPlayer_l() 
D/AudioPlayer(  329): start of Playback, useOffload 0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
,V/OMXCodec(  329): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  329): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  329): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976704
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,V/OMXCodec(  329): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973978224
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973978384
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974970032
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  329): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  329): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  329): allocateBuffersOnPort portIndex=1
,V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1434f10 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1434e70 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1434880 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] allocated buffer 0xb1003fb0 on output port
V/OMXCodec(  329): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  329): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  329): notify(0xb11638c0, 6, 0, 0)
V/AudioCache(  329): ignored
V/MediaPlayerService(  329): wait for playback complete
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae804000, 0xb57fa000, 4096)
,V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae805000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae806000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae807000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae808000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae809000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae80a000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
,V/AudioCache(  329): memcpy(0xae80b000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae80c000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae80d000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae80e000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae80f000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae810000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae811000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
,V/AudioCache(  329): memcpy(0xae812000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae813000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae814000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae815000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae816000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae817000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae818000, 0xb57fa000, 4096)
,V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae819000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae81a000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae81b000, 0xb57fa000, 4096)
,V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae81c000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae81d000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae81e000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
,V/AudioCache(  329): memcpy(0xae81f000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae820000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae821000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae822000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae823000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae824000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae825000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae826000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae827000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae828000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae829000, 0xb57fa000, 4096)
,V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae82a000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae82b000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae82c000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae82d000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae82e000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae82f000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae830000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae831000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae832000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae833000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae834000, 0xb57fa000, 4096)
V/AudioCache(  329): write(0xb57fa000, 4096)
V/AudioCache(  329): memcpy(0xae835000, 0xb57fa000, 4096)
V/OMXCodec(  329): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  329): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  329): postAudioEOS() 
V/AudioCache(  329): write(0xb57fa000, 280)
V/AudioCache(  329): memcpy(0xae836000, 0xb57fa000, 280)
V/AwesomePlayer(  329): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  329): onStreamDone
V/AwesomePlayer(  329): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  329): notify(0xb11638c0, 2, 0, 0)
V/AudioCache(  329): playback complete
V/AwesomePlayer(  329): pause_l() 
V/AudioCache(  329): notify(0xb11638c0, 7, 0, 0)
V/AudioCache(  329): ignored
V/AwesomePlayer(  329): cancelPlayerEvents
V/AudioCache(  329): wait - success
V/MediaPlayerService(  329): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  329): Pause Playback at 1068125
,V/AwesomePlayer(  329): reset_l() 
V/AudioCache(  329): notify(0xb11638c0, 8, 0, 0)
V/AudioCache(  329): ignored
V/AwesomePlayer(  329): cancelPlayerEvents
D/AudioPlayer(  329): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  329): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  329): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  329): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb1434830 on port 0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
,V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb1434790 on port 0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
,V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb1434740 on port 0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
,V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb14346f0 on port 0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb1003fb0 on port 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
D/QRemote ( 7198): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb1434880 on port 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb1434e70 on port 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeing buffer 0xb1434f10 on port 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  329): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  329): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  329): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  329): AudioPlayer releasing audio source
D/AudioPlayer(  329): AudioPlayer done releasing audio source
V/AwesomePlayer(  329): reset_l() 
V/AwesomePlayer(  329): cancelPlayerEvents
V/AwesomePlayer(  329): ~AwesomePlayer call
V/AwesomePlayer(  329): reset_l() 
V/AwesomePlayer(  329): cancelPlayerEvents
V/SoundPool( 7198): close(31)
V/SoundPool( 7198): pointer = 0x9ffb9000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7198): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7198): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2240
I/UEI.SmartControl( 6760): Supports setup maps: true
D/UEI.SmartControl( 6760): QS start statue = true Error code = 0
I/UEI.SmartControl( 6760): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6760): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6760): ### init IR Blaster...
,D/serial_port( 6760): Configuring serial port
,E/UEI.SmartControl( 6760): UEIBLaster setting for 616
I/UEI.SmartControl( 6760): Setting serial record hearder size = 2
I/UEI.SmartControl( 6760): configuring settings for MAXQ616
,I/UEI.SmartControl( 6760): Get version...
D/UEI.SmartControl( 6760): serial port data available: 21
,D/UEI.SmartControl( 6760): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6760): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6760): QS saving settings...
D/UEI.SmartControl( 6760): IR Blaster version: 25672567
,D/UEI.SmartControl( 6760): serial port data available: 4
,I/UEI.SmartControl( 6760): Device manager: loading config....
D/UEI.SmartControl( 6760): ----------- loading internal config...
W/ContextImpl( 6760): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6760): Services init done
D/UEI.SmartControl( 6760): QS Service init finished
,D/UEI.SmartControl( 6760): QS Service version name: 2.1.91
D/UEI.SmartControl( 6760): QS Service version code: 201091
D/UEI.SmartControl( 6760): Service requested: Control
E/UEI.SmartControl( 6760): Loading SETTINGS...
D/UEI.SmartControl( 6760): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6760): Internal service binding...
I/QRemote ( 7198): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6760): ------ IControl API: 11
D/UEI.SmartControl( 6760): File observer start...
E/UEI.SmartControl( 6760): IR Port is disabled: false
D/UEI.SmartControl( 6760): Starting file observer...
,I/UEI.SmartControl( 6760): Registering callback...
I/UEI.SmartControl( 6760): ------ IControl API: 19
I/UEI.SmartControl( 6760): Registering Services Ready callback...
D/UEI.SmartControl( 6760): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6760): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6760): -----service ready thread exits
I/QRemote ( 7198): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7198): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7198): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7198): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7198): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6760): ------ IControl API: 8
,D/QRemote ( 7198): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,D/QRemote ( 7198): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7198): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7198): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7198): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7198): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7198): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7198): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7198): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7198): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7198): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7198): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7198): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7198): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7198): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452521107962]
D/QRemote ( 7198): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1038): Killing 6200:com.android.contacts/u0a19 (adj 15): empty #17
,D/QRemote ( 7198): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1038): failed to open /acct/uid_10019/pid_6200/cgroup.procs: No such file or directory
,V/QRemote ( 7198): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7198): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7198): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7198): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7198): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7198): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7198): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7198): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2732): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=289063  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=289078  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 7139): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7139): MCCMNC not supported: null
D/QRemote ( 7198): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7198): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7198): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7139): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7139): MCCMNC not supported: null
I/wpa_supplicant( 2732): wlan0: Associated with c0:ff:d4:d3:aa:48
D/QRemote ( 7198): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/QRemote ( 7198): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=289161  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=289161  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
I/QRemote ( 7198): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1038):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289161
E/WifiStateMachine( 1038):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289161
E/WifiStateMachine( 1038):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289162
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289162
E/WifiStateMachine( 1038):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=289162
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=289162  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 2732): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2732): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1038): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1038): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1038): sendTetherStateChangedBroadcast 1, 0, 0
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=289173  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=289173  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=289173  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=289174
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=289174
D/WifiNative-wlan0( 1038): doString: [STATUS]
D/WifiNative-wlan0( 1038):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/WifiServiceExtension( 1038): setVHTCapabilityType  : false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATED
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
V/WiFiOffLoadBroadcast( 7139): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1038): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1038): setKeepAlivePacketInterval msec : 60
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7139): MCCMNC not supported: null
D/ConnectivityService( 1038): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1038): Got NetworkAgent Messenger
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1038): NetworkAgent connected
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/QRemote ( 7198): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7198): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7198): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/UsbSettingsReceiver( 7139): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7139): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7139): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7139): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7139): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/UsbSettingsControl( 7139): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7139): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7139): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7139): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7139): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7139): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7139): [AUTORUN] setTetherStatus() : status=false
D/CommandListener(  325): Setting iface cfg
E/WifiStateMachine( 1038): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1038): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState
D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289208  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289209  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=289210  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
V/WiFiOffLoadBroadcast( 7139): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateGROUP_HANDSHAKE
,E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289216  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289216  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=289216  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 7139): MCCMNC not supported: null
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 7198): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7198): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7198): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 0
D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7139): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7139): MCCMNC not supported: null
D/QRemote ( 7198): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7198): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7198): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7139): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7139): MCCMNC not supported: null
D/QRemote ( 7198): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7198): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7198): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2732): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 0
D/WifiNative-wlan0( 1038): SET ps 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2732): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1038): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@ce2dcd4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@ce2dcd4 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1038): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): DHCP Start wake lock is acquired.
D/CommandListener(  325): Setting iface cfg
D/CommandListener(  325): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1038): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
E/WifiStateMachine( 1038):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2732): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2732): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1038): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System t,o android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService( 1038): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1469): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1038): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
V/WfdStateTracker( 1970): handleWifiStateChangedEvent: 1
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1038): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1038): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1038): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  325): netlink response contains error (File exists)
D/ConnectivityService( 1038): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1038): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1038): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1038): Setting Dns servers for network 101 to [/192.168.1.1]
V/WiFiOffLoadBroadcast( 7139): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1038): currentScore = 0, newScore = 20
D/ConnectivityService( 1038):    accepting network in place of null
D/ConnectivityService( 1038): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Connected
D/TelephonyNetworkFactory-1( 1873): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1038): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1038): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for l,egacy network type 1
D/CSLegacyTypeTracker( 1038): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1038): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1038): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1038): validation of new default Network = false
D/ConnectivityService( 1038): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1038): enableDataServiceNotify 
D/DSQN    ( 1038): start dsqn bin
D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = clients3.google.com, class = 1, type = 1
D/LocSvc_java( 1038): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
I/StatusBar.NetworkController( 1469): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1469): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524290
W/dsqn    ( 7261): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7261): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/NetworkPolicy( 1038): [LG_RESTRICTED] checkMobilePolicy_type()
E/DSQN    ( 7261): DSQN ssw
D/WiFiOffLoadBroadcast( 7139): MCCMNC not supported: null
D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
D/QRemote ( 7198): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7198): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 7198): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7139): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7139): MCCMNC not supported: null
D/QRemote ( 7198): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7198): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7198): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7176): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/libc-netbsd(  325): res_queryN name = clients3.google.com succeed
D/PCSuite ( 7176): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7139): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7139): MCCMNC not supported: null
,D/QRemote ( 7198): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7198): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7198): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7198): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7198): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  325): argv[0]=dsqncommand
D/LGDataListener(  325): argv[1]=wlan0
D/LGDataListener(  325): argv[2]=1
D/LGDataListener(  325): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1038): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1038): start to monitor internet connection
D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7176): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7176): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7139): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7139): MCCMNC not supported: null
D/QRemote ( 7198): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7198): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7198): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7198): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7198): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 14:05:08 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452521108852], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452521108832]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Validated
D/ConnectivityService( 1038): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1873): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524290
D/TelephonyIcons( 1469): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1469): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1038): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1038): [bssid] hash key :c0:ff:d4:d3:aa:48
,D/LgDhcpStateMachineHelper( 1038): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7267): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7267): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6815 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7267): version 5.5.6 starting
E/dhcpcd  ( 7267): get_duid: m
D/dhcpcd  ( 7267): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7267): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/dhcpcd  ( 7267): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7267): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7267): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7267): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7267): wlan0: sending REQUEST (xid 0x64960cb0), next in 4.20 seconds
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=487768736, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{294680d6 type 2 when 289861 com.google.android.gms} when 289861
,D/[Concierge]Service( 2637): onStartCommand(). Type : 9
,D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  325): res_queryN name = mtalk.google.com, class = 1, type = 1
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=487768736 [*alarm*], flags=0x0
,D/libc-netbsd(  325): res_queryN name = mtalk.google.com succeed
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6596): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5946): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5946): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7295 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7295): onCreate
,W/AppUp4:DB( 7295):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7295):  setFingerPrint start
I/AppUp4:DB( 7295):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7295):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 7295):  SDK version = 21
I/AppUp4:DB( 7295):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7295): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7295): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7295): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7295): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7295): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7295): onReceive
D/LgDataFeature( 7295): LgDataFeature() Constructor: none
D/LgDataFeature( 7295): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7295): Context : android.app.ReceiverRestrictedContext@38d19847
D/AppUp4:CustFacade( 7295): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7295): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7295): begin check event
I/AppUp4:CustModeStarterReceiver( 7295): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7295): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7295): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7295): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7295): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1038): Killing 6648:com.lge.email/u0a23 (adj 15): empty #17
D/GCM     ( 2142): Connected
,D/LGDMClient( 4356): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4356): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_6648/cgroup.procs: No such file or directory
W/ContextImpl( 4356): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/GCM     ( 2142): Message class com.google.f.a.a.p
W/ContextImpl( 4356): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3375): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4356): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,V/DownloadManager( 3375): DownloadService onCreate
I/LGDMClient( 4356): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3375): in removeSpuriousFiles
D/LGDMClient( 4356): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4356): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3375): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@352f023b on behalf of 3375
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3375): in trimDatabase
V/DownloadManager( 3375): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@ad17eb1 on behalf of 3375
,I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7326 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 4356): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3375): DownloadService onStartCommand
E/LGDMClient( 4356): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3375): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@18018717 on behalf of 3375
V/DownloadManager( 3375): processing inserted download 1
V/DownloadManager( 3375): processing inserted download 4
V/DownloadManager( 3375): processing inserted download 7
V/DownloadManager( 3375): processing inserted download 8
,D/LGDMClient( 4356): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3375): processing inserted download 9
D/LGDMClient( 4356): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3375): processing inserted download 10
V/DownloadManager( 3375): processing inserted download 16
V/DownloadManager( 3375): processing inserted download 17
V/DownloadManager( 3375): processing inserted download 18
V/DownloadManager( 3375): processing inserted download 21
V/DownloadManager( 3375): DownloadService onDestroy
,W/ResourcesManager( 7326): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7326): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7326): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7326): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 7326): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7326): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7326): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7326): LgDataFeature() Constructor: none
D/LgDataFeature( 7326): LgDataFeature() Constructor Done, null
,D/eas_req ( 7326): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7354 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7326): JNI_OnLoad()
I/HubEmail( 7326): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7326): registerNatives()
I/HubEmail( 7326): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7326): registerNativeMethods()
I/HubEmail( 7326): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7326): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1038): Killing 6226:com.android.gallery3d/u0a27 (adj 15): empty #17
E/WifiStateMachine( 1038):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1038): identical MTU - not setting
I/dhcpcd  ( 7267): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1469): CM callback handler got msg 524295
,W/libprocessgroup( 1038): failed to open /acct/uid_10027/pid_6226/cgroup.procs: No such file or directory
,W/Settings( 7326): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7326): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/dhcpcd  ( 7267): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7267): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7267): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7267): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7267): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7267): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7267): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7267): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/LgeMiscReceiver( 3334): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3334): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3334): networkInfo.isConnected() = false
,I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7391 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1038): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7422 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6550:com.android.defcontainer/u0a4 (adj 15): empty #17
D/DhcpStateMachine( 1038): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1038): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper( 1038): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1038): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): bShouldSendDhcpAction Result: false
,D/DhcpStateMachine( 1038): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1038): RunningState
W/libprocessgroup( 1038): failed to open /acct/uid_10004/pid_6550/cgroup.procs: No such file or directory
,D/libc-netbsd(  325): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7443 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6679:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6679/cgroup.procs: No such file or directory
,V/FormManager( 7354): There are no updated forms. The schedule will be deleted.
V/FormManager( 7354): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1038): Killing 6720:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
I/art     ( 7443): Almond Protected OAT
,W/libprocessgroup( 1038): failed to open /acct/uid_10080/pid_6720/cgroup.procs: No such file or directory
,D/WeatherApplication( 7443): removeAccount
D/WeatherApplication( 7443): Account.length = 0
E/WeatherApplication( 7443): OPERATOR:OPEN
D/WeatherAncestor( 7443): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:5:11
,D/Weather.Utils( 7443): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7443): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7443): 2 : This is isUpdating : false
D/WeatherAncestor( 7443): connectivity changed - connection : true
D/WeatherService( 7443): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7443): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7443): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7443): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7443): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7443): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:5:11
I/ActivityManager( 1038): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7462 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6793:com.lge.eula/1000 (adj 15): empty #17
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1038):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6793/cgroup.procs: No such file or directory
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7462): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7462): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7462): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7462): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1038): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5946): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 7462): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7462): Loading: webviewchromium
I/LibraryLoader( 7462): Time to load native libraries: 4 ms (timestamps 2452-2456)
I/LibraryLoader( 7462): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7462): Binding Chromium to main looper Looper (main, tid 1) {dccde0e}
I/LibraryLoader( 7462): Expected native library version number "",actual native library version number ""
I/chromium( 7462): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7462): Initializing chromium process, renderers=0
,W/art     ( 7462): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  329): registerClient() client 0xb1523200, uid 10093
W/chromium( 7462): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
W/AudioManagerAndroid( 7462): Requires BLUETOOTH permission
I/chromium( 7462): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7462): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,I/Adreno-EGL( 7462): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7462): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7462): Build Date: 12/12/14 금
I/Adreno-EGL( 7462): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7462): Remote Branch: 
I/Adreno-EGL( 7462): Local Patches: 
I/Adreno-EGL( 7462): Reconstruct Branch: 
,I/NSApplication( 7462): Starting up...
,I/ActivityManager( 1038): Killing 6815:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6815/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2331): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6596): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/ChimeraCfgMgr( 2331): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/NetworkStateForAutoUpdateMonitor( 7295): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7295): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7295): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7295): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7295): onReceive
,D/AppUp4:CustFacade( 7295): Context : android.app.ReceiverRestrictedContext@38d19847
D/AppUp4:CustFacade( 7295): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7295): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7295): begin check event
I/AppUp4:CustModeStarterReceiver( 7295): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4356): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4356): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4356): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4356): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4356): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4356): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4356): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3375): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 4356): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3375): DownloadService onCreate
,W/ContextImpl( 4356): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4356): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4356): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4356): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3375): in removeSpuriousFiles
V/DownloadManager( 3375): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@24e54ed on behalf of 3375
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DownloadManager( 3375): in trimDatabase
V/DownloadManager( 3375): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@3d0d7db3 on behalf of 3375
V/DownloadManager( 3375): DownloadService onStartCommand
V/DownloadManager( 3375): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/LgeMiscReceiver( 3334): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3334): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3334): networkInfo.isConnected() = false
W/Settings( 7326): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7326): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WeatherAncestor( 7443): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:5:12
,D/Weather.Utils( 7443): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7443): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7443): 2 : This is isUpdating : false
D/WeatherAncestor( 7443): connectivity changed - connection : true
D/WeatherService( 7443): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@225c419d
D/ForecastDataCache( 7443): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7443): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7443): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7443): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7443): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:5:12
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
W/Kids    ( 2331): [AccountUtils] Account not ready
W/Kids    ( 2331): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2331): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2331): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2331): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2331): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2331): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2331): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2331): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2331): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2331): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2331): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2331): 	at java.lang.Thread.run(Thread.java:818)
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{31d8420f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/FormManager( 7354): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7354): Alarm would be updated, because LastCheckTime has been updated.
D/ChimeraCfgMgr( 2331): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6596): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7295): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7295): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7295): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7295): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7295): onReceive
D/AppUp4:CustFacade( 7295): Context : android.app.ReceiverRestrictedContext@38d19847
D/AppUp4:CustFacade( 7295): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7295): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7295): begin check event
I/AppUp4:CustModeStarterReceiver( 7295): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4356): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4356): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4356): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 86099(4MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.717ms total 132.555ms
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@2d4852e9 on behalf of 3375
V/DownloadManager( 3375): processing inserted download 1
V/DownloadManager( 3375): processing inserted download 4
V/DownloadManager( 3375): processing inserted download 7
V/DownloadManager( 3375): processing inserted download 8
V/DownloadManager( 3375): processing inserted download 9
V/DownloadManager( 3375): processing inserted download 10
W/ContextImpl( 4356): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3375): processing inserted download 16
V/DownloadManager( 3375): processing inserted download 17
V/DownloadManager( 3375): processing inserted download 18
V/DownloadManager( 3375): processing inserted download 21
I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/DownloadManager( 3375): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3375): DownloadService onDestroy
V/DownloadManager( 3375): DownloadService onCreate
V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DownloadManager( 3375): in removeSpuriousFiles
D/LGDMClient( 4356): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4356): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3375): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@1a447b6e on behalf of 3375
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
D/LGDMClient( 4356): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
D/LGDMClient( 4356): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,I/DownloadManager( 3375): in trimDatabase
V/DownloadManager( 3375): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@31d8420f on behalf of 3375
V/DownloadManager( 3375): DownloadService onStartCommand
V/DownloadManager( 3375): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@2ce0f02b on behalf of 3375
V/DownloadManager( 3375): processing inserted download 1
,V/DownloadManager( 3375): processing inserted download 4
V/DownloadManager( 3375): processing inserted download 7
W/Settings( 7326): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3375): processing inserted download 8
W/Settings( 7326): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3375): processing inserted download 9
V/DownloadManager( 3375): processing inserted download 10
V/DownloadManager( 3375): processing inserted download 16
V/DownloadManager( 3375): processing inserted download 17
V/DownloadManager( 3375): processing inserted download 18
V/DownloadManager( 3375): processing inserted download 21
W/ContextImpl( 4356): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4356): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LGDMClient( 4356): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4356): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3375): DownloadService onDestroy
W/Kids    ( 2331): [AccountUtils] Account not ready
W/Kids    ( 2331): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2331): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2331): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2331): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2331): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2331): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2331): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2331): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2331): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2331): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2331): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2331): 	at java.lang.Thread.run(Thread.java:818)
I/LgeMiscReceiver( 3334): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3334): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3334): networkInfo.isConnected() = true
D/PhoneState( 3334): setPdpRejectCasuse : false
W/ResourcesManager( 1418): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/WeatherAncestor( 7443): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:5:12
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/Weather.Utils( 7443): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7443): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7443): 2 : This is isUpdating : false
D/WeatherAncestor( 7443): connectivity changed - connection : true
D/WeatherService( 7443): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@225c419d
D/ForecastDataCache( 7443): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7443): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7443): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7443): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7443): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:5:12
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
,W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1418): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{31d8420f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/FormManager( 7354): There are no updated forms. The schedule will be deleted.
V/FormManager( 7354): Alarm would be updated, because LastCheckTime has been updated.
D/ChimeraCfgMgr( 2331): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
W/Kids    ( 2331): [AccountUtils] Account not ready
W/Kids    ( 2331): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2331): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2331): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2331): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2331): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2331): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2331): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2331): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2331): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2331): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2331): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2331): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{31d8420f V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6760): Internal timer expired: 4
D/UEI.SmartControl( 6760): unbind internal service
,D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = www.google.com, class = 1, type = 1
,D/serial_port( 6760): close(fd = 24)
,I/UEI.SmartControl( 6760): Serial port is closed.
,D/libc-netbsd(  325): res_queryN name = www.google.com succeed
,D/libc-netbsd(  325): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  325): res_queryN name = clients3.google.com, class = 1, type = 1
,D/libc-netbsd(  325): res_queryN name = clients3.google.com succeed
,V/WifiInternetCheck( 1038): isHttpConnectionAvailable - We got a valid response : 204
,I/jxcore-log( 7042): Test app app.js loaded
I/jxcore-log( 7042): 
,I/chromium( 7042): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7042): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 7042): --= Surplus to requirements =--
I/jxcore-log( 7042): 
I/jxcore-log( 7042): ****TEST TOOK:  ms ****
I/jxcore-log( 7042): 
I/jxcore-log( 7042): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7042): 
,D/AndroidRuntime( 7576): 
D/AndroidRuntime( 7576): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7576): CheckJNI is OFF
D/AndroidRuntime( 7576): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1038): Killing 7042:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,W/PackageSettings( 1038): Skipping PackageSetting{37dbd91f com.example.hello/10319} due to missing metadata
,I/WindowState( 1038): WIN DEATH: Window{1d071211 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1038): Client connection lost with reason: 4
D/InputDispatcher( 1038): Window went away: Window{1d071211 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1038):   Force finishing activity ActivityRecord{b4cb5a2 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  345): DFP En is all cleared set to be enabled
,I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1038):   Force finishing activity ActivityRecord{b4cb5a2 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1038): Duplicate finish request for ActivityRecord{b4cb5a2 u0 com.test.thalitest/.MainActivity t4 f}
,W/ActivityManager( 1038): Spurious death for ProcessRecord{e4fedc9 7042:com.test.thalitest/u0a311}, curProc for 7042: null
I/[LGHome]EVENT( 2088): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{2b9fa2d7 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
I/[LGHome]EVENT( 2088): [Launcher.java:903:onResume()]onResume
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{3fe007c4 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2088): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/KeyguardModel( 1469): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/GeofencerStateMachine( 1838): Ignoring removeGeofence because network location is disabled.
E/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI] [+] updateMediaPlayerInfo
,D/LIA_Service_RemotePackageHandler( 2047): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3740): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/InputReader( 1038): Reconfiguring input devices.  changes=0x00000010
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,D/PostponalbeReceiver( 6596): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,I/[LGHome]GBoardWebView( 2088): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1924): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3740): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2088): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,W/System.err( 4589): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4589): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4589): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4589): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4589): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4589): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4589): 	at android.os.Looper.loop(Looper.java:135)
,W/System.err( 4589): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4589): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4589): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4589): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4589): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/art     ( 4648): Explicit concurrent mark sweep GC freed 16116(915KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 302us total 127.658ms
I/[SystemUI]QSlideListController( 1469): onReceive = android.intent.action.PACKAGE_REMOVED
,D/administrator( 1038): Handling package changes for user 0
D/SplitUIManager( 1890): split_name #11 / not available #0
D/SplitUIService( 1890): removed split : 
,D/AppUp4:PreloadHelper( 7295): added Exclude : com.test.thalitest
I/ActivityManager( 1038): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7610 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]EVENT( 2088): [Launcher.java:1056:onResume()]onResume end
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
D/SplitUIManager( 1890): split_name #11 / not available #0
I/SplitUIService( 1890): split app #11
,I/ActivityManager( 1038): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7627 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2088): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1924): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3740): handleMessage: what(1000) actionID(0x1000004)
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1469): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
I/[LGHome]GBoardWebView( 2088): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/KeyguardModel( 1469): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ActivityManager( 1038): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3812): [BTUI] [-] updateMediaPlayerInfo
V/BoardContentProvider( 3740): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2088): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2088): , create_time: 1430558575574
I/GBoardWebViewUtils( 2088): , expire_time: 0
I/GBoardWebViewUtils( 2088): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2088): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2088): , display: false
I/GBoardWebViewUtils( 2088): , animation: false }
I/GBoardWebViewUtils( 2088): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2088): , create_time: 1430558575600
I/GBoardWebViewUtils( 2088): , expire_time: 0
I/GBoardWebViewUtils( 2088): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2088): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2088): , display: false
I/GBoardWebViewUtils( 2088): , animation: false }
I/GBoardWebViewUtils( 2088): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2088): , create_time: 1452175675684
I/GBoardWebViewUtils( 2088): , expire_time: 0
I/GBoardWebViewUtils( 2088): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2088): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2088): , display: false
I/GBoardWebViewUtils( 2088): , animation: false }
D/WallpaperManager( 2088): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@31282935,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/[LGHome]EVENT( 2088): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2088): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/LockScreenSettings( 7610): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/NotificationService( 1038): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1038): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1038): Receieved: android.intent.action.PACKAGE_REMOVED
W/ResourcesManager( 7627): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7627): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7627): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
D/PhoneStatusBar( 1469): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
D/TaskPersister( 1038): removeObsoleteFile: deleting file=4_task.xml
I/[SystemUI]NavigationThemeResource( 1469): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1469):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1469): , Keyguard show=false, IME shown=false, Panel expanded=false
W/ResourcesManager( 7627): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7627): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1469): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1469): createShortcutInfo...
D/KeyguardModel( 1469): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1469): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1469): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1469): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1469): createShortcutInfo...
D/KeyguardModel( 1469): handleShortcutListChanged...
D/KeyguardModel( 1469): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1469): createShortcutInfo...
,D/KeyguardModel( 1469): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1469): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1469): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourceType( 1469): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1469): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,I/[LGHome]EVENT( 2088): [Launcher.java:5349:onStop()]onStop
D/KeyguardModel( 1469): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1469): createShortcutInfo...
W/ResourcesManager( 1038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager( 1038): Killing 6843:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/ThermalEngine(  339): Thermal-Server: Thermal received msg from  override
,W/ResourceType( 1038): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/Thermal-Lib( 3197): Thermal-Lib-Client: Client request sent
I/art     ( 1038): Explicit concurrent mark sweep GC freed 23284(1518KB) AllocSpace objects, 5(464KB) LOS objects, 33% free, 44MB/66MB, paused 1.596ms total 245.443ms
,I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 7576): Shutting down VM
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/KeyguardModel( 1469): handleShortcutListChanged...
I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2088): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2088): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
W/libprocessgroup( 1038): failed to open /acct/uid_10005/pid_6843/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]EVENT( 2088): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{3f125756 u0 com.lge.launcher2/.Launcher t3} time:295519
I/[Concierge]WidgetView( 2088): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2637): onStartCommand(). Type : 8
D/[Concierge]Service( 2637): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2637): Update widget ID : 11
D/[Concierge]WidgetView( 2088): change position of spinner
I/SystemConfig( 7627): BUILD Country: EU
I/SystemConfig( 7627): BUILD Operator: OPEN
I/[Concierge]WidgetView( 2088): initWebView(). Time : 1452521114977
,D/[Concierge]Service( 2637): onStartCommand(). Type : 0
I/[Concierge]WebView( 2088): Return exist ConciergeWebView. Reuse : 811696613
D/[Concierge]WidgetView( 2088): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2088): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2088): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@d944a64
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2088): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2088): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2088): Widget kill message received. Destory myself. My : 1452520848476, New one : 1452521114977
,D/[Concierge]WidgetView( 2088): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2088): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/ActivityManager( 1038): Killing 6924:com.google.android.apps.books/u0a54 (adj 15): empty #17
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2088): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2088): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 2088): Timeline: Activity_idle id: android.os.BinderProxy@1aa927b8 time:295629
,W/libprocessgroup( 1038): failed to open /acct/uid_10054/pid_6924/cgroup.procs: No such file or directory
I/SystemConfig( 7627): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7627): existFile = false
I/SystemConfig( 7627): canReadFile = false
I/SystemConfig( 7627): systemFeature RCS result false
D/SystemConfig( 7627): refreshRcsSupport() :false
I/PackageChangeReceiver( 7326): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2164): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1038): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7652 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 7652): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7652): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7652): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7652): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 7652): Total System Memory = 2995761152
,I/chromium( 2088): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
D/SystemHelper( 7652): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1038): Killing 6286:com.android.vending/u0a44 (adj 15): empty #17
,I/GBoardtInterface( 2088): onReloaded()
,I/GBoardWebViewClient( 2088): onPageFinished url:file:///android_asset/www/main.html
D/LIA_Service_NativeEventReceiver( 2047): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2047): startLIAService() : Trying to start LIA service ...
W/libprocessgroup( 1038): failed to open /acct/uid_10044/pid_6286/cgroup.procs: No such file or directory
V/BoardContentProvider( 3740): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Service_LIAService( 2047): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
V/BoardContentProvider( 3740): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/PostponalbeReceiver( 6596): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,I/ActivityManager( 1038): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7674 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
D/ActionManagerService( 1924): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 3740): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3740): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1924): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3740): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3740): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3740): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3740): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3740): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2088): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2088): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2088): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2088): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/art     (  360): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 205us total 10.107ms
D/GBoardUriUtils( 2088): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2088): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay

```
