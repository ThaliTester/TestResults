#### Test 550731521dbc378_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 157911558000; DSPS: 5315288; Offset : -4308123379
,D/AndroidRuntime( 6969): 
D/AndroidRuntime( 6969): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6969): CheckJNI is OFF
D/AndroidRuntime( 6969): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1955): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{3730cd0c #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{3730cd0c #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  348): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6984 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6969): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1855): Display #0 changed.
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{37a76ae6 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{8bec827 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6984): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6984): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6984): Loading: webviewchromium
I/LibraryLoader( 6984): Time to load native libraries: 5 ms (timestamps 1767-1772)
I/LibraryLoader( 6984): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6984): Binding Chromium to main looper Looper (main, tid 1) {4a03416}
I/LibraryLoader( 6984): Expected native library version number "",actual native library version number ""
I/chromium( 6984): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6984): Initializing chromium process, renderers=0
W/art     ( 6984): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  319): registerClient() client 0xb54f53c0, uid 10311
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2095a136:true
W/chromium( 6984): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6984): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6984): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6984): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6984): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6984): Build Date: 12/12/14 금
I/Adreno-EGL( 6984): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6984): Remote Branch: 
I/Adreno-EGL( 6984): Local Patches: 
I/Adreno-EGL( 6984): Reconstruct Branch: 
W/chromium( 6984): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6984): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6984): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6984): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6984): CordovaWebView is running on device made by: LGE
W/art     ( 6984): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6984): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6984): Render dirty regions requested: true
I/OpenGLRenderer( 6984): Initialized EGL, version 1.4
W/ActivityManager( 1037): Activity pause timeout for ActivityRecord{1892655 u0 com.test.thalitest/.MainActivity t4}
D/OpenGLRenderer( 6984): Enabling debug mode 0
D/Atlas   ( 6984): Validating map...
D/SplitWindow( 1037): check instance of lgWin Window{134ed140 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1452): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@b31f07c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1452): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1452):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1452): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LgDataFeature( 6984): LgDataFeature() Constructor: none
D/LgDataFeature( 6984): LgDataFeature() Constructor Done, null
I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +626ms (total +713ms)
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{1892655 u0 com.test.thalitest/.MainActivity t4} time:162172
I/Timeline( 6984): Timeline: Activity_idle id: android.os.BinderProxy@302bcec6 time:162173
I/chromium( 6984): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6984): 
D/JsMessageQueue( 6984): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6984): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6984): 
D/jxcore_app_log( 6984): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435060992
,D/JX-Cordova( 6984): jxcore cordova android initializing
,E/GBMv2   (  348): DFP En is all cleared set to be enabled
E/GBMv2   (  348): Set value is all cleared set the max
I/GBMv2   (  348): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6984): Initializing JXcore engine
W/jxcore-log( 6984): JXcore engine is ready
,W/jxcore-log( 6984): Starting JXcore engine
W/.test.thalitest( 6984): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8398]" dev="sockfs" ino=8398 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6984): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 6984): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8659]" dev="sockfs" ino=8659 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6984): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6984): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33320]" dev="sockfs" ino=33320 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 6984): Background sticky concurrent mark sweep GC freed 125457(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.629ms total 134.130ms
,W/jxcore-log( 6984): Platform android
W/jxcore-log( 6984): 
W/jxcore-log( 6984): Process ARCH arm
W/jxcore-log( 6984): 
,I/jxcore-log( 6984): JXcore Cordova bridge is ready!
I/jxcore-log( 6984): 
W/jxcore-log( 6984): JXcore engine is started
,I/Choreographer( 6984): Skipped 132 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 6984): Toggling radios to true
I/jxcore-log( 6984): 
D/BluetoothAdapter( 6984): enable(): BT is already enabled..!
,D/WifiService( 1037): New client listening to asynchronous messages
D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=6984, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1037): setWifiEnabled: true pid=6984, uid=10311
,E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=6984, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1037): reconnect pid=6984, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECT 0 0
I/jxcore-log( 6984): Radios toggled
I/jxcore-log( 6984): 
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECT 0 0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/WifiNative: ( 1037): [165,952,450 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
I/jxcore-log( 6984): Received device characteristics:
I/jxcore-log( 6984): Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 6984): Bluetooth name: G3-1
I/jxcore-log( 6984): Device name: LGE-LG-D855
I/jxcore-log( 6984): 
I/jxcore-log( 6984): Perf Test app loaded loaded
I/jxcore-log( 6984): 
,I/jxcore-log( 6984): check test folder,
I/jxcore-log( 6984): 
,I/jxcore-log( 6984): found test : ./testFindPeers.js
I/jxcore-log( 6984): 
,I/jxcore-log( 6984): found test : ./testSendData.js,
I/jxcore-log( 6984): 
I/wpa_supplicant( 2672): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1037): InitialState.processMessage what=4
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1037): DISCONNECT: returned true
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7068 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/DhcpStateMachine( 1037): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  314): Clearing all IP addresses on wlan0
I/chromium( 6984): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 6984): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
V/NativeCrypto( 2128): Read error: ssl=0xaf45be00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2128): SSL shutdown failed: ssl=0xaf45be00: I/O error during system call, Broken pipe
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=321635098, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{2b8c7335 type 0 when 1451989214614 com.android.vending} when 1451989214614
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/WifiHS20( 1037): hidePasspointNotification off =false
D/ConnectivityService( 1037): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1955): handleWifiStateChangedEvent: 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=-10ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-10ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/[Concierge]Service( 2600): onStartCommand(). Type : 9
E/WifiStateMachine( 1037): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1037):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [166,123,718 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
D/WifiNative-wlan0( 1037): RECONNECT: returned true
I/wpa_supplicant( 2672): wlan0: CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1037):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=166124
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=166125
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=321635098 [*alarm*], flags=0x0
,D/CommandListener(  314): Clearing all IP addresses on wlan0
D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): stop dsqn bin
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=166152  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=166153  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=0
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=166156  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=166161  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1037): hidePasspointNotification off =false
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1452): CM callback handler got msg 524292
,D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
W/ResourcesManager( 7068): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/ResourcesManager( 7068): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService( 1037): Removing idletimer
D/TelephonyNetworkFactory-1( 1855): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1037): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1037):, EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
W/ResourcesManager( 7068): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
W/ResourcesManager( 7068): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7068): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7068): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1452): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1452): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-147ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/UsbSettingsReceiver( 7068): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7068): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7068): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7068): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7068): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7068): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 7068): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7068): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7068): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7068): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7068): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7104 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6267): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6267): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6267): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ActivityManager( 1037): Killing 2193:com.lge.music/u0a34 (adj 15): empty #17
,I/PCSuite ( 7104): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7104): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7104): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/AudioFlinger(  319): 2193 died, releasing its sessions
V/AudioFlinger(  319):  pid 1855 @ 0
V/AudioFlinger(  319):  pid 3355 @ 1
V/AudioFlinger(  319):  pid 3355 @ 2
W/libprocessgroup( 1037): failed to open /acct/uid_10034/pid_2193/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 7068): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7068): LgDataFeature() Constructor: none
D/LgDataFeature( 7068): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7068): MCCMNC not supported: null
,I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7128 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1037): Killing 6648:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,I/art     (  352): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 472us total 22.767ms
,I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 417us total 20.381ms
,I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 424us total 19.777ms
,W/libprocessgroup( 1037): failed to open /acct/uid_10008/pid_6648/cgroup.procs: No such file or directory
W/ResourcesManager( 7128): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7128): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7128): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7128): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7128): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7128): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7128): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 7128): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7128): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7128): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7128): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7128): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 7128): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 7128): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/PCSuite ( 7104): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7104): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7104): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7068): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7068): MCCMNC not supported: null
,D/QRemote ( 7128): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7128): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7128): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7104): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7104): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7104): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7068): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7068): MCCMNC not supported: null
D/QRemote ( 7128): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7128): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7128): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7104): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7104): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7104): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7068): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7068): MCCMNC not supported: null
D/QRemote ( 7128): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7128): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7128): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7068): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7068): MCCMNC not supported: null
D/QRemote ( 7128): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7128): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7128): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7128): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7128): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7128): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7128): LgDataFeature() Constructor: none
D/LgDataFeature( 7128): LgDataFeature() Constructor Done, null
,V/SoundPool( 7128): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7128): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7128): create sampleID=1, fd=31, offset=17813 length=10857164
,V/SoundPool( 7128): doLoad: loading sample sampleID=1
,I/QRemote ( 7128): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/QRemote ( 7128): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/UEI.SmartControl( 6811): QS Service created
V/SoundPool( 7128): Start decode
V/MediaPlayer[Native]( 7128): decode(31, 10857164, 17813)
V/MediaPlayerService(  319): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  319): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  319): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  319): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  319): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  319): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  319): player type = 3
E/QRemote ( 7128): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7128): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/AwesomePlayer(  319): AwesomePlayer create()
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/AwesomePlayer(  319): setAudioSink() 
V/AwesomePlayer(  319): reset_l() 
V/AudioCache(  319): notify(0xb5474740, 8, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
D/Utils   (  319): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  319): setDataSource_l dataSource
V/LGParserOSAL(  319): SniffLGParser start
V/LGParserOSAL(  319): MainType:5, SubType=0
V/LGParserOSAL(  319): #### check Mime : application/ogg
V/LGParserOSAL(  319): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  319): Use LGExtractor :application/ogg 
I/UEI.SmartControl( 6811): Service initServices...
D/UEI.SmartControl( 6811): QS start get config
,V/LGMDMManager( 7128): Create singleton instance
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
,D/OMXCodec(  319): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
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
V/AudioSystem(  319): isOffloadSupported()
V/AudioPolicyManager(  319): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  319): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  319): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  319): init()
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  319): allocateBuffers
V/OMXCodec(  319): allocateBuffersOnPort portIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on input port
V/OMXCodec(  319): allocateBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf3d0 on output port
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
V/AudioCache(  319): notify(0xb5474740, 5, 0, 0)
V/AudioCache(  319): ignored
V/AudioCache(  319): notify(0xb5474740, 1, 0, 0)
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
,V/OMXCodec(  319): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  319): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
,V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  319): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885568
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885648
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044799440
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  319): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  319): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  319): allocateBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7dd0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] allocated buffer 0xb57bf790 on output port
V/OMXCodec(  319): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  319): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  319): notify(0xb5474740, 6, 0, 0)
V/AudioCache(  319): ignored
V/MediaPlayerService(  319): wait for playback complete
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab602000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab603000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab604000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab605000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab606000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab607000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab608000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab609000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab60a000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab60b000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab60c000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab60d000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab60e000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
,V/AudioCache(  319): memcpy(0xab60f000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab610000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab611000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab612000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab613000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab614000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab615000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab616000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab617000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab618000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab619000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab61a000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab61b000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab61c000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab61d000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab61e000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab61f000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab620000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab621000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab622000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab623000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab624000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab625000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab626000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab627000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
,V/AudioCache(  319): memcpy(0xab628000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab629000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab62a000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab62b000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab62c000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab62d000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab62e000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab62f000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab630000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab631000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab632000, 0xb147e000, 4096)
V/AudioCache(  319): write(0xb147e000, 4096)
V/AudioCache(  319): memcpy(0xab633000, 0xb147e000, 4096)
V/OMXCodec(  319): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  319): postAudioEOS() 
V/AudioCache(  319): write(0xb147e000, 280)
V/AudioCache(  319): memcpy(0xab634000, 0xb147e000, 280)
V/AwesomePlayer(  319): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  319): onStreamDone
V/AwesomePlayer(  319): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  319): notify(0xb5474740, 2, 0, 0)
V/AudioCache(  319): playback complete
V/AwesomePlayer(  319): pause_l() 
V/AudioCache(  319): notify(0xb5474740, 7, 0, 0)
V/AudioCache(  319): ignored
V/AwesomePlayer(  319): cancelPlayerEvents
V/AudioCache(  319): wait - success
V/MediaPlayerService(  319): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  319): Pause Playback at 1068125
V/AwesomePlayer(  319): reset_l() 
V/AudioCache(  319): notify(0xb5474740, 8, 0, 0)
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
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb57bf790 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
,V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7dd0 on port 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  319): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,V/OMXCodec(  319): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  319): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  319): AudioPlayer releasing audio source
D/AudioPlayer(  319): AudioPlayer done releasing audio source
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/AwesomePlayer(  319): ~AwesomePlayer call
V/AwesomePlayer(  319): reset_l() 
V/AwesomePlayer(  319): cancelPlayerEvents
V/SoundPool( 7128): close(31)
V/SoundPool( 7128): pointer = 0x9fe39000, size = 205080, sampleRate = 48000, numChannels = 2
,D/QRemote ( 7128): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7128): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7128): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6024,
I/UEI.SmartControl( 6811): Supports setup maps: true
,D/UEI.SmartControl( 6811): QS start statue = true Error code = 0,
I/UEI.SmartControl( 6811): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6811): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6811): ### init IR Blaster...,
D/serial_port( 6811): Configuring serial port
E/UEI.SmartControl( 6811): UEIBLaster setting for 616
I/UEI.SmartControl( 6811): Setting serial record hearder size = 2
I/UEI.SmartControl( 6811): configuring settings for MAXQ616
,I/UEI.SmartControl( 6811): Get version...
D/UEI.SmartControl( 6811): serial port data available: 21
,D/UEI.SmartControl( 6811): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6811): IR Blaster version: 256702256704300002
,I/UEI.SmartControl( 6811): QS saving settings...
D/UEI.SmartControl( 6811): IR Blaster version: 25672567
D/UEI.SmartControl( 6811): serial port data available: 4
,W/ContextImpl( 6811): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6811): Services init done
D/UEI.SmartControl( 6811): QS Service init finished
I/UEI.SmartControl( 6811): Device manager: loading config....
,D/UEI.SmartControl( 6811): ----------- loading internal config...
D/UEI.SmartControl( 6811): QS Service version name: 2.1.91
D/UEI.SmartControl( 6811): QS Service version code: 201091
D/UEI.SmartControl( 6811): Service requested: Control
,E/UEI.SmartControl( 6811): Loading SETTINGS...
D/UEI.SmartControl( 6811): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6811): Internal service binding...
I/QRemote ( 7128): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6811): ------ IControl API: 11
D/UEI.SmartControl( 6811): File observer start...
E/UEI.SmartControl( 6811): IR Port is disabled: false
D/UEI.SmartControl( 6811): Starting file observer...
I/UEI.SmartControl( 6811): Registering callback...
I/UEI.SmartControl( 6811): ------ IControl API: 19
I/UEI.SmartControl( 6811): Registering Services Ready callback...
,D/UEI.SmartControl( 6811): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6811): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6811): -----service ready thread exits
I/QRemote ( 7128): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7128): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
,D/QRemote ( 7128): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7128): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7128): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6811): ------ IControl API: 8
D/QRemote ( 7128): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7128): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7128): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
,D/QRemote ( 7128): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7128): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7128): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7128): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7128): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7128): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7128): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7128): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7128): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7128): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7128): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7128): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1451989216762]
D/QRemote ( 7128): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1037): Killing 6151:com.lge.appbox.client/u0a11 (adj 15): empty #17
,D/QRemote ( 7128): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_6151/cgroup.procs: No such file or directory
,V/QRemote ( 7128): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 7128): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7128): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7128): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7128): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7128): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7128): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,D/QRemote ( 7128): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2672): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=168232  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=168261  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7068): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7068): MCCMNC not supported: null
D/QRemote ( 7128): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7128): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7128): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7068): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2672): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,I/wpa_supplicant( 2672): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2672): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=168343  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=168344  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=168344
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=168345
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=168345
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=168359
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=168359
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=168363  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=168384  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=168388  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=168388  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=168389
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=168389
,D/WifiNative-wlan0( 1037): doString: [STATUS]
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
,I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WiFiOffLoadBroadcast( 7068): MCCMNC not supported: null
D/QRemote ( 7128): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7128): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
I/QRemote ( 7128): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 7068): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7068): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7068): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7068): [AUTORUN] persist.sys.usb.config = ptp_only,adb
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/UsbSettingsReceiver( 7068): [AUTORUN] onReceive() : app userid = 0, current userid = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/UsbSettingsControl( 7068): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7068): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7068): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7068): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7068): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7068): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsControl( 7068): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7068): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
D/WiFiOffLoadBroadcast( 7068): MCCMNC not supported: null
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/QRemote ( 7128): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7128): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7128): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/CommandListener(  314): Setting iface cfg
E/WifiStateMachine( 1037): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=168463  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=168464  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=168464  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=168466  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=168467  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=168467  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 7068): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7068): MCCMNC not supported: null
D/QRemote ( 7128): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7128): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7128): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 7068): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a614eab target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a614eab target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/CommandListener(  314): Setting iface cfg
D/CommandListener(  314): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1037): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
,D/WiFiOffLoadBroadcast( 7068): MCCMNC not supported: null
,D/QRemote ( 7128): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7128): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7128): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7068): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
D/WiFiOffLoadBroadcast( 7068): MCCMNC not supported: null
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,V/WfdStateTracker( 1955): handleWifiStateChangedEvent: 1
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  314): netlink response contains error (File exists)
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1037): Setting Dns servers for network 101 to [/192.168.1.1]
D/QRemote ( 7128): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7128): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7128): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1855): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 28
I/StatusBar.NetworkController( 1452): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1452): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
,D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1037): validation of new default Network = false
D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7199): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7199): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1452): CM callback handler got msg 524290
V/WiFiOffLoadBroadcast( 7068): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7068): MCCMNC not supported: null
E/DSQN    ( 7199): DSQN ssw
D/QRemote ( 7128): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7128): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7128): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7068): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/WiFiOffLoadBroadcast( 7068): MCCMNC not supported: null
,D/QRemote ( 7128): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7128): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/TelephonyIcons( 1452): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
I/QRemote ( 7128): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7104): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7104): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7068): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7068): MCCMNC not supported: null
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
D/QRemote ( 7128): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7128): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7128): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7128): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7128): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7104): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7104): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDataListener(  314): argv[0]=dsqncommand
D/LGDataListener(  314): argv[1]=wlan0
D/LGDataListener(  314): argv[2]=1
D/LGDataListener(  314): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
V/WiFiOffLoadBroadcast( 7068): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7068): MCCMNC not supported: null
D/QRemote ( 7128): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7128): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7128): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7128): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7128): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 10:20:17 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451989217759], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451989217735]}
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
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1855): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1855):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityManager.CallbackHandler( 1452): CM callback handler got msg 524290
D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7205): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,W/dhcpcd  ( 7205): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7205): version 5.5.6 starting
E/dhcpcd  ( 7205): get_duid: m
,D/dhcpcd  ( 7205): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
,D/dhcpcd  ( 7205): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/TelephonyIcons( 1452): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1452): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7205): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7205): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7205): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 7205): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7205): wlan0: sending REQUEST (xid 0x778f346), next in 3.71 seconds
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1037): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1037): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,I/NetworkMonitor( 5912): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5912): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 6617): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7235 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7235): onCreate
W/AppUp4:DB( 7235):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7235):  setFingerPrint start
I/AppUp4:DB( 7235):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7235):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7235):  SDK version = 21
I/AppUp4:DB( 7235):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7235): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7235): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7235): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7235): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7235): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7235): onReceive
D/LgDataFeature( 7235): LgDataFeature() Constructor: none
D/LgDataFeature( 7235): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7235): Context : android.app.ReceiverRestrictedContext@3ad2af84
D/AppUp4:CustFacade( 7235): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7235): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7235): begin check event
I/AppUp4:CustModeStarterReceiver( 7235): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7235): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7235): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7235): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7235): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1037): Killing 6175:com.android.contacts/u0a19 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_6175/cgroup.procs: No such file or directory
,D/LGDMClient( 4325): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4325): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3380): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,E/WifiStateMachine( 1037):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
V/DownloadManager( 3380): DownloadService onCreate
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/LGDMClient( 4325): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
I/DownloadManager( 3380): in removeSpuriousFiles
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
V/DownloadManager( 3380): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
I/LGDMClient( 4325): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@38a3bf68 on behalf of 3380
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1037): identical MTU - not setting
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
D/ConnectivityManager.CallbackHandler( 1452): CM callback handler got msg 524295
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,I/DownloadManager( 3380): in trimDatabase
V/DownloadManager( 3380): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@2922dc67 on behalf of 3380
D/LGDMClient( 4325): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4325): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3380): DownloadService onStartCommand
V/DownloadManager( 3380): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@1a96a14 on behalf of 3380
,E/LGDMClient( 4325): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4325): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4325): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3380): processing inserted download 1
V/DownloadManager( 3380): processing inserted download 4
V/DownloadManager( 3380): processing inserted download 7
V/DownloadManager( 3380): processing inserted download 8
D/eas_req ( 6678): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3380): processing inserted download 9
V/DownloadManager( 3380): processing inserted download 10
V/DownloadManager( 3380): processing inserted download 16
,V/DownloadManager( 3380): processing inserted download 17
,V/DownloadManager( 3380): processing inserted download 18
V/DownloadManager( 3380): processing inserted download 21
V/DownloadManager( 3380): DownloadService onDestroy
I/ActivityManager( 1037): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7266 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 6678): JNI_OnLoad()
I/HubEmail( 6678): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6678): registerNatives()
I/HubEmail( 6678): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6678): registerNativeMethods()
I/HubEmail( 6678): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6678): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6678): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6678): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3355): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3355): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3355): networkInfo.isConnected() = false
,I/ActivityManager( 1037): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7289 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/dhcpcd  ( 7205): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 7205): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7205): wlan0: adding IP address 192.168.1.141/24
,D/dhcpcd  ( 7205): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7205): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7205): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7205): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7205): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7205): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
I/ActivityManager( 1037): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7325 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6563:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10004/pid_6563/cgroup.procs: No such file or directory
,D/libc-netbsd(  314): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7266): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7266): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1037): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7350 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6706:com.android.gallery3d/u0a27 (adj 15): empty #17
D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1037): RunningState
W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_6706/cgroup.procs: No such file or directory
I/ActivityManager( 1037): Killing 6729:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,I/art     ( 7350): Almond Protected OAT
,W/libprocessgroup( 1037): failed to open /acct/uid_10061/pid_6729/cgroup.procs: No such file or directory
,D/WeatherApplication( 7350): removeAccount
D/WeatherApplication( 7350): Account.length = 0
E/WeatherApplication( 7350): OPERATOR:OPEN
D/WeatherAncestor( 7350): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:19
,D/Weather.Utils( 7350): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7350): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7350): 2 : This is isUpdating : false
D/WeatherAncestor( 7350): connectivity changed - connection : true
,D/WeatherService( 7350): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7350): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7350): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7350): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7350): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7350): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:19
,I/ActivityManager( 1037): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7368 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6765:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10080/pid_6765/cgroup.procs: No such file or directory
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7368): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7368): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7368): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7368): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 6984): BLE is supported
I/jxcore-log( 6984): 
I/WebViewFactory( 7368): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7368): Loading: webviewchromium
I/LibraryLoader( 7368): Time to load native libraries: 5 ms (timestamps 1030-1035)
I/LibraryLoader( 7368): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7368): Binding Chromium to main looper Looper (main, tid 1) {3a0dc77f}
I/LibraryLoader( 7368): Expected native library version number "",actual native library version number ""
I/chromium( 7368): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7368): Initializing chromium process, renderers=0
W/art     ( 7368): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7368): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
V/AudioPolicyService(  319): registerClient() client 0xb54f5ec0, uid 10093
I/chromium( 7368): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7368): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
W/AudioManagerAndroid( 7368): Requires BLUETOOTH permission
I/Adreno-EGL( 7368): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7368): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7368): Build Date: 12/12/14 금
I/Adreno-EGL( 7368): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7368): Remote Branch: 
I/Adreno-EGL( 7368): Local Patches: 
I/Adreno-EGL( 7368): Reconstruct Branch: 
E/WifiStateMachine( 1037):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1037):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
I/NSApplication( 7368): Starting up...
I/ActivityManager( 1037): Killing 6837:com.lge.eula/1000 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6837/cgroup.procs: No such file or directory
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3205ed65 type 2 when 171301 com.google.android.gms} when 171301
D/ChimeraCfgMgr( 2324): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/ChimeraCfgMgr( 2324): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/ContextImpl( 6617): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7235): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7235): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7235): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7235): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7235): onReceive
D/AppUp4:CustFacade( 7235): Context : android.app.ReceiverRestrictedContext@3ad2af84
D/AppUp4:CustFacade( 7235): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7235): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7235): begin check event
I/AppUp4:CustModeStarterReceiver( 7235): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/art     ( 1037): Explicit concurrent mark sweep GC freed 102734(4MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 3.080ms total 167.063ms
D/LGDMClient( 4325): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4325): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/WifiInternetCheck( 1037): Single check msg out of sync, ignoring.
W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4325): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3380): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4325): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4325): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4325): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3380): DownloadService onCreate
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/DownloadManager( 3380): in removeSpuriousFiles
V/DownloadManager( 3380): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/Tethering( 1037): MasterInitialState.processMessage what=3
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@34d0a0b2 on behalf of 3380
I/NetworkMonitor( 5912): type=WIFI subType= reason=null isConnected=true
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/LgeMiscReceiver( 3355): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3355): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3355): networkInfo.isConnected() = false
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
,I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
E/LGDMClient( 4325): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4325): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4325): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 6678): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WeatherAncestor( 7350): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:20
I/DownloadManager( 3380): in trimDatabase
,V/DownloadManager( 3380): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/Weather.Utils( 7350): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7350): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7350): 2 : This is isUpdating : false
D/WeatherAncestor( 7350): connectivity changed - connection : true
D/WeatherService( 7350): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@b637ba2
,W/Settings( 6678): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ForecastDataCache( 7350): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7350): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7350): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7350): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7350): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:20
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@12bd1380 on behalf of 3380
V/DownloadManager( 3380): DownloadService onStartCommand
V/DownloadManager( 3380): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@182415fe on behalf of 3380
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
,W/Kids    ( 2324): [AccountUtils] Account not ready
W/Kids    ( 2324): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2324): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2324): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2324): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2324): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2324): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2324): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2324): 	at java.lang.Thread.run(Thread.java:818)
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3380): processing inserted download 1
,V/DownloadManager( 3380): processing inserted download 4
V/DownloadManager( 3380): processing inserted download 7
V/DownloadManager( 3380): processing inserted download 8
D/LgeQuickCoverNLService( 1401): onNotificationPosted
V/DownloadManager( 3380): processing inserted download 9
V/DownloadManager( 3380): processing inserted download 10
V/DownloadManager( 3380): processing inserted download 16
D/SmartCoverUpdateMonitor( 1401): received broadcast com.lge.intent.action.NLDataPosted
V/DownloadManager( 3380): processing inserted download 17
E/SmartCoverUpdateMonitor( 1401): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1401): handleNotificationPosted(true)
D/QuickCircle( 1401): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1401): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post do just update job
D/LgeQuickCoverNotificationData( 1401): showAll3
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1401): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  0
V/DownloadManager( 3380): processing inserted download 18
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  1
V/DownloadManager( 3380): processing inserted download 21
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1401): updateNotificationData: count=3
V/DownloadManager( 3380): DownloadService onDestroy
,D/ChimeraCfgMgr( 2324): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/GpsLocationProvider( 1037): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/QuickStatusbarLayout( 1401): Notification difference=198
,D/QuickStatusbarLayout( 1401): child = android.widget.LinearLayout{169fe7ac V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = mtalk.google.com, class = 1, type = 1
W/ContextImpl( 6617): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7235): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7235): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7235): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7235): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7235): onReceive
,D/GpsLocationProvider( 1037): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AppUp4:CustFacade( 7235): Context : android.app.ReceiverRestrictedContext@3ad2af84
,D/AppUp4:CustFacade( 7235): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7235): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7235): begin check event
I/AppUp4:CustModeStarterReceiver( 7235): Event For GoodConnectivity, noConnectivity : false, but skip! 
V/FormManager( 7266): There are no updated forms. The schedule will be deleted.
D/LGDMClient( 4325): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4325): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
V/FormManager( 7266): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3380): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/libc-netbsd(  314): res_queryN name = mtalk.google.com succeed
V/DownloadManager( 3380): DownloadService onCreate
D/LGDMClient( 4325): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/DownloadManager( 3380): in removeSpuriousFiles
V/DownloadManager( 3380): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@169fe7ac on behalf of 3380
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3380): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3380): in trimDatabase
V/DownloadManager( 3380): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@35b43c75 on behalf of 3380
D/LGDMClient( 4325): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4325): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4325): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2ca58966 type 2 when 171716 android} when 171716
,W/ContextImpl( 4325): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
W/Settings( 6678): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6678): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 4325): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4325): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4325): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3380): DownloadService onStartCommand
,V/DownloadManager( 3380): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3380): created cursor android.database.sqlite.SQLiteCursor@f9d298 on behalf of 3380
V/DownloadManager( 3380): processing inserted download 1
V/DownloadManager( 3380): processing inserted download 4
V/DownloadManager( 3380): processing inserted download 7
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3380): processing inserted download 8
V/DownloadManager( 3380): processing inserted download 9
I/LgeMiscReceiver( 3355): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3355): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3355): networkInfo.isConnected() = true
D/PhoneState( 3355): setPdpRejectCasuse : false
V/DownloadManager( 3380): processing inserted download 10
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3380): processing inserted download 16
D/LgeQuickCoverNLService( 1401): onNotificationPosted
,V/DownloadManager( 3380): processing inserted download 17
,V/DownloadManager( 3380): processing inserted download 18
V/DownloadManager( 3380): processing inserted download 21
D/SmartCoverUpdateMonitor( 1401): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1401): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1401): handleNotificationPosted(true)
D/QuickCircle( 1401): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1401): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post do just update job
D/LgeQuickCoverNotificationData( 1401): showAll3
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1401): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1401): updateNotificationData: count=3
W/Kids    ( 2324): [AccountUtils] Account not ready
W/Kids    ( 2324): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2324): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2324): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2324): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2324): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2324): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2324): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2324): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3380): DownloadService onDestroy
D/WeatherAncestor( 7350): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:20
,D/Weather.Utils( 7350): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7350): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7350): 2 : This is isUpdating : false
D/WeatherAncestor( 7350): connectivity changed - connection : true
D/WeatherService( 7350): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@b637ba2
D/ForecastDataCache( 7350): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7350): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7350): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7350): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7350): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:20:20
D/QuickStatusbarLayout( 1401): Notification difference=198
D/QuickStatusbarLayout( 1401): child = android.widget.LinearLayout{169fe7ac V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2324): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/FormManager( 7266): There are no updated forms. The schedule will be deleted.
V/FormManager( 7266): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1037): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7456 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2324): [AccountUtils] Account not ready
W/Kids    ( 2324): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2324): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2324): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2324): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2324): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2324): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2324): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2324): 	at java.lang.Thread.run(Thread.java:818)
,D/LgeQuickCoverNLService( 1401): onNotificationPosted
D/SmartCoverUpdateMonitor( 1401): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1401): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1401): handleNotificationPosted(true)
D/QuickCircle( 1401): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1401): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post do just update job
D/LgeQuickCoverNotificationData( 1401): showAll3
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1401): showNotificationWithSetupData: display=false
D/GCM     ( 2128): Connected
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1401): updateNotificationData: count=3
,D/GCM     ( 2128): Message class com.google.f.a.a.p
,D/QuickStatusbarLayout( 1401): Notification difference=198
D/QuickStatusbarLayout( 1401): child = android.widget.LinearLayout{169fe7ac V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/ReaderUtils( 7456): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 7456): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7456): Created application version: 3.2.35 (30235)
,I/BooksSync( 7456): Starting books sync
,D/BooksSync( 7456): started syncMyEbooks
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7456): Authentication error
E/BooksAccountManager( 7456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7456): 	at android.os.Binder.execTransact(Binder.java:446)
,E/HttpHelper( 7456): null auth token
D/LgeQuickCoverNLService( 1401): onNotificationPosted
D/UEI.SmartControl( 6811): Internal timer expired: 4
D/UEI.SmartControl( 6811): unbind internal service
D/SmartCoverUpdateMonitor( 1401): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1401): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1401): handleNotificationPosted(true)
D/QuickCircle( 1401): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1401): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1401): post do just update job
D/LgeQuickCoverNotificationData( 1401): showAll3
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1401): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.googleapis.com, class = 1, type = 1
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1401): updateNotificationData: count=3
D/QuickStatusbarLayout( 1401): Notification difference=198
D/QuickStatusbarLayout( 1401): child = android.widget.LinearLayout{169fe7ac V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  314): res_queryN name = www.googleapis.com succeed
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  314): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = www.google.com succeed
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = clients3.google.com succeed
D/serial_port( 6811): close(fd = 24)
,I/UEI.SmartControl( 6811): Serial port is closed.
V/WifiInternetCheck( 1037): isHttpConnectionAvailable - We got a valid response : 204
,W/ApiaryClient( 7456): Error response from books API: {
W/ApiaryClient( 7456):  "error": {
W/ApiaryClient( 7456):   "errors": [
W/ApiaryClient( 7456):    {
W/ApiaryClient( 7456):     "domain": "global",
W/ApiaryClient( 7456):     "reason": "required",
W/ApiaryClient( 7456):     "message": "Login Required",
W/ApiaryClient( 7456):     "locationType": "header",
W/ApiaryClient( 7456):     "location": "Authorization"
W/ApiaryClient( 7456):    }
W/ApiaryClient( 7456):   ],
W/ApiaryClient( 7456):   "code": 401,
W/ApiaryClient( 7456):   "message": "Login Required"
W/ApiaryClient( 7456):  }
W/ApiaryClient( 7456): }
,W/ApiaryClient( 7456): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=462671852887336133&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7456): Headers:
W/ApiaryClient( 7456): accept-encoding: [gzip]
W/ApiaryClient( 7456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7456): gdata-version: 2
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 2128): Explicit concurrent mark sweep GC freed 31041(1798KB) AllocSpace objects, 16(2MB) LOS objects, 51% free, 30MB/62MB, paused 2.611ms total 82.272ms
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7456): Authentication error
E/BooksAccountManager( 7456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7456): null auth token
W/ResourcesManager( 1401): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1401): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1401): onNotificationPosted
D/SmartCoverUpdateMonitor( 1401): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1401): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1401): handleNotificationPosted(true)
D/QuickCircle( 1401): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1401): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post do just update job
D/LgeQuickCoverNotificationData( 1401): showAll3
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1401): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
W/ResourcesManager( 1401): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1401): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,E/LgeQuickCoverOverlayWindow( 1401): updateNotificationData: count=3
D/QuickStatusbarLayout( 1401): Notification difference=198
D/QuickStatusbarLayout( 1401): child = android.widget.LinearLayout{169fe7ac V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7456): Error response from books API: {
W/ApiaryClient( 7456):  "error": {
W/ApiaryClient( 7456):   "errors": [
W/ApiaryClient( 7456):    {
W/ApiaryClient( 7456):     "domain": "global",
W/ApiaryClient( 7456):     "reason": "required",
W/ApiaryClient( 7456):     "message": "Login Required",
W/ApiaryClient( 7456):     "locationType": "header",
W/ApiaryClient( 7456):     "location": "Authorization"
W/ApiaryClient( 7456):    }
W/ApiaryClient( 7456):   ],
W/ApiaryClient( 7456):   "code": 401,
W/ApiaryClient( 7456):   "message": "Login Required"
W/ApiaryClient( 7456):  }
W/ApiaryClient( 7456): }
W/ApiaryClient( 7456): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=462671852887336133&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7456): Headers:
W/ApiaryClient( 7456): accept-encoding: [gzip]
W/ApiaryClient( 7456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7456): gdata-version: 2
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1401): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1401): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1401): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1401): handleNotificationPosted(true)
D/QuickCircle( 1401): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1401): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post do just update job
D/LgeQuickCoverNotificationData( 1401): showAll3
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1401): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1401): updateNotificationData: count=3
,W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7456): Authentication error
E/BooksAccountManager( 7456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7456): null auth token
,D/QuickStatusbarLayout( 1401): Notification difference=198
D/QuickStatusbarLayout( 1401): child = android.widget.LinearLayout{169fe7ac V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7456): Error response from books API: {
W/ApiaryClient( 7456):  "error": {
W/ApiaryClient( 7456):   "errors": [
W/ApiaryClient( 7456):    {
W/ApiaryClient( 7456):     "domain": "global",
W/ApiaryClient( 7456):     "reason": "required",
W/ApiaryClient( 7456):     "message": "Login Required",
W/ApiaryClient( 7456):     "locationType": "header",
W/ApiaryClient( 7456):     "location": "Authorization"
W/ApiaryClient( 7456):    }
W/ApiaryClient( 7456):   ],
W/ApiaryClient( 7456):   "code": 401,
W/ApiaryClient( 7456):   "message": "Login Required"
W/ApiaryClient( 7456):  }
W/ApiaryClient( 7456): }
W/ApiaryClient( 7456): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=462671852887336133&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7456): Headers:
W/ApiaryClient( 7456): accept-encoding: [gzip]
W/ApiaryClient( 7456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7456): gdata-version: 2
,I/GAV4    ( 7368): Thread[GAThread,5,main]: No campaign data found.
,E/BooksSync( 7456): Soft error: 
E/BooksSync( 7456): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=462671852887336133&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7456): Headers:
E/BooksSync( 7456): accept-encoding: [gzip]
E/BooksSync( 7456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7456): gdata-version: 2
E/BooksSync( 7456): 
E/BooksSync( 7456): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7456): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7456): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7456): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7456): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7456): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7456): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7456): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7456): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7456): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7456): {
E/BooksSync( 7456):  "error": {
E/BooksSync( 7456):   "errors": [
E/BooksSync( 7456):    {
E/BooksSync( 7456):     "domain": "global",
E/BooksSync( 7456):     "reason": "required",
E/BooksSync( 7456):     "message": "Login Required",
E/BooksSync( 7456):     "locationType": "header",
E/BooksSync( 7456):     "location": "Authorization"
E/BooksSync( 7456):    }
E/BooksSync( 7456):   ],
E/BooksSync( 7456):   "code": 401,
E/BooksSync( 7456):   "message": "Login Required"
E/BooksSync( 7456):  }
E/BooksSync( 7456): }
E/BooksSync( 7456): 
E/BooksSync( 7456): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7456): 	... 8 more
,E/BooksSync( 7456): Sync error
E/BooksSync( 7456): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=462671852887336133&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7456): Headers:
E/BooksSync( 7456): accept-encoding: [gzip]
E/BooksSync( 7456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7456): gdata-version: 2
E/BooksSync( 7456): 
E/BooksSync( 7456): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7456): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7456): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7456): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7456): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7456): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7456): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7456): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7456): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7456): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7456): {
E/BooksSync( 7456):  "error": {
E/BooksSync( 7456):   "errors": [
E/BooksSync( 7456):    {
E/BooksSync( 7456):     "domain": "global",
E/BooksSync( 7456):     "reason": "required",
E/BooksSync( 7456):     "message": "Login Required",
E/BooksSync( 7456):     "locationType": "header",
E/BooksSync( 7456):     "location": "Authorization"
E/BooksSync( 7456):    }
E/BooksSync( 7456):   ],
E/BooksSync( 7456):   "code": 401,
E/BooksSync( 7456):   "message": "Login Required"
E/BooksSync( 7456):  }
E/BooksSync( 7456): }
E/BooksSync( 7456): 
E/BooksSync( 7456): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7456): 	... 8 more
,I/BooksSync( 7456): Finished books sync
I/ActivityManager( 1037): Killing 6859:com.lge.bnr/1000 (adj 15): empty #17
,D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 171716, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_6859/cgroup.procs: No such file or directory
,I/GAV2    ( 7456): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 177913784519; DSPS: 5970721; Offset : -4308124227
,V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{3689f1b9 type 0 when 1451989235506 com.android.vending} when 1451989235506
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2e7879fe type 2 when 187000 com.google.android.gms} when 187000
,V/QRemote ( 7128): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7128): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6024
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/VacuumService( 2128): Vacuum at: now=1451989238221 tag=VacuumService
,I/GoogleURLConnFactory( 2128): Using platform SSLCertificateSocketFactory
,W/Uploader( 2128): No account for auth token provided
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  314): res_queryN name = play.googleapis.com succeed
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 28110(1288KB) AllocSpace objects, 7(880KB) LOS objects, 33% free, 44MB/66MB, paused 4.138ms total 143.302ms
,W/Uploader( 2128): No account for auth token provided
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6267): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6267): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6267): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 2128): No account for auth token provided
,W/Uploader( 2128):  no longer exists, so no auth token.
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 197915713522; DSPS: 6626144; Offset : -4308118195
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{382e9586 type 2 when 201859 android} when 201859
,E/WifiStateMachine( 1037):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1037):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1037):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{fb60674 type 0 when 1451989258621 com.android.vending} when 1451989258621
,I/[SystemUI]TimeTickManager( 1452): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1452): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1452): called onTimeUpdated()
I/[SystemUI]Clock( 1452): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1452): called onTimeUpdated()
I/[SystemUI]DateView( 1452): called onTimeUpdated()
I/[SystemUI]DateView( 1452): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1452): handleTimeUpdate
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6267): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6267): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6267): [1] 5.onFinished: Giving up after 6 failures.
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 217917628618; DSPS: 7281567; Offset : -4308125576
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 237919511475; DSPS: 7936988; Offset : -4308104266
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=321635098, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{b8d6c36 type 2 when 240792 android} when 240792
D/[Concierge]Service( 2600): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=321635098 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 257922886207; DSPS: 8592459; Offset : -4308117116
,I/[SystemUI]TimeTickManager( 1452): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1452): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1452): called onTimeUpdated()
I/[SystemUI]Clock( 1452): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1452): called onTimeUpdated()
I/[SystemUI]DateView( 1452): called onTimeUpdated()
I/[SystemUI]DateView( 1452): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1452): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 277925059637; DSPS: 9247890; Offset : -4308110329
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 297927319577; DSPS: 9903324; Offset : -4308108690
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=321635098, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{29f3b737 type 2 when 308336 android} when 308336
D/[Concierge]Service( 2600): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=321635098 [*alarm*], flags=0x0
,I/BooksSync( 7456): Starting books sync
,D/BooksSync( 7456): started syncMyEbooks
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1401): onNotificationPosted
D/SmartCoverUpdateMonitor( 1401): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1401): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1401): handleNotificationPosted(true)
D/QuickCircle( 1401): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1401): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post do just update job
D/LgeQuickCoverNotificationData( 1401): showAll3
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
,E/LgeQuickCoverOverlayWindow( 1401): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1401): updateNotificationData: count=3
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7456): Authentication error
E/BooksAccountManager( 7456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7456): null auth token
,D/QuickStatusbarLayout( 1401): Notification difference=198
D/QuickStatusbarLayout( 1401): child = android.widget.LinearLayout{169fe7ac V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7456): Error response from books API: {
W/ApiaryClient( 7456):  "error": {
W/ApiaryClient( 7456):   "errors": [
W/ApiaryClient( 7456):    {
W/ApiaryClient( 7456):     "domain": "global",
W/ApiaryClient( 7456):     "reason": "required",
W/ApiaryClient( 7456):     "message": "Login Required",
W/ApiaryClient( 7456):     "locationType": "header",
W/ApiaryClient( 7456):     "location": "Authorization"
W/ApiaryClient( 7456):    }
W/ApiaryClient( 7456):   ],
W/ApiaryClient( 7456):   "code": 401,
W/ApiaryClient( 7456):   "message": "Login Required"
W/ApiaryClient( 7456):  }
W/ApiaryClient( 7456): }
,W/ApiaryClient( 7456): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5497227954098528187&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7456): Headers:
W/ApiaryClient( 7456): accept-encoding: [gzip]
W/ApiaryClient( 7456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7456): gdata-version: 2
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1401): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1401): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1401): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1401): handleNotificationPosted(true)
D/QuickCircle( 1401): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1401): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post do just update job
D/LgeQuickCoverNotificationData( 1401): showAll3
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1401): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1401): updateNotificationData: count=3
,W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7456): Authentication error
E/BooksAccountManager( 7456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7456): null auth token
D/QuickStatusbarLayout( 1401): Notification difference=198
D/QuickStatusbarLayout( 1401): child = android.widget.LinearLayout{169fe7ac V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 7456): Error response from books API: {
W/ApiaryClient( 7456):  "error": {
W/ApiaryClient( 7456):   "errors": [
W/ApiaryClient( 7456):    {
W/ApiaryClient( 7456):     "domain": "global",
W/ApiaryClient( 7456):     "reason": "required",
W/ApiaryClient( 7456):     "message": "Login Required",
W/ApiaryClient( 7456):     "locationType": "header",
W/ApiaryClient( 7456):     "location": "Authorization"
W/ApiaryClient( 7456):    }
W/ApiaryClient( 7456):   ],
W/ApiaryClient( 7456):   "code": 401,
W/ApiaryClient( 7456):   "message": "Login Required"
W/ApiaryClient( 7456):  }
W/ApiaryClient( 7456): }
,W/ApiaryClient( 7456): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5497227954098528187&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7456): Headers:
W/ApiaryClient( 7456): accept-encoding: [gzip]
W/ApiaryClient( 7456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7456): gdata-version: 2
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1401): onNotificationPosted
D/SmartCoverUpdateMonitor( 1401): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1401): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1401): handleNotificationPosted(true)
D/QuickCircle( 1401): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1401): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post do just update job
D/LgeQuickCoverNotificationData( 1401): showAll3
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1401): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1401): updateNotificationData: count=3
,W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7456): Authentication error
E/BooksAccountManager( 7456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7456): null auth token
,D/QuickStatusbarLayout( 1401): Notification difference=198
D/QuickStatusbarLayout( 1401): child = android.widget.LinearLayout{169fe7ac V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7456): Error response from books API: {
W/ApiaryClient( 7456):  "error": {
W/ApiaryClient( 7456):   "errors": [
W/ApiaryClient( 7456):    {
W/ApiaryClient( 7456):     "domain": "global",
W/ApiaryClient( 7456):     "reason": "required",
W/ApiaryClient( 7456):     "message": "Login Required",
W/ApiaryClient( 7456):     "locationType": "header",
W/ApiaryClient( 7456):     "location": "Authorization"
W/ApiaryClient( 7456):    }
W/ApiaryClient( 7456):   ],
W/ApiaryClient( 7456):   "code": 401,
W/ApiaryClient( 7456):   "message": "Login Required"
W/ApiaryClient( 7456):  }
W/ApiaryClient( 7456): }
,W/ApiaryClient( 7456): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5497227954098528187&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7456): Headers:
W/ApiaryClient( 7456): accept-encoding: [gzip]
W/ApiaryClient( 7456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7456): gdata-version: 2
E/BooksSync( 7456): Soft error: 
E/BooksSync( 7456): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5497227954098528187&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7456): Headers:
E/BooksSync( 7456): accept-encoding: [gzip]
E/BooksSync( 7456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7456): gdata-version: 2
E/BooksSync( 7456): 
E/BooksSync( 7456): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7456): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7456): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7456): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7456): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7456): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7456): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7456): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7456): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7456): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7456): {
E/BooksSync( 7456):  "error": {
E/BooksSync( 7456):   "errors": [
E/BooksSync( 7456):    {
E/BooksSync( 7456):     "domain": "global",
E/BooksSync( 7456):     "reason": "required",
E/BooksSync( 7456):     "message": "Login Required",
E/BooksSync( 7456):     "locationType": "header",
E/BooksSync( 7456):     "location": "Authorization"
E/BooksSync( 7456):    }
E/BooksSync( 7456):   ],
E/BooksSync( 7456):   "code": 401,
E/BooksSync( 7456):   "message": "Login Required"
E/BooksSync( 7456):  }
E/BooksSync( 7456): }
E/BooksSync( 7456): 
E/BooksSync( 7456): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7456): 	... 8 more
,E/BooksSync( 7456): Sync error
E/BooksSync( 7456): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-5497227954098528187&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7456): Headers:
E/BooksSync( 7456): accept-encoding: [gzip]
E/BooksSync( 7456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7456): gdata-version: 2
E/BooksSync( 7456): 
E/BooksSync( 7456): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7456): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7456): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7456): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7456): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7456): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7456): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7456): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7456): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7456): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7456): {
E/BooksSync( 7456):  "error": {
E/BooksSync( 7456):   "errors": [
E/BooksSync( 7456):    {
E/BooksSync( 7456):     "domain": "global",
E/BooksSync( 7456):     "reason": "required",
E/BooksSync( 7456):     "message": "Login Required",
E/BooksSync( 7456):     "locationType": "header",
E/BooksSync( 7456):     "location": "Authorization"
E/BooksSync( 7456):    }
E/BooksSync( 7456):   ],
E/BooksSync( 7456):   "code": 401,
E/BooksSync( 7456):   "message": "Login Required"
E/BooksSync( 7456):  }
E/BooksSync( 7456): }
E/BooksSync( 7456): 
E/BooksSync( 7456): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7456): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7456): 	... 8 more
I/BooksSync( 7456): Finished books sync
D/SyncManager( 1037): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 308336, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 317929650507; DSPS: 10558761; Offset : -4308127717
,I/[SystemUI]TimeTickManager( 1452): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1452): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1452): called onTimeUpdated()
I/[SystemUI]Clock( 1452): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1452): called onTimeUpdated()
I/[SystemUI]DateView( 1452): called onTimeUpdated()
I/[SystemUI]DateView( 1452): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1452): handleTimeUpdate
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 337932046958; DSPS: 11214199; Offset : -4308111663
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=321635098, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{3aa738e9 type 2 when 338538 android} when 338538
D/[Concierge]Service( 2600): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=321635098 [*alarm*], flags=0x0
,I/jxcore-log( 6984): Connected to the server!
I/jxcore-log( 6984): 
,I/chromium( 6984): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 357934150388; DSPS: 11869628; Offset : -4308113764
,I/[SystemUI]LGPowerUI( 1452): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1452): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1452): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1452): onReceive = android.intent.action.BATTERY_CHANGED
,D/WifiController( 1037): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1452): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1955): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1955): Battery Level Remaining: 100%
D/LEDHandler( 1955): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3796): Disconnected process message: 10, size: 0
D/LGDMClient( 4325): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4325): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1401): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1401): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1401): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1401): handleNotificationPosted(true)
D/QuickCircle( 1401): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1401): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post do just update job
D/LgeQuickCoverNotificationData( 1401): showAll3
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1401): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1401): updateNotificationData: count=3
,W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 6267): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6267): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6267): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6267): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6267): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6267): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6267): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1401): Notification difference=198
D/QuickStatusbarLayout( 1401): child = android.widget.LinearLayout{169fe7ac V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6267): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  314): res_queryN name = play.googleapis.com succeed
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 377936013297; DSPS: 12525049; Offset : -4308112557
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=321635098, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,D/[Concierge]Service( 2600): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1452): setTimeTickHandler, called onTimeChanged(),
I/KeyguardUpdateMonitor( 1452): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1452): called onTimeUpdated()
I/[SystemUI]Clock( 1452): called onTimeUpdated()
I/LgeClockWidgetControlView( 1452): called onTimeUpdated()
I/[SystemUI]DateView( 1452): called onTimeUpdated()
I/[SystemUI]DateView( 1452): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1452): handleTimeUpdate
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=321635098 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 397941356883; DSPS: 13180584; Offset : -4308109652
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 417943524740; DSPS: 13836015; Offset : -4308108335
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 437945558951; DSPS: 14491442; Offset : -4308118879
,I/[SystemUI]TimeTickManager( 1452): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1452): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1452): called onTimeUpdated()
I/[SystemUI]Clock( 1452): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1452): called onTimeUpdated()
I/[SystemUI]DateView( 1452): called onTimeUpdated()
I/[SystemUI]DateView( 1452): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1452): handleTimeUpdate
I/jxcore-log( 6984): --- start :testFindPeers.js---
I/jxcore-log( 6984): 
,I/jxcore-log( 6984): testFindPeers created [object Object]
I/jxcore-log( 6984): 
I/jxcore-log( 6984): serverPort is 8876
I/jxcore-log( 6984): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6984): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6984): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6984): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6984): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6984): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6984): getBluetoothService() called with no BluetoothManagerCallback
D/LGBluetoothServiceAdapter( 3796): [BTUI] createSocketChannel FD=84 mFd=82
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): start: OK
I/io.jxcore.node.ConnectionHelper( 6984): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6984): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6984): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6984): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): start: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6984): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): start: Starting P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6984): start: OK
I/jxcore-log( 6984): StartBroadcasting started ok
I/jxcore-log( 6984): 
I/io.jxcore.node.ConnectionHelper( 6984): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6984): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6984): onDiscoveryManagerStateChanged: RUNNING
I/chromium( 6984): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=37 dispatchEvent: P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1037):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1037):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 128
D/LGWifiP2pService( 1037):  grpcapab: 9
D/LGWifiP2pService( 1037):  devcapab: 4
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1037):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1037):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 128
D/LGWifiP2pService( 1037):  grpcapab: 9
D/LGWifiP2pService( 1037):  devcapab: 4
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=38 dispatchEvent: P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=147477 obj=Device: Android_608e
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,D/LGWifiP2pService( 1037): InactiveState{ when=-17ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-17ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-17ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037): InactiveState{ when=-20ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-20ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-20ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-21ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-21ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-21ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-22ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-22ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-22ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-22ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-23ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-23ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-23ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-24ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-24ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=6 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 6984): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service request added successfully
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 457947714203; DSPS: 15146873; Offset : -4308130297
,I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=40 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=41 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
,D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001010a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b6037688
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service discovery started successfully,
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=43 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=44 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=45 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=46 dispatchEvent: P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=47 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1037):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1037):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 128
D/LGWifiP2pService( 1037):  grpcapab: 9
D/LGWifiP2pService( 1037):  devcapab: 4
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1037):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1037):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 128
D/LGWifiP2pService( 1037):  grpcapab: 9
D/LGWifiP2pService( 1037):  devcapab: 4
D/LGWifiP2pServi,ce( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_8ae2
D/LGWifiP2pService( 1037):  deviceAddress: 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null,
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION,
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139287 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139287 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139287 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139287 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler ,}
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-18ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-18ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-18ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-19ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-19ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-19ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-20ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-20ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-20ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-21ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-21ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-21ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-22ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-22ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-22ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-24ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-24ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-24ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-25ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-25ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-25ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=48 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001010a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001010a436f72646f7661703270c00c000c01]
D/LGWifiP2pService( 1037): InactiveState{ when=-34ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-34ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-34ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=49 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:37:96:ac 3 55000101000a436f72646f7661703270c00c000c013f7b227069223a2237433a46393a30453a33373a39363a4142222c22706e223a2241352d31222c227261223a2237433a46393a30453a33373a39363a4142227dc027
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-14ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-14ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-14ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-15ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-15ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-17ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=50 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001010a436f72646f7661703270c00c000c01
D/LGWifiP2pService( 1037): InactiveState{ when=-24ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-24ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-24ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-24ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-25ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C,:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6984): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,D/io.jxcore.node.ConnectionHelper( 6984): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
,I/jxcore-log( 6984): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"A5-1","peerAvailable":true}]
I/jxcore-log( 6984): 
I/jxcore-log( 6984): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 6984): 
I/jxcore-log( 6984): weAreDoneNow
I/jxcore-log( 6984): 
I/jxcore-log( 6984): done, now sending data to server
I/jxcore-log( 6984): 
D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=51 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:e7:c4:e6:4c:f8 0 3 120001010a436f72646f7661703270c00c000c01
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 477949798050; DSPS: 15802301; Offset : -4308121646
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): setState: RESTARTING
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2672): P2P-FIND-STOPPED 
D/WfdsMonitor( 1955): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=52 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): Start timer timeout, starting now...
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139265 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139265 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
,D/LGWifiP2pService( 1037): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=54 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1037):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1037):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 128
D/LGWifiP2pService( 1037):  grpcapab: 9
D/LGWifiP2pService( 1037):  devcapab: 4
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1037):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1037):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 128
D/LGWifiP2pService( 1037):  grpcapab: 9
D/LGWifiP2pService( 1037):  devcapab: 4
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=19 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=19 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 6984): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service request added successfully
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001020a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service discovery started successfully
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 497952520022; DSPS: 16457750; Offset : -4308115712
,I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/[SystemUI]LGPowerUI( 1452): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1452): On Skip Timer : true
D/LEDHandler( 1955): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1955): Battery Level Remaining: 100%
D/LEDHandler( 1955): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1452): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1452): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1037): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1452): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3796): Disconnected process message: 10, size: 0
D/LGDMClient( 4325): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4325): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:70:12:80 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:70:12:80 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=56 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:70:12:80 0 3 120001040a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=57 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:75:42 0 3 120001020a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001020a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001020a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=58 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001020a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=59 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=60 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139307 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBo,olean: P2P_SERV_DISC_CANCEL_REQ b60376a0
,D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=23 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=23 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 6984): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service request added successfully
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=61 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001030a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=62 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=63 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=64 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001030a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=65 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service discovery started successfully
D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=66 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000103000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6984): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 6984): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000103000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000103000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=67 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:75:42 3 55000103000a436f72646f7661703270c00c000c013f7b227069223a2230383a45433a41393a35303a37353a3431222c22706e223a2241332d31222c227261223a2230383a45433a41393a35303a37353a3431227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 6984): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 6984): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
I/[SystemUI]TimeTickManager( 1452): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1452): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1452): called onTimeUpdated()
I/[SystemUI]Clock( 1452): called onTimeUpdated()
I/LgeClockWidgetControlView( 1452): called onTimeUpdated()
I/[SystemUI]DateView( 1452): called onTimeUpdated()
I/[SystemUI]DateView( 1452): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1452): handleTimeUpdate
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=68 dispatchEvent: P2P-SERV-DISC-REQ 2412 92:b6:86:43:73:1c 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=69 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=70 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=71 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139287 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-15ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-15ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-15ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-17ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-17ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-17ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.D,iscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 517954495535; DSPS: 17113175; Offset : -4308123946
,D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=72 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001040a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=73 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001040a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=74 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=75 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=76 dispatchEvent: P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1037):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1037):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 128
D/LGWifiP2pService( 1037):  grpcapab: 9
D/LGWifiP2pService( 1037):  devcapab: 4
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1037):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1037):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 128
D/LGWifiP2pService( 1037):  grpcapab: 9
D/LGWifiP2pService( 1037):  devcapab: 4
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139287 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-14ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-14ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-14ms what=139283 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-17ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-17ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-17ms what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=30 target=com.andro,id.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
,D/WifiP2pManager( 6984): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service request added successfully
D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=77 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 3 120001040a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001050a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=78 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 3 120001050a436f72646f7661703270c00c000c01
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001040a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service discovery started successfully
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001050a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=79 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001050a436f72646f7661703270c00c000c01
D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 3 120001050a436f72646f7661703270c00c000c01]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=80 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 3 120001050a436f72646f7661703270c00c000c01
,I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=81 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
I/wpa_supplicant( 2672): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1955): Event [P2P: Reject scan trigger since one is already pending]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=82 dispatchEvent: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
,D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=83 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1037):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1037):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 128
D/LGWifiP2pService( 1037):  grpcapab: 9
D/LGWifiP2pService( 1037):  devcapab: 4
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1037):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1037):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 128
D/LGWifiP2pService( 1037):  grpcapab: 9
D/LGWifiP2pService( 1037):  devcapab: 4
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139287 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2,
,I/wpa_supplicant( 2672): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2672): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/WfdsMonitor( 1955): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28]
D/WfdsMonitor( 1955): Event [P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8]
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=84 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1037): Event [P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=85 dispatchEvent: P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=-14ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-14ms what=147478 obj=Device: 
D/LGWifiP2pService( 1037):  deviceAddress: 92:e7:c4:e6:4c:f8
D/LGWifiP2pService( 1037):  primary type: null
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 0
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 0
D/LGWifiP2pService( 1037):  status: 4
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139287 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139287 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.,thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=37 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=37 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 6984): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service request added successfully
I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=86 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 537956124694; DSPS: 17768588; Offset : -4308112427
,I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=87 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001050a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376a0
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2672): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1955): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=88 dispatchEvent: P2P: Reject scan trigger since one is already pending
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service discovery started successfully
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=89 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001060a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001030a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001030a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=90 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001030a436f72646f7661703270c00c000c01
I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=91 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001040a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001040a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=92 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 3 120001040a436f72646f7661703270c00c000c01
,I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=93 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
,I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=94 dispatchEvent: P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/LGWifiP2pService( 1037):  deviceAddress: a2:39:f7:70:12:80
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 4488
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): restart: Restarting...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERV_DISC_CANCEL_REQ b60376a0
D/WifiNative-p2p0( 1037): P2P_SERV_DISC_CANCEL_REQ b60376a0: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service request
,D/WifiP2pManager( 6984): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service request added successfully
I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=95 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=96 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=97 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1037):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1037):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 128
D/LGWifiP2pService( 1037):  grpcapab: 9
D/LGWifiP2pService( 1037):  devcapab: 4
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1037):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1037):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 128
D/LGWifiP2pService( 1037):  grpcapab: 9
D/LGWifiP2pService( 1037):  devcapab: 4
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139287 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139310 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001060a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1037):    returned b60376a0
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=98 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service discovery started successfully
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=99 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:51:18:23
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000106000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000106000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=100 dispatchEvent: P2P-SERV-DISC-RESP 7e:f9:0e:51:18:23 3 67000106000a436f72646f7661703270c00c000c01517b227069223a2237433a46393a30453a35313a31383a3232222c22706e223a225468616c692054657374202847616c61787920413529222c227261223a2237433a46393a30453a35313a31383a3232227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6984): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6984): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 557958014582; DSPS: 18424010; Offset : -4308114472
,D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001070a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=101 dispatchEvent: P2P-SERV-DISC-REQ 2412 44:80:eb:7b:5a:07 0 3 120001070a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001050a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001050a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=102 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:51:18:23 0 3 120001050a436f72646f7661703270c00c000c01
,I/jxcore-log( 6984): teardown
I/jxcore-log( 6984): 
,I/jxcore-log( 6984): testFindPeers stopped
I/jxcore-log( 6984): 
I/io.jxcore.node.ConnectionHelper( 6984): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6984): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6984): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6984): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6984): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6984): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6984): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): stop: Stopping services
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
,D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): stop: Stopping P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
,I/wpa_supplicant( 2672): P2P-FIND-STOPPED 
D/WfdsMonitor( 1955): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=103 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
,D/LGWifiP2pService( 1037): remove channel information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6984): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6984): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6984): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): setState: NOT_STARTED
I/jxcore-log( 6984): StopBroadcasting went ok
I/jxcore-log( 6984): 
I/io.jxcore.node.ConnectionHelper( 6984): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6984): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6984): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 6984): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 6984): --- start :testSendData.js---
I/jxcore-log( 6984): 
I/jxcore-log( 6984): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":13}bt-address length : 0
I/jxcore-log( 6984): 
,I/jxcore-log( 6984): daya100000
I/jxcore-log( 6984): 
I/jxcore-log( 6984): check server
I/jxcore-log( 6984): 
I/jxcore-log( 6984): serverPort is 41985
I/jxcore-log( 6984): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6984): bind: Binding a new listener
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6984): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6984): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6984): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6984): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6984): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): start: OK
I/io.jxcore.node.ConnectionHelper( 6984): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): start: Peer ID: 58:3F:54:73:64:C0, peer name: G3-1
D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6984): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6984): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): start: {"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6984): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d52167c0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState add service
D/LGWifiP2pService( 1037): add a new client
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 3f7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a2247332d31222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1037): P2P_SERVICE_ADD bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): start: Starting P2P device discovery...
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6984): start: OK
I/jxcore-log( 6984): StartBroadcasting started ok
I/jxcore-log( 6984): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6984): Waiting for incoming connections...
,I/jxcore-log( 6984): null
I/jxcore-log( 6984): 
I/jxcore-log( 6984): 2016-01-05T10:26:49.441Z SendDataTCPServer.js: TCP/IP server is bound to port: 41985
I/jxcore-log( 6984): 
I/io.jxcore.node.ConnectionHelper( 6984): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6984): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): setState: RESTARTING
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2672): P2P-FIND-STOPPED 
D/WfdsMonitor( 1955): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=104 dispatchEvent: P2P-FIND-STOPPED 
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6984): onDiscoveryManagerStateChanged: RUNNING
,I/chromium( 6984): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): setState: RESTARTING
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=105 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
,E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 5260 a2:39:f7:6f:c9:5d 0 7 120001070a436f72646f7661703270c00c000c01]
,I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 5260 a2:39:f7:6f:c9:5d 0 7 120001070a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=106 dispatchEvent: P2P-SERV-DISC-REQ 5260 a2:39:f7:6f:c9:5d 0 7 120001070a436f72646f7661703270c00c000c01
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=107 dispatchEvent: P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=108 dispatchEvent: P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=109 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=110 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=111 dispatchEvent: P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1037):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1037):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 128
D/LGWifiP2pService( 1037):  grpcapab: 9
D/LGWifiP2pService( 1037):  devcapab: 4
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=147477 obj=Device: DIRECT-qjWorkCentre 3025
D/LGWifiP2pService( 1037):  deviceAddress: 9e:93:4e:3e:3a:c5
D/LGWifiP2pService( 1037):  primary type: 3-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 128
D/LGWifiP2pService( 1037):  grpcapab: 9
D/LGWifiP2pService( 1037):  devcapab: 4
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1037):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 10,37):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 33
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=147477 obj=Device: A3-1
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:75:42
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/LGWifiP2pService( 1037):  deviceAddress: ee:1f:72:18:8b:78
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 9e:93:4e:3e:ba:c5 p2p_dev_addr=9e:93:4e:3e:3a:c5 pri_dev_type=3-0050F204-5 name='DIRECT-qjWorkCentre 3025' config_methods=0x80 dev_capab=0x4 group_capab=0x9]
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
,D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-7ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-7ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-7ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139287 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-9ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-9ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-9ms what=139283 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-10ms what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-10ms what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-10ms what=139287 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-11ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-11ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-11ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139287 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-12ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-12ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-12ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139283 arg2=27 target=com.android.internal.util,.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-17ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-17ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-17ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-18ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-18ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-18ms what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-20ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-20ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-20ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-21ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-21ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-21ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-22ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-22ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-23ms what=139287 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-23ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-23ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-23ms what=139283 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-24ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-24ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-24ms what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-25ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-25ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-25ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-5ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-5ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,D/LGWifiP2pService( 1037): InactiveState{ when=-13ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-13ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-13ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=-17ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-17ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-17ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139301 arg2=10 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139301 arg2=10 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState add service request
D/WifiP2pManager( 6984): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service request added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): Start timer timeout, starting now...,
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139265 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139265 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=112 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/LGWifiP2pService( 1037): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139310 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState discover services
D/WifiNative-p2p0( 1037): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001070a436f72646f7661703270c00c000c01]
,D/WifiNative-p2p0( 1037):    returned b60376b8
,D/WifiNative-p2p0( 1037): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2672): p2p0: P2P: Reject scan trigger since one is already pending
,D/WfdsMonitor( 1955): Event [P2P: Reject scan trigger since one is already pending]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P: Reject scan trigger since one is already pending]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=113 dispatchEvent: P2P: Reject scan trigger since one is already pending
,D/WifiNative-p2p0( 1037): P2P_FIND 120: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service discovery started successfully
I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=114 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1037):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
,D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139287 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-1ms what=139283 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-2ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-2ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-2ms what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-3ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-3ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-3ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000107000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000107000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=115 dispatchEvent: P2P-SERV-DISC-RESP 0a:ec:a9:50:76:28 7 67000107000a436f72646f7661703270c00c000c01517b227069223a2230383a45433a41393a35303a37363a3237222c22706e223a225468616c692054657374202847616c61787920413329222c227261223a2230383a45433a41393a35303a37363a3237227dc027
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6984): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6984): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
I/jxcore-log( 6984): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 6984): 
I/jxcore-log( 6984): Found peer : Thali Test (Galaxy A3), Available: true
I/jxcore-log( 6984): 
I/jxcore-log( 6984): startWithNextDevice
I/jxcore-log( 6984): 
I/jxcore-log( 6984): device[1]: 08:EC:A9:50:76:27
I/jxcore-log( 6984): 
I/jxcore-log( 6984): 2016-01-05T10:26:54.962Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6984): 
I/jxcore-log( 6984): 2016-01-05T10:26:54.963Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6984): 
I/jxcore-log( 6984): 2016-01-05T10:26:54.964Z SendDataConnector.js: do connect now
I/jxcore-log( 6984): 
I/io.jxcore.node.ConnectionHelper( 6984): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6984): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): connect: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6984): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6984): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6984): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6984): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 6984): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6984): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 831)
W/LGMDMUISystemServiceAdapter( 6984): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 6984): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3796): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3796): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 08eca9507627  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
D/LGBluetoothServiceAdapter( 3796): [BTUI] connectSocket FD=85 mFd=84
W/bt-btm  ( 3796): btm_acl_created hci_handle=2 link_role=1  transport=1
W/bt-btm  ( 3796): btm_acl_created hci_handle=2 link_role=0  transport=1
W/bt-l2cap( 3796): L2CAP - st: CLOSED evt: 0
W/bt-l2cap( 3796): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,W/bt-btm  ( 3796): btm_read_remote_version_complete: BDA: 08-ec-a9-50-76-27
W/bt-btm  ( 3796): btm_read_remote_version_complete lmp_version 7 manufacturer 29 lmp_subversion 2003
,W/bt-l2cap( 3796): L2CAP - st: W4_L2CAP_CON_RSP evt: 19
,W/bt-l2cap( 3796): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3796): L2CAP - st: CONFIG evt: 24
W/bt-btm  ( 3796): btm_process_remote_ext_features_page 0: BDA: 08-ec-a9-50-76-27
W/bt-btm  ( 3796): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3796): btm_process_remote_ext_features_page 1: BDA: 08-ec-a9-50-76-27
W/bt-btif ( 3796): info:x10
W/bt-l2cap( 3796): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-l2cap( 3796): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3796): L2CAP - st: CONFIG evt: 25
D/        ( 3796): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3796): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3796): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
,W/bt-l2cap( 3796): L2CAP-Upper layer Config_Rsp,Local CID: 0x0040,Remote CID: 0x0040,PSM: 1,our MTU present:1,our MTU:672
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8cf7cfc:true
,D/LGBluetoothFeatureConfig( 7068): isPrivacyLogsEnabled : true
D/LGBluetoothPowerSaveListener( 7068): [BTUI] ACL connected => AclLinkCount = 1
,W/bt-l2cap( 3796): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3796): L2CAP-peer_Config_Rsp,Local CID: 0x0040,Remote CID: 0x0040,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-sdp  ( 3796): process_service_search_attr_rsp
W/bt-l2cap( 3796): L2CA_DisconnectReq()  CID: 0x0040
W/bt-l2cap( 3796): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
W/bt-l2cap( 3796): L2CA_ErtmConnectReq()  PSM: 0x0003  BDA: 08eca9507627  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
W/bt-l2cap( 3796): L2CAP - st: CLOSED evt: 21
,I/BluetoothBondStateMachine( 3796): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 3796): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3796): checkBluetoothPairing btPolicy: false
,I/BluetoothBondStateMachine( 3796): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3796): Entering PendingCommandState State
,I/ActivityManager( 1037): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7701 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 3796): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
D/BluetoothRemoteDevices( 3796): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3796): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 3796): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3796): StableState(): Entering Off State
,W/bt-btm  ( 3796): Security Manager: encrypt_change status:0 State:2, encr_enable = 1
W/bt-l2cap( 3796): L2CAP - st: ORIG_W4_SEC_COMP evt: 7
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@119df1da:true
W/bt-l2cap( 3796): L2CAP - st: W4_L2CAP_CON_RSP evt: 11
W/bt-l2cap( 3796): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3796): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3796): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3796): L2CAP-Upper layer Config_Rsp,Local CID: 0x0041,Remote CID: 0x0041,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3796): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3796): L2CAP-peer_Config_Rsp,Local CID: 0x0041,Remote CID: 0x0041,PSM: 3,peer MTU present: 0,peer MTU: 1691
W/bt-l2cap( 3796): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3796): new conn_srvc id:26, app_id:1
W/bt-btif ( 3796): new conn_srvc id:26, app_id:1 count:1
W/bt-btif ( 3796): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3796): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6984): onSocketConnected: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6984): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 831)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6984): onBytesWritten: 63 bytes successfully written (thread ID: 832)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6984): Outgoing connection initialized (*handshake* thread ID: 832)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6984): Exiting thread (thread ID: 831)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6984): Entering thread (ID: 832)
,E/ActivityThread( 7701): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 7701): No ProfileInfo entries
I/LG Account v2.2( 7701): isEnabled: false
I/Feature ( 7701): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 7701): [Lifetracker]Country: EU
I/Feature ( 7701): [Lifetracker]Operator: OPEN
I/Feature ( 7701): [Lifetracker]Ranking support: false
I/Feature ( 7701): [Lifetracker]Comfort support: false
I/Feature ( 7701): [Lifetracker]Accessory: true
I/Feature ( 7701): [Lifetracker]Health device: true
I/Feature ( 7701): [Lifetracker]Extra Pedometer: false
I/Feature ( 7701): [Lifetracker]Blood glucose device: false
I/Feature ( 7701): [Lifetracker]Device Number: 3
I/ActivityManager( 1037): Killing 6889:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6984): onBytesRead: Read 81 bytes successfully (thread ID: 832)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6984): Handshake succeeded with [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6984): onHandshakeSucceeded: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6984): Exiting thread (ID: 832)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): onConnected: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6984): onConnected: Outgoing connection to peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/io.jxcore.node.ConnectionHelper( 6984): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 6984): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6984): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6984): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 6984): Entering thread (ID: 833)
D/io.jxcore.node.OutgoingSocketThread( 6984): Server socket local port: 53060
I/io.jxcore.node.OutgoingSocketThread( 6984): Now accepting connections...
W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_6889/cgroup.procs: No such file or directory
,I/io.jxcore.node.ConnectionHelper( 6984): onListeningForIncomingConnections: Outgoing connection is using port 53060 (peer ID: 08:EC:A9:50:76:27)
,I/jxcore-log( 6984): 2016-01-05T10:26:57.536Z SendDataConnector.js: CLIENT connected to 53060, error: null
I/jxcore-log( 6984): 
I/jxcore-log( 6984): 2016-01-05T10:26:57.536Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6984): 
,I/io.jxcore.node.OutgoingSocketThread( 6984): Incoming data from address: /127.0.0.1, port: 53060
D/io.jxcore.node.OutgoingSocketThread( 6984): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6984): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6984): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6984): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6984): Exiting thread (ID: 833)
D/io.jxcore.node.StreamCopyingThread( 6984): Entering thread (ID: 835, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6984): Entering thread (ID: 834, name: Sender)
I/jxcore-log( 6984): 2016-01-05T10:26:57.570Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6984): 
D/        ( 3796): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:29928
,I/jxcore-log( 6984): 2016-01-05T10:26:58.350Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6984): 
,D/        ( 3796): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19038
,I/jxcore-log( 6984): 2016-01-05T10:26:58.406Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6984): 
I/jxcore-log( 6984): 2016-01-05T10:26:58.467Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6984): 
,D/        ( 3796): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9138
,I/jxcore-log( 6984): 2016-01-05T10:26:58.542Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6984): 
D/        ( 3796): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2208
,I/jxcore-log( 6984): 2016-01-05T10:26:58.619Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6984): 
I/jxcore-log( 6984): 2016-01-05T10:26:58.636Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6984): 
,I/jxcore-log( 6984): 2016-01-05T10:26:58.692Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6984): 
,I/jxcore-log( 6984): 2016-01-05T10:26:58.776Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6984): 
,I/jxcore-log( 6984): 2016-01-05T10:26:58.859Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6984): 
,I/jxcore-log( 6984): 2016-01-05T10:26:58.869Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6984): 
I/jxcore-log( 6984): 2016-01-05T10:26:58.870Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6984): 
I/jxcore-log( 6984): oneRoundDownNow
I/jxcore-log( 6984): 
I/jxcore-log( 6984): 2016-01-05T10:26:58.876Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6984): 
I/jxcore-log( 6984): 2016-01-05T10:26:58.876Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6984): 
,D/io.jxcore.node.ConnectionHelper( 6984): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 6984): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 6984): close
D/io.jxcore.node.OutgoingSocketThread( 6984): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6984): doStop: Thread ID: 835
D/io.jxcore.node.OutgoingSocketThread( 6984): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6984): doStop: Thread ID: 834
D/io.jxcore.node.OutgoingSocketThread( 6984): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6984): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 6984): Either failed to read from the output stream or write to the input stream (thread ID: 834, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6984): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6984): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 6984): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6984): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6984): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 6984): Either failed to read from the output stream or write to the input stream (thread ID: 835, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6984): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6984): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/bt-l2cap( 3796): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/io.jxcore.node.ConnectionHelper( 6984): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6984): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 6984): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6984): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6984): Exiting thread (ID: 834, name: Sender)
E/io.jxcore.node.ConnectionHelper( 6984): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6984): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6984): Exiting thread (ID: 835, name: Receiver)
I/jxcore-log( 6984): 2016-01-05T10:26:58.891Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6984): 
I/jxcore-log( 6984): ---- round done--------
I/jxcore-log( 6984): 
I/jxcore-log( 6984): startWithNextDevice
I/jxcore-log( 6984): 
,W/bt-rfcomm( 3796): rfc_port_closed
W/bt-btif ( 3796): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,W/bt-l2cap( 3796): L2CA_DisconnectReq()  CID: 0x0041
W/bt-l2cap( 3796): L2CAP - st: W4_L2CAP_DISC_RSP evt: 18
,I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/[SystemUI]TimeTickManager( 1452): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1452): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1452): called onTimeUpdated()
I/[SystemUI]Clock( 1452): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1452): called onTimeUpdated()
I/[SystemUI]DateView( 1452): called onTimeUpdated()
I/[SystemUI]DateView( 1452): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1452): handleTimeUpdate
,D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 120001060a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 120001060a436f72646f7661703270c00c000c01]
,E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=116 dispatchEvent: P2P-SERV-DISC-REQ 2412 0a:ec:a9:50:76:28 0 7 120001060a436f72646f7661703270c00c000c01
D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 120001060a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=117 dispatchEvent: P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 120001060a436f72646f7661703270c00c000c01
,D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 7e:f9:0e:37:96:ac 0 7 120001060a436f72646f7661703270c00c000c01]
D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 7 120001090a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 7 120001090a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=118 dispatchEvent: P2P-SERV-DISC-REQ 2412 a2:39:f7:6f:c9:5d 0 7 120001090a436f72646f7661703270c00c000c01
E/bt-btm  ( 3796): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3796): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1037): Connected BT device : -1
I/BluetoothMapService( 3796): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3796): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3796): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3796): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3796): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3796): state: -2147483648
D/LGBluetoothPowerSaveListener( 7068): [BTUI] ACL disconnected => AclLinkCount = 0
,D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11156ce8:true
,I/BTConnectionReceiver( 4605): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4605): Bluetooth Device Name: Thali Test (Galaxy A3)
I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=119 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/btif_config_util( 3796): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2672): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/WfdsMonitor( 1955): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/WifiMonitor( 1037): Event [P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=120 dispatchEvent: P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/LGWifiP2pService( 1037):  deviceAddress: 7e:f9:0e:37:96:ac
D/LGWifiP2pService( 1037):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1037):  secondary type: null
D/LGWifiP2pService( 1037):  wps: 392
D/LGWifiP2pService( 1037):  grpcapab: 0
D/LGWifiP2pService( 1037):  devcapab: 37
D/LGWifiP2pService( 1037):  status: 3
D/LGWifiP2pService( 1037):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1955): WIFI_P2P_PEERS_CHANGED_ACTION
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=139287 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1037): InactiveState{ when=-4ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-4ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-5ms what=139283 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1037): No p2p device connected
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-6ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-6ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-6ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): InactiveState{ when=-8ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-8ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=-8ms what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 7: DIRECT-qjWorkCentre 3025 9e:93:4e:3e:3a:c5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ],
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=121 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=122 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=321635098, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{30be3f01 type 2 when 575767 android} when 575767
D/[Concierge]Service( 2600): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=321635098 [*alarm*], flags=0x0
,I/BooksSync( 7456): Starting books sync
,D/BooksSync( 7456): started syncMyEbooks
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1401): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1401): received broadcast com.lge.intent.action.NLDataPosted
,E/SmartCoverUpdateMonitor( 1401): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1401): handleNotificationPosted(true)
D/QuickCircle( 1401): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1401): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post do just update job
D/LgeQuickCoverNotificationData( 1401): showAll3
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1401): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
E/BooksAccountManager( 7456): Authentication error
E/BooksAccountManager( 7456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7456): null auth token
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1401): updateNotificationData: count=3
D/libc-netbsd(  314): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  314): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/QuickStatusbarLayout( 1401): Notification difference=198
D/QuickStatusbarLayout( 1401): child = android.widget.LinearLayout{169fe7ac V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  314): res_queryN name = www.googleapis.com succeed
,I/wpa_supplicant( 2672): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1955): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=123 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2672): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
,W/ApiaryClient( 7456): Error response from books API: {
W/ApiaryClient( 7456):  "error": {
W/ApiaryClient( 7456):   "errors": [
W/ApiaryClient( 7456):    {
W/ApiaryClient( 7456):     "domain": "global",
W/ApiaryClient( 7456):     "reason": "required",
W/ApiaryClient( 7456):     "message": "Login Required",
W/ApiaryClient( 7456):     "locationType": "header",
W/ApiaryClient( 7456):     "location": "Authorization"
W/ApiaryClient( 7456):    }
W/ApiaryClient( 7456):   ],
W/ApiaryClient( 7456):   "code": 401,
W/ApiaryClient( 7456):   "message": "Login Required"
W/ApiaryClient( 7456):  }
W/ApiaryClient( 7456): }
,W/ApiaryClient( 7456): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2150816272643404995&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7456): Headers:
W/ApiaryClient( 7456): accept-encoding: [gzip]
W/ApiaryClient( 7456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7456): gdata-version: 2
,D/WfdsMonitor( 1955): Event [P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 7 120001080a436f72646f7661703270c00c000c01]
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 7 120001080a436f72646f7661703270c00c000c01]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=124 dispatchEvent: P2P-SERV-DISC-REQ 2412 ee:1f:72:63:11:86 0 7 120001080a436f72646f7661703270c00c000c01
I/jxcore-log( 6984): teardown
I/jxcore-log( 6984): 
,I/jxcore-log( 6984): testSendData stopped
I/jxcore-log( 6984): 
I/io.jxcore.node.ConnectionHelper( 6984): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6984): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6984): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6984): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6984): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6984): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6984): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6984): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6984): stop: Stopping services
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139298 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139298 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 0a436f72646f7661703270c00c000c01: returned true
D/WifiNative-p2p0( 1037): doBoolean: P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001
D/WifiNative-p2p0( 1037): P2P_SERVICE_DEL bonjour 3f7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a2267332d31222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001: returned true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): stop: Stopping P2P device discovery...
,D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=139268 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1037): doBoolean: P2P_STOP_FIND
I/wpa_supplicant( 2672): P2P-FIND-STOPPED 
D/WifiMonitor( 1037): Event [P2P-FIND-STOPPED ]
E/WifiMonitor( 1037): WifiMonitor:p2p0 cnt=125 dispatchEvent: P2P-FIND-STOPPED 
D/WfdsMonitor( 1955): Event [P2P-FIND-STOPPED ]
D/WifiNative-p2p0( 1037): P2P_STOP_FIND: returned true
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): setState: NOT_INITIALIZED
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=139307 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=139307 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState clear service request
D/LGWifiP2pService( 1037): remove channel information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6984): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6984): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6984): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6984): setState: NOT_STARTED
I/jxcore-log( 6984): StopBroadcasting went ok
I/jxcore-log( 6984): 
I/jxcore-log( 6984): 2016-01-05T10:27:06.027Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6984): 
I/jxcore-log( 6984): 2016-01-05T10:27:06.029Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 6984): 
I/io.jxcore.node.ConnectionHelper( 6984): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6984): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6984): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6984): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6984): onDiscoveryManagerStateChanged: NOT_STARTED
,I/chromium( 6984): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 52099(2MB) AllocSpace objects, 6(736KB) LOS objects, 33% free, 44MB/66MB, paused 3.313ms total 173.137ms
,I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1401): onNotificationPosted
D/SmartCoverUpdateMonitor( 1401): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1401): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1401): handleNotificationPosted(true)
D/QuickCircle( 1401): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1401): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post do just update job
D/LgeQuickCoverNotificationData( 1401): showAll3
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1401): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1401): updateNotificationData: count=3
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7456): Authentication error
E/BooksAccountManager( 7456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7456): null auth token
,D/QuickStatusbarLayout( 1401): Notification difference=198
D/QuickStatusbarLayout( 1401): child = android.widget.LinearLayout{169fe7ac V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/jxcore-log( 6984): ****TEST TOOK:  ms ****
I/jxcore-log( 6984): 
I/jxcore-log( 6984): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6984): 
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 577965349210; DSPS: 19079610; Offset : -4308103959
,W/ApiaryClient( 7456): Error response from books API: {
W/ApiaryClient( 7456):  "error": {
W/ApiaryClient( 7456):   "errors": [
W/ApiaryClient( 7456):    {
W/ApiaryClient( 7456):     "domain": "global",
W/ApiaryClient( 7456):     "reason": "required",
W/ApiaryClient( 7456):     "message": "Login Required",
W/ApiaryClient( 7456):     "locationType": "header",
W/ApiaryClient( 7456):     "location": "Authorization"
W/ApiaryClient( 7456):    }
W/ApiaryClient( 7456):   ],
W/ApiaryClient( 7456):   "code": 401,
W/ApiaryClient( 7456):   "message": "Login Required"
W/ApiaryClient( 7456):  }
W/ApiaryClient( 7456): }
,W/ApiaryClient( 7456): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2150816272643404995&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7456): Headers:
W/ApiaryClient( 7456): accept-encoding: [gzip]
W/ApiaryClient( 7456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7456): gdata-version: 2
,W/ProcessCpuTracker( 1037): Skipping unknown process pid 7770
W/ProcessCpuTracker( 1037): Skipping unknown process pid 7773
,D/AndroidRuntime( 7777): 
D/AndroidRuntime( 7777): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7777): CheckJNI is OFF
D/AndroidRuntime( 7777): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
,I/ActivityManager( 1037): Killing 6984:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/PackageSettings( 1037): Skipping PackageSetting{10ee357c com.example.hello/10319} due to missing metadata
,I/WindowState( 1037): WIN DEATH: Window{134ed140 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1037): Client connection lost with reason: 4
D/InputDispatcher( 1037): Window went away: Window{134ed140 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{1892655 u0 com.test.thalitest/.MainActivity t4}
W/bt-l2cap( 3796): l2c_link_hci_conn_req:current link_role= 1
,E/GBMv2   (  348): DFP En is all cleared set to be enabled
W/ActivityManager( 1037): Spurious death for ProcessRecord{16b4d465 6984:com.test.thalitest/u0a311}, curProc for 6984: null
I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{1892655 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{1892655 u0 com.test.thalitest/.MainActivity t4 f}
,W/bt-btm  ( 3796): btm_acl_created hci_handle=1 link_role=1  transport=1
W/bt-btm  ( 3796): btm_acl_created hci_handle=1 link_role=1  transport=1
I/[LGHome]EVENT( 2073): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2073): [Launcher.java:903:onResume()]onResume
,D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{f614ad4 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1955): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1955): topRunningActivity=ActivityInfo{2531a47d co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2073): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2073): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1907): notifyUserLog: 1000003
,D/LIA_Informant_ActionManagerMessageHandler( 3709): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2073): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2073): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2073): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2073): [Launcher.java:1114:onPause()]onPause
D/KeyguardModel( 1452): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1820): Ignoring removeGeofence because network location is disabled.
E/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3796): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2030): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3709): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/PostponalbeReceiver( 6617): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/System.err( 4554): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4554): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4554): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4554): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
,W/System.err( 4554): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4554): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4554): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4554): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4554): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4554): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4554): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4554): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/administrator( 1037): Handling package changes for user 0
,D/AppUp4:PreloadHelper( 7235): added Exclude : com.test.thalitest
,I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7806 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/[LGHome]GBoardWebView( 2073): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,D/ActionManagerService( 1907): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3709): handleMessage: what(1000) actionID(0x1000004)
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,D/SplitUIManager( 1872): split_name #11 / not available #0
D/SplitUIService( 1872): removed split : 
I/ActivityManager( 1037): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7825 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
V/BoardContentProvider( 3709): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2073): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2073): , create_time: 1430558575574
I/GBoardWebViewUtils( 2073): , expire_time: 0
I/GBoardWebViewUtils( 2073): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2073): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2073): , display: false
I/GBoardWebViewUtils( 2073): , animation: false }
I/GBoardWebViewUtils( 2073): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2073): , create_time: 1430558575600
I/GBoardWebViewUtils( 2073): , expire_time: 0
I/GBoardWebViewUtils( 2073): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2073): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2073): , display: false
I/GBoardWebViewUtils( 2073): , animation: false }
I/GBoardWebViewUtils( 2073): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1451568242148
I/GBoardWebViewUtils( 2073): , create_time: 1451568243131
I/GBoardWebViewUtils( 2073): , expire_time: 0
I/GBoardWebViewUtils( 2073): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1451568242148&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2073): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2073): , display: false
I/GBoardWebViewUtils( 2073): , animation: false }
,I/[SystemUI]QSlideListController( 1452): onReceive = android.intent.action.PACKAGE_REMOVED
I/art     ( 4605): Explicit concurrent mark sweep GC freed 22516(1261KB) AllocSpace objects, 1(16KB) LOS objects, 34% free, 30MB/46MB, paused 589us total 209.187ms
D/WallpaperManager( 2073): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@b31f07c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1452): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1452): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/[LGHome]GBoardWebView( 2073): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/SplitUIManager( 1872): split_name #11 / not available #0
I/SplitUIService( 1872): split app #11
W/ResourcesManager( 7806): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7806): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7806): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7806): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7806): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/LockScreenSettings( 7825): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
D/PhoneStatusBar( 1452): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1452): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1452):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1452): , Keyguard show=false, IME shown=false, Panel expanded=false
,W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
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
D/KeyguardModel( 1452): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1452): createShortcutInfo...
D/KeyguardModel( 1452): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1452): createShortcutInfo...
W/ResourcesManager( 1452): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1452): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1452): createShortcutInfo...
W/ResourcesManager( 1452): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1452): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1452): createShortcutInfo...
,I/[LGHome]EVENT( 2073): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]EVENT( 2073): [Launcher.java:5349:onStop()]onStop
W/ResourcesManager( 1452): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
W/ResourcesManager( 1452): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1452): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1452): createShortcutInfo...
I/ThermalEngine(  328): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3144): Thermal-Lib-Client: Client request sent
D/KeyguardModel( 1452): handleShortcutListChanged...
D/KeyguardModel( 1452): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1452): createShortcutInfo...
,D/KeyguardModel( 1452): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1452): createShortcutInfo...
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1452): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1452): createShortcutInfo...
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1452): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1452): createShortcutInfo...
I/SystemConfig( 7806): BUILD Country: EU
W/ResourceType( 1452): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1452): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/SystemConfig( 7806): BUILD Operator: OPEN
,D/KeyguardModel( 1452): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1452): createShortcutInfo...
D/KeyguardModel( 1452): handleShortcutListChanged...
V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[LGHome]Launcher.Model( 2073): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/GLSUser ( 2128): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2128): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2128): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2128): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2128): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[LGHome]Launcher.Model( 2073): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2073): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2073): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{31df7927 u0 com.lge.launcher2/.Launcher t3} time:579025
I/ActivityManager( 1037): Killing 7104:com.lge.sync/1000 (adj 15): empty #17
,I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2073): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2073): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 20377(1381KB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 2.080ms total 406.242ms
,D/[Concierge]Service( 2600): onStartCommand(). Type : 8
D/[Concierge]Service( 2600): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]WidgetView( 2073): change position of spinner
D/[Concierge]Service( 2600): Update widget ID : 11
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_7104/cgroup.procs: No such file or directory
D/AndroidRuntime( 7777): Shutting down VM
,D/VoicemailCleanupService( 2147): Cleaning up data for package: com.test.thalitest
I/SystemConfig( 7806): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7806): existFile = false
I/SystemConfig( 7806): canReadFile = false
I/SystemConfig( 7806): systemFeature RCS result false
D/SystemConfig( 7806): refreshRcsSupport() :false
I/[Concierge]WidgetView( 2073): initWebView(). Time : 1451989628195
,D/[Concierge]Service( 2600): onStartCommand(). Type : 0
I/PackageChangeReceiver( 6678): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager( 1037): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7852 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1037): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2128): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2128): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2128): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2128): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2128): 	at android.os.Binder.execTransact(Binder.java:446)
I/art     (  352): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 9.570ms
,I/[Concierge]WebView( 2073): Return exist ConciergeWebView. Reuse : 415180874
D/[Concierge]WidgetView( 2073): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2073): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/BooksAccountManager( 7456): Authentication error
E/BooksAccountManager( 7456): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7456): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7456): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7456): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7456): null auth token
I/[LgeWidgetLib]ExtViewHost( 2073): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@10f0da9d
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
D/LgeQuickCoverNLService( 1401): onNotificationPosted
D/SmartCoverUpdateMonitor( 1401): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1401): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1401): handleNotificationPosted(true)
D/QuickCircle( 1401): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1401): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): post do just update job
D/LgeQuickCoverNotificationData( 1401): showAll3
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1401): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1401): showNotificationWithSetupData: display=false
I/[LGHome]Launcher.Model( 2073): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  0
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 8.905ms
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
D/[Concierge]WidgetView( 2073): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2073): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/art     (  352): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 191us total 8.830ms
D/LgeQuickCoverOverlayWindow( 1401): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1401): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1401): updateNotificationData: count=3
D/QuickStatusbarLayout( 1401): Notification difference=198
D/QuickStatusbarLayout( 1401): child = android.widget.LinearLayout{169fe7ac V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ResourcesManager( 7852): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/[Concierge]WidgetView( 2073): Widget kill message received. Destory myself. My : 1451989077299, New one : 1451989628195
D/[Concierge]WidgetView( 2073): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2073): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7852): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7852): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7852): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LgeWidgetLib]LgeAppWidgetHostView( 2073): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2073): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2073): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 2073): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2073): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/AppConfig( 7852): Total System Memory = 2995761152
,D/SystemHelper( 7852): region [EU], country [EU], operator [OPEN], sub-operator []
I/Timeline( 2073): Timeline: Activity_idle id: android.os.BinderProxy@1979b261 time:579252
,I/ActivityManager( 1037): Killing 7266:com.lge.formmanager/u0a26 (adj 15): empty #17
,D/LIA_Service_NativeEventReceiver( 2030): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/LIA_Service_PlatformUtil( 2030): startLIAService() : Trying to start LIA service ...
W/libprocessgroup( 1037): failed to open /acct/uid_10026/pid_7266/cgroup.procs: No such file or directory
D/LIA_Service_LIAService( 2030): onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,D/PostponalbeReceiver( 6617): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
D/CoreEventReceiver( 7701): [onReceive] Action=android.intent.action.PACKAGE_REMOVED
D/PackageIntentReceiver( 7068): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 7068): Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
,D/HideNavigationAppsReceiver( 7068): replacing : false
D/HideNavigationAppsReceiver( 7068): Delete mPackageMame : com.test.thalitest
D/ButtonCombinationReceiver( 7068): Receive package name : com.test.thalitest
D/ButtonCombinationReceiver( 7068): replacing : false
I/UpdateIcingCorporaServi( 4605): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/ActivityManager( 1037): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7874 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ApiaryClient( 7456): Error response from books API: {
W/ApiaryClient( 7456):  "error": {
W/ApiaryClient( 7456):   "errors": [
W/ApiaryClient( 7456):    {
W/ApiaryClient( 7456):     "domain": "global",
W/ApiaryClient( 7456):     "reason": "required",
W/ApiaryClient( 7456):     "message": "Login Required",
W/ApiaryClient( 7456):     "locationType": "header",
W/ApiaryClient( 7456):     "location": "Authorization"
W/ApiaryClient( 7456):    }
W/ApiaryClient( 7456):   ],
W/ApiaryClient( 7456):   "code": 401,
W/ApiaryClient( 7456):   "message": "Login Required"
W/ApiaryClient( 7456):  }
W/ApiaryClient( 7456): }
W/ApiaryClient( 7456): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7456): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-2150816272643404995&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7456): Headers:
W/ApiaryClient( 7456): accept-encoding: [gzip]
W/ApiaryClient( 7456): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7456): gdata-version: 2
,I/chromium( 2073): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,E/SQLiteLog( 4605): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/IcingCorporaProvider( 4605): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 4605): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 4605): 	at beg.a(PG:301)
E/IcingCorporaProvider( 4605): 	at beg.c(PG:222)
E/IcingCorporaProvider( 4605): 	at cun.b(PG:660)
E/IcingCorporaProvider( 4605): 	at cun.a(PG:651)
E/IcingCorporaProvider( 4605): 	at cun.g(PG:597)
E/IcingCorporaProvider( 4605): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 4605): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/IcingCorporaProvider( 4605): 	at android.content.ContentResolver.update(ContentResolver.java:1349)
E/IcingCorporaProvider( 4605): 	at cuw.Tg(PG:368)
E/IcingCorporaProvider( 4605): 	at cuy.ub(PG:301)
E/IcingCorporaProvider( 4605): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/IcingCorporaProvider( 4605): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/IcingCorporaProvider( 4605): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 4605): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 4605): 	at android.os.Looper.loop(Looper.java:135)
E/IcingCorporaProvider( 4605): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 4605): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 4605): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 4605): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
E/IcingCorporaProvider( 4605): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 4605): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 4605): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/IcingCorporaProvider( 4605): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/IcingCorporaProvider( 4605): 	at bea.a(PG:382)
E/IcingCorporaProvider( 4605): 	at beg.i(PG:325)
E/IcingCorporaProvider( 4605): 	at beh.call(PG:215)
E/IcingCorporaProvider( 4605): 	at beg.a(PG:299)
E/IcingCorporaProvider( 4605): 	... 15 more
W/IcingCorporaProvider( 4605): notifyTableChanged failed.
W/IcingCorporaProvider( 4605): Table change notification failed for TableStorageSpec[applications]
I/UpdateIcingCorporaServi( 4605): UpdateCorporaTask done [took 86 ms] updated apps [took 86 ms] 
D/DocsApplication( 7874): Installing DEX configuration.
D/DexInstaller( 7874): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper( 7874): Provided clientMode=RELEASE, packageInfo=PackageInfo{227e8d4a com.google.android.apps.docs}
,D/TAG     ( 7874): onCreate()
D/CrossAppStateProvider( 7874): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
I/GBoardtInterface( 2073): onReloaded()
,I/GBoardWebViewClient( 2073): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3709): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3709): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1907): notifyUserLog: 1000001

```
