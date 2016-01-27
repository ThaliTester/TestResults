#### Test 568182540458528_thali03_LGE-LG-D855 Logs


```
--------- beginning of system
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2f2a8fad type 2 when 236492 android} when 236492
,--------- beginning of main
D/AndroidRuntime( 6969): 
D/AndroidRuntime( 6969): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6969): CheckJNI is OFF
D/AndroidRuntime( 6969): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1935): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{19b412e2 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{19b412e2 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  342): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6988 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6969): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1846): Display #0 changed.
D/SplitWindowPolicy( 1935): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1935): topRunningActivity=ActivityInfo{2be306cc co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1935): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1935): topRunningActivity=ActivityInfo{29843d15 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6988): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6988): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6988): Loading: webviewchromium
,I/LibraryLoader( 6988): Time to load native libraries: 6 ms (timestamps 5278-5284)
I/LibraryLoader( 6988): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6988): Binding Chromium to main looper Looper (main, tid 1) {e91e97c}
I/LibraryLoader( 6988): Expected native library version number "",actual native library version number ""
I/chromium( 6988): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6988): Initializing chromium process, renderers=0
,W/art     ( 6988): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  322): registerClient() client 0xb14fdaa0, uid 10311
,W/chromium( 6988): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6988): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6988): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6988): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6988): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6988): Build Date: 12/12/14 금
I/Adreno-EGL( 6988): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6988): Remote Branch: 
I/Adreno-EGL( 6988): Local Patches: 
I/Adreno-EGL( 6988): Reconstruct Branch: 
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 27241(1207KB) AllocSpace objects, 4(448KB) LOS objects, 33% free, 44MB/66MB, paused 1.710ms total 131.628ms
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@394ee0eb:true
W/chromium( 6988): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6988): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6988): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6988): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6988): CordovaWebView is running on device made by: LGE
W/art     ( 6988): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6988): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1037): Activity pause timeout for ActivityRecord{c391673 u0 com.test.thalitest/.MainActivity t4}
D/OpenGLRenderer( 6988): Render dirty regions requested: true
I/OpenGLRenderer( 6988): Initialized EGL, version 1.4
D/OpenGLRenderer( 6988): Enabling debug mode 0
D/Atlas   ( 6988): Validating map...
D/SplitWindow( 1037): check instance of lgWin Window{2d37b8b6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1468): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1468): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1468):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1468): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@8d44869,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LgDataFeature( 6988): LgDataFeature() Constructor: none
D/LgDataFeature( 6988): LgDataFeature() Constructor Done, null
I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +643ms (total +741ms)
I/Timeline( 6988): Timeline: Activity_idle id: android.os.BinderProxy@e0a9ac time:275716
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{c391673 u0 com.test.thalitest/.MainActivity t4} time:275718
D/JsMessageQueue( 6988): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6988): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435090176
I/chromium( 6988): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6988): 
I/chromium( 6988): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/chromium( 6988): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6988): 
E/GBMv2   (  342): DFP En is all cleared set to be enabled
,E/GBMv2   (  342): Set value is all cleared set the max
I/GBMv2   (  342): DFP Enabled. Ignore VFP set
W/jxcore-log( 6988): Initializing JXcore engine
W/jxcore-log( 6988): JXcore engine is ready
,W/Thread-814( 7050): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10263]" dev="sockfs" ino=10263 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-814( 7050): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-814( 7050): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8692]" dev="sockfs" ino=8692 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-814( 7050): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-814( 7050): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[34986]" dev="sockfs" ino=34986 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6988): Starting JXcore engine
,I/art     ( 6988): Background sticky concurrent mark sweep GC freed 132002(13MB) AllocSpace objects, 19(7MB) LOS objects, 28% free, 40MB/56MB, paused 933us total 126.676ms
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 277692683232; DSPS: 9240184; Offset : -4311165932
,W/jxcore-log( 6988): Platform android
W/jxcore-log( 6988): 
W/jxcore-log( 6988): Process ARCH arm
W/jxcore-log( 6988): 
I/jxcore-log( 6988): JXcore Cordova bridge is ready!
I/jxcore-log( 6988): 
W/jxcore-log( 6988): JXcore engine is started
,I/jxcore-log( 6988): Toggling radios to true
I/jxcore-log( 6988): 
,D/BluetoothAdapter( 6988): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
,D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=6988, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=6988, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=6988, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1037): [278,455,064 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1037): reconnect pid=6988, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6988): Radios toggled
I/jxcore-log( 6988): 
I/jxcore-log( 6988): My device name is: LGE-LG-D855
I/jxcore-log( 6988): 
I/wpa_supplicant( 2700): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/Tethering( 1037): InitialState.processMessage what=4
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037): DISCONNECT: returned true
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
,I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/DhcpStateMachine( 1037): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  318): Clearing all IP addresses on wlan0
V/NativeCrypto( 2066): Read error: ssl=0xaf498e00: I/O error during system call, Connection timed out
V/NativeCrypto( 2066): SSL shutdown failed: ssl=0xaf498e00: I/O error during system call, Broken pipe
,I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7069 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [278,570,241 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
I/wpa_supplicant( 2700): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): ignoring duplicate network state non-change
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
V/WfdStateTracker( 1935): handleWifiStateChangedEvent: 0
,D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1037): RECONNECT: returned true
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=278595
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=278595
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
,I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ResourcesManager( 7069): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7069): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 7069): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7069): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7069): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 7069): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/CommandListener(  318): Clearing all IP addresses on wlan0
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=0
D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): stop dsqn bin
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=278659  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=278660  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/WifiHS20( 1037): hidePasspointNotification off =false
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=278669  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524292
,D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
,D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=278678  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/NetworkManagementService( 1037): Removing idletimer
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1846): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
,D/TelephonyNetworkFactory-1( 1846):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
,D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1037): StoppedState
,D/DhcpStateMachine( 1037): StoppedState{ when=-185ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsReceiver( 7069): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7069): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7069): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7069): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7069): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7069): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7069): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7069): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7069): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7069): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7069): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7106 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6564:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10008/pid_6564/cgroup.procs: No such file or directory
,I/PCSuite ( 7106): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7106): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7106): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7069): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7069): LgDataFeature() Constructor: none
,D/LgDataFeature( 7069): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7069): MCCMNC not supported: null
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7127 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1037): Killing 6058:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_6058/cgroup.procs: No such file or directory
,W/ResourcesManager( 7127): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7127): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7127): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7127): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7127): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 7127): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7127): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7127): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7127): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7127): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7127): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7127): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7106): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7106): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7106): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7069): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 7127): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/WiFiOffLoadBroadcast( 7069): MCCMNC not supported: null
D/QRemote ( 7127): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/QRemote ( 7127): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7127): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7127): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7106): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7106): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7106): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7069): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7069): MCCMNC not supported: null
D/QRemote ( 7127): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7127): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7127): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7106): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7106): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7106): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7069): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7069): MCCMNC not supported: null
,D/QRemote ( 7127): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7127): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7127): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7069): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7069): MCCMNC not supported: null
D/QRemote ( 7127): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7127): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7127): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7127): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7127): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,D/QRemote ( 7127): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7127): LgDataFeature() Constructor: none
D/LgDataFeature( 7127): LgDataFeature() Constructor Done, null
,V/SoundPool( 7127): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7127): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7127): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7127): doLoad: loading sample sampleID=1
I/QRemote ( 7127): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/UEI.SmartControl( 6762): QS Service created
V/SoundPool( 7127): Start decode
V/MediaPlayer[Native]( 7127): decode(31, 10857164, 17813)
V/MediaPlayerService(  322): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  322): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  322): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  322): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  322): [FindUsePlayer] componentName = [9101]
D/QRemote ( 7127): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
W/MediaPlayerFactory(  322): [getPlayerType:fd] nType = 3
,V/MediaPlayerService(  322): player type = 3
V/AwesomePlayer(  322): AwesomePlayer create()
V/AwesomePlayer(  322): reset_l() 
V/AwesomePlayer(  322): cancelPlayerEvents
V/AwesomePlayer(  322): setAudioSink() 
V/AwesomePlayer(  322): reset_l() 
V/AudioCache(  322): notify(0xb5474b80, 8, 0, 0)
V/AudioCache(  322): ignored
,V/AwesomePlayer(  322): cancelPlayerEvents
D/Utils   (  322): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  322): setDataSource_l dataSource
V/LGParserOSAL(  322): SniffLGParser start
V/LGParserOSAL(  322): MainType:5, SubType=0
V/LGParserOSAL(  322): #### check Mime : application/ogg
V/LGParserOSAL(  322): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  322): Use LGExtractor :application/ogg 
I/UEI.SmartControl( 6762): Service initServices...
D/UEI.SmartControl( 6762): QS start get config
,E/QRemote ( 7127): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7127): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 7127): Create singleton instance
V/LGParserOSAL(  322): supported mime: application/ogg
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
V/LGCodecOSAL(  322): Not support LGCodec
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
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc0b0 on input port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on input port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  322): allocateBuffersOnPort portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port,
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcc90 on output port
V/OMXCodec(  322): init() mAsyncCompletion wait!!! 
V/OMXCodec(  322): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  322): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  322): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  322): finishAsyncPrepare_l() 
V/AudioCache(  322): notify(0xb5474b80, 5, 0, 0)
V/AudioCache(  322): ignored
V/AudioCache(  322): notify(0xb5474b80, 1, 0, 0)
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
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795904
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796144
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796944
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  322): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  322): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  322): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  322): allocateBuffersOnPort portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] allocated buffer 0xb174b150 on output port
V/OMXCodec(  322): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  322): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  322): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  322): notify(0xb5474b80, 6, 0, 0)
V/AudioCache(  322): ignored
V/MediaPlayerService(  322): wait for playback complete
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab602000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab603000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab604000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab605000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab606000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab607000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab608000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab609000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab60a000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab60b000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab60c000, 0xb57df000, 4096)
,V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab60d000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab60e000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab60f000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab610000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab611000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab612000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab613000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab614000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab615000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab616000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab617000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab618000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab619000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab61a000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab61b000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab61c000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab61d000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab61e000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab61f000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab620000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab621000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab622000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab623000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab624000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab625000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab626000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab627000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab628000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab629000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab62a000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab62b000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab62c000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab62d000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab62e000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab62f000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab630000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab631000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab632000, 0xb57df000, 4096)
V/AudioCache(  322): write(0xb57df000, 4096)
V/AudioCache(  322): memcpy(0xab633000, 0xb57df000, 4096)
V/OMXCodec(  322): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  322): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  322): postAudioEOS() 
V/AudioCache(  322): write(0xb57df000, 280)
V/AudioCache(  322): memcpy(0xab634000, 0xb57df000, 280)
V/AwesomePlayer(  322): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  322): onStreamDone
V/AwesomePlayer(  322): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  322): notify(0xb5474b80, 2, 0, 0)
V/AudioCache(  322): playback complete
V/AwesomePlayer(  322): pause_l() 
V/AudioCache(  322): notify(0xb5474b80, 7, 0, 0)
V/AudioCache(  322): ignored
V/AwesomePlayer(  322): cancelPlayerEvents
V/AudioCache(  322): wait - success
V/MediaPlayerService(  322): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  322): Pause Playback at 1068125
V/AwesomePlayer(  322): reset_l() 
V/AudioCache(  322): notify(0xb5474b80, 8, 0, 0)
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
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc0b0 on port 0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb174b150 on port 1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  322): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 1
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
V/SoundPool( 7127): close(31)
V/SoundPool( 7127): pointer = 0x9ffcc000, size = 205080, sampleRate = 48000, numChannels = 2
,D/QRemote ( 7127): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7127): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7127): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1044
,I/UEI.SmartControl( 6762): Supports setup maps: true
,D/UEI.SmartControl( 6762): QS start statue = true Error code = 0
I/UEI.SmartControl( 6762): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6762): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6762): ### init IR Blaster...
D/serial_port( 6762): Configuring serial port
E/UEI.SmartControl( 6762): UEIBLaster setting for 616
,I/UEI.SmartControl( 6762): Setting serial record hearder size = 2
I/UEI.SmartControl( 6762): configuring settings for MAXQ616
I/UEI.SmartControl( 6762): Get version...
D/UEI.SmartControl( 6762): serial port data available: 21
,D/UEI.SmartControl( 6762): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6762): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6762): QS saving settings...
D/UEI.SmartControl( 6762): IR Blaster version: 25672567
,D/UEI.SmartControl( 6762): serial port data available: 4
,W/ContextImpl( 6762): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
I/UEI.SmartControl( 6762): Device manager: loading config....
D/UEI.SmartControl( 6762): ----------- loading internal config...
,E/UEI.SmartControl( 6762): Services init done
D/UEI.SmartControl( 6762): QS Service init finished
D/UEI.SmartControl( 6762): QS Service version name: 2.1.91
D/UEI.SmartControl( 6762): QS Service version code: 201091
D/UEI.SmartControl( 6762): Service requested: Control
D/UEI.SmartControl( 6762): Request IControl service: devices are loaded...
E/UEI.SmartControl( 6762): Loading SETTINGS...
D/UEI.SmartControl( 6762): Internal service binding...
I/QRemote ( 7127): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,I/UEI.SmartControl( 6762): ------ IControl API: 11
D/UEI.SmartControl( 6762): File observer start...
E/UEI.SmartControl( 6762): IR Port is disabled: false
D/UEI.SmartControl( 6762): Starting file observer...
I/UEI.SmartControl( 6762): Registering callback...
I/UEI.SmartControl( 6762): ------ IControl API: 19
I/UEI.SmartControl( 6762): Registering Services Ready callback...
,D/UEI.SmartControl( 6762): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6762): Notify AllClients services are ready: 0
I/QRemote ( 7127): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 7127): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7127): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7127): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7127): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6762): ------ IControl API: 8
D/QRemote ( 7127): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7127): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7127): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7127): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/UEI.SmartControl( 6762): -----service ready thread exits
D/QRemote ( 7127): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7127): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7127): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7127): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 7127): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7127): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7127): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7127): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7127): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7127): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7127): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453857174894]
D/QRemote ( 7127): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1037): Killing 6079:com.android.contacts/u0a19 (adj 15): empty #17
D/QRemote ( 7127): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_6079/cgroup.procs: No such file or directory
,V/QRemote ( 7127): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7127): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7127): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7127): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7127): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7127): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7127): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7127): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2700): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
,W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=280622  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=280630  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7069): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7069): MCCMNC not supported: null
D/QRemote ( 7127): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7127): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7127): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7069): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7069): MCCMNC not supported: null
D/QRemote ( 7127): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7127): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7127): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2700): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=281087  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=281088  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281088
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281092
I/wpa_supplicant( 2700): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281093
I/wpa_supplicant( 2700): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281093
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=281093
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=281095  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=281097  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=281125  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=281131  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=281131
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=281132
D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7069): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1037): NetworkAgent connected
D/WiFiOffLoadBroadcast( 7069): MCCMNC not supported: null
,D/QRemote ( 7127): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7127): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7127): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7069): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/CommandListener(  318): Setting iface cfg
E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateFOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281208  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281209  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=281209  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 7069): MCCMNC not supported: null
E/WifiStateMachine( 1037):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281215  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 7127): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7127): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281215  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
I/QRemote ( 7127): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=281216  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/UsbSettingsReceiver( 7069): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7069): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7069): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7069): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/UsbSettingsReceiver( 7069): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/UsbSettingsControl( 7069): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7069): [AUTORUN] onReceive() : availableList=[wlan0]
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/UsbSettingsReceiver( 7069): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7069): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7069): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7069): [AUTORUN] onReceive() : TetherState Changed=wlan0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/UsbSettingsControl( 7069): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 7069): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7069): MCCMNC not supported: null
D/QRemote ( 7127): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7127): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7127): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7069): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26245814 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@26245814 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/CommandListener(  318): Setting iface cfg
D/CommandListener(  318): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
D/WiFiOffLoadBroadcast( 7069): MCCMNC not supported: null
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/QRemote ( 7127): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/QRemote ( 7127): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
I/QRemote ( 7127): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2700): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
,D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1468): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/WfdStateTracker( 1935): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1468): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  318): netlink response contains error (File exists)
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1037): Setting Dns servers for network 101 to [/192.168.1.1]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc-netbsd(  318): res_queryN name = clients3.google.com, class = 1, type = 28
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/StatusBar.NetworkController( 1468): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/TelephonyNetworkFactory-1( 1846): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/StatusBar.NetworkController( 1468): mWifiConnected = true, mWifiLevel = 0
D/TelephonyNetworkFactory-1( 1846):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
,W/dsqn    ( 7200): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524290
W/dsqn    ( 7200): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
,E/DSQN    ( 7200): DSQN ssw
V/WiFiOffLoadBroadcast( 7069): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WiFiOffLoadBroadcast( 7069): MCCMNC not supported: null
D/QRemote ( 7127): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7127): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7127): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7069): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7069): MCCMNC not supported: null
D/QRemote ( 7127): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7127): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7127): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7106): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7106): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7069): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7069): MCCMNC not supported: null
D/QRemote ( 7127): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7127): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7127): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7127): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7127): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7106): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7106): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7069): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7069): MCCMNC not supported: null
D/QRemote ( 7127): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7127): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7127): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7127): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7127): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
,W/dhcpcd  ( 7205): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7205): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6838 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
,D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 7205): version 5.5.6 starting
E/dhcpcd  ( 7205): get_duid: m
D/dhcpcd  ( 7205): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7205): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/libc-netbsd(  318): res_queryN name = clients3.google.com, class = 1, type = 1
D/dhcpcd  ( 7205): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7205): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7205): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7205): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7205): wlan0: sending REQUEST (xid 0x137baef2), next in 3.86 seconds
,D/libc-netbsd(  318): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  318): argv[0]=dsqncommand
D/LGDataListener(  318): argv[1]=wlan0
D/LGDataListener(  318): argv[2]=1
D/LGDataListener(  318): notifyDSQN DSQN STARTMONITOR wlan0 1
,D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jan 2016 01:12:56 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453857176224], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453857176203]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524290
,D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1846): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1846):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/TelephonyIcons( 1468): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1468): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5450): type=WIFI subType= reason=null isConnected=true
D/Tethering( 1037): MasterInitialState.processMessage what=3
,D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6536): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5450): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7221 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7221): onCreate
W/AppUp4:DB( 7221):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7221):  setFingerPrint start
I/AppUp4:DB( 7221):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7221):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7221):  SDK version = 21
I/AppUp4:DB( 7221):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7221): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7221): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7221): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7221): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7221): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7221): onReceive
D/LgDataFeature( 7221): LgDataFeature() Constructor: none
D/LgDataFeature( 7221): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7221): Context : android.app.ReceiverRestrictedContext@ca1725a
D/AppUp4:CustFacade( 7221): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7221): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7221): begin check event
I/AppUp4:CustModeStarterReceiver( 7221): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7221): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7221): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7221): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7221): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1037): Killing 6592:com.lge.email/u0a23 (adj 15): empty #17
D/LGDMClient( 4286): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4286): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_6592/cgroup.procs: No such file or directory
,W/ContextImpl( 4286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3416): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3416): DownloadService onCreate
,D/LGDMClient( 4286): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4286): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4286): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4286): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3416): in removeSpuriousFiles
V/DownloadManager( 3416): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@40b4699 on behalf of 3416
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
,I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3416): in trimDatabase
V/DownloadManager( 3416): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@1ba5dd5e on behalf of 3416
I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7245 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3416): DownloadService onStartCommand
V/DownloadManager( 3416): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@18c0b355 on behalf of 3416
W/ContextImpl( 4286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3416): processing inserted download 1
V/DownloadManager( 3416): processing inserted download 4
V/DownloadManager( 3416): processing inserted download 7
V/DownloadManager( 3416): processing inserted download 8
V/DownloadManager( 3416): processing inserted download 9
V/DownloadManager( 3416): processing inserted download 10
V/DownloadManager( 3416): processing inserted download 16
E/LGDMClient( 4286): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3416): processing inserted download 17
D/LGDMClient( 4286): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4286): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3416): processing inserted download 18
V/DownloadManager( 3416): processing inserted download 21
V/DownloadManager( 3416): processing inserted download 22
,V/DownloadManager( 3416): DownloadService onDestroy
W/ResourcesManager( 7245): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7245): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7245): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7245): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7245): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7245): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7245): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7245): LgDataFeature() Constructor: none
,D/LgDataFeature( 7245): LgDataFeature() Constructor Done, null
,D/eas_req ( 7245): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7276 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  346): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 465us total 23.944ms
,I/art     (  346): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 434us total 21.095ms
,I/art     (  346): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 407us total 18.706ms
,I/HubEmail( 7245): JNI_OnLoad()
I/HubEmail( 7245): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7245): registerNatives()
I/HubEmail( 7245): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7245): registerNativeMethods()
I/HubEmail( 7245): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7245): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1037): Killing 6452:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10004/pid_6452/cgroup.procs: No such file or directory
,W/Settings( 7245): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7245): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3373): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3373): action = android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
I/LgeMiscReceiver( 3373): networkInfo.isConnected() = false
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1037): identical MTU - not setting
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1468): CM callback handler got msg 524295
I/dhcpcd  ( 7205): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7305 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 7205): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7205): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7205): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7205): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7205): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7205): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7205): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7205): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7345 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6618:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_6618/cgroup.procs: No such file or directory
,D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
I/jxcore-log( 6988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6988): 
,D/libc-netbsd(  318): res_queryN name = static-avc.lglime.com succeed
,I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7365 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6642:com.google.android.apps.docs/u0a61 (adj 15): empty #17
V/FormManager( 7276): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7276): Alarm would be updated, because LastCheckTime has been updated.
W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6642/cgroup.procs: No such file or directory
,I/ActivityManager( 1037): Killing 6685:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/art     ( 7365): Almond Protected OAT
W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_6685/cgroup.procs: No such file or directory
,D/WeatherApplication( 7365): removeAccount
D/WeatherApplication( 7365): Account.length = 0
E/WeatherApplication( 7365): OPERATOR:OPEN
D/WeatherAncestor( 7365): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:12:58
D/Weather.Utils( 7365): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7365): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7365): 2 : This is isUpdating : false
D/WeatherAncestor( 7365): connectivity changed - connection : true
D/WeatherService( 7365): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7365): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7365): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7365): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7365): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7365): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:12:58
I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7384 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 6731:com.lge.eula/1000 (adj 15): empty #17
,E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6731/cgroup.procs: No such file or directory
,I/jxcore-log( 6988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6988): 
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7384): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7384): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7384): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/jxcore-log( 6988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6988): 
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
I/jxcore-log( 6988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6988): 
W/ContextImpl( 7384): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/jxcore-log( 6988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6988): 
,I/jxcore-log( 6988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6988): 
,I/jxcore-log( 6988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6988): 
I/jxcore-log( 6988): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6988): 
I/WebViewFactory( 7384): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7384): Loading: webviewchromium
I/LibraryLoader( 7384): Time to load native libraries: 3 ms (timestamps 3986-3989)
I/LibraryLoader( 7384): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7384): Binding Chromium to main looper Looper (main, tid 1) {2aac5f2d}
,I/LibraryLoader( 7384): Expected native library version number "",actual native library version number ""
I/chromium( 7384): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7384): Initializing chromium process, renderers=0
W/art     ( 7384): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7384): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7384): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=46780 len=2953
I/chromium( 7384): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:40 off:229536 len:643667
V/AudioPolicyService(  322): registerClient() client 0xb1019e20, uid 10093
W/AudioManagerAndroid( 7384): Requires BLUETOOTH permission
I/Adreno-EGL( 7384): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7384): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7384): Build Date: 12/12/14 금
I/Adreno-EGL( 7384): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7384): Remote Branch: 
I/Adreno-EGL( 7384): Local Patches: 
I/Adreno-EGL( 7384): Reconstruct Branch: 
,I/NSApplication( 7384): Starting up...
,I/ActivityManager( 1037): Killing 5986:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_5986/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2336): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
D/ChimeraCfgMgr( 2336): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6536): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5450): type=WIFI subType= reason=null isConnected=true
I/NetworkStateForAutoUpdateMonitor( 7221): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7221): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7221): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7221): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7221): onReceive
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7221): Context : android.app.ReceiverRestrictedContext@ca1725a
D/AppUp4:CustFacade( 7221): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7221): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 7221): begin check event
,I/AppUp4:CustModeStarterReceiver( 7221): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4286): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4286): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/DownloadManager( 3416): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4286): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3416): DownloadService onCreate
I/DownloadManager( 3416): in removeSpuriousFiles
V/DownloadManager( 3416): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4286): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@c90c65b on behalf of 3416
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4286): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4286): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/DownloadManager( 3416): in trimDatabase
V/DownloadManager( 3416): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3416): DownloadService onStartCommand
V/DownloadManager( 3416): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@357a3a36 on behalf of 3416
,V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@3e8b6d37 on behalf of 3416
V/DownloadManager( 3416): processing inserted download 1
W/Settings( 7245): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3373): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3373): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3373): networkInfo.isConnected() = false
V/DownloadManager( 3416): processing inserted download 4
E/LGDMClient( 4286): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4286): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4286): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3416): processing inserted download 7
V/DownloadManager( 3416): processing inserted download 8
V/DownloadManager( 3416): processing inserted download 9
V/DownloadManager( 3416): processing inserted download 10
V/DownloadManager( 3416): processing inserted download 16
V/DownloadManager( 3416): processing inserted download 17
V/DownloadManager( 3416): processing inserted download 18
V/DownloadManager( 3416): processing inserted download 21
V/DownloadManager( 3416): processing inserted download 22
W/Settings( 7245): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/WeatherAncestor( 7365): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:12:59
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3416): DownloadService onDestroy
W/Kids    ( 2336): [AccountUtils] Account not ready
W/Kids    ( 2336): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2336): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2336): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2336): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2336): 	at java.lang.Thread.run(Thread.java:818)
,D/Weather.Utils( 7365): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7365): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7365): 2 : This is isUpdating : false
D/WeatherAncestor( 7365): connectivity changed - connection : true
D/WeatherService( 7365): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31d22168
D/ForecastDataCache( 7365): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7365): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7365): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7365): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7365): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:12:59
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1419): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
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
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{17a7c3c2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2336): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6536): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
V/FormManager( 7276): There are no updated forms. The schedule will be deleted.
V/FormManager( 7276): Alarm would be updated, because LastCheckTime has been updated.
I/NetworkStateForAutoUpdateMonitor( 7221): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7221): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7221): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7221): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7221): onReceive
I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/AppUp4:CustFacade( 7221): Context : android.app.ReceiverRestrictedContext@ca1725a
D/AppUp4:CustFacade( 7221): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7221): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7221): begin check event
,I/AppUp4:CustModeStarterReceiver( 7221): Event For GoodConnectivity, noConnectivity : false, but skip! 
V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4286): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4286): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/jxcore-log( 6988): Test app app.js loaded
I/jxcore-log( 6988): 
,V/DownloadManager( 3416): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3416): DownloadService onCreate
D/LGDMClient( 4286): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/chromium( 6988): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6988): setDiscoveryMode: Mode set to BLE
I/DownloadManager( 3416): in removeSpuriousFiles
V/DownloadManager( 3416): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/jxcore-log( 6988): BLE advertisement is supported
I/jxcore-log( 6988): 
,I/LGDMClient( 4286): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2336): [AccountUtils] Account not ready
W/Kids    ( 2336): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2336): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2336): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2336): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2336): 	at java.lang.Thread.run(Thread.java:818)
W/ContextImpl( 4286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/LGDMClient( 4286): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4286): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/FormManager( 7276): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7276): Alarm would be updated, because LastCheckTime has been updated.
I/art     ( 1037): Explicit concurrent mark sweep GC freed 90341(4MB) AllocSpace objects, 4(320KB) LOS objects, 33% free, 44MB/66MB, paused 1.196ms total 93.668ms
,V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@258cf80d on behalf of 3416
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3416): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.51.57_COM_COM_8275_2_20151201044833536_RELG-D855_21.apk
I/DownloadManager( 3416): in trimDatabase
V/DownloadManager( 3416): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@17a7c3c2 on behalf of 3416
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
W/Settings( 7245): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
,D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
V/DownloadManager( 3416): DownloadService onStartCommand
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
V/DownloadManager( 3416): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
I/LgeMiscReceiver( 3373): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3373): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3373): networkInfo.isConnected() = true
D/PhoneState( 3373): setPdpRejectCasuse : false
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
W/Settings( 7245): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 4286): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3416): created cursor android.database.sqlite.SQLiteCursor@2a1e0809 on behalf of 3416
V/DownloadManager( 3416): processing inserted download 1
V/DownloadManager( 3416): processing inserted download 4
V/DownloadManager( 3416): processing inserted download 7
V/DownloadManager( 3416): processing inserted download 8
V/DownloadManager( 3416): processing inserted download 9
V/DownloadManager( 3416): processing inserted download 10
V/DownloadManager( 3416): processing inserted download 16
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
,D/LGDMClient( 4286): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4286): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3416): processing inserted download 17
D/WeatherAncestor( 7365): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:12:59
D/Weather.Utils( 7365): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7365): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7365): 2 : This is isUpdating : false
D/WeatherAncestor( 7365): connectivity changed - connection : true
D/WeatherService( 7365): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@31d22168
D/ForecastDataCache( 7365): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7365): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7365): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7365): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7365): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:12:59
,V/DownloadManager( 3416): processing inserted download 18
V/DownloadManager( 3416): processing inserted download 21
V/DownloadManager( 3416): processing inserted download 22
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{17a7c3c2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/jxcore-log( 6988): --= Surplus to requirements =--
I/jxcore-log( 6988): 
I/jxcore-log( 6988): ****TEST TOOK:  ms ****
I/jxcore-log( 6988): 
I/jxcore-log( 6988): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6988): 
,V/DownloadManager( 3416): DownloadService onDestroy
D/ChimeraCfgMgr( 2336): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1381f6a4 type 2 when 284711 com.google.android.gms} when 284711
I/art     ( 2066): Explicit concurrent mark sweep GC freed 45691(2MB) AllocSpace objects, 14(1783KB) LOS objects, 51% free, 30MB/62MB, paused 2.398ms total 70.295ms
,D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = mtalk.google.com, class = 1, type = 1
I/GLSUser ( 2066): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2066): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2066): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2066): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2066): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  318): res_queryN name = mtalk.google.com succeed
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2336): [AccountUtils] Account not ready
W/Kids    ( 2336): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2336): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2336): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2336): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2336): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2336): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2336): 	at java.lang.Thread.run(Thread.java:818)
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
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{17a7c3c2 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/AndroidRuntime( 7485): 
D/AndroidRuntime( 7485): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7485): CheckJNI is OFF
,D/GCM     ( 2066): Connected
,D/GCM     ( 2066): Message class com.google.f.a.a.p
D/AndroidRuntime( 7485): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
,I/ActivityManager( 1037): Killing 6988:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/PackageSettings( 1037): Skipping PackageSetting{639a3e3 com.example.hello/10319} due to missing metadata
,D/UEI.SmartControl( 6762): Internal timer expired: 2
D/UEI.SmartControl( 6762): unbind internal service
,I/WindowState( 1037): WIN DEATH: Window{2d37b8b6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1037): Client connection lost with reason: 4
D/InputDispatcher( 1037): Window went away: Window{2d37b8b6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/serial_port( 6762): close(fd = 24)
,I/UEI.SmartControl( 6762): Serial port is closed.
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{c391673 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  342): DFP En is all cleared set to be enabled
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{c391673 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{c391673 u0 com.test.thalitest/.MainActivity t4 f}
,W/ActivityManager( 1037): Spurious death for ProcessRecord{1b39d910 6988:com.test.thalitest/u0a311}, curProc for 6988: null
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=478732728, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,D/SplitWindowPolicy( 1935): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1935): topRunningActivity=ActivityInfo{b28982a co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2027): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1935): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1935): topRunningActivity=ActivityInfo{3921c61b co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2027): [Launcher.java:903:onResume()]onResume
I/[SystemUI]TimeTickManager( 1468): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1468): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1468): called onTimeUpdated()
I/[SystemUI]Clock( 1468): called onTimeUpdated()
I/LgeClockWidgetControlView( 1468): called onTimeUpdated()
I/[LGHome]EVENT( 2027): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[SystemUI]DateView( 1468): called onTimeUpdated()
I/[LGHome]Launcher.Model( 2027): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/[SystemUI]DateView( 1468): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1468): handleTimeUpdate
I/[LGHome]GBoardWebView( 2027): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,D/ActionManagerService( 1899): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3734): handleMessage: what(1000) actionID(0x1000003)
D/LIA_Service_RemotePackageHandler( 1990): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/KeyguardModel( 1468): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
E/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI] [+] updateMediaPlayerInfo
,D/LIA_MrGDBLogger_PackageInfoDetector( 3734): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/GeofencerStateMachine( 1811): Ignoring removeGeofence because network location is disabled.
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 4574): Explicit concurrent mark sweep GC freed 18535(1094KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 606us total 63.737ms
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  318): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  318): res_queryN name = www.google.com succeed
,I/[LGHome]LGActivityUtil( 2027): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/PostponalbeReceiver( 6536): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4521): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
D/libc-netbsd(  318): default dns: query_ipv6=0, query_ipv4=1
D/administrator( 1037): Handling package changes for user 0
D/libc-netbsd(  318): res_queryN name = clients3.google.com, class = 1, type = 1
I/[LGHome]EVENT( 2027): [Launcher.java:1056:onResume()]onResume end
D/libc-netbsd(  318): res_queryN name = clients3.google.com succeed
W/System.err( 4521): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4521): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4521): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4521): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4521): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4521): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4521): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4521): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 4521): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4521): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4521): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/[LGHome]EVENT( 2027): [Launcher.java:1114:onPause()]onPause
D/ActionManagerService( 1899): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2027): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 3734): handleMessage: what(1000) actionID(0x1000004)
I/[SystemUI]QSlideListController( 1468): onReceive = android.intent.action.PACKAGE_REMOVED
V/BoardContentProvider( 3734): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,D/AppUp4:PreloadHelper( 7221): added Exclude : com.test.thalitest
,V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7514 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/GBoardWebViewUtils( 2027): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2027): , create_time: 1430558575574
I/GBoardWebViewUtils( 2027): , expire_time: 0
I/GBoardWebViewUtils( 2027): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2027): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2027): , display: false
I/GBoardWebViewUtils( 2027): , animation: false }
I/GBoardWebViewUtils( 2027): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2027): , create_time: 1430558575600
I/GBoardWebViewUtils( 2027): , expire_time: 0
I/GBoardWebViewUtils( 2027): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2027): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2027): , display: false
I/GBoardWebViewUtils( 2027): , animation: false }
I/GBoardWebViewUtils( 2027): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1453384801259
I/GBoardWebViewUtils( 2027): , create_time: 1453384801850
I/GBoardWebViewUtils( 2027): , expire_time: 0
I/GBoardWebViewUtils( 2027): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2027): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2027): , display: false
I/GBoardWebViewUtils( 2027): , animation: false }
D/SplitUIManager( 1863): split_name #11 / not available #0
,D/SplitUIService( 1863): removed split : 
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@8d44869,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1468): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1468): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/[LGHome]GBoardWebView( 2027): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,I/ActivityManager( 1037): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7533 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
D/WallpaperManager( 2027): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI] [-] updateMediaPlayerInfo
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1468): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[LGHome]EVENT( 2027): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[SystemUI]NavigationThemeResource( 1468): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1468):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1468): , Keyguard show=false, IME shown=false, Panel expanded=false
,D/SplitUIManager( 1863): split_name #11 / not available #0
I/SplitUIService( 1863): split app #11
I/[LGHome]EVENT( 2027): [Launcher.java:5349:onStop()]onStop
W/ResourcesManager( 7514): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7514): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7514): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7514): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7514): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LockScreenSettings( 7533): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/KeyguardModel( 1468): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1468): createShortcutInfo...
D/KeyguardModel( 1468): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1468): createShortcutInfo...
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1468): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1468): createShortcutInfo...
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1468): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1468): createShortcutInfo...
W/ResourcesManager( 1468): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1468): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1468): createShortcutInfo...
I/ActivityManager( 1037): Killing 6790:com.lge.bnr/1000 (adj 15): empty #17
,I/[LGHome]Launcher.Model( 2027): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,E/[Concierge]WebView( 2027): View is detached but the BroadcastReceiver got Time-tick!!!
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 23683(1514KB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 1.456ms total 287.163ms
I/[LGHome]Launcher.Model( 2027): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2027): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2027): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/ThermalEngine(  336): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3158): Thermal-Lib-Client: Client request sent
,D/AndroidRuntime( 7485): Shutting down VM
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2027): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/KeyguardModel( 1468): handleShortcutListChanged...
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6790/cgroup.procs: No such file or directory
I/[Concierge]WidgetView( 2027): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2613): onStartCommand(). Type : 8
D/[Concierge]Service( 2613): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{9826f3b u0 com.lge.launcher2/.Launcher t3} time:285913
,D/[Concierge]WidgetView( 2027): change position of spinner
D/KeyguardModel( 1468): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1468): createShortcutInfo...
D/[Concierge]Service( 2613): Update widget ID : 11
D/[Concierge]Service( 2613): onStartCommand(). Type : 0
D/KeyguardModel( 1468): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1468): createShortcutInfo...
I/[Concierge]WidgetView( 2027): initWebView(). Time : 1453857180505
,W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1468): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1468): createShortcutInfo...
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1468): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1468): createShortcutInfo...
W/ResourceType( 1468): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1468): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1468): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1468): createShortcutInfo...
I/[Concierge]WebView( 2027): Return exist ConciergeWebView. Reuse : 655379802
I/SystemConfig( 7514): BUILD Country: EU
I/SystemConfig( 7514): BUILD Operator: OPEN
D/[Concierge]WidgetView( 2027): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2027): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2027): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@33ca8d3b
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2027): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2027): isWidgetUpdateSkippable ? true
I/[LGHome]EVENT( 2027): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/[Concierge]WidgetBroadcastReceiver( 2027): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2027): Widget kill message received. Destory myself. My : 1453856923435, New one : 1453857180505
D/[Concierge]WidgetView( 2027): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2027): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/KeyguardModel( 1468): handleShortcutListChanged...
,I/ActivityManager( 1037): Killing 6852:com.google.android.apps.books/u0a54 (adj 15): empty #17
I/[LgeWidgetLib]LgeAppWidgetHostView( 2027): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2027): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 2027): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2027): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2027): Timeline: Activity_idle id: android.os.BinderProxy@2af71f1f time:286044
,W/libprocessgroup( 1037): failed to open /acct/uid_10054/pid_6852/cgroup.procs: No such file or directory
I/PackageChangeReceiver( 7245): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/VoicemailCleanupService( 2379): Cleaning up data for package: com.test.thalitest
I/SystemConfig( 7514): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7514): existFile = false
I/SystemConfig( 7514): canReadFile = false
I/SystemConfig( 7514): systemFeature RCS result false
D/SystemConfig( 7514): refreshRcsSupport() :false
I/ActivityManager( 1037): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7558 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/chromium( 2027): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
W/ResourcesManager( 7558): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7558): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7558): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7558): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/GBoardtInterface( 2027): onReloaded()
I/GBoardWebViewClient( 2027): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3734): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3734): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1899): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3734): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3734): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1899): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3734): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3734): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3734): getSize() : size - 0
V/BoardContentProvider( 3734): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/LIA_Informant_Tips_SmartTipsActionManager( 3734): onSettingEvent() : GBoard On - add scheduler - 0
D/GBoardUriUtils( 2027): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2027): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2027): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2027): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2027): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2027): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1453384801259&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/AppConfig( 7558): Total System Memory = 2995761152
D/SystemHelper( 7558): region [EU], country [EU], operator [OPEN], sub-operator []
E/SharedPreferencesImpl( 7558): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak

```
