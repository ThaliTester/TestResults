#### Test 54970261ac9928f_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 227196336068; DSPS: 7586465; Offset : -4334691869
,D/AndroidRuntime( 7203): 
D/AndroidRuntime( 7203): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7203): CheckJNI is OFF
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 247210918264; DSPS: 8242303; Offset : -4334694341
D/AndroidRuntime( 7203): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1998): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{3440156f #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{3440156f #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  356): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7224 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7203): Shutting down VM
V/ActivityManager( 1038): Display changed displayId=0
D/DSDPConnection( 1892): Display #0 changed.
D/SplitWindowPolicy( 1998): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1998): topRunningActivity=ActivityInfo{12c8b9ee co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1998): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1998): topRunningActivity=ActivityInfo{2431de8f co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7224): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7224): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7224): Loading: webviewchromium
,I/LibraryLoader( 7224): Time to load native libraries: 5 ms (timestamps 7658-7663)
,I/LibraryLoader( 7224): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7224): Binding Chromium to main looper Looper (main, tid 1) {3d56c51e}
,I/LibraryLoader( 7224): Expected native library version number "",actual native library version number ""
,I/chromium( 7224): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7224): Initializing chromium process, renderers=0
,W/art     ( 7224): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  335): registerClient() client 0xb14fd6e0, uid 10311
,W/chromium( 7224): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7224): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7224): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@420ae81:true
I/Adreno-EGL( 7224): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7224): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7224): Build Date: 12/12/14 금
I/Adreno-EGL( 7224): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7224): Remote Branch: 
I/Adreno-EGL( 7224): Local Patches: 
I/Adreno-EGL( 7224): Reconstruct Branch: 
,W/chromium( 7224): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7224): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7224): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7224): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7224): CordovaWebView is running on device made by: LGE
,W/art     ( 7224): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1038): Activity pause timeout for ActivityRecord{8ab227c u0 com.test.thalitest/.MainActivity t4}
W/art     ( 7224): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7224): Render dirty regions requested: true
I/OpenGLRenderer( 7224): Initialized EGL, version 1.4
,D/OpenGLRenderer( 7224): Enabling debug mode 0
D/Atlas   ( 7224): Validating map...
,D/SplitWindow( 1038): check instance of lgWin Window{3c0d5ef3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7224): LgDataFeature() Constructor: none
D/LgDataFeature( 7224): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1466): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3e5bdc9f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1466): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1466):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1466): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 7224): Timeline: Activity_idle id: android.os.BinderProxy@3bccb1ce time:248124
,I/ActivityManager( 1038): Displayed com.test.thalitest/.MainActivity: +683ms (total +756ms)
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{8ab227c u0 com.test.thalitest/.MainActivity t4} time:248127
D/JsMessageQueue( 7224): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 7224): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7224): 
,I/[SystemUI]LGPowerUI( 1466): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1466): On Skip Timer : true
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController( 1038): battery changed pluggedType: 2
D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/KeyguardUpdateMonitor( 1466): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1466): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1998): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1998): Battery Level Remaining: 100%
D/LEDHandler( 1998): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3796): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1466): onReceive = android.intent.action.BATTERY_CHANGED
D/jxcore_app_log( 7224): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435069184
D/JX-Cordova( 7224): jxcore cordova android initializing
,E/GBMv2   (  356): DFP En is all cleared set to be enabled
,E/GBMv2   (  356): Set value is all cleared set the max
I/GBMv2   (  356): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7224): Initializing JXcore engine
W/jxcore-log( 7224): JXcore engine is ready
W/jxcore-log( 7224): Starting JXcore engine
W/.test.thalitest( 7224): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10714]" dev="sockfs" ino=10714 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7224): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7224): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10863]" dev="sockfs" ino=10863 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7224): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7224): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[34839]" dev="sockfs" ino=34839 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7224): Background sticky concurrent mark sweep GC freed 124648(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.631ms total 112.627ms
W/jxcore-log( 7224): Platform android
W/jxcore-log( 7224): 
W/jxcore-log( 7224): Process ARCH arm
W/jxcore-log( 7224): 
,I/jxcore-log( 7224): JXcore Cordova bridge is ready!
I/jxcore-log( 7224): 
W/jxcore-log( 7224): JXcore engine is started
,I/chromium( 7224): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7224): 
I/jxcore-log( 7224): Toggling radios to true
I/jxcore-log( 7224): 
,D/BluetoothAdapter( 7224): enable(): BT is already enabled..!
D/WifiService( 1038): New client listening to asynchronous messages
D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=7224, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: true pid=7224, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1038): disconnect pid=7224, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1038): [250,654,564 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1038): reconnect pid=7224, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7224): Radios toggled
I/jxcore-log( 7224): 
I/wpa_supplicant( 2661): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/Tethering( 1038): InitialState.processMessage what=4
,D/WifiNative-wlan0( 1038): DISCONNECT: returned true
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7293 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/LGWifiP2pService( 1038): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/DhcpStateMachine( 1038): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  330): Clearing all IP addresses on wlan0
V/NativeCrypto( 2143): Read error: ssl=0xaf065a00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2143): SSL shutdown failed: ssl=0xaf065a00: I/O error during system call, Broken pipe
E/WifiStateMachine( 1038): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1038):  DisconnectingState CMD_RECONNECT 0 0
,D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): ignoring duplicate network state non-change
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1038):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1038): [250,814,222 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
I/wpa_supplicant( 2661): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1038): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WifiNative-wlan0( 1038): RECONNECT: returned true
E/WifiStateMachine( 1038):  DisconnectingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=250826
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=250826
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
V/WfdStateTracker( 1998): handleWifiStateChangedEvent: 0
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/CommandListener(  330): Clearing all IP addresses on wlan0
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=250858  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=250858  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/libc-netbsd(  330): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiHS20( 1038): hidePasspointNotification off =false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=250864  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1038): Removing idletimer
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524292
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/TelephonyNetworkFactory-1( 1892): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1892):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [ty,pe: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=250879  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
W/ResourcesManager( 7293): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7293): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 7293): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7293): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7293): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7293): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-140ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7293): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7293): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7293): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7293): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7293): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7293): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7293): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7293): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7293): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7293): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7293): [AUTORUN] setTetherStatus() : status=false
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{18390be5 type 0 when 1452269741515 com.android.vending} when 1452269741515
,D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7330 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/PCSuite ( 7330): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7330): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7330): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7293): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7293): LgDataFeature() Constructor: none
,D/LgDataFeature( 7293): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7293): MCCMNC not supported: null
D/QRemote ( 6961): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6961): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6961): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7330): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7330): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7330): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7293): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WiFiOffLoadBroadcast( 7293): MCCMNC not supported: null
D/QRemote ( 6961): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6961): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6961): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7330): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7330): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7330): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7293): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/WiFiOffLoadBroadcast( 7293): MCCMNC not supported: null
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QRemote ( 6961): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6961): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6961): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7330): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7330): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7330): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7293): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/Finsky  ( 6321): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6321): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6321): [1] 5.onFinished: Giving up after 6 failures.
D/WiFiOffLoadBroadcast( 7293): MCCMNC not supported: null
D/QRemote ( 6961): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6961): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6961): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1038): Killing 6716:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10019/pid_6716/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 7293): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7293): MCCMNC not supported: null
,D/QRemote ( 6961): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6961): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6961): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/ActivityManager( 1038): Killing 6738:com.lge.email/u0a23 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_6738/cgroup.procs: No such file or directory
,I/wpa_supplicant( 2661): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=4 known=0 got=4 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=252949  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=252963  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
V/WiFiOffLoadBroadcast( 7293): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7293): MCCMNC not supported: null
D/QRemote ( 6961): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6961): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6961): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7293): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7293): MCCMNC not supported: null
D/QRemote ( 6961): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6961): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6961): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2661): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/Tethering( 1038): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/UsbSettingsReceiver( 7293): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7293): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7293): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7293): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7293): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/UsbSettingsControl( 7293): [AUTORUN] getUsbConnected() : connected=true
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/UsbSettingsReceiver( 7293): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7293): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7293): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7293): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/WifiMonitor( 1038): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=253053  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=253053  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=253054
I/wpa_supplicant( 2661): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/WifiStateMachine( 1038):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=253054
E/WifiStateMachine( 1038):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=253054
I/wpa_supplicant( 2661): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=253054
E/WifiStateMachine( 1038):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=253054
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=253055  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1038): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1038): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=253070  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/UsbSettingsReceiver( 7293): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7293): [AUTORUN] setTetherStatus() : status=false
,E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=253071  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=253072  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=253072
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=253073
D/WifiNative-wlan0( 1038): doString: [STATUS]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1038): setVHTCapabilityType  : false
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7293): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/WifiServerServiceExt( 1038): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1038): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1038): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1038): NetworkAgent connected
,D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7293): MCCMNC not supported: null
D/QRemote ( 6961): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6961): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6961): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/CommandListener(  330): Setting iface cfg
,E/WifiStateMachine( 1038): Start Dhcp Watchdog 2
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=253113  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=253113  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/DhcpStateMachine( 1038): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=253114  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=253117  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=253117  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=253117  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 7293): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7293): MCCMNC not supported: null
,D/QRemote ( 6961): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6961): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6961): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7293): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 0
D/WifiNative-wlan0( 1038): SET ps 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1038): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/WiFiOffLoadBroadcast( 7293): MCCMNC not supported: null
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@358e706e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@358e706e target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine( 1038): DHCP Start wake lock is acquired.
D/CommandListener(  330): Setting iface cfg
D/CommandListener(  330): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1038): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 6961): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/QRemote ( 6961): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6961): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1038):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2661): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
,V/WiFiOffLoadBroadcast( 7293): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7293): MCCMNC not supported: null
D/QRemote ( 6961): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6961): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6961): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1038): ignoring duplicate network state non-change
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1038): Adding iface wlan0 to network 101
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/WfdStateTracker( 1998): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1466): mWifiConnected = true, mWifiLevel = 0
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
E/ConnectivityService( 1038): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1038): Adding Route [fe80::/64 -> :: wlan0] to network 101
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1038): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  330): netlink response contains error (File exists)
D/ConnectivityService( 1038): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1038): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1038): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
,D/ConnectivityService( 1038): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1038): currentScore = 0, newScore = 20
D/ConnectivityService( 1038):    accepting network in place of null
,D/ConnectivityService( 1038): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1038): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/TelephonyNetworkFactory-1( 1892): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1892):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1038): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1038): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1038): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
D/libc-netbsd(  330): res_queryN name = clients3.google.com, class = 1, type = 28
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1038): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1038): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1038): validation of new default Network = false
D/ConnectivityService( 1038): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1038): enableDataServiceNotify 
D/DSQN    ( 1038): start dsqn bin
D/LocSvc_java( 1038): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7375): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7375): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524290
V/WiFiOffLoadBroadcast( 7293): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/NetworkPolicy( 1038): [LG_RESTRICTED] checkMobilePolicy_type()
,E/DSQN    ( 7375): DSQN ssw
D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 7293): MCCMNC not supported: null
D/QRemote ( 6961): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6961): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6961): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7293): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7293): MCCMNC not supported: null
D/QRemote ( 6961): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6961): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6961): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/libc-netbsd(  330): res_queryN name = clients3.google.com, class = 1, type = 1
,I/PCSuite ( 7330): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7330): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7293): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7293): MCCMNC not supported: null
,D/QRemote ( 6961): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6961): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6961): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6961): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6961): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7330): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7330): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7293): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7293): MCCMNC not supported: null
D/libc-netbsd(  330): res_queryN name = clients3.google.com succeed
D/QRemote ( 6961): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6961): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6961): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6961): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 6961): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  330): argv[0]=dsqncommand
D/LGDataListener(  330): argv[1]=wlan0
D/LGDataListener(  330): argv[2]=1
,D/LGDataListener(  330): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1038): DSQM DsqnNotification wlan0  1
,D/DSQN    ( 1038): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 16:15:58 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452269758124], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452269758102]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Validated
D/ConnectivityService( 1038): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1038): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1892): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1892):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/DhcpStateMachine( 1038): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1038): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1038): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 7381): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7381): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
I/dhcpcd  ( 7381): version 5.5.6 starting
E/dhcpcd  ( 7381): get_duid: m
D/dhcpcd  ( 7381): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7381): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/dhcpcd  ( 7381): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7381): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7381): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 7381): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7381): wlan0: sending REQUEST (xid 0x295ea33b), next in 4.41 seconds
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1038): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6636): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkMonitor( 5976): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5976): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7409 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7409): onCreate
W/AppUp4:DB( 7409):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7409):  setFingerPrint start
I/AppUp4:DB( 7409):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7409):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7409):  SDK version = 21
I/AppUp4:DB( 7409):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7409): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7409): onReceive
D/LgDataFeature( 7409): LgDataFeature() Constructor: none
D/LgDataFeature( 7409): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7409): Context : android.app.ReceiverRestrictedContext@2802fbcc
D/AppUp4:CustFacade( 7409): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7409): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7409): begin check event
I/AppUp4:CustModeStarterReceiver( 7409): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7409): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7409): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7409): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7409): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1038): Killing 6762:com.android.gallery3d/u0a27 (adj 15): empty #17
D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1038): failed to open /acct/uid_10027/pid_6762/cgroup.procs: No such file or directory
W/ContextImpl( 4289): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4289): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,E/WifiStateMachine( 1038):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
V/DownloadManager( 3387): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
,D/ConnectivityService( 1038): identical MTU - not setting
,D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
V/DownloadManager( 3387): DownloadService onCreate
D/LGDMClient( 4289): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4289): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 4289): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524295
I/LGDMClient( 4289): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/DownloadManager( 3387): in removeSpuriousFiles
V/DownloadManager( 3387): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3387): created cursor android.database.sqlite.SQLiteCursor@1d885d30 on behalf of 3387
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
,I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3387): in trimDatabase
V/DownloadManager( 3387): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3387): created cursor android.database.sqlite.SQLiteCursor@11392f2e on behalf of 3387
I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7435 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ContextImpl( 4289): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3387): DownloadService onStartCommand
E/LGDMClient( 4289): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4289): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4289): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3387): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3387): created cursor android.database.sqlite.SQLiteCursor@1ce1c5c on behalf of 3387
V/DownloadManager( 3387): processing inserted download 1
V/DownloadManager( 3387): processing inserted download 4
,V/DownloadManager( 3387): processing inserted download 7
V/DownloadManager( 3387): processing inserted download 8
V/DownloadManager( 3387): processing inserted download 9
V/DownloadManager( 3387): processing inserted download 10
V/DownloadManager( 3387): processing inserted download 16
V/DownloadManager( 3387): processing inserted download 17
V/DownloadManager( 3387): processing inserted download 18
V/DownloadManager( 3387): processing inserted download 21
V/DownloadManager( 3387): DownloadService onDestroy
,W/ResourcesManager( 7435): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7435): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7435): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7435): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 7435): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7435): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
I/dhcpcd  ( 7381): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,W/ResourceType( 7435): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7435): LgDataFeature() Constructor: none
,D/LgDataFeature( 7435): LgDataFeature() Constructor Done, null
,I/dhcpcd  ( 7381): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7381): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7381): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7381): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7381): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7381): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7381): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7381): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/eas_req ( 7435): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7468 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7435): JNI_OnLoad()
I/HubEmail( 7435): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7435): registerNatives()
I/HubEmail( 7435): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7435): registerNativeMethods()
I/HubEmail( 7435): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7435): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1038): Killing 6806:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6806/cgroup.procs: No such file or directory
,W/Settings( 7435): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 7435): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3349): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3349): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3349): networkInfo.isConnected() = false
,D/DhcpStateMachine( 1038): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1038): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1038): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1038): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1038): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1038): RunningState
I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7499 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  330): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  330): res_queryN name = static-avc.lglime.com, class = 1, type = 1
I/ActivityManager( 1038): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7519 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6847:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
W/libprocessgroup( 1038): failed to open /acct/uid_10080/pid_6847/cgroup.procs: No such file or directory
D/libc-netbsd(  330): res_queryN name = static-avc.lglime.com succeed
I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7536 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6899:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6899/cgroup.procs: No such file or directory
I/art     ( 7536): Almond Protected OAT
D/WeatherApplication( 7536): removeAccount
D/WeatherApplication( 7536): Account.length = 0
E/WeatherApplication( 7536): OPERATOR:OPEN
D/WeatherAncestor( 7536): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:16:0
D/Weather.Utils( 7536): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7536): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7536): 2 : This is isUpdating : false
D/WeatherAncestor( 7536): connectivity changed - connection : true
D/WeatherService( 7536): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7536): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7536): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7536): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7536): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7536): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:16:0
I/ActivityManager( 1038): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7557 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6872:com.google.android.apps.plus/u0a97 (adj 15): empty #17
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/libprocessgroup( 1038): failed to open /acct/uid_10097/pid_6872/cgroup.procs: No such file or directory
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7557): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7557): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7557): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7557): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/FormManager( 7468): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7468): Alarm would be updated, because LastCheckTime has been updated.
V/WifiInternetCheck( 1038): Single check msg out of sync, ignoring.
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5976): type=WIFI subType= reason=null isConnected=true
,I/WebViewFactory( 7557): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7557): Loading: webviewchromium
I/LibraryLoader( 7557): Time to load native libraries: 3 ms (timestamps 6269-6272)
I/LibraryLoader( 7557): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7557): Binding Chromium to main looper Looper (main, tid 1) {2c56c6e7}
,I/LibraryLoader( 7557): Expected native library version number "",actual native library version number ""
I/chromium( 7557): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7557): Initializing chromium process, renderers=0
,W/art     ( 7557): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7557): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7557): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7557): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  335): registerClient() client 0xb57bbc40, uid 10093
,W/AudioManagerAndroid( 7557): Requires BLUETOOTH permission
I/Adreno-EGL( 7557): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7557): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7557): Build Date: 12/12/14 금
I/Adreno-EGL( 7557): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7557): Remote Branch: 
I/Adreno-EGL( 7557): Local Patches: 
I/Adreno-EGL( 7557): Reconstruct Branch: 
,I/NSApplication( 7557): Starting up...
,I/ActivityManager( 1038): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7619 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6940:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/art     (  360): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 20.026ms
,I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 26.787ms
,I/art     (  360): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 437us total 20.317ms
,I/ActivityManager( 1038): Killing 6921:com.lge.bnr/1000 (adj 15): empty #18
,W/libprocessgroup( 1038): failed to open /acct/uid_10005/pid_6940/cgroup.procs: No such file or directory
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6921/cgroup.procs: No such file or directory
,W/ResourcesManager( 7619): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=227359499, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{1fdfd31b type 2 when 256909 com.google.android.gms} when 256909
,D/[Concierge]Service( 2663): onStartCommand(). Type : 9
,I/GLSActivity( 2143): [ac] getting account id
,I/GLSUser ( 2143): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/ChimeraCfgMgr( 2393): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 82749(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 1.720ms total 102.738ms
,D/ChimeraCfgMgr( 2393): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 6636): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7409): onReceive
,D/AppUp4:CustFacade( 7409): Context : android.app.ReceiverRestrictedContext@2802fbcc
D/AppUp4:CustFacade( 7409): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7409): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7409): begin check event
I/AppUp4:CustModeStarterReceiver( 7409): Event For GoodConnectivity, noConnectivity : false, but skip! 
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
,D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
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
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/Kids    ( 2393): [AccountUtils] Account not ready
W/Kids    ( 2393): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2393): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2393): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2393): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2393): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2393): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2393): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2393): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2393): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2393): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2393): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2393): 	at java.lang.Thread.run(Thread.java:818)
D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4289): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4289): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{32cf9af4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LGDMClient( 4289): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3387): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 4289): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/DownloadManager( 3387): DownloadService onCreate
I/DownloadManager( 3387): in removeSpuriousFiles
V/DownloadManager( 3387): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4289): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3387): created cursor android.database.sqlite.SQLiteCursor@38ad103a on behalf of 3387
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
E/LGDMClient( 4289): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
D/LGDMClient( 4289): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4289): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 4289): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4289): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3387): in trimDatabase
V/DownloadManager( 3387): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3387): created cursor android.database.sqlite.SQLiteCursor@3d9d38e1 on behalf of 3387
V/DownloadManager( 3387): DownloadService onStartCommand
V/DownloadManager( 3387): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3387): created cursor android.database.sqlite.SQLiteCursor@24bf606 on behalf of 3387
,I/LgeMiscReceiver( 3349): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3349): action = android.net.conn.CONNECTIVITY_CHANGE
W/Settings( 7435): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3349): networkInfo.isConnected() = false
V/DownloadManager( 3387): processing inserted download 1
V/DownloadManager( 3387): processing inserted download 4
V/DownloadManager( 3387): processing inserted download 7
V/DownloadManager( 3387): processing inserted download 8
,W/Settings( 7435): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WeatherAncestor( 7536): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:16:2
D/Weather.Utils( 7536): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7536): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7536): 2 : This is isUpdating : false
D/WeatherAncestor( 7536): connectivity changed - connection : true
D/WeatherService( 7536): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@37a6152a
V/DownloadManager( 3387): processing inserted download 9
D/ForecastDataCache( 7536): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7536): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7536): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7536): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7536): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:16:2
V/DownloadManager( 3387): processing inserted download 10
V/DownloadManager( 3387): processing inserted download 16
V/DownloadManager( 3387): processing inserted download 17
V/DownloadManager( 3387): processing inserted download 18
V/DownloadManager( 3387): processing inserted download 21
V/DownloadManager( 3387): DownloadService onDestroy
,D/ChimeraCfgMgr( 2393): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6636): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7409): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7409): onReceive
D/AppUp4:CustFacade( 7409): Context : android.app.ReceiverRestrictedContext@2802fbcc
D/AppUp4:CustFacade( 7409): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7409): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7409): begin check event
I/AppUp4:CustModeStarterReceiver( 7409): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,V/FormManager( 7468): There are no updated forms. The schedule will be deleted.
W/ContextImpl( 4289): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4289): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/FormManager( 7468): Alarm would be updated, because LastCheckTime has been updated.
V/DownloadManager( 3387): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4289): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3387): DownloadService onCreate
,I/LGDMClient( 4289): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4289): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4289): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,W/ContextImpl( 4289): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3387): in removeSpuriousFiles
V/DownloadManager( 3387): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 3349): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3349): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3349): networkInfo.isConnected() = true
D/PhoneState( 3349): setPdpRejectCasuse : false
V/DownloadManager( 3387): created cursor android.database.sqlite.SQLiteCursor@32cf9af4 on behalf of 3387
,I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3387): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
W/Settings( 7435): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 4289): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4289): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4289): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/DownloadManager( 3387): in trimDatabase
V/DownloadManager( 3387): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3387): DownloadService onStartCommand
,V/DownloadManager( 3387): created cursor android.database.sqlite.SQLiteCursor@32bbe663 on behalf of 3387
D/WeatherAncestor( 7536): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:16:2
W/Settings( 7435): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3387): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3387): created cursor android.database.sqlite.SQLiteCursor@2dc57260 on behalf of 3387
V/DownloadManager( 3387): processing inserted download 1
V/DownloadManager( 3387): processing inserted download 4
V/DownloadManager( 3387): processing inserted download 7
D/Weather.Utils( 7536): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7536): 2 : All the weather widget is gone.
V/DownloadManager( 3387): processing inserted download 8
V/DownloadManager( 3387): processing inserted download 9
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/UpdateThreadPoolManager( 7536): 2 : This is isUpdating : false
D/WeatherAncestor( 7536): connectivity changed - connection : true
D/WeatherService( 7536): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@37a6152a
V/DownloadManager( 3387): processing inserted download 10
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ForecastDataCache( 7536): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7536): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7536): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7536): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7536): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:16:2
V/DownloadManager( 3387): processing inserted download 16
V/DownloadManager( 3387): processing inserted download 17
V/DownloadManager( 3387): processing inserted download 18
W/Kids    ( 2393): [AccountUtils] Account not ready
W/Kids    ( 2393): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2393): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2393): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2393): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2393): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2393): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2393): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2393): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2393): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2393): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2393): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2393): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3387): processing inserted download 21
V/DownloadManager( 3387): DownloadService onDestroy
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
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
,D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/libc-netbsd(  330): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  330): res_queryN name = www.google.com, class = 1, type = 1
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{32cf9af4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/ChimeraCfgMgr( 2393): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=227359499 [*alarm*], flags=0x0
D/libc-netbsd(  330): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  330): res_queryN name = mtalk.google.com, class = 1, type = 1
D/libc-netbsd(  330): res_queryN name = www.google.com succeed
,D/libc-netbsd(  330): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  330): res_queryN name = clients3.google.com, class = 1, type = 1
V/FormManager( 7468): There are no updated forms. The schedule will be deleted.
V/FormManager( 7468): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2393): [AccountUtils] Account not ready
W/Kids    ( 2393): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2393): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2393): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2393): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2393): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2393): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2393): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2393): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2393): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2393): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2393): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2393): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
D/libc-netbsd(  330): res_queryN name = mtalk.google.com succeed
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
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/libc-netbsd(  330): res_queryN name = clients3.google.com succeed
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{32cf9af4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/WifiInternetCheck( 1038): isHttpConnectionAvailable - We got a valid response : 204
,I/jxcore-log( 7224): Test app app.js loaded
I/jxcore-log( 7224): 
,I/Choreographer( 7224): Skipped 418 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7224): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 7224): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/GCM     ( 2143): Connected
,D/GCM     ( 2143): Message class com.google.f.a.a.p
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{2dae588c type 2 when 260657 android} when 260657
,I/GAV4    ( 7557): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1038): Killing 7034:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10054/pid_7034/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 267213687608; DSPS: 8897754; Offset : -4334704805
,I/jxcore-log( 7224): TAP version 13
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # multiplex can send data
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 1 String should be length:200
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # basic
I/jxcore-log( 7224): 
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 287215535673; DSPS: 9553174; Offset : -4334687794
,E/WifiStateMachine( 1038):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{38ab92db type 2 when 302244 android} when 302244
,I/ActivityManager( 1038): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7710 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 7710): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 7710): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7710): Created application version: 3.2.35 (30235)
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/BooksSync( 7710): Starting books sync
,D/BooksSync( 7710): started syncMyEbooks
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7710): Authentication error
E/BooksAccountManager( 7710): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7710): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7710): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7710): null auth token
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
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/libc-netbsd(  330): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  330): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
,D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{32cf9af4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  330): res_queryN name = www.googleapis.com succeed
W/ApiaryClient( 7710): Error response from books API: {
W/ApiaryClient( 7710):  "error": {
W/ApiaryClient( 7710):   "errors": [
W/ApiaryClient( 7710):    {
W/ApiaryClient( 7710):     "domain": "global",
W/ApiaryClient( 7710):     "reason": "required",
W/ApiaryClient( 7710):     "message": "Login Required",
W/ApiaryClient( 7710):     "locationType": "header",
W/ApiaryClient( 7710):     "location": "Authorization"
W/ApiaryClient( 7710):    }
W/ApiaryClient( 7710):   ],
W/ApiaryClient( 7710):   "code": 401,
W/ApiaryClient( 7710):   "message": "Login Required"
W/ApiaryClient( 7710):  }
W/ApiaryClient( 7710): }
W/ApiaryClient( 7710): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7710): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3887221357775430932&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7710): Headers:
W/ApiaryClient( 7710): accept-encoding: [gzip]
W/ApiaryClient( 7710): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7710): gdata-version: 2
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7710): Authentication error
E/BooksAccountManager( 7710): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7710): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7710): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7710): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{32cf9af4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/jxcore-log( 7224): ok 2 sane
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
W/ApiaryClient( 7710): Error response from books API: {
W/ApiaryClient( 7710):  "error": {
W/ApiaryClient( 7710):   "errors": [
W/ApiaryClient( 7710):    {
W/ApiaryClient( 7710):     "domain": "global",
W/ApiaryClient( 7710):     "reason": "required",
W/ApiaryClient( 7710):     "message": "Login Required",
W/ApiaryClient( 7710):     "locationType": "header",
W/ApiaryClient( 7710):     "location": "Authorization"
W/ApiaryClient( 7710):    }
W/ApiaryClient( 7710):   ],
W/ApiaryClient( 7710):   "code": 401,
W/ApiaryClient( 7710):   "message": "Login Required"
W/ApiaryClient( 7710):  }
W/ApiaryClient( 7710): }
,W/ApiaryClient( 7710): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7710): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3887221357775430932&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7710): Headers:
W/ApiaryClient( 7710): accept-encoding: [gzip]
W/ApiaryClient( 7710): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7710): gdata-version: 2
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7710): Authentication error
E/BooksAccountManager( 7710): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7710): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7710): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7710): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{32cf9af4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/jxcore-log( 7224): # another
I/jxcore-log( 7224): 
,W/ApiaryClient( 7710): Error response from books API: {
W/ApiaryClient( 7710):  "error": {
W/ApiaryClient( 7710):   "errors": [
W/ApiaryClient( 7710):    {
W/ApiaryClient( 7710):     "domain": "global",
W/ApiaryClient( 7710):     "reason": "required",
W/ApiaryClient( 7710):     "message": "Login Required",
W/ApiaryClient( 7710):     "locationType": "header",
W/ApiaryClient( 7710):     "location": "Authorization"
W/ApiaryClient( 7710):    }
W/ApiaryClient( 7710):   ],
W/ApiaryClient( 7710):   "code": 401,
W/ApiaryClient( 7710):   "message": "Login Required"
W/ApiaryClient( 7710):  }
W/ApiaryClient( 7710): }
,W/ApiaryClient( 7710): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7710): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3887221357775430932&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7710): Headers:
W/ApiaryClient( 7710): accept-encoding: [gzip]
W/ApiaryClient( 7710): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7710): gdata-version: 2
I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,E/BooksSync( 7710): Soft error: 
E/BooksSync( 7710): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7710): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3887221357775430932&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7710): Headers:
E/BooksSync( 7710): accept-encoding: [gzip]
E/BooksSync( 7710): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7710): gdata-version: 2
E/BooksSync( 7710): 
E/BooksSync( 7710): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7710): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7710): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7710): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7710): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7710): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7710): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7710): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7710): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7710): {
E/BooksSync( 7710):  "error": {
E/BooksSync( 7710):   "errors": [
E/BooksSync( 7710):    {
E/BooksSync( 7710):     "domain": "global",
E/BooksSync( 7710):     "reason": "required",
E/BooksSync( 7710):     "message": "Login Required",
E/BooksSync( 7710):     "locationType": "header",
E/BooksSync( 7710):     "location": "Authorization"
E/BooksSync( 7710):    }
E/BooksSync( 7710):   ],
E/BooksSync( 7710):   "code": 401,
E/BooksSync( 7710):   "message": "Login Required"
E/BooksSync( 7710):  }
E/BooksSync( 7710): }
E/BooksSync( 7710): 
E/BooksSync( 7710): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7710): 	... 8 more
,E/BooksSync( 7710): Sync error
E/BooksSync( 7710): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7710): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=3887221357775430932&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7710): Headers:
E/BooksSync( 7710): accept-encoding: [gzip]
E/BooksSync( 7710): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7710): gdata-version: 2
E/BooksSync( 7710): 
E/BooksSync( 7710): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7710): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7710): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7710): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7710): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7710): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7710): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7710): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7710): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7710): {
E/BooksSync( 7710):  "error": {
E/BooksSync( 7710):   "errors": [
E/BooksSync( 7710):    {
E/BooksSync( 7710):     "domain": "global",
E/BooksSync( 7710):     "reason": "required",
E/BooksSync( 7710):     "message": "Login Required",
E/BooksSync( 7710):     "locationType": "header",
E/BooksSync( 7710):     "location": "Authorization"
E/BooksSync( 7710):    }
E/BooksSync( 7710):   ],
E/BooksSync( 7710):   "code": 401,
E/BooksSync( 7710):   "message": "Login Required"
E/BooksSync( 7710):  }
E/BooksSync( 7710): }
E/BooksSync( 7710): 
E/BooksSync( 7710): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7710): 	... 8 more
I/BooksSync( 7710): Finished books sync
I/ActivityManager( 1038): Killing 7150:com.lge.clock/u0a10 (adj 15): empty #17
,D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 302244, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1038): failed to open /acct/uid_10010/pid_7150/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 307217502644; DSPS: 10208599; Offset : -4334704440
,I/GAV2    ( 7710): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 7224): ok 3 sane
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 4 should be equal
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 5 null
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 6 (unnamed assert)
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ok 7 should be equal
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 8 should not throw
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
I/jxcore-log( 7224): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 9 (unnamed assert)
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 10 (unnamed assert)
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 11 should not throw
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ok 12 should be equal
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ok 13 should be equal
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 327219454617; DSPS: 10864023; Offset : -4334705592
,I/jxcore-log( 7224): ok 14 should be equal
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # failed to get mobile documents path
I/jxcore-log( 7224): 
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=227359499, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{3c99dfb4 type 2 when 332388 android} when 332388
D/[Concierge]Service( 2663): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=227359499 [*alarm*], flags=0x0
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 15 should be equal
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 16 should be equal
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ok 17 should be equal
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ok 18 should be equal
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # #init should register the networkChanged event
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 19 should be equal
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # #startBroadcasting should throw on null device name
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 347220905130; DSPS: 11519430; Offset : -4334689562
,I/jxcore-log( 7224): ok 20 should throw
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 21 should throw
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # #startBroadcasting should throw on non-number port
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 22 should throw
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # #startBroadcasting should throw on NaN port
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 23 should throw
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # #startBroadcasting should throw on negative port
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 24 should throw
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # #startBroadcasting should throw on too large port
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 25 should throw
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 26 should be equal
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ok 27 should be equal
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ok 28 should be equal
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 367222378300; DSPS: 12174838; Offset : -4334681157
,I/jxcore-log( 7224): ok 29 should be equal
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ok 30 should be equal
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ok 31 should be equal
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 25846(1194KB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/66MB, paused 2.289ms total 179.265ms
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 6321): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6321): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6321): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6321): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6321): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6321): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6321): 	at android.os.Binder.execTransact(Binder.java:446)
,D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1419): post do just update job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
,E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true,
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/System  ( 6321): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  330): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  330): res_queryN name = play.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{32cf9af4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  330): res_queryN name = play.googleapis.com succeed
,I/jxcore-log( 7224): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 7224): 
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=227359499, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,D/[Concierge]Service( 2663): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=227359499 [*alarm*], flags=0x0
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 32 should be equal
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ok 33 should be equal
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 7224): 
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 387224027302; DSPS: 12830253; Offset : -4334710492
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 34 should be equal
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ok 35 should be equal
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 36 should be equal
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ok 37 should be equal
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 38 should be equal
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 407226047554; DSPS: 13485679; Offset : -4334704531
,I/jxcore-log( 7224): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 39 should be equal
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 40 should be equal
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # should call Mobile("Disconnect") without an error
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ok 41 should be equal
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ok 42 should be equal
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 427227922808; DSPS: 14141100; Offset : -4334690822
,I/jxcore-log( 7224): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,I/jxcore-log( 7224): ok 43 should be equal
I/jxcore-log( 7224): 
I/jxcore-log( 7224): ok 44 should be equal
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
I/jxcore-log( 7224): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 7224): 
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 447229819467; DSPS: 14796522; Offset : -4334686253
,I/jxcore-log( 7224): # teardown
I/jxcore-log( 7224): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269962973.7224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): bind: Binding a new listener
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269962973.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7224): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3796): [BTUI] createSocketChannel FD=84 mFd=82
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: OK
I/io.jxcore.node.ConnectionHelper( 7224): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269962973.7224
,D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269962973.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): start: {"pi":"58:3F:54:73:64:C0","pn":"1452269962973.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452269962973.7224","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8a7b90e6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8a7b90e6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState add service
D/LGWifiP2pService( 1038): add a new client
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936323937332e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936323937332e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936323937331f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936323937331f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): start: Starting P2P device discovery...
,D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2661): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1998): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1038): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1038): P2P_FIND 120: returned true
D/LGWifiP2pService( 1038): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7224): start: OK
I/jxcore-log( 7224): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 7224): 
I/io.jxcore.node.ConnectionHelper( 7224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): stop: Stopping services
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936323937331f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936323937331f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1038): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2661): P2P-FIND-STOPPED 
D/WfdsMonitor( 1998): Event [P2P-FIND-STOPPED ]
,D/WifiMonitor( 1038): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1038): P2P_STOP_FIND: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: NOT_STARTED
I/jxcore-log( 7224): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 7224): 
D/LGWifiP2pService( 1038): InactiveState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): discovery change broadcast false
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service request
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963093.7224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): bind: Binding a new listener
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963093.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7224): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: OK
I/io.jxcore.node.ConnectionHelper( 7224): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963093.7224
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963093.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): start: {"pi":"58:3F:54:73:64:C0","pn":"1452269963093.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452269963093.7224","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@45380af2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@45380af2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState add service
D/LGWifiP2pService( 1038): add a new client
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333039332e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333039332e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333039331f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333039331f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7224): start: OK
I/jxcore-log( 7224): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 7224): 
I/io.jxcore.node.ConnectionHelper( 7224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): shutdown
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2661): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1998): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1038): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
,D/WifiNative-p2p0( 1038): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: NOT_STARTED
I/jxcore-log( 7224): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 7224): 
D/LGWifiP2pService( 1038): discovery change broadcast true
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963141.7224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): bind: Binding a new listener
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333039331f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963141.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7224): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: OK
I/io.jxcore.node.ConnectionHelper( 7224): start: Using peer discovery mode: WIFI
,D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333039331f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1038): remove client information from framework
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963141.7224
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963141.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): start: {"pi":"58:3F:54:73:64:C0","pn":"1452269963141.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452269963141.7224","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1038): InactiveState{ when=-24ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2661): P2P-FIND-STOPPED 
D/WfdsMonitor( 1998): Event [P2P-FIND-STOPPED ]
,D/WifiMonitor( 1038): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=38 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1038): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1038): InactiveState{ when=-33ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-33ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service request
D/LGWifiP2pService( 1038): InactiveState{ when=-8ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-9ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): discovery change broadcast false
D/LGWifiP2pService( 1038): InactiveState{ when=-2ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@44ee39fe target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-2ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@44ee39fe target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState add service
D/LGWifiP2pService( 1038): add a new client
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333134312e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7224): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Waiting for incoming connections...
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333134312e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333134311f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/jxcore-log( 7224): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 7224): 
I/io.jxcore.node.ConnectionHelper( 7224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: NOT_STARTED
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333134311f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_FIND 120
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: NOT_STARTED
I/wpa_supplicant( 2661): p2p0: P2P: Reject scan trigger, since one is already pending
I/jxcore-log( 7224): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 7224): 
D/WfdsMonitor( 1998): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1038): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=39 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1038): P2P_FIND 120: returned true
D/LGWifiP2pService( 1038): discovery change broadcast true
D/LGWifiP2pService( 1038): InactiveState{ when=-4ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-4ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333134311f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963191.7224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): bind: Binding a new listener
,D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333134311f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1038): remove client information from framework
D/LGWifiP2pService( 1038): InactiveState{ when=-9ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_STOP_FIND
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/wpa_supplicant( 2661): P2P-FIND-STOPPED 
D/WfdsMonitor( 1998): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963191.7224","ra":"58:3F:54:73:64:C0"}
D/WifiMonitor( 1038): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): setConnectionTimeout: 15000
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): startListeningForIncomingConnections: Starting...
D/WifiNative-p2p0( 1038): P2P_STOP_FIND: returned true
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): discovery change broadcast false
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service request
W/BluetoothAdapter( 7224): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: OK
I/io.jxcore.node.ConnectionHelper( 7224): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963191.7224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Waiting for incoming connections...
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963191.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): start: {"pi":"58:3F:54:73:64:C0","pn":"1452269963191.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452269963191.7224","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8ea8f2b4 target=com.android.in,ternal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8ea8f2b4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState add service
D/LGWifiP2pService( 1038): add a new client
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333139312e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333139312e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333139311f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333139311f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): start: Starting P2P device discovery...
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2661): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1998): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1038): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=41 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7224): start: OK
D/WifiNative-p2p0( 1038): P2P_FIND 120: returned true
D/LGWifiP2pService( 1038): discovery change broadcast true
I/jxcore-log( 7224): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 7224): 
I/io.jxcore.node.ConnectionHelper( 7224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: NOT_STARTED
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333139311f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/jxcore-log( 7224): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 7224): 
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333139311f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1038): remove client information from framework
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2661): P2P-FIND-STOPPED 
D/WfdsMonitor( 1998): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1038): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=42 dispatchEvent: P2P-FIND-STOPPED 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963217.7224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): bind: Binding a new listener
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/WifiNative-p2p0( 1038): P2P_STOP_FIND: returned true
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963217.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7224): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: OK
I/io.jxcore.node.ConnectionHelper( 7224): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1038): InactiveState{ when=-9ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-9ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963217.7224
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963217.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): bind: Binding a new listener
D/LGWifiP2pService( 1038): InactiveState{ when=-11ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-11ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): start: {"pi":"58:3F:54:73:64:C0","pn":"1452269963217.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452269963217.7224","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a7849676 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a7849676 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState add service
D/LGWifiP2pService( 1038): add a new client
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333231372e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333231372e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333231371f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333231371f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): start: Starting P2P device discovery...
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2661): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1998): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1038): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiNative-p2p0( 1038): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7224): start: OK
D/LGWifiP2pService( 1038): discovery change broadcast true
I/jxcore-log( 7224): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 7224): 
I/io.jxcore.node.ConnectionHelper( 7224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): stop: Stopping services
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333231371f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333231371f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1038): remove client information from framework
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: NOT_STARTED
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2661): P2P-FIND-STOPPED 
D/WfdsMonitor( 1998): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1038): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1038): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service request
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 7224): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 7224): 
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963244.7224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): bind: Binding a new listener
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963244.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7224): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: OK
I/io.jxcore.node.ConnectionHelper( 7224): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963244.7224
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963244.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): start: {"pi":"58:3F:54:73:64:C0","pn":"1452269963244.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452269963244.7224","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@39bc8ff6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@39bc8ff6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState add service
D/LGWifiP2pService( 1038): add a new client
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333234342e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: INITIALIZED
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333234342e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333234341f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333234341f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7224): start: OK
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2661): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1038): P2P_FIND 120: returned true
D/WfdsMonitor( 1998): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1038): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService( 1038): discovery change broadcast true
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 7224): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 7224): 
I/io.jxcore.node.ConnectionHelper( 7224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): stop: Stopping services
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: NOT_STARTED
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333234341f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333234341f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1038): remove client information from framework
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_STOP_FIND
,I/wpa_supplicant( 2661): P2P-FIND-STOPPED 
D/WfdsMonitor( 1998): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1038): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=46 dispatchEvent: P2P-FIND-STOPPED 
I/jxcore-log( 7224): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 7224): 
D/WifiNative-p2p0( 1038): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1038): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service request
D/LGWifiP2pService( 1038): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963272.7224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): bind: Binding a new listener
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963272.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7224): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: OK
I/io.jxcore.node.ConnectionHelper( 7224): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963272.7224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Waiting for incoming connections...
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963272.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): start: {"pi":"58:3F:54:73:64:C0","pn":"1452269963272.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452269963272.7224","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@54a0d2b4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@54a0d2b4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState add service
D/LGWifiP2pService( 1038): add a new client
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333237322e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333237322e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333237321f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333237321f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): start: Starting P2P device discovery...
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: OK
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: RUNNING
D/WifiNative-p2p0( 1038): doBoolean: P2P_FIND 120
I/io.jxcore.node.ConnectionHelper( 7224): start: OK
I/wpa_supplicant( 2661): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1998): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1038): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=47 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1038): P2P_FIND 120: returned true
D/LGWifiP2pService( 1038): discovery change broadcast true
I/jxcore-log( 7224): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 7224): 
I/io.jxcore.node.ConnectionHelper( 7224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): stop: Stopping services
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: NOT_STARTED
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333237321f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333237321f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1038): remove client information from framework
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2661): P2P-FIND-STOPPED 
D/WfdsMonitor( 1998): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1038): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=48 dispatchEvent: P2P-FIND-STOPPED 
I/jxcore-log( 7224): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 7224): 
D/WifiNative-p2p0( 1038): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service request
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963296.7224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): bind: Binding a new listener
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963296.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7224): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: OK
I/io.jxcore.node.ConnectionHelper( 7224): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963296.7224
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963296.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): start: {"pi":"58:3F:54:73:64:C0","pn":"1452269963296.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452269963296.7224","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@94cfdb28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@94cfdb28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState add service
D/LGWifiP2pService( 1038): add a new client
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333239362e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333239362e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333239361f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7224): start: OK
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333239361f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_FIND 120
I/jxcore-log( 7224): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 7224): 
I/wpa_supplicant( 2661): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1998): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1038): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 7224): stop
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=49 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1038): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: NOT_STARTED
D/LGWifiP2pService( 1038): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): stop: Stopping services
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: The given listener does not exist in the list
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333239361f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: NOT_STARTED
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333239361f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1038): remove client information from framework
I/jxcore-log( 7224): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 7224): 
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2661): P2P-FIND-STOPPED 
D/WfdsMonitor( 1998): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1038): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-FIND-STOPPED 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
D/WifiNative-p2p0( 1038): P2P_STOP_FIND: returned true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1038): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-4ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963316.7224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): bind: Binding a new listener
D/LGWifiP2pService( 1038): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): discovery change broadcast false
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963316.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7224): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: OK
I/io.jxcore.node.ConnectionHelper( 7224): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963316.7224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Waiting for incoming connections...
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963316.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): start: {"pi":"58:3F:54:73:64:C0","pn":"1452269963316.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452269963316.7224","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@79a1c776 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@79a1c776 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState add service
D/LGWifiP2pService( 1038): add a new client
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333331362e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333331362e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333331361f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333331361f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7224): start: OK
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2661): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1998): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1038): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=51 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 7224): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 7224): 
D/WifiNative-p2p0( 1038): P2P_FIND 120: returned true
D/LGWifiP2pService( 1038): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 7224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333331361f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: NOT_STARTED
I/jxcore-log( 7224): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 7224): 
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333331361f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
D/LGWifiP2pService( 1038): remove client information from framework
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2661): P2P-FIND-STOPPED 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to WIFI
D/WfdsMonitor( 1998): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1038): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=52 dispatchEvent: P2P-FIND-STOPPED 
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-p2p0( 1038): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1038): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963344.7224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): bind: Binding a new listener
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service request
D/LGWifiP2pService( 1038): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963344.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7224): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): start: OK
I/io.jxcore.node.ConnectionHelper( 7224): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: Peer ID: 58:3F:54:73:64:C0, peer name: 1452269963344.7224
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Waiting for incoming connections...
,D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7224): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"1452269963344.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): start: {"pi":"58:3F:54:73:64:C0","pn":"1452269963344.7224","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"1452269963344.7224","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@94860a34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@94860a34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState add service
D/LGWifiP2pService( 1038): add a new client
,D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333334342e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): start: Starting P2P device discovery...
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a22313435323236393936333334342e37323234222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333334341f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: RUNNING
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333334341f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
I/io.jxcore.node.ConnectionHelper( 7224): start: OK
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2661): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1998): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1038): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=53 dispatchEvent: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 7224): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 7224): 
D/WifiNative-p2p0( 1038): P2P_FIND 120: returned true
D/LGWifiP2pService( 1038): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 7224): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7224): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7224): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7224): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7224): stop: Stopping services
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1038): P2pEnabledState clear service
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: NOT_INITIALIZED
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333334341f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7224): release: No more listeners, de-initializing...
D/WifiNative-p2p0( 1038): P2P_SERVICE_DEL bonjour 2d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a22313435323236393936333334341f37323234222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7224): release: No more listeners, de-initializing...
D/LGWifiP2pService( 1038): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setState: NOT_STARTED
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2661): P2P-FIND-STOPPED 
D/WfdsMonitor( 1998): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1038): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=54 dispatchEvent: P2P-FIND-STOPPED 
I/jxcore-log( 7224): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 7224): 
D/WifiNative-p2p0( 1038): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState clear service request
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): discovery change broadcast false
I/jxcore-log( 7224): # setup
I/jxcore-log( 7224): 
,I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7224): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7224): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7224): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery stopped successfully
I/io.j,xcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7224): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7224): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7224): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7224): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: NOT_STARTED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7224): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local services cleared successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7224): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 7224): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 7224): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7224): Local services cleared successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7224): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7224): Service requests cleared successfully
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 467231357532; DSPS: 15451933; Offset : -4334704714
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 487233378931; DSPS: 16107359; Offset : -4334697345
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
,I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 507235407776; DSPS: 16762785; Offset : -4334682557
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 527237302770; DSPS: 17418208; Offset : -4334710327
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 547238672294; DSPS: 18073612; Offset : -4334683471
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=227359499, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{1dc00722 type 2 when 561763 android} when 561763
D/[Concierge]Service( 2663): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=227359499 [*alarm*], flags=0x0
,I/BooksSync( 7710): Starting books sync
,D/BooksSync( 7710): started syncMyEbooks
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7710): Authentication error
E/BooksAccountManager( 7710): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7710): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7710): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7710): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{32cf9af4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  330): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  330): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  330): res_queryN name = www.googleapis.com succeed
W/ApiaryClient( 7710): Error response from books API: {
W/ApiaryClient( 7710):  "error": {
W/ApiaryClient( 7710):   "errors": [
W/ApiaryClient( 7710):    {
W/ApiaryClient( 7710):     "domain": "global",
W/ApiaryClient( 7710):     "reason": "required",
W/ApiaryClient( 7710):     "message": "Login Required",
W/ApiaryClient( 7710):     "locationType": "header",
W/ApiaryClient( 7710):     "location": "Authorization"
W/ApiaryClient( 7710):    }
W/ApiaryClient( 7710):   ],
W/ApiaryClient( 7710):   "code": 401,
W/ApiaryClient( 7710):   "message": "Login Required"
W/ApiaryClient( 7710):  }
W/ApiaryClient( 7710): }
W/ApiaryClient( 7710): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7710): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3101294464087474517&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7710): Headers:
W/ApiaryClient( 7710): accept-encoding: [gzip]
W/ApiaryClient( 7710): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7710): gdata-version: 2
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7710): Authentication error
E/BooksAccountManager( 7710): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7710): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7710): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7710): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
,D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{32cf9af4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7710): Error response from books API: {
W/ApiaryClient( 7710):  "error": {
W/ApiaryClient( 7710):   "errors": [
W/ApiaryClient( 7710):    {
W/ApiaryClient( 7710):     "domain": "global",
W/ApiaryClient( 7710):     "reason": "required",
W/ApiaryClient( 7710):     "message": "Login Required",
W/ApiaryClient( 7710):     "locationType": "header",
W/ApiaryClient( 7710):     "location": "Authorization"
W/ApiaryClient( 7710):    }
W/ApiaryClient( 7710):   ],
W/ApiaryClient( 7710):   "code": 401,
W/ApiaryClient( 7710):   "message": "Login Required"
W/ApiaryClient( 7710):  }
W/ApiaryClient( 7710): }
W/ApiaryClient( 7710): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7710): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3101294464087474517&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7710): Headers:
W/ApiaryClient( 7710): accept-encoding: [gzip]
W/ApiaryClient( 7710): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7710): gdata-version: 2
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7710): Authentication error
E/BooksAccountManager( 7710): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7710): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7710): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7710): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{32cf9af4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7710): Error response from books API: {
W/ApiaryClient( 7710):  "error": {
W/ApiaryClient( 7710):   "errors": [
W/ApiaryClient( 7710):    {
W/ApiaryClient( 7710):     "domain": "global",
W/ApiaryClient( 7710):     "reason": "required",
W/ApiaryClient( 7710):     "message": "Login Required",
W/ApiaryClient( 7710):     "locationType": "header",
W/ApiaryClient( 7710):     "location": "Authorization"
W/ApiaryClient( 7710):    }
W/ApiaryClient( 7710):   ],
W/ApiaryClient( 7710):   "code": 401,
W/ApiaryClient( 7710):   "message": "Login Required"
W/ApiaryClient( 7710):  }
W/ApiaryClient( 7710): }
,W/ApiaryClient( 7710): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7710): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3101294464087474517&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7710): Headers:
W/ApiaryClient( 7710): accept-encoding: [gzip]
W/ApiaryClient( 7710): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7710): gdata-version: 2
E/BooksSync( 7710): Soft error: 
E/BooksSync( 7710): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7710): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3101294464087474517&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7710): Headers:
E/BooksSync( 7710): accept-encoding: [gzip]
E/BooksSync( 7710): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7710): gdata-version: 2
E/BooksSync( 7710): 
E/BooksSync( 7710): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7710): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7710): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7710): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7710): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7710): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7710): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7710): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7710): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7710): {
E/BooksSync( 7710):  "error": {
E/BooksSync( 7710):   "errors": [
E/BooksSync( 7710):    {
E/BooksSync( 7710):     "domain": "global",
E/BooksSync( 7710):     "reason": "required",
E/BooksSync( 7710):     "message": "Login Required",
E/BooksSync( 7710):     "locationType": "header",
E/BooksSync( 7710):     "location": "Authorization"
E/BooksSync( 7710):    }
E/BooksSync( 7710):   ],
E/BooksSync( 7710):   "code": 401,
E/BooksSync( 7710):   "message": "Login Required"
E/BooksSync( 7710):  }
E/BooksSync( 7710): }
E/BooksSync( 7710): 
E/BooksSync( 7710): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7710): 	... 8 more
,E/BooksSync( 7710): Sync error
E/BooksSync( 7710): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7710): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3101294464087474517&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7710): Headers:
E/BooksSync( 7710): accept-encoding: [gzip]
E/BooksSync( 7710): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7710): gdata-version: 2
E/BooksSync( 7710): 
E/BooksSync( 7710): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7710): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7710): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7710): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7710): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7710): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7710): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7710): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7710): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7710): {
E/BooksSync( 7710):  "error": {
E/BooksSync( 7710):   "errors": [
E/BooksSync( 7710):    {
E/BooksSync( 7710):     "domain": "global",
E/BooksSync( 7710):     "reason": "required",
E/BooksSync( 7710):     "message": "Login Required",
E/BooksSync( 7710):     "locationType": "header",
E/BooksSync( 7710):     "location": "Authorization"
E/BooksSync( 7710):    }
E/BooksSync( 7710):   ],
E/BooksSync( 7710):   "code": 401,
E/BooksSync( 7710):   "message": "Login Required"
E/BooksSync( 7710):  }
E/BooksSync( 7710): }
E/BooksSync( 7710): 
E/BooksSync( 7710): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7710): 	... 8 more
I/BooksSync( 7710): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 561763, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 567240779733; DSPS: 18729041; Offset : -4334681771
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 587242453372; DSPS: 19384456; Offset : -4334686625
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{151f96fc type 2 when 591967 android} when 591967
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 607244353208; DSPS: 20039878; Offset : -4334678957
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 627246294137; DSPS: 20695302; Offset : -4334691153
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 647247872359; DSPS: 21350714; Offset : -4334699872
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=227359499, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,D/[Concierge]Service( 2663): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=227359499 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 667249563654; DSPS: 22006129; Offset : -4334686887
,I/[SystemUI]LGPowerUI( 1466): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1466): On Skip Timer : true
,D/LEDHandler( 1998): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1998): Battery Level Remaining: 100%
D/LEDHandler( 1998): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1466): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1466): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1038): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1466): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3796): Disconnected process message: 10, size: 0
D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 687251610730; DSPS: 22661556; Offset : -4334684410
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 707253119315; DSPS: 23316966; Offset : -4334701808
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 727254999985; DSPS: 23972387; Offset : -4334682946
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 747256971436; DSPS: 24627812; Offset : -4334694902
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 767259161948; DSPS: 25283244; Offset : -4334701786
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 787261336525; DSPS: 25938675; Offset : -4334694088
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 807263191726; DSPS: 26594096; Offset : -4334700224
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 827264525050; DSPS: 27249500; Offset : -4334709857
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 847266110617; DSPS: 27904912; Offset : -4334711151
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
,I/[SystemUI]Clock( 1466): called onTimeUpdated()
I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 867267889098; DSPS: 28560330; Offset : -4334702611
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 887269767944; DSPS: 29215751; Offset : -4334685364
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 907272240698; DSPS: 29871192; Offset : -4334684534
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 927274220274; DSPS: 30526617; Offset : -4334688496
,I/[SystemUI]LGPowerUI( 1466): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1466): On Skip Timer : true
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController( 1038): battery changed pluggedType: 2
D/HeadsetStateMachine( 3796): Disconnected process message: 10, size: 0
,D/LEDHandler( 1998): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1998): Battery Level Remaining: 100%
D/LEDHandler( 1998): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1466): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1466): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1466): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=227359499, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,W/bt-smp  ( 3796): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3796): Plain text(LSB ~ MSB) = d1 a6 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3796): Encrypted text(LSB ~ MSB) = 3e 70 2b fa ac b2 e4 ad 21 77 b5 84 5a 77 55 bc 
,W/bt-btm  ( 3796): Stopping oneshot timer
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{215c4185 type 2 when 943424 com.android.bluetooth} when 943424
D/[Concierge]Service( 2663): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=227359499 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 947276195681; DSPS: 31182042; Offset : -4334696940
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 967278171873; DSPS: 31837467; Offset : -4334704339
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 987279911708; DSPS: 32492884; Offset : -4334703693
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1007281511910; DSPS: 33148296; Offset : -4334690744
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1027283095340; DSPS: 33803708; Offset : -4334694175
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1047284759707; DSPS: 34459123; Offset : -4334708223
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1067286420012; DSPS: 35114537; Offset : -4334695945
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=227359499, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{21c9bda type 2 when 1075115 android} when 1075115
D/[Concierge]Service( 2663): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=227359499 [*alarm*], flags=0x0
,I/BooksSync( 7710): Starting books sync
,D/BooksSync( 7710): started syncMyEbooks
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2143): Explicit concurrent mark sweep GC freed 34423(1994KB) AllocSpace objects, 23(3MB) LOS objects, 51% free, 30MB/62MB, paused 2.615ms total 56.246ms
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
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
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
E/BooksAccountManager( 7710): Authentication error
E/BooksAccountManager( 7710): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7710): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7710): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7710): null auth token
,D/libc-netbsd(  330): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  330): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{32cf9af4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  330): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7710): Error response from books API: {
W/ApiaryClient( 7710):  "error": {
W/ApiaryClient( 7710):   "errors": [
W/ApiaryClient( 7710):    {
W/ApiaryClient( 7710):     "domain": "global",
W/ApiaryClient( 7710):     "reason": "required",
W/ApiaryClient( 7710):     "message": "Login Required",
W/ApiaryClient( 7710):     "locationType": "header",
W/ApiaryClient( 7710):     "location": "Authorization"
W/ApiaryClient( 7710):    }
W/ApiaryClient( 7710):   ],
W/ApiaryClient( 7710):   "code": 401,
W/ApiaryClient( 7710):   "message": "Login Required"
W/ApiaryClient( 7710):  }
W/ApiaryClient( 7710): }
,W/ApiaryClient( 7710): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7710): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=433582523555718663&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7710): Headers:
W/ApiaryClient( 7710): accept-encoding: [gzip]
W/ApiaryClient( 7710): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7710): gdata-version: 2
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7710): Authentication error
E/BooksAccountManager( 7710): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7710): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7710): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7710): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{32cf9af4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7710): Error response from books API: {
W/ApiaryClient( 7710):  "error": {
W/ApiaryClient( 7710):   "errors": [
W/ApiaryClient( 7710):    {
W/ApiaryClient( 7710):     "domain": "global",
W/ApiaryClient( 7710):     "reason": "required",
W/ApiaryClient( 7710):     "message": "Login Required",
W/ApiaryClient( 7710):     "locationType": "header",
W/ApiaryClient( 7710):     "location": "Authorization"
W/ApiaryClient( 7710):    }
W/ApiaryClient( 7710):   ],
W/ApiaryClient( 7710):   "code": 401,
W/ApiaryClient( 7710):   "message": "Login Required"
W/ApiaryClient( 7710):  }
W/ApiaryClient( 7710): }
,W/ApiaryClient( 7710): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7710): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=433582523555718663&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7710): Headers:
W/ApiaryClient( 7710): accept-encoding: [gzip]
W/ApiaryClient( 7710): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7710): gdata-version: 2
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 32079(1690KB) AllocSpace objects, 7(880KB) LOS objects, 33% free, 44MB/66MB, paused 3.199ms total 159.610ms
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2143): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2143): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2143): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2143): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2143): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7710): Authentication error
E/BooksAccountManager( 7710): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7710): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7710): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7710): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7710): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{32cf9af4 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7710): Error response from books API: {
W/ApiaryClient( 7710):  "error": {
W/ApiaryClient( 7710):   "errors": [
W/ApiaryClient( 7710):    {
W/ApiaryClient( 7710):     "domain": "global",
W/ApiaryClient( 7710):     "reason": "required",
W/ApiaryClient( 7710):     "message": "Login Required",
W/ApiaryClient( 7710):     "locationType": "header",
W/ApiaryClient( 7710):     "location": "Authorization"
W/ApiaryClient( 7710):    }
W/ApiaryClient( 7710):   ],
W/ApiaryClient( 7710):   "code": 401,
W/ApiaryClient( 7710):   "message": "Login Required"
W/ApiaryClient( 7710):  }
W/ApiaryClient( 7710): }
,W/ApiaryClient( 7710): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7710): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=433582523555718663&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7710): Headers:
W/ApiaryClient( 7710): accept-encoding: [gzip]
W/ApiaryClient( 7710): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7710): gdata-version: 2
E/BooksSync( 7710): Soft error: 
E/BooksSync( 7710): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7710): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=433582523555718663&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7710): Headers:
E/BooksSync( 7710): accept-encoding: [gzip]
E/BooksSync( 7710): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7710): gdata-version: 2
E/BooksSync( 7710): 
E/BooksSync( 7710): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7710): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7710): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7710): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7710): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7710): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7710): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7710): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7710): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7710): {
E/BooksSync( 7710):  "error": {
E/BooksSync( 7710):   "errors": [
E/BooksSync( 7710):    {
E/BooksSync( 7710):     "domain": "global",
E/BooksSync( 7710):     "reason": "required",
E/BooksSync( 7710):     "message": "Login Required",
E/BooksSync( 7710):     "locationType": "header",
E/BooksSync( 7710):     "location": "Authorization"
E/BooksSync( 7710):    }
E/BooksSync( 7710):   ],
E/BooksSync( 7710):   "code": 401,
E/BooksSync( 7710):   "message": "Login Required"
E/BooksSync( 7710):  }
E/BooksSync( 7710): }
E/BooksSync( 7710): 
E/BooksSync( 7710): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7710): 	... 8 more
,E/BooksSync( 7710): Sync error
E/BooksSync( 7710): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7710): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=433582523555718663&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7710): Headers:
E/BooksSync( 7710): accept-encoding: [gzip]
E/BooksSync( 7710): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7710): gdata-version: 2
E/BooksSync( 7710): 
E/BooksSync( 7710): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7710): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7710): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7710): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7710): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7710): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7710): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7710): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7710): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7710): {
E/BooksSync( 7710):  "error": {
E/BooksSync( 7710):   "errors": [
E/BooksSync( 7710):    {
E/BooksSync( 7710):     "domain": "global",
E/BooksSync( 7710):     "reason": "required",
E/BooksSync( 7710):     "message": "Login Required",
E/BooksSync( 7710):     "locationType": "header",
E/BooksSync( 7710):     "location": "Authorization"
E/BooksSync( 7710):    }
E/BooksSync( 7710):   ],
E/BooksSync( 7710):   "code": 401,
E/BooksSync( 7710):   "message": "Login Required"
E/BooksSync( 7710):  }
E/BooksSync( 7710): }
E/BooksSync( 7710): 
E/BooksSync( 7710): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7710): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7710): 	... 8 more
I/BooksSync( 7710): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1075115, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1087288202869; DSPS: 35769955; Offset : -4334683212
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=227359499, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,I/ActivityManager( 1038): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7985 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2663): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7985): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7985): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2d53f559
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=227359499 [*alarm*], flags=0x0
,I/ActivityManager( 1038): Killing 6321:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10044/pid_6321/cgroup.procs: No such file or directory
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{23a9a1f4 type 2 when 1105950 android} when 1105950
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1107289800360; DSPS: 36425368; Offset : -4334702657
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1127292356187; DSPS: 37080812; Offset : -4334710568
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1147293728575; DSPS: 37736217; Offset : -4334711550
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1167295715182; DSPS: 38391642; Offset : -4334708456
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1187297068924; DSPS: 39047046; Offset : -4334697539
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1207298688917; DSPS: 39702459; Offset : -4334694899
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
I/UsageStatsService( 1038): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1227300802972; DSPS: 40357888; Offset : -4334686557
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1247302694891; DSPS: 41013310; Offset : -4334686754
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1267304541966; DSPS: 41668731; Offset : -4334701329
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1287305970709; DSPS: 42324137; Offset : -4334676576
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1307307853252; DSPS: 42979559; Offset : -4334685941
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1327309259548; DSPS: 43634966; Offset : -4334713893
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1347311698603; DSPS: 44290405; Offset : -4334685675
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1367313632188; DSPS: 44945829; Offset : -4334705267
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1387315218379; DSPS: 45601241; Offset : -4334705860
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1407317077538; DSPS: 46256662; Offset : -4334708533
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1427318993052; DSPS: 46912084; Offset : -4334685005
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1447321539763; DSPS: 47567528; Offset : -4334701719
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1467323534495; DSPS: 48222953; Offset : -4334690681
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1487325191935; DSPS: 48878367; Offset : -4334681190
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1507326774584; DSPS: 49533779; Offset : -4334685377
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1527328470669; DSPS: 50189195; Offset : -4334698277
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1547329796598; DSPS: 50844599; Offset : -4334715408
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1567331630342; DSPS: 51500018; Offset : -4334682123
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=227359499, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{154a7d1d type 2 when 1157749 com.google.android.gms} when 1157749
D/[Concierge]Service( 2663): onStartCommand(). Type : 9
,D/GCM     ( 2143): Message class com.google.f.a.a.i
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=227359499 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1587333641948; DSPS: 52155444; Offset : -4334684599
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1607335215431; DSPS: 52810856; Offset : -4334697978
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1627336531152; DSPS: 53466259; Offset : -4334694590
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{506d963 type 2 when 1634236 android} when 1634236
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1466): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1466): On Skip Timer : true
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1038): battery changed pluggedType: 2
D/HeadsetStateMachine( 3796): Disconnected process message: 10, size: 0
D/LEDHandler( 1998): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1998): Battery Level Remaining: 100%
D/LEDHandler( 1998): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1466): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1466): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1466): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1647338483748; DSPS: 54121683; Offset : -4334695067
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1667339834053; DSPS: 54777087; Offset : -4334687510
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1687341531650; DSPS: 55432503; Offset : -4334698767
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
,I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1707343418778; DSPS: 56087925; Offset : -4334703885
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1727344867468; DSPS: 56743332; Offset : -4334689521
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1747346577929; DSPS: 57398748; Offset : -4334688123
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1767348546724; DSPS: 58054173; Offset : -4334702944
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1787351098540; DSPS: 58709616; Offset : -4334684009
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1807352944781; DSPS: 59365037; Offset : -4334699341
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
,I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1827354883681; DSPS: 60020460; Offset : -4334683126
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=227359499, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{1916ce19 type 2 when 1843453 com.android.bluetooth} when 1843453
,W/bt-smp  ( 3796): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3796): Plain text(LSB ~ MSB) = ea 56 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3796): Encrypted text(LSB ~ MSB) = 1b 93 34 85 63 71 f3 18 63 f0 d8 d5 8c 44 56 d2 
W/bt-btm  ( 3796): Stopping oneshot timer
I/ProcessStatsService( 1038): Prepared write state in 14ms
I/ProcessStatsService( 1038): Prepared write state in 19ms
,D/[Concierge]Service( 2663): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=227359499 [*alarm*], flags=0x0
,I/ProcessStatsService( 1038): Pruning old procstats: /data/system/procstats/state-2016-01-07-17-44-01.bin
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1847356555600; DSPS: 60675875; Offset : -4334689752
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1867358183091; DSPS: 61331288; Offset : -4334679484
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1887360732824; DSPS: 61986732; Offset : -4334693436
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1907362426201; DSPS: 62642148; Offset : -4334708756
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1927364424578; DSPS: 63297573; Offset : -4334694205
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{21d78ede type 0 when 1452270671424 com.google.android.gms} when 1452270671424
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{3403a8bf type 2 when 1897879 com.google.android.gms} when 1897879
,D/[Concierge]Service( 2663): onStartCommand(). Type : 9
,D/LocationManagerService( 1038): getAllProviders()=[passive, gps, network]
,V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2143): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 2143): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2143): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2143): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2143): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/EventLogService( 2393): Aggregate from 1452268871374 (log), 1452268871374 (data)
E/Ads     ( 2393): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1947365959988; DSPS: 63952983; Offset : -4334684752
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1967367887220; DSPS: 64608406; Offset : -4334680128
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 1987369496483; DSPS: 65263819; Offset : -4334688322
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=227359499, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,D/[Concierge]Service( 2663): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7985): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7985): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2d53f559
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=227359499 [*alarm*], flags=0x0
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2007371524341; DSPS: 65919246; Offset : -4334705090
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2027373460427; DSPS: 66574669; Offset : -4334691663
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2047375104534; DSPS: 67230083; Offset : -4334695375
,I/[SystemUI]LGPowerUI( 1466): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1466): On Skip Timer : true
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1038): battery changed pluggedType: 2
D/HeadsetStateMachine( 3796): Disconnected process message: 10, size: 0
D/LEDHandler( 1998): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1998): Battery Level Remaining: 100%
D/LEDHandler( 1998): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1466): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1466): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1466): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4289): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,TIME-OUT KILL (timeout was 1800000ms),I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 2067377058432; DSPS: 67885507; Offset : -4334694706
I/[SystemUI]LGPowerUI( 1466): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1466): On Skip Timer : true
D/AndroidRuntime( 8218): 
D/AndroidRuntime( 8218): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8218): CheckJNI is OFF
D/AndroidRuntime( 8218): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1038): Killing 7224:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1038): WIN DEATH: Window{3c0d5ef3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1038): Client connection lost with reason: 4
D/InputDispatcher( 1038): Window went away: Window{3c0d5ef3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1038): Skipping PackageSetting{1c8a46c4 com.example.hello/10319} due to missing metadata
I/ActivityManager( 1038): Killing 7468:com.lge.formmanager/u0a26 (adj 15): empty for 1816s
I/ActivityManager( 1038): Killing 7435:com.lge.email/u0a23 (adj 15): empty for 1816s
I/ActivityManager( 1038): Killing 7409:com.lge.appbox.client/u0a11 (adj 15): empty for 1816s
I/ActivityManager( 1038): Killing 6961:com.lge.qremote/u0a112 (adj 15): empty for 1821s
I/ActivityManager( 1038): Killing 7293:com.android.settings/1000 (adj 15): empty for 1821s
I/ActivityManager( 1038): Killing 6782:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty for 1821s
I/ActivityManager( 1038): Killing 7330:com.lge.sync/1000 (adj 15): empty for 1821s
I/ActivityManager( 1038):   Force finishing activity ActivityRecord{8ab227c u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  356): DFP En is all cleared set to be enabled
W/ActivityManager( 1038): Spurious death for ProcessRecord{664c543 7224:com.test.thalitest/u0a311}, curProc for 7224: null
W/libprocessgroup( 1038): failed to open /acct/uid_10026/pid_7468/cgroup.procs: No such file or directory
W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_7435/cgroup.procs: No such file or directory
W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_7409/cgroup.procs: No such file or directory
W/libprocessgroup( 1038): failed to open /acct/uid_10112/pid_6961/cgroup.procs: No such file or directory
E/lowmemorykiller(  276): Error opening /proc/6782/oom_score_adj; errno=2
W/ActivityManager( 1038): Exception when unbinding service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service
W/ActivityManager( 1038): android.os.DeadObjectException
W/ActivityManager( 1038): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 1038): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager( 1038): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
W/ActivityManager( 1038): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
W/ActivityManager( 1038): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2160)
W/ActivityManager( 1038): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:14986)
W/ActivityManager( 1038): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4958)
W/ActivityManager( 1038): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5128)
W/ActivityManager( 1038): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1216)
W/ActivityManager( 1038): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:553)
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_7293/cgroup.procs: No such file or directory
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6782/cgroup.procs: No such file or directory
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_7330/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 2106): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2106): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2106): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2106): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1958): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3767): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2106): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2106): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2106): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2106): [Launcher.java:1114:onPause()]onPause
D/SplitWindowPolicy( 1998): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1998): topRunningActivity=ActivityInfo{ca5851c co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1998): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1998): topRunningActivity=ActivityInfo{20b06525 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/[LGHome]GBoardWebView( 2106): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1958): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3767): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 3767): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/KeyguardModel( 1466): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1038): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1838): Ignoring removeGeofence because network location is disabled.
E/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2060): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3767): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/WeatherAncestor( 7536): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 17:46:19
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
I/art     ( 4576): Explicit concurrent mark sweep GC freed 16929(944KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 455us total 82.354ms
W/System.err( 4521): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4521): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4521): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4521): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4521): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4521): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4521): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4521): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4521): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4521): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4521): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4521): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1038): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8259 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
I/GBoardWebViewUtils( 2106): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2106): , create_time: 1430558575574
I/GBoardWebViewUtils( 2106): , expire_time: 0
I/GBoardWebViewUtils( 2106): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2106): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2106): , display: false
I/GBoardWebViewUtils( 2106): , animation: false }
I/GBoardWebViewUtils( 2106): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2106): , create_time: 1430558575600
I/GBoardWebViewUtils( 2106): , expire_time: 0
I/GBoardWebViewUtils( 2106): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2106): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2106): , display: false
I/GBoardWebViewUtils( 2106): , animation: false }
I/GBoardWebViewUtils( 2106): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2106): , create_time: 1452175675684
I/GBoardWebViewUtils( 2106): , expire_time: 0
I/GBoardWebViewUtils( 2106): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2106): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2106): , display: false
I/GBoardWebViewUtils( 2106): , animation: false }
I/[SystemUI]QSlideListController( 1466): onReceive = android.intent.action.PACKAGE_REMOVED
D/Weather.Utils( 7536): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7536): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7536): 2 : This is isUpdating : false
D/WallpaperManager( 2106): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/art     ( 1038): Explicit concurrent mark sweep GC freed 35486(2MB) AllocSpace objects, 11(416KB) LOS objects, 33% free, 44MB/67MB, paused 2.042ms total 127.423ms
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1466): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/Weather.Utils( 7536): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7536): 2 : All the weather widget is gone.
D/WeatherAncestor( 7536): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 17:46:19
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3e5bdc9f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1466): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/PostponalbeReceiver( 6636): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
I/[LGHome]GBoardWebView( 2106): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
D/SplitUIManager( 1909): split_name #11 / not available #0
D/SplitUIService( 1909): removed split : 
I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8281 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/administrator( 1038): Handling package changes for user 0
W/ActivityManager( 1038): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI] installed app name: Music
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
D/SplitUIManager( 1909): split_name #11 / not available #0
I/SplitUIService( 1909): split app #11
I/[LGHome]EVENT( 2106): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]EVENT( 2106): [Launcher.java:5349:onStop()]onStop
I/LockScreenSettings( 8259): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/KeyguardModel( 1466): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1466): createShortcutInfo...
D/KeyguardModel( 1466): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1466): createShortcutInfo...
I/ThermalEngine(  347): Thermal-Server: Thermal received msg from  override
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
I/Thermal-Lib( 2960): Thermal-Lib-Client: Client request sent
W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1466): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1466): createShortcutInfo...
I/ActivityManager( 1038): Killing 7499:com.android.chrome/u0a57 (adj 15): empty for 1817s
I/AppUp4:AppBoxCP( 8281): onCreate
W/AppUp4:DB( 8281):  [AppBoxDatabaseHelper] construct
I/NotificationService( 1038): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1038): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1038): Receieved: android.intent.action.PACKAGE_REMOVED
I/AppUp4:DB( 8281):  setFingerPrint start
I/AppUp4:DB( 8281):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 8281):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 8281):  SDK version = 21
I/AppUp4:DB( 8281):  beforefinger == newfinger no write in DB
I/[LGHome]Launcher.Model( 2106): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2106): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2106): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2106): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/KeyguardModel( 1466): handleShortcutListChanged...
W/libprocessgroup( 1038): failed to open /acct/uid_10057/pid_7499/cgroup.procs: No such file or directory
W/ResourcesManager( 1038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/AppUp4:AppBoxApplication( 8281): AppBoxApplication onCreate()
D/PhoneStatusBar( 1466): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1466): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1466):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1466): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1038): removeObsoleteFile: deleting file=4_task.xml
D/KeyguardModel( 1466): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1466): createShortcutInfo...
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{3bf3ef8f u0 com.lge.launcher2/.Launcher t3} time:2075334
D/KeyguardModel( 1466): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
D/KeyguardModel( 1466): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1466): createShortcutInfo...
I/[LGHome]Launcher.Model( 2106): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1466): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourceType( 1038): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[Concierge]WidgetView( 2106): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/[Concierge]Service( 2663): onStartCommand(). Type : 8
D/[Concierge]Service( 2663): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2663): Update widget ID : 11
D/[Concierge]WidgetView( 2106): change position of spinner
D/AppUp4:PreloadHelper( 8281): added Exclude : com.test.thalitest
D/KeyguardModel( 1466): handleShortcutListChanged...
I/art     ( 1038): Explicit concurrent mark sweep GC freed 14255(825KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.202ms total 242.288ms
I/ActivityManager( 1038): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8301 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/[Concierge]WidgetView( 2106): initWebView(). Time : 1452271580151
D/[Concierge]Service( 2663): onStartCommand(). Type : 0
I/ActivityManager( 1038): Killing 7519:com.lge.drmservice/u0a62 (adj 15): empty for 1817s
W/libprocessgroup( 1038): failed to open /acct/uid_10062/pid_7519/cgroup.procs: No such file or directory
D/AndroidRuntime( 8218): Shutting down VM
I/[Concierge]WebView( 2106): Return exist ConciergeWebView. Reuse : 273038180
D/[Concierge]WidgetView( 2106): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2106): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
W/ResourcesManager( 8301): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8301): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8301): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/[LgeWidgetLib]ExtViewHost( 2106): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2376d6f2
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
W/ResourcesManager( 8301): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 8301): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]Launcher.Model( 2106): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 2106): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/[Concierge]WidgetView( 2106): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2106): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2106): Widget kill message received. Destory myself. My : 1452269533599, New one : 1452271580151
D/[Concierge]WidgetView( 2106): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2106): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2106): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2106): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2106): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/SystemConfig( 8301): BUILD Country: EU
I/SystemConfig( 8301): BUILD Operator: OPEN
I/[LGHome]Launcher( 2106): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2106): Timeline: Activity_idle id: android.os.BinderProxy@18285caf time:2075523
I/ActivityManager( 1038): Killing 7557:com.google.android.apps.magazines/u0a93 (adj 15): empty for 1818s
I/chromium( 2106): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
I/GBoardtInterface( 2106): onReloaded()
I/GBoardWebViewClient( 2106): onPageFinished url:file:///android_asset/www/main.html
W/libprocessgroup( 1038): failed to open /acct/uid_10093/pid_7557/cgroup.procs: No such file or directory
V/BoardContentProvider( 3767): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/VoicemailCleanupService( 2170): Cleaning up data for package: com.test.thalitest
E/SQLiteLog( 2170): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/SystemConfig( 8301): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 8301): existFile = false
I/SystemConfig( 8301): canReadFile = false
I/SystemConfig( 8301): systemFeature RCS result false
D/SystemConfig( 8301): refreshRcsSupport() :false
E/SQLiteLog( 2170): (3850) statement aborts at 37: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 2170): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 2170): Process: android.process.acore, PID: 2170
E/AndroidRuntime( 2170): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2170): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2170): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:739)
E/AndroidRuntime( 2170): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
E/AndroidRuntime( 2170): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2170): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1600)
E/AndroidRuntime( 2170): 	at com.android.providers.contacts.util.DbModifierWithNotification.delete(DbModifierWithNotification.java:161)
E/AndroidRuntime( 2170): 	at com.android.providers.contacts.voicemail.VoicemailContentTable.delete(VoicemailContentTable.java:229)
E/AndroidRuntime( 2170): 	at com.android.providers.contacts.voicemail.VoicemailContentProvider.delete(VoicemailContentProvider.java:135)
E/AndroidRuntime( 2170): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 2170): 	at android.content.ContentResolver.delete(ContentResolver.java:1315)
E/AndroidRuntime( 2170): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 2170): 	at com.android.providers.contacts.voicemail.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 2170): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2170): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2170): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 2170): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ContactsProvider2ForLG( 2170): performBackgroundTask SQLiteDiskIOException during query
D/ContactsProvider2ForLG( 2170): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
D/ContactsProvider2ForLG( 2170): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
D/ContactsProvider2ForLG( 2170): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
D/ContactsProvider2ForLG( 2170): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
D/ContactsProvider2ForLG( 2170): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
D/ContactsProvider2ForLG( 2170): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
D/ContactsProvider2ForLG( 2170): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
D/ContactsProvider2ForLG( 2170): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:394)
D/ContactsProvider2ForLG( 2170): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:363)
D/ContactsProvider2ForLG( 2170): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:974)
D/ContactsProvider2ForLG( 2170): 	at com.android.providers.contacts.ContactsProvider2ForLG.performBackgroundTask(ContactsProvider2ForLG.java:375)
D/ContactsProvider2ForLG( 2170): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:748)
D/ContactsProvider2ForLG( 2170): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/ContactsProvider2ForLG( 2170): 	at android.os.Looper.loop(Looper.java:135)
D/ContactsProvider2ForLG( 2170): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8326 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a

```
