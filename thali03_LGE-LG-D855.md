#### Test 54312298c831015_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 287718079607; DSPS: 9568687; Offset : -4310867685
,D/AndroidRuntime( 6985): 
D/AndroidRuntime( 6985): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6985): CheckJNI is OFF
D/AndroidRuntime( 6985): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1035): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1970): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1035): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1035): setTaskToReturnTo : TaskRecord{20bd98ef #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1035): setTaskToReturnTo : TaskRecord{20bd98ef #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1035): AppWindowTokenEx init.. 
E/GBMv2   (  340): DFP En is all cleared set to be enabled
I/ActivityManager( 1035): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7004 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6985): Shutting down VM
V/ActivityManager( 1035): Display changed displayId=0
D/DSDPConnection( 1873): Display #0 changed.
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{278dc407 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{2d80c934 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7004): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7004): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7004): Loading: webviewchromium
,I/LibraryLoader( 7004): Time to load native libraries: 5 ms (timestamps 2409-2414)
I/LibraryLoader( 7004): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7004): Binding Chromium to main looper Looper (main, tid 1) {3f210577}
,I/LibraryLoader( 7004): Expected native library version number "",actual native library version number ""
I/chromium( 7004): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7004): Initializing chromium process, renderers=0
,W/art     ( 7004): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  309): registerClient() client 0xb57dada0, uid 10311
,W/chromium( 7004): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7004): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7004): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1035): Message: 20
D/BluetoothManagerService( 1035): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33e61601:true
I/Adreno-EGL( 7004): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7004): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7004): Build Date: 12/12/14 금
I/Adreno-EGL( 7004): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7004): Remote Branch: 
I/Adreno-EGL( 7004): Local Patches: 
I/Adreno-EGL( 7004): Reconstruct Branch: 
,W/chromium( 7004): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7004): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7004): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7004): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7004): CordovaWebView is running on device made by: LGE
,W/art     ( 7004): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7004): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1035): Activity pause timeout for ActivityRecord{2d2d1ffc u0 com.test.thalitest/.MainActivity t4}
,D/OpenGLRenderer( 7004): Render dirty regions requested: true
I/OpenGLRenderer( 7004): Initialized EGL, version 1.4
D/OpenGLRenderer( 7004): Enabling debug mode 0
,D/Atlas   ( 7004): Validating map...
,D/SplitWindow( 1035): check instance of lgWin Window{2edd6a73 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 7004): LgDataFeature() Constructor: none
D/LgDataFeature( 7004): LgDataFeature() Constructor Done, null
,I/SystemUI[Framework]( 1035): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,D/PhoneStatusBar( 1466): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1035): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1035): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1035): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2d4c3277,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1466): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1466):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1466): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1035): Displayed com.test.thalitest/.MainActivity: +678ms (total +767ms)
I/Timeline( 1035): Timeline: Activity_windows_visible id: ActivityRecord{2d2d1ffc u0 com.test.thalitest/.MainActivity t4} time:292874
I/Timeline( 7004): Timeline: Activity_idle id: android.os.BinderProxy@14283a67 time:292874
,I/chromium( 7004): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7004): 
,D/JsMessageQueue( 7004): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7004): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435096320
,D/JX-Cordova( 7004): jxcore cordova android initializing
,E/GBMv2   (  340): DFP En is all cleared set to be enabled
,E/GBMv2   (  340): Set value is all cleared set the max
I/GBMv2   (  340): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7004): Initializing JXcore engine
W/jxcore-log( 7004): JXcore engine is ready
,W/jxcore-log( 7004): Starting JXcore engine
W/.test.thalitest( 7004): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8266]" dev="sockfs" ino=8266 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7004): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7004): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8472]" dev="sockfs" ino=8472 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7004): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7004): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33692]" dev="sockfs" ino=33692 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7004): Background sticky concurrent mark sweep GC freed 123267(11MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.678ms total 126.259ms
,W/jxcore-log( 7004): Platform android
W/jxcore-log( 7004): 
,W/jxcore-log( 7004): Process ARCH arm
W/jxcore-log( 7004): 
I/jxcore-log( 7004): JXcore Cordova bridge is ready!
I/jxcore-log( 7004): 
W/jxcore-log( 7004): JXcore engine is started
,I/jxcore-log( 7004): Toggling radios to true
I/jxcore-log( 7004): 
D/BluetoothAdapter( 7004): enable(): BT is already enabled..!
D/WifiService( 1035): New client listening to asynchronous messages
D/WifiServiceImplEx( 1035): setWifiEnabled: true pid=7004, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1035): setWifiEnabled: true pid=7004, uid=10311
E/WifiService( 1035): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1035): disconnect pid=7004, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1035): reconnect pid=7004, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7004): Radios toggled
I/jxcore-log( 7004): 
E/WifiStateMachine( 1035):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_DISCONNECT 0 0
D/BluetoothManagerService( 1035): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 7004): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7004): 
E/WifiNative: ( 1035): [296,742,441 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1035): doBoolean: DISCONNECT
I/jxcore-log( 7004): Perf Test app loaded loaded
I/jxcore-log( 7004): 
I/jxcore-log( 7004): check test folder
I/jxcore-log( 7004): 
I/jxcore-log( 7004): found test : ./testFindPeers.js
I/jxcore-log( 7004): 
I/jxcore-log( 7004): found test : ./testSendData.js
I/jxcore-log( 7004): 
I/wpa_supplicant( 2641): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1035): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1035): DISCONNECT: returned true
D/Tethering( 1035): InitialState.processMessage what=4
E/WifiMonitor( 1035): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1035): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
D/Tethering( 1035): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2641): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
D/WifiNative-wlan0( 1035): SET ps 1: returned true
D/CommandListener(  305): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1035): RunningState{ when=-10ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2142): Read error: ssl=0xaa6d8800: I/O error during system call, Connection timed out
V/NativeCrypto( 2142): SSL shutdown failed: ssl=0xaa6d8800: I/O error during system call, Broken pipe
D/ConnectivityService( 1035): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/ActivityManager( 1035): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7105 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
E/WifiStateMachine( 1035): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1035):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1035): [296,847,935 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1035): doBoolean: RECONNECT
I/wpa_supplicant( 2641): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1035): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1035): hidePasspointNotification off =false
V/WfdStateTracker( 1970): handleWifiStateChangedEvent: 0
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1035): RECONNECT: returned true
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1035):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=296860
E/WifiStateMachine( 1035):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=296861
D/LGWifiP2pService( 1035): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2641): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
I/jxcore-log( 7004): found test : ./testSendData2.js
I/jxcore-log( 7004): 
D/WifiNative-wlan0( 1035): SET ps 1: returned true
E/jxcore  ( 7004): Error!: missing ) after argument list
E/jxcore  ( 7004): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
D/WifiHS20( 1035): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/CommandListener(  305): Clearing all IP addresses on wlan0
D/ConnectivityService( 1035): Default network via Wi-Fi disconnect. stop DSQN
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1035): disableDataServiceNotify
D/DSQN    ( 1035): stop dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
I/chromium( 7004): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/DSQN    ( 1035): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiHS20( 1035): hidePasspointNotification off =false
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=296902  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=296902  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1035):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
I/chromium( 7004): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7004): 
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1035): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=296908  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiHS20( 1035): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=296913  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1035): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateDISCONNECTED
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1035): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1035): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( ,1035): setSupplicantStateSCANNING
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1035): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524292
D/TelephonyNetworkFactory-1( 1873): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1035): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkManagementService( 1035): Removing idletimer
V/NetworkPolicy( 1035): [LG_RESTRICTED] !!!isConnected  type  :1
W/Settings( 1035): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LocSvc_java( 1035): Sending msg: 4 arg1:0 arg2:1
D/ConnectivityService( 1035): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1035): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
V/NetworkPolicy( 1035): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1035): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
,D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7105): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7105): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7105): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7105): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7105): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7105): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/chromium( 7004): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/DhcpStateMachine( 1035): StoppedState
D/DhcpStateMachine( 1035): StoppedState{ when=-143ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbSettingsReceiver( 7105): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7105): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7105): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7105): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7105): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7105): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7105): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7105): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7105): [AUTORUN] onReceive() : errorList=[]
,D/UsbSettingsControl( 7105): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7105): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/ActivityManager( 1035): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7140 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 6536:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10008/pid_6536/cgroup.procs: No such file or directory
,I/PCSuite ( 7140): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7140): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7140): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7105): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7105): LgDataFeature() Constructor: none
D/LgDataFeature( 7105): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7105): MCCMNC not supported: null
I/ActivityManager( 1035): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7164 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1035): Killing 6056:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10011/pid_6056/cgroup.procs: No such file or directory
,W/ResourcesManager( 7164): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7164): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7164): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7164): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7164): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 7164): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7164): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7164): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7164): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7164): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7164): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7164): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7140): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7140): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7140): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7164): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,V/WiFiOffLoadBroadcast( 7105): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 7164): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,D/WiFiOffLoadBroadcast( 7105): MCCMNC not supported: null
D/QRemote ( 7164): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7164): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7164): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7140): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7140): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7140): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7105): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7105): MCCMNC not supported: null
D/QRemote ( 7164): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7164): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7164): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7140): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7140): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7140): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7105): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7105): MCCMNC not supported: null
D/QRemote ( 7164): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7164): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7164): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7105): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7105): MCCMNC not supported: null
D/QRemote ( 7164): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7164): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7164): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7164): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7164): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7164): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7164): LgDataFeature() Constructor: none
D/LgDataFeature( 7164): LgDataFeature() Constructor Done, null
,V/SoundPool( 7164): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7164): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7164): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7164): doLoad: loading sample sampleID=1
I/QRemote ( 7164): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7164): Start decode
V/MediaPlayer[Native]( 7164): decode(31, 10857164, 17813)
V/MediaPlayerService(  309): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  309): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  309): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  309): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  309): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  309): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  309): player type = 3
V/AwesomePlayer(  309): AwesomePlayer create()
,V/AwesomePlayer(  309): reset_l() ,
V/AwesomePlayer(  309): cancelPlayerEvents
V/AwesomePlayer(  309): setAudioSink() 
V/AwesomePlayer(  309): reset_l() 
V/AudioCache(  309): notify(0xb5474a80, 8, 0, 0)
V/AudioCache(  309): ignored
V/AwesomePlayer(  309): cancelPlayerEvents
D/Utils   (  309): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  309): setDataSource_l dataSource
V/LGParserOSAL(  309): SniffLGParser start
V/LGParserOSAL(  309): MainType:5, SubType=0
V/LGParserOSAL(  309): #### check Mime : application/ogg
V/LGParserOSAL(  309): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  309): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6703): QS Service created
D/QRemote ( 7164): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,I/UEI.SmartControl( 6703): Service initServices...
D/UEI.SmartControl( 6703): QS start get config
,V/LGParserOSAL(  309): supported mime: application/ogg
V/AwesomePlayer(  309): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  309): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  309): mBitrate = -1 bits/sec
V/AwesomePlayer(  309): AudioTrack Setting
V/AwesomePlayer(  309): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  309): setAudioSource() 
V/MediaPlayerService(  309): prepare
V/AwesomePlayer(  309): prepareAsync_l() 
V/MediaPlayerService(  309): wait for prepare
V/AwesomePlayer(  309): onPrepareAsyncEvent() 
V/AwesomePlayer(  309): initAudioDecoder() 
W/Utils   (  309): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  309): isOffloadSupported()
V/AudioPolicyManager(  309): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  309): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  309): isAudioPlaybackHookOn() false
V/AwesomePlayer(  309): getUseOffload() = 0 
V/OMXCodec(  309): OMXCodec::Create
V/OMXCodec(  309): findMatchingCodecs()
V/OMXCodec(  309): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  309): matchingCodecs.size()=1
V/OMXCodec(  309): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
E/QRemote ( 7164): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7164): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/OMXCodec(  309): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  309): LG Codec Adapter start
V/OMXCodec(  309): OMXCodec Createtor
V/OMXCodec(  309): setComponentRole
V/OMXCodec(  309): configureCodec protected=0
V/LGCodecAdapter(  309): called getLGCodecSpecificData
,V/LGCodecOSAL(  309): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  309): Called LGconfigureCodecMETA
V/LGCodecOSAL(  309): Called LGconfigureCodecMSG
V/LGCodecOSAL(  309): Not support LGCodec
V/OMXCodec(  309): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  309): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  309): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  309): Could not offload audio decode, try pcm offload
W/Utils   (  309): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  309): isOffloadSupported()
V/AudioPolicyManager(  309): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  309): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  309): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  309): init()
V/OMXCodec(  309): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  309): allocateBuffers
V/OMXCodec(  309): allocateBuffersOnPort portIndex=0
V/OMXCodec(  309): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  309): [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
V/OMXCodec(  309): [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
V/OMXCodec(  309): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
,V/OMXCodec(  309): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
V/OMXCodec(  309): allocateBuffersOnPort portIndex=1
V/OMXCodec(  309): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  309): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
V/OMXCodec(  309): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
V/OMXCodec(  309): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
V/OMXCodec(  309): [OMX.google.vorbis.decoder] allocated buffer 0xb57c2240 on output port
V/OMXCodec(  309): init() mAsyncCompletion wait!!! 
V/OMXCodec(  309): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  309): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  309): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  309): init() mAsyncCompletion wait!!! 
,V/OMXCodec(  309): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  309): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  309): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  309): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  309): finishAsyncPrepare_l() 
V/AudioCache(  309): notify(0xb5474a80, 5, 0, 0)
V/AudioCache(  309): ignored
V/AudioCache(  309): notify(0xb5474a80, 1, 0, 0)
V/AudioCache(  309): prepared
V/AudioCache(  309): wait - success
V/MediaPlayerService(  309): start
V/AwesomePlayer(  309): play_l() 
V/AwesomePlayer(  309): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  309): createAudioPlayer_l
,V/AwesomePlayer(  309): seekAudioIfNecessary_l() 
V/AwesomePlayer(  309): startAudioPlayer_l() 
D/AudioPlayer(  309): start of Playback, useOffload 0
V/OMXCodec(  309): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  309): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  309): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  309): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  309): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  309): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  309): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
,V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  309): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  309): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  309): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  309): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044811328
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  309): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  309): [OMX.google.vorbis.decoder] initOutputFormat()
,V/OMXCodec(  309): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  309): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  309): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  309): allocateBuffersOnPort portIndex=1
V/OMXCodec(  309): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  309): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
V/OMXCodec(  309): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
V/OMXCodec(  309): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
,V/OMXCodec(  309): [OMX.google.vorbis.decoder] allocated buffer 0xb57c2740 on output port
V/OMXCodec(  309): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  309): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  309): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  309): notify(0xb5474a80, 6, 0, 0)
V/AudioCache(  309): ignored
V/MediaPlayerService(  309): wait for playback complete
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac202000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac203000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac204000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac205000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac206000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
,V/AudioCache(  309): memcpy(0xac207000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac208000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac209000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac20a000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac20b000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac20c000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac20d000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac20e000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac20f000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac210000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac211000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac212000, 0xb1693000, 4096)
,V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac213000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac214000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac215000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac216000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac217000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac218000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac219000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac21a000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac21b000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac21c000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac21d000, 0xb1693000, 4096)
,V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac21e000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac21f000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac220000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac221000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac222000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac223000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac224000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac225000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac226000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac227000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac228000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac229000, 0xb1693000, 4096)
,V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac22a000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac22b000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac22c000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac22d000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac22e000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac22f000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac230000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac231000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac232000, 0xb1693000, 4096)
V/AudioCache(  309): write(0xb1693000, 4096)
V/AudioCache(  309): memcpy(0xac233000, 0xb1693000, 4096)
V/OMXCodec(  309): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  309): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  309): postAudioEOS() 
V/AudioCache(  309): write(0xb1693000, 280)
V/AudioCache(  309): memcpy(0xac234000, 0xb1693000, 280)
V/LGMDMManager( 7164): Create singleton instance
V/AwesomePlayer(  309): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  309): onStreamDone
V/AwesomePlayer(  309): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  309): notify(0xb5474a80, 2, 0, 0)
V/AudioCache(  309): playback complete
V/AwesomePlayer(  309): pause_l() 
V/AudioCache(  309): notify(0xb5474a80, 7, 0, 0)
V/AudioCache(  309): ignored
V/AwesomePlayer(  309): cancelPlayerEvents
V/AudioCache(  309): wait - success
V/MediaPlayerService(  309): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  309): Pause Playback at 1068125
V/AwesomePlayer(  309): reset_l() 
V/AudioCache(  309): notify(0xb5474a80, 8, 0, 0)
V/AudioCache(  309): ignored
V/AwesomePlayer(  309): cancelPlayerEvents
D/AudioPlayer(  309): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  309): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  309): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  309): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  309): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  309): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  309): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeing buffer 0xb57c2740 on port 1
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  309): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f10 on port 1
V/OMXCodec(  309): [OMX.google.vor,bis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  309): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  309): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  309): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
,V/OMXCodec(  309): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  309): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  309): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  309): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  309): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  309): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  309): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  309): AudioPlayer releasing audio source
D/AudioPlayer(  309): AudioPlayer done releasing audio source
V/AwesomePlayer(  309): reset_l() 
V/AwesomePlayer(  309): cancelPlayerEvents
V/AwesomePlayer(  309): ~AwesomePlayer call
V/AwesomePlayer(  309): reset_l() 
V/AwesomePlayer(  309): cancelPlayerEvents
V/SoundPool( 7164): close(31)
V/SoundPool( 7164): pointer = 0x9ff36000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 7164): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7164): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 7164): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5233
I/UEI.SmartControl( 6703): Supports setup maps: true
,D/UEI.SmartControl( 6703): QS start statue = true Error code = 0
I/UEI.SmartControl( 6703): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6703): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6703): ### init IR Blaster...
D/serial_port( 6703): Configuring serial port
E/UEI.SmartControl( 6703): UEIBLaster setting for 616
I/UEI.SmartControl( 6703): Setting serial record hearder size = 2
I/UEI.SmartControl( 6703): configuring settings for MAXQ616
I/UEI.SmartControl( 6703): Get version...
D/UEI.SmartControl( 6703): serial port data available: 21
,D/UEI.SmartControl( 6703): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6703): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6703): QS saving settings...
,D/UEI.SmartControl( 6703): IR Blaster version: 25672567
D/UEI.SmartControl( 6703): serial port data available: 4
,W/ContextImpl( 6703): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,I/UEI.SmartControl( 6703): Device manager: loading config....
D/UEI.SmartControl( 6703): ----------- loading internal config...
E/UEI.SmartControl( 6703): Services init done
D/UEI.SmartControl( 6703): QS Service init finished
D/UEI.SmartControl( 6703): QS Service version name: 2.1.91
D/UEI.SmartControl( 6703): QS Service version code: 201091
D/UEI.SmartControl( 6703): Service requested: Control
E/UEI.SmartControl( 6703): Loading SETTINGS...
,D/UEI.SmartControl( 6703): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6703): -- Open brand translation xml: brands_translations_ko
I/QRemote ( 7164): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6703): Internal service binding...
I/UEI.SmartControl( 6703): ------ IControl API: 11
D/UEI.SmartControl( 6703): File observer start...
E/UEI.SmartControl( 6703): IR Port is disabled: false
D/UEI.SmartControl( 6703): Starting file observer...
I/UEI.SmartControl( 6703): Registering callback...
I/UEI.SmartControl( 6703): ------ IControl API: 19
,I/UEI.SmartControl( 6703): Registering Services Ready callback...
I/UEI.SmartControl( 6703): Notify AllClients services are ready: 0
I/QRemote ( 7164): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 7164): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7164): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/UEI.SmartControl( 6703): -----service ready thread exits
D/QRemote ( 7164): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7164): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6703): ------ IControl API: 8
D/QRemote ( 7164): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7164): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7164): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7164): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7164): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7164): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7164): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7164): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7164): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 7164): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7164): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7164): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7164): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7164): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7164): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1450739092606]
D/QRemote ( 7164): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1035): Killing 6076:com.android.contacts/u0a19 (adj 15): empty #17
,D/QRemote ( 7164): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1035): failed to open /acct/uid_10019/pid_6076/cgroup.procs: No such file or directory
,V/QRemote ( 7164): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7164): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7164): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7164): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7164): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7164): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7164): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7164): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2641): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1035): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1035): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1035): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1035):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1035):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1035):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1035):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1035): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=298990  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=299024  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateASSOCIATING
,D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7105): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7105): MCCMNC not supported: null
D/QRemote ( 7164): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7164): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7164): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7105): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/wpa_supplicant( 2641): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
I/wpa_supplicant( 2641): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2641): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=299103  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor( 1035): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1035): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1035): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1035): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=299108  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/Tethering( 1035): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine( 1035):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=299118
E/WifiStateMachine( 1035):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=299118
E/WifiStateMachine( 1035):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=299120
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=299120
E/WifiStateMachine( 1035):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=299120
E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=299123  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=299152  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,E/WifiStateMachine( 1035):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=299158  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
,E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=299160  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1035):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=299162
D/WiFiOffLoadBroadcast( 7105): MCCMNC not supported: null
E/WifiStateMachine( 1035):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=299163
D/WifiNative-wlan0( 1035): doString: [STATUS]
D/WifiMonitor( 1035): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1035): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1035):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1035): setVHTCapabilityType  : false
,D/QRemote ( 7164): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7164): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7164): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/WifiServerServiceExt( 1035): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1035): setKeepAlivePacketInterval msec : 60
D/UsbSettingsReceiver( 7105): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7105): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7105): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7105): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7105): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7105): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7105): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7105): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7105): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7105): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7105): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7105): [AUTORUN] setTetherStatus() : status=false
D/ConnectivityService( 1035): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1035): Got NetworkAgent Messenger
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1035): NetworkAgent connected
E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
,D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
E/WifiConfigStore( 1035): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1035): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1035): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1035): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7105): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7105): MCCMNC not supported: null
D/WifiNative-wlan0( 1035): SAVE_CONFIG: returned true
D/CommandListener(  305): Setting iface cfg
E/WifiStateMachine( 1035): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1035): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): WaitBeforeStartState
E/WifiStateMachine( 1035):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=299210  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=299211  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=299211  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1035):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
D/QRemote ( 7164): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1035):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/QRemote ( 7164): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/WifiStateMachine( 1035):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
I/QRemote ( 7164): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1035):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=299220  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=299221  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=299221  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1035):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1035):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1035): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 7105): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7105): MCCMNC not supported: null
D/QRemote ( 7164): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7164): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7164): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/wpa_supplicant( 2641): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1035): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 0
D/WifiNative-wlan0( 1035): SET ps 0: returned true
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2641): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1035): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1035): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1035): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@288fcf31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@288fcf31 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1035): DHCP Start wake lock is acquired.
D/CommandListener(  305): Setting iface cfg
D/CommandListener(  305): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1035): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/WiFiOffLoadBroadcast( 7105): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1035): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1035): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1035):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1035):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1035):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1035): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2641): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1035): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1035): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1035): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1035): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2641): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1035): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1035): doBoolean: SET ps 1
,D/WiFiOffLoadBroadcast( 7105): MCCMNC not supported: null
,D/QRemote ( 7164): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7164): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7164): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1035): SET ps 1: returned true
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
V/WiFiOffLoadBroadcast( 7105): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1035):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,E/WifiStateMachine( 1035):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1035): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1035): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1035): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1035): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1035): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WiFiOffLoadBroadcast( 7105): MCCMNC not supported: null
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1035): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/WfdStateTracker( 1970): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1466): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1035): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1035): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService( 1035): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1035): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/QRemote ( 7164): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7164): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1035): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/QRemote ( 7164): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/Netd    (  305): netlink response contains error (File exists)
D/ConnectivityService( 1035): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1035): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1035): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1035): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1035): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1035): currentScore = 0, newScore = 20
D/ConnectivityService( 1035):    accepting network in place of null
D/ConnectivityService( 1035): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Connected
D/TelephonyNetworkFactory-1( 1873): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/WIFI    ( 1035): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = true, mWifiLevel = 0
E/ConnectivityService( 1035): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe8,0::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1035): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1035): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1035): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1035): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/libc-netbsd(  305): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1035): validation of new default Network = false
D/ConnectivityService( 1035): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1035): enableDataServiceNotify 
D/DSQN    ( 1035): start dsqn bin
D/LocSvc_java( 1035): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1035): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1035): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1035): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1035): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524290
W/dsqn    ( 7242): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7242): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/DSQN    ( 7242): DSQN ssw
V/NetworkPolicy( 1035): [LG_RESTRICTED] checkMobilePolicy_type()
V/WiFiOffLoadBroadcast( 7105): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7105): MCCMNC not supported: null
D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7164): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7164): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7164): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  305): res_queryN name = clients3.google.com, class = 1, type = 1
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7105): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7105): MCCMNC not supported: null
D/QRemote ( 7164): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7164): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7164): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7140): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7140): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7105): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7105): MCCMNC not supported: null
D/libc-netbsd(  305): res_queryN name = clients3.google.com succeed
D/QRemote ( 7164): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7164): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 7164): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7164): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7164): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  305): argv[0]=dsqncommand
D/LGDataListener(  305): argv[1]=wlan0
D/LGDataListener(  305): argv[2]=1
D/LGDataListener(  305): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1035): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1035): start to monitor internet connection
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7140): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7140): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Dec 2015 23:04:53 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450739093528], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450739093511]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1035): Validated
D/ConnectivityService( 1035): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1035):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1035): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1035): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/WiFiOffLoadBroadcast( 7105): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1035): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524290
D/ConnectivityService( 1035): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1035): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1035):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1873): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,D/WiFiOffLoadBroadcast( 7105): MCCMNC not supported: null
,D/DhcpStateMachine( 1035): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1035): [bssid] hash key :c0:ff:d4:d3:aa:48
,D/LgDhcpStateMachineHelper( 1035): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/QRemote ( 7164): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7164): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7164): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7164): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7164): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
W/dhcpcd  ( 7248): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7248): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6837 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/dhcpcd  ( 7248): version 5.5.6 starting
E/dhcpcd  ( 7248): get_duid: m
D/dhcpcd  ( 7248): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7248): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 7248): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7248): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7248): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7248): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7248): wlan0: sending REQUEST (xid 0x1bbfa8d7), next in 3.48 seconds
,D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1035): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6497): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,D/Tethering( 1035): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 5422): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5422): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1035): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7265 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7265): onCreate
,W/AppUp4:DB( 7265):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7265):  setFingerPrint start
I/AppUp4:DB( 7265):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7265):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 7265):  SDK version = 21
I/AppUp4:DB( 7265):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7265): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7265): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7265): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7265): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7265): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7265): onReceive
D/LgDataFeature( 7265): LgDataFeature() Constructor: none
D/LgDataFeature( 7265): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7265): Context : android.app.ReceiverRestrictedContext@38feea4d
E/WifiStateMachine( 1035):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/AppUp4:CustFacade( 7265): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7265): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7265): begin check event
E/WifiStateMachine( 1035):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
I/AppUp4:CustModeStarterReceiver( 7265): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7265): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
E/WifiStateMachine( 1035):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/AppUp4:CustModeStarterReceiver( 7265): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7265): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7265): handleAsyncCustNotification do not startCustService
E/WifiStateMachine( 1035):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
I/ActivityManager( 1035): Killing 6561:com.lge.email/u0a23 (adj 15): empty #17
,E/WifiStateMachine( 1035):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1035):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1035): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1035): identical MTU - not setting
D/Nat464Xlat( 1035): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1035): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1035):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1035): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524295
W/libprocessgroup( 1035): failed to open /acct/uid_10023/pid_6561/cgroup.procs: No such file or directory
D/LGDMClient( 4300): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4300): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4300): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4300): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,D/LGDMClient( 4300): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/DownloadManager( 3400): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3400): DownloadService onCreate
I/LGDMClient( 4300): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4300): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4300): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3400): in removeSpuriousFiles
,V/DownloadManager( 3400): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3400): created cursor android.database.sqlite.SQLiteCursor@33ab6061 on behalf of 3400
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3400): in trimDatabase
,V/DownloadManager( 3400): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3400): created cursor android.database.sqlite.SQLiteCursor@235bc786 on behalf of 3400
I/ActivityManager( 1035): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7310 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ContextImpl( 4300): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3400): DownloadService onStartCommand
V/DownloadManager( 3400): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3400): created cursor android.database.sqlite.SQLiteCursor@39dca19d on behalf of 3400
E/LGDMClient( 4300): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3400): processing inserted download 1
D/LGDMClient( 4300): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4300): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3400): processing inserted download 4
V/DownloadManager( 3400): processing inserted download 7
D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=650587568, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{1e9614a8 type 2 when 300522 com.google.android.gms} when 300522
V/DownloadManager( 3400): processing inserted download 8
V/DownloadManager( 3400): processing inserted download 9
V/DownloadManager( 3400): processing inserted download 10
V/DownloadManager( 3400): processing inserted download 16
V/DownloadManager( 3400): processing inserted download 17
,V/DownloadManager( 3400): processing inserted download 18
V/DownloadManager( 3400): processing inserted download 21
D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,V/DownloadManager( 3400): DownloadService onDestroy
,W/ResourcesManager( 7310): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7310): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7310): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7310): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 7310): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7310): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7310): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7310): LgDataFeature() Constructor: none
D/LgDataFeature( 7310): LgDataFeature() Constructor Done, null
,D/eas_req ( 7310): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1035): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7337 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7310): JNI_OnLoad()
I/HubEmail( 7310): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7310): registerNatives()
I/HubEmail( 7310): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7310): registerNativeMethods()
I/HubEmail( 7310): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7310): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/art     (  344): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 4.919ms total 29.969ms
I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 297us total 16.989ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 13.678ms
,I/ActivityManager( 1035): Killing 6591:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_10027/pid_6591/cgroup.procs: No such file or directory
,W/Settings( 7310): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7310): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3344): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3344): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3344): networkInfo.isConnected() = false
,I/ActivityManager( 1035): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7366 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  305): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/dhcpcd  ( 7248): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
I/dhcpcd  ( 7248): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7248): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7248): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7248): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7248): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7248): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7248): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7248): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/libc-netbsd(  305): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7337): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7337): Alarm would be updated, because LastCheckTime has been updated.
,I/ActivityManager( 1035): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7401 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 6615:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,D/DhcpStateMachine( 1035): DHCPV4 succeeded on wlan0
,W/libprocessgroup( 1035): failed to open /acct/uid_10061/pid_6615/cgroup.procs: No such file or directory
D/LgDhcpStateMachineHelper( 1035): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1035): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1035): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1035): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1035): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1035): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1035): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1035): RunningState
I/ActivityManager( 1035): Killing 6664:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10080/pid_6664/cgroup.procs: No such file or directory
,I/ActivityManager( 1035): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7429 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 6738:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6738/cgroup.procs: No such file or directory
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7004): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7004): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 7004): BLE supported!!
I/jxcore-log( 7004): 
,I/art     ( 7429): Almond Protected OAT
,D/WeatherApplication( 7429): removeAccount
,D/WeatherApplication( 7429): Account.length = 0
E/WeatherApplication( 7429): OPERATOR:OPEN
D/WeatherAncestor( 7429): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:4:55
D/Weather.Utils( 7429): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7429): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7429): 2 : This is isUpdating : false
D/WeatherAncestor( 7429): connectivity changed - connection : true
,D/WeatherService( 7429): 2 : isServiceAlived():false forecastCache:null
E/WifiStateMachine( 1035):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1035):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
D/ForecastDataCache( 7429): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7429): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7429): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7429): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 7429): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:4:55
,I/ActivityManager( 1035): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7450 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 6685:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10097/pid_6685/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7450): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7450): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7450): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7450): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
V/WifiInternetCheck( 1035): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1035): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1035): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/Tethering( 1035): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5422): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1035): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/WebViewFactory( 7450): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7450): Loading: webviewchromium
I/LibraryLoader( 7450): Time to load native libraries: 5 ms (timestamps 2451-2456)
,I/LibraryLoader( 7450): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7450): Binding Chromium to main looper Looper (main, tid 1) {2267adac}
I/LibraryLoader( 7450): Expected native library version number "",actual native library version number ""
I/chromium( 7450): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7450): Initializing chromium process, renderers=0
W/art     ( 7450): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7450): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7450): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7450): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,V/AudioPolicyService(  309): registerClient() client 0xb558afe0, uid 10093
,W/AudioManagerAndroid( 7450): Requires BLUETOOTH permission
I/Adreno-EGL( 7450): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7450): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7450): Build Date: 12/12/14 금
I/Adreno-EGL( 7450): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7450): Remote Branch: 
I/Adreno-EGL( 7450): Local Patches: 
I/Adreno-EGL( 7450): Reconstruct Branch: 
,I/NSApplication( 7450): Starting up...
,I/ActivityManager( 1035): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7508 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 6760:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6760/cgroup.procs: No such file or directory
,W/ResourcesManager( 7508): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2375): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/ChimeraCfgMgr( 2375): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/ContextImpl( 6497): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/art     ( 2142): Explicit concurrent mark sweep GC freed 36002(2MB) AllocSpace objects, 9(1296KB) LOS objects, 51% free, 30MB/62MB, paused 1.243ms total 87.173ms
I/NetworkStateForAutoUpdateMonitor( 7265): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 7265): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7265): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7265): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7265): onReceive
,D/AppUp4:CustFacade( 7265): Context : android.app.ReceiverRestrictedContext@38feea4d
D/AppUp4:CustFacade( 7265): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7265): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7265): begin check event
I/AppUp4:CustModeStarterReceiver( 7265): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4300): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4300): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4300): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/art     ( 1035): Explicit concurrent mark sweep GC freed 82711(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 2.404ms total 142.090ms
,W/ContextImpl( 4300): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4300): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4300): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4300): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/DownloadManager( 3400): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 4300): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/GLSActivity( 2142): [ac] getting account id
V/DownloadManager( 3400): DownloadService onCreate
,I/DownloadManager( 3400): in removeSpuriousFiles
V/DownloadManager( 3400): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3400): created cursor android.database.sqlite.SQLiteCursor@7ecd1e3 on behalf of 3400
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
,I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/GLSUser ( 2142): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
I/DownloadManager( 3400): in trimDatabase
W/ContextImpl( 4300): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3400): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
E/LGDMClient( 4300): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3400): created cursor android.database.sqlite.SQLiteCursor@21e6ba99 on behalf of 3400
D/LGDMClient( 4300): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3400): DownloadService onStartCommand
V/DownloadManager( 3400): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4300): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/DownloadManager( 3400): created cursor android.database.sqlite.SQLiteCursor@e90a93f on behalf of 3400
V/DownloadManager( 3400): processing inserted download 1
V/DownloadManager( 3400): processing inserted download 4
V/DownloadManager( 3400): processing inserted download 7
I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3400): processing inserted download 8
V/DownloadManager( 3400): processing inserted download 9
W/Settings( 7310): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3400): processing inserted download 10
,W/Settings( 7310): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3400): processing inserted download 16
V/DownloadManager( 3400): processing inserted download 17
I/LgeMiscReceiver( 3344): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3344): action = android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3400): processing inserted download 18
I/LgeMiscReceiver( 3344): networkInfo.isConnected() = false
V/DownloadManager( 3400): processing inserted download 21
D/WeatherAncestor( 7429): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:4:57
V/DownloadManager( 3400): DownloadService onDestroy
D/Weather.Utils( 7429): 2 : the weather widgets(using time tick) are gone.
,D/Weather.Utils( 7429): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 7429): 2 : This is isUpdating : false
D/WeatherAncestor( 7429): connectivity changed - connection : true
D/WeatherService( 7429): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2c168213
D/ForecastDataCache( 7429): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7429): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7429): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7429): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7429): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:4:57
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2375): [AccountUtils] Account not ready
W/Kids    ( 2375): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2375): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2375): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2375): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2375): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2375): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2375): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2375): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2375): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2375): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2375): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2375): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LgeQuickCoverNLService( 1419): onNotificationPosted
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
V/FormManager( 7337): There are no updated forms. The schedule will be deleted.
,W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/FormManager( 7337): Alarm would be updated, because LastCheckTime has been updated.
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/UEI.SmartControl( 6703): Internal timer expired: 4
D/UEI.SmartControl( 6703): unbind internal service
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2adf6755 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2375): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=650587568 [*alarm*], flags=0x0
D/PostponalbeReceiver( 6497): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = mtalk.google.com, class = 1, type = 1
W/ContextImpl( 6497): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7265): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7265): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7265): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7265): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7265): onReceive
I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AppUp4:CustFacade( 7265): Context : android.app.ReceiverRestrictedContext@38feea4d
D/AppUp4:CustFacade( 7265): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7265): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7265): begin check event
,I/AppUp4:CustModeStarterReceiver( 7265): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4300): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4300): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/libc-netbsd(  305): res_queryN name = mtalk.google.com succeed
W/ContextImpl( 4300): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4300): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3400): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4300): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,V/DownloadManager( 3400): DownloadService onCreate
I/DownloadManager( 3400): in removeSpuriousFiles
V/DownloadManager( 3400): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/LGDMClient( 4300): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3400): created cursor android.database.sqlite.SQLiteCursor@2adf6755 on behalf of 3400
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3400): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3400): in trimDatabase
V/DownloadManager( 3400): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3400): created cursor android.database.sqlite.SQLiteCursor@1359156a on behalf of 3400
D/LGDMClient( 4300): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 4300): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/LGDMClient( 4300): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
E/LGDMClient( 4300): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4300): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4300): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = www.google.com, class = 1, type = 1
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/Kids    ( 2375): [AccountUtils] Account not ready
W/Kids    ( 2375): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2375): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2375): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2375): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2375): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2375): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2375): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2375): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2375): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2375): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2375): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2375): 	at java.lang.Thread.run(Thread.java:818)
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
,E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/Settings( 7310): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7310): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/LgeMiscReceiver( 3344): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3344): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3344): networkInfo.isConnected() = true
D/PhoneState( 3344): setPdpRejectCasuse : false
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2adf6755 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,V/DownloadManager( 3400): DownloadService onStartCommand
V/DownloadManager( 3400): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3400): created cursor android.database.sqlite.SQLiteCursor@357c23d1 on behalf of 3400
D/libc-netbsd(  305): res_queryN name = www.google.com succeed
D/WeatherAncestor( 7429): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:4:57
V/DownloadManager( 3400): processing inserted download 1
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
V/DownloadManager( 3400): processing inserted download 4
D/libc-netbsd(  305): res_queryN name = clients3.google.com, class = 1, type = 1
D/Weather.Utils( 7429): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7429): 2 : All the weather widget is gone.
D/libc-netbsd(  305): res_queryN name = clients3.google.com succeed
D/UpdateThreadPoolManager( 7429): 2 : This is isUpdating : false
D/WeatherAncestor( 7429): connectivity changed - connection : true
D/WeatherService( 7429): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2c168213
D/ForecastDataCache( 7429): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7429): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7429): 2 : Cache is up-to-date, count: 0
V/DownloadManager( 3400): processing inserted download 7
D/Weather_cast( 7429): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7429): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:4:57
V/DownloadManager( 3400): processing inserted download 8
V/DownloadManager( 3400): processing inserted download 9
,V/DownloadManager( 3400): processing inserted download 10
V/DownloadManager( 3400): processing inserted download 16
V/DownloadManager( 3400): processing inserted download 17
V/DownloadManager( 3400): processing inserted download 18
V/DownloadManager( 3400): processing inserted download 21
D/serial_port( 6703): close(fd = 24)
V/FormManager( 7337): There are no updated forms. The schedule will be deleted.
V/DownloadManager( 3400): DownloadService onDestroy
,V/FormManager( 7337): Alarm would be updated, because LastCheckTime has been updated.
I/UEI.SmartControl( 6703): Serial port is closed.
D/ChimeraCfgMgr( 2375): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/WifiInternetCheck( 1035): isHttpConnectionAvailable - We got a valid response : 204
,I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
,I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2375): [AccountUtils] Account not ready
W/Kids    ( 2375): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2375): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2375): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2375): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2375): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2375): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2375): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2375): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2375): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2375): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2375): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2375): 	at java.lang.Thread.run(Thread.java:818)
,D/LgeQuickCoverNLService( 1419): onNotificationPosted
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
,E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2adf6755 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/GCM     ( 2142): Connected
,D/GCM     ( 2142): Message class com.google.f.a.a.p
V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{3db4fa12 type 2 when 304616 android} when 304616
,V/QRemote ( 7164): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7164): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5233
,I/BooksSync( 6861): Starting books sync
,D/BooksSync( 6861): started syncMyEbooks
,V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
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
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2142): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2142): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2142): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2142): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6861): Authentication error
E/BooksAccountManager( 6861): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6861): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6861): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6861): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2adf6755 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  305): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  305): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6861): Error response from books API: {
W/ApiaryClient( 6861):  "error": {
W/ApiaryClient( 6861):   "errors": [
W/ApiaryClient( 6861):    {
W/ApiaryClient( 6861):     "domain": "global",
W/ApiaryClient( 6861):     "reason": "required",
W/ApiaryClient( 6861):     "message": "Login Required",
W/ApiaryClient( 6861):     "locationType": "header",
W/ApiaryClient( 6861):     "location": "Authorization"
W/ApiaryClient( 6861):    }
W/ApiaryClient( 6861):   ],
W/ApiaryClient( 6861):   "code": 401,
W/ApiaryClient( 6861):   "message": "Login Required"
W/ApiaryClient( 6861):  }
W/ApiaryClient( 6861): }
,W/ApiaryClient( 6861): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6861): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3923997831007830273&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6861): Headers:
W/ApiaryClient( 6861): accept-encoding: [gzip]
W/ApiaryClient( 6861): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6861): gdata-version: 2
I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2142): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2142): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2142): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2142): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6861): Authentication error
E/BooksAccountManager( 6861): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6861): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6861): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6861): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2adf6755 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6861): Error response from books API: {
W/ApiaryClient( 6861):  "error": {
W/ApiaryClient( 6861):   "errors": [
W/ApiaryClient( 6861):    {
W/ApiaryClient( 6861):     "domain": "global",
W/ApiaryClient( 6861):     "reason": "required",
W/ApiaryClient( 6861):     "message": "Login Required",
W/ApiaryClient( 6861):     "locationType": "header",
W/ApiaryClient( 6861):     "location": "Authorization"
W/ApiaryClient( 6861):    }
W/ApiaryClient( 6861):   ],
W/ApiaryClient( 6861):   "code": 401,
W/ApiaryClient( 6861):   "message": "Login Required"
W/ApiaryClient( 6861):  }
W/ApiaryClient( 6861): }
W/ApiaryClient( 6861): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6861): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3923997831007830273&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6861): Headers:
W/ApiaryClient( 6861): accept-encoding: [gzip]
W/ApiaryClient( 6861): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6861): gdata-version: 2
,I/GAV4    ( 7450): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
W/GLSActivity( 2142): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2142): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2142): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2142): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6861): Authentication error
E/BooksAccountManager( 6861): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6861): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6861): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6861): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2adf6755 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6861): Error response from books API: {
W/ApiaryClient( 6861):  "error": {
W/ApiaryClient( 6861):   "errors": [
W/ApiaryClient( 6861):    {
W/ApiaryClient( 6861):     "domain": "global",
W/ApiaryClient( 6861):     "reason": "required",
W/ApiaryClient( 6861):     "message": "Login Required",
W/ApiaryClient( 6861):     "locationType": "header",
W/ApiaryClient( 6861):     "location": "Authorization"
W/ApiaryClient( 6861):    }
W/ApiaryClient( 6861):   ],
W/ApiaryClient( 6861):   "code": 401,
W/ApiaryClient( 6861):   "message": "Login Required"
W/ApiaryClient( 6861):  }
W/ApiaryClient( 6861): }
,W/ApiaryClient( 6861): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6861): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3923997831007830273&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6861): Headers:
W/ApiaryClient( 6861): accept-encoding: [gzip]
W/ApiaryClient( 6861): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6861): gdata-version: 2
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 307719583011; DSPS: 10224096; Offset : -4310859460
,E/BooksSync( 6861): Soft error: 
E/BooksSync( 6861): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6861): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3923997831007830273&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6861): Headers:
E/BooksSync( 6861): accept-encoding: [gzip]
E/BooksSync( 6861): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6861): gdata-version: 2
E/BooksSync( 6861): 
E/BooksSync( 6861): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6861): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6861): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6861): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6861): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6861): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6861): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6861): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6861): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6861): {
E/BooksSync( 6861):  "error": {
E/BooksSync( 6861):   "errors": [
E/BooksSync( 6861):    {
E/BooksSync( 6861):     "domain": "global",
E/BooksSync( 6861):     "reason": "required",
E/BooksSync( 6861):     "message": "Login Required",
E/BooksSync( 6861):     "locationType": "header",
E/BooksSync( 6861):     "location": "Authorization"
E/BooksSync( 6861):    }
E/BooksSync( 6861):   ],
E/BooksSync( 6861):   "code": 401,
E/BooksSync( 6861):   "message": "Login Required"
E/BooksSync( 6861):  }
E/BooksSync( 6861): }
E/BooksSync( 6861): 
E/BooksSync( 6861): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6861): 	... 8 more
,E/BooksSync( 6861): Sync error
E/BooksSync( 6861): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6861): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-3923997831007830273&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6861): Headers:
E/BooksSync( 6861): accept-encoding: [gzip]
E/BooksSync( 6861): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6861): gdata-version: 2
E/BooksSync( 6861): 
E/BooksSync( 6861): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6861): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6861): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6861): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6861): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6861): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6861): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6861): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6861): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6861): {
E/BooksSync( 6861):  "error": {
E/BooksSync( 6861):   "errors": [
E/BooksSync( 6861):    {
E/BooksSync( 6861):     "domain": "global",
E/BooksSync( 6861):     "reason": "required",
E/BooksSync( 6861):     "message": "Login Required",
E/BooksSync( 6861):     "locationType": "header",
E/BooksSync( 6861):     "location": "Authorization"
E/BooksSync( 6861):    }
E/BooksSync( 6861):   ],
E/BooksSync( 6861):   "code": 401,
E/BooksSync( 6861):   "message": "Login Required"
E/BooksSync( 6861):  }
E/BooksSync( 6861): }
E/BooksSync( 6861): 
E/BooksSync( 6861): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6861): 	... 8 more
I/BooksSync( 6861): Finished books sync
I/ActivityManager( 1035): Killing 6787:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,D/SyncManager( 1035): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 304616, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1035): failed to open /acct/uid_10005/pid_6787/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 327721266337; DSPS: 10879511; Offset : -4310854626
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=650587568, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{14a5e835 type 2 when 334669 android} when 334669
D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=650587568 [*alarm*], flags=0x0
,E/WifiStateMachine( 1035):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1035):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1035):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1035):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1035):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1035):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 347722870079; DSPS: 11534924; Offset : -4310868341
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=650587568, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,D/[Concierge]Service( 2621): onStartCommand(). Type : 9
I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=650587568 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 367724720436; DSPS: 12190345; Offset : -4310879609
,I/[SystemUI]LGPowerUI( 1466): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1466): On Skip Timer : true
,W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1035): battery changed pluggedType: 2
D/HeadsetStateMachine( 3799): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1466): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1466): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1970): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1970): Battery Level Remaining: 100%
D/LEDHandler( 1970): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1466): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4300): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4300): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2142): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2142): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2142): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2142): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6178): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6178): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6178): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6178): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6178): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6178): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6178): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 6178): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  305): res_queryN name = play.googleapis.com succeed
,I/art     ( 1035): Explicit concurrent mark sweep GC freed 26391(1226KB) AllocSpace objects, 8(1024KB) LOS objects, 33% free, 44MB/66MB, paused 4.180ms total 174.318ms
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
,D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
,D/QuickCircle( 1419): onNotificationPosted() : isPosted true
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
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2adf6755 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 387726321626; DSPS: 12845757; Offset : -4310865308
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 407728101775; DSPS: 13501175; Offset : -4310855177
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 427729676611; DSPS: 14156587; Offset : -4310867203
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 447731819312; DSPS: 14812017; Offset : -4310860785
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 467733328002; DSPS: 15467427; Offset : -4310877974
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 487734923672; DSPS: 16122839; Offset : -4310869270
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 507736461633; DSPS: 16778249; Offset : -4310857111
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 527738239646; DSPS: 17433668; Offset : -4310879634
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 547740192243; DSPS: 18089092; Offset : -4310880214
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 567742024370; DSPS: 18744512; Offset : -4310879090
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=650587568, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{2525360f type 2 when 567781 android} when 567781
D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=650587568 [*alarm*], flags=0x0
,I/BooksSync( 6861): Starting books sync
,D/BooksSync( 6861): started syncMyEbooks
,V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
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
,E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2142): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2142): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2142): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2142): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6861): Authentication error
E/BooksAccountManager( 6861): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6861): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6861): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2adf6755 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/HttpHelper( 6861): null auth token
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  305): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  305): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6861): Error response from books API: {
W/ApiaryClient( 6861):  "error": {
W/ApiaryClient( 6861):   "errors": [
W/ApiaryClient( 6861):    {
W/ApiaryClient( 6861):     "domain": "global",
W/ApiaryClient( 6861):     "reason": "required",
W/ApiaryClient( 6861):     "message": "Login Required",
W/ApiaryClient( 6861):     "locationType": "header",
W/ApiaryClient( 6861):     "location": "Authorization"
W/ApiaryClient( 6861):    }
W/ApiaryClient( 6861):   ],
W/ApiaryClient( 6861):   "code": 401,
W/ApiaryClient( 6861):   "message": "Login Required"
W/ApiaryClient( 6861):  }
W/ApiaryClient( 6861): }
,W/ApiaryClient( 6861): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6861): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2550710458603101830&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6861): Headers:
W/ApiaryClient( 6861): accept-encoding: [gzip]
W/ApiaryClient( 6861): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6861): gdata-version: 2
V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2142): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2142): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2142): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2142): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6861): Authentication error
E/BooksAccountManager( 6861): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6861): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6861): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6861): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2adf6755 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6861): Error response from books API: {
W/ApiaryClient( 6861):  "error": {
W/ApiaryClient( 6861):   "errors": [
W/ApiaryClient( 6861):    {
W/ApiaryClient( 6861):     "domain": "global",
W/ApiaryClient( 6861):     "reason": "required",
W/ApiaryClient( 6861):     "message": "Login Required",
W/ApiaryClient( 6861):     "locationType": "header",
W/ApiaryClient( 6861):     "location": "Authorization"
W/ApiaryClient( 6861):    }
W/ApiaryClient( 6861):   ],
W/ApiaryClient( 6861):   "code": 401,
W/ApiaryClient( 6861):   "message": "Login Required"
W/ApiaryClient( 6861):  }
W/ApiaryClient( 6861): },
,W/ApiaryClient( 6861): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6861): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2550710458603101830&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6861): Headers:
W/ApiaryClient( 6861): accept-encoding: [gzip]
W/ApiaryClient( 6861): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6861): gdata-version: 2
V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
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
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2142): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2142): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2142): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2142): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6861): Authentication error
E/BooksAccountManager( 6861): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6861): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6861): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6861): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2adf6755 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6861): Error response from books API: {
W/ApiaryClient( 6861):  "error": {
W/ApiaryClient( 6861):   "errors": [
W/ApiaryClient( 6861):    {
W/ApiaryClient( 6861):     "domain": "global",
W/ApiaryClient( 6861):     "reason": "required",
W/ApiaryClient( 6861):     "message": "Login Required",
W/ApiaryClient( 6861):     "locationType": "header",
W/ApiaryClient( 6861):     "location": "Authorization"
W/ApiaryClient( 6861):    }
W/ApiaryClient( 6861):   ],
W/ApiaryClient( 6861):   "code": 401,
W/ApiaryClient( 6861):   "message": "Login Required"
W/ApiaryClient( 6861):  }
W/ApiaryClient( 6861): }
W/ApiaryClient( 6861): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6861): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2550710458603101830&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6861): Headers:
W/ApiaryClient( 6861): accept-encoding: [gzip]
W/ApiaryClient( 6861): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6861): gdata-version: 2
,E/BooksSync( 6861): Soft error: 
E/BooksSync( 6861): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6861): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2550710458603101830&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6861): Headers:
E/BooksSync( 6861): accept-encoding: [gzip]
E/BooksSync( 6861): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6861): gdata-version: 2
E/BooksSync( 6861): 
E/BooksSync( 6861): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6861): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6861): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6861): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6861): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6861): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6861): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6861): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6861): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6861): {
E/BooksSync( 6861):  "error": {
E/BooksSync( 6861):   "errors": [
E/BooksSync( 6861):    {
E/BooksSync( 6861):     "domain": "global",
E/BooksSync( 6861):     "reason": "required",
E/BooksSync( 6861):     "message": "Login Required",
E/BooksSync( 6861):     "locationType": "header",
E/BooksSync( 6861):     "location": "Authorization"
E/BooksSync( 6861):    }
E/BooksSync( 6861):   ],
E/BooksSync( 6861):   "code": 401,
E/BooksSync( 6861):   "message": "Login Required"
E/BooksSync( 6861):  }
E/BooksSync( 6861): }
E/BooksSync( 6861): 
E/BooksSync( 6861): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6861): 	... 8 more
E/BooksSync( 6861): Sync error
E/BooksSync( 6861): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6861): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=2550710458603101830&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6861): Headers:
E/BooksSync( 6861): accept-encoding: [gzip]
E/BooksSync( 6861): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6861): gdata-version: 2
E/BooksSync( 6861): 
E/BooksSync( 6861): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6861): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6861): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6861): 	at com.google.android.apps.books.data.NetworkTaskQ,ueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6861): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6861): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6861): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6861): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6861): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6861): {
E/BooksSync( 6861):  "error": {
E/BooksSync( 6861):   "errors": [
E/BooksSync( 6861):    {
E/BooksSync( 6861):     "domain": "global",
E/BooksSync( 6861):     "reason": "required",
E/BooksSync( 6861):     "message": "Login Required",
E/BooksSync( 6861):     "locationType": "header",
E/BooksSync( 6861):     "location": "Authorization"
E/BooksSync( 6861):    }
E/BooksSync( 6861):   ],
E/BooksSync( 6861):   "code": 401,
E/BooksSync( 6861):   "message": "Login Required"
E/BooksSync( 6861):  }
E/BooksSync( 6861): }
E/BooksSync( 6861): 
E/BooksSync( 6861): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6861): 	... 8 more
I/BooksSync( 6861): Finished books sync
,D/SyncManager( 1035): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 567781, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 587743578112; DSPS: 19399923; Offset : -4310881770
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{115ced01 type 2 when 597959 android} when 597959
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 607745162220; DSPS: 20055335; Offset : -4310884628
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 627746706951; DSPS: 20710745; Offset : -4310865724
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 647748339496; DSPS: 21366158; Offset : -4310850611
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 667749922978; DSPS: 22021570; Offset : -4310854069
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 687752070106; DSPS: 22677001; Offset : -4310873559
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 707753588484; DSPS: 23332411; Offset : -4310881216
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 727755165663; DSPS: 23987822; Offset : -4310860408
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 747756688468; DSPS: 24643232; Offset : -4310863351
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 767758430960; DSPS: 25298649; Offset : -4310860517
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 787761005484; DSPS: 25954094; Offset : -4310880065
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 807762863446; DSPS: 26609514; Offset : -4310852924
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 827764655886; DSPS: 27264933; Offset : -4310861073
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 847766412493; DSPS: 27920351; Offset : -4310874459
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 867768029412; DSPS: 28575764; Offset : -4310875051
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 887769536435; DSPS: 29231173; Offset : -4310863284
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=650587568, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{48d67a6 type 0 when 1450739678920 com.google.android.gms} when 1450739678920
,D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=650587568 [*alarm*], flags=0x0
,I/EventLogService( 2375): Aggregate from 1450737878832 (log), 1450737878832 (data)
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=650587568, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,I/ActivityManager( 1035): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7750 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7750): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7750): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@9820b76
D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=650587568 [*alarm*], flags=0x0
I/ActivityManager( 1035): Killing 6178:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1035): failed to open /acct/uid_10044/pid_6178/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 907771381064; DSPS: 29886594; Offset : -4310880410
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 927773177098; DSPS: 30542012; Offset : -4310854291
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{39e8f983 type 2 when 942695 com.android.bluetooth} when 942695
,W/bt-smp  ( 3799): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3799): Plain text(LSB ~ MSB) = 60 77 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3799): Encrypted text(LSB ~ MSB) = 6b 64 2e 40 dd 1d 6a d4 b6 08 01 0c 07 1e 81 d0 
W/bt-btm  ( 3799): Stopping oneshot timer
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 947781427715; DSPS: 31197643; Offset : -4310872011
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
,I/[SystemUI]DateView( 1466): called onTimeUpdated()
,I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 967783088697; DSPS: 31853057; Offset : -4310861009
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 987784620356; DSPS: 32508467; Offset : -4310855125
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1007786109724; DSPS: 33163876; Offset : -4310861171
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1027787676695; DSPS: 33819288; Offset : -4310881062
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1047789549395; DSPS: 34474709; Offset : -4310869752
,I/[SystemUI]LGPowerUI( 1466): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1466): On Skip Timer : true
,D/LEDHandler( 1970): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1970): Battery Level Remaining: 100%
D/LEDHandler( 1970): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1466): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1466): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1466): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController( 1035): battery changed pluggedType: 2
D/HeadsetStateMachine( 3799): Disconnected process message: 10, size: 0
,D/LGDMClient( 4300): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4300): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1067791706836; DSPS: 35130140; Offset : -4310879163
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
,I/[SystemUI]DateView( 1466): called onTimeUpdated()
,I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1087793547558; DSPS: 35785560; Offset : -4310869756
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=650587568, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{228a5700 type 2 when 1090190 android} when 1090190
D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=650587568 [*alarm*], flags=0x0
,I/BooksSync( 6861): Starting books sync
D/BooksSync( 6861): started syncMyEbooks
,V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1419): onNotificationPosted
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
W/GLSActivity( 2142): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2142): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2142): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2142): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
E/BooksAccountManager( 6861): Authentication error
E/BooksAccountManager( 6861): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6861): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6861): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6861): null auth token
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/libc-netbsd(  305): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  305): res_queryN name = www.googleapis.com, class = 1, type = 1
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2adf6755 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  305): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6861): Error response from books API: {
W/ApiaryClient( 6861):  "error": {
W/ApiaryClient( 6861):   "errors": [
W/ApiaryClient( 6861):    {
W/ApiaryClient( 6861):     "domain": "global",
W/ApiaryClient( 6861):     "reason": "required",
W/ApiaryClient( 6861):     "message": "Login Required",
W/ApiaryClient( 6861):     "locationType": "header",
W/ApiaryClient( 6861):     "location": "Authorization"
W/ApiaryClient( 6861):    }
W/ApiaryClient( 6861):   ],
W/ApiaryClient( 6861):   "code": 401,
W/ApiaryClient( 6861):   "message": "Login Required"
W/ApiaryClient( 6861):  }
W/ApiaryClient( 6861): }
,W/ApiaryClient( 6861): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6861): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8683601183686967775&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6861): Headers:
W/ApiaryClient( 6861): accept-encoding: [gzip]
W/ApiaryClient( 6861): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6861): gdata-version: 2
V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
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
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2142): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2142): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2142): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2142): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6861): Authentication error
E/BooksAccountManager( 6861): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6861): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6861): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6861): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2adf6755 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6861): Error response from books API: {
W/ApiaryClient( 6861):  "error": {
W/ApiaryClient( 6861):   "errors": [
W/ApiaryClient( 6861):    {
W/ApiaryClient( 6861):     "domain": "global",
W/ApiaryClient( 6861):     "reason": "required",
W/ApiaryClient( 6861):     "message": "Login Required",
W/ApiaryClient( 6861):     "locationType": "header",
W/ApiaryClient( 6861):     "location": "Authorization"
W/ApiaryClient( 6861):    }
W/ApiaryClient( 6861):   ],
W/ApiaryClient( 6861):   "code": 401,
W/ApiaryClient( 6861):   "message": "Login Required"
W/ApiaryClient( 6861):  }
W/ApiaryClient( 6861): }
,W/ApiaryClient( 6861): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6861): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8683601183686967775&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6861): Headers:
W/ApiaryClient( 6861): accept-encoding: [gzip]
W/ApiaryClient( 6861): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6861): gdata-version: 2
V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1035): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1035): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1035): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1035): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1035): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): post do just update job
,D/LgeQuickCoverNotificationData( 1419): showAll3
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
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
,W/GLSActivity( 2142): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2142): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2142): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2142): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2142): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6861): Authentication error
E/BooksAccountManager( 6861): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6861): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6861): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6861): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6861): null auth token
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{2adf6755 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6861): Error response from books API: {
W/ApiaryClient( 6861):  "error": {
W/ApiaryClient( 6861):   "errors": [
W/ApiaryClient( 6861):    {
W/ApiaryClient( 6861):     "domain": "global",
W/ApiaryClient( 6861):     "reason": "required",
W/ApiaryClient( 6861):     "message": "Login Required",
W/ApiaryClient( 6861):     "locationType": "header",
W/ApiaryClient( 6861):     "location": "Authorization"
W/ApiaryClient( 6861):    }
W/ApiaryClient( 6861):   ],
W/ApiaryClient( 6861):   "code": 401,
W/ApiaryClient( 6861):   "message": "Login Required"
W/ApiaryClient( 6861):  }
W/ApiaryClient( 6861): }
,W/ApiaryClient( 6861): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6861): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8683601183686967775&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6861): Headers:
W/ApiaryClient( 6861): accept-encoding: [gzip]
W/ApiaryClient( 6861): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6861): gdata-version: 2
E/BooksSync( 6861): Soft error: 
E/BooksSync( 6861): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6861): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8683601183686967775&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6861): Headers:
E/BooksSync( 6861): accept-encoding: [gzip]
E/BooksSync( 6861): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6861): gdata-version: 2
E/BooksSync( 6861): 
E/BooksSync( 6861): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6861): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6861): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6861): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6861): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6861): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6861): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6861): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6861): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6861): {
E/BooksSync( 6861):  "error": {
E/BooksSync( 6861):   "errors": [
E/BooksSync( 6861):    {
E/BooksSync( 6861):     "domain": "global",
E/BooksSync( 6861):     "reason": "required",
E/BooksSync( 6861):     "message": "Login Required",
E/BooksSync( 6861):     "locationType": "header",
E/BooksSync( 6861):     "location": "Authorization"
E/BooksSync( 6861):    }
E/BooksSync( 6861):   ],
E/BooksSync( 6861):   "code": 401,
E/BooksSync( 6861):   "message": "Login Required"
E/BooksSync( 6861):  }
E/BooksSync( 6861): }
E/BooksSync( 6861): 
E/BooksSync( 6861): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6861): 	... 8 more
E/BooksSync( 6861): Sync error
E/BooksSync( 6861): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6861): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-8683601183686967775&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6861): Headers:
E/BooksSync( 6861): accept-encoding: [gzip]
E/BooksSync( 6861): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6861): g,data-version: 2
E/BooksSync( 6861): 
E/BooksSync( 6861): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6861): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6861): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6861): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6861): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6861): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6861): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6861): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6861): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6861): {
E/BooksSync( 6861):  "error": {
E/BooksSync( 6861):   "errors": [
E/BooksSync( 6861):    {
E/BooksSync( 6861):     "domain": "global",
E/BooksSync( 6861):     "reason": "required",
E/BooksSync( 6861):     "message": "Login Required",
E/BooksSync( 6861):     "locationType": "header",
E/BooksSync( 6861):     "location": "Authorization"
E/BooksSync( 6861):    }
E/BooksSync( 6861):   ],
E/BooksSync( 6861):   "code": 401,
E/BooksSync( 6861):   "message": "Login Required"
E/BooksSync( 6861):  }
E/BooksSync( 6861): }
E/BooksSync( 6861): 
E/BooksSync( 6861): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6861): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6861): 	... 8 more
I/BooksSync( 6861): Finished books sync
,D/SyncManager( 1035): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1090190, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1107795414320; DSPS: 36440981; Offset : -4310864358
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{2f94942 type 2 when 1121008 android} when 1121008
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1127797246343; DSPS: 37096401; Offset : -4310863389
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1147798996024; DSPS: 37751818; Offset : -4310853236
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1167801138204; DSPS: 38407249; Offset : -4310877726
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1187802895020; DSPS: 39062666; Offset : -4310860438
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1207804440792; DSPS: 39718077; Offset : -4310871036
,D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=650587568, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{23827d53 type 2 when 1203754 com.google.android.gms} when 1203754
,D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,D/GCM     ( 2142): Message class com.google.f.a.a.i
,D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=650587568 [*alarm*], flags=0x0
,I/UsageStatsService( 1035): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1227806042348; DSPS: 40373489; Offset : -4310856395
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1247807517965; DSPS: 41028898; Offset : -4310876217
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1267809132437; DSPS: 41684311; Offset : -4310879099
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1287811614096; DSPS: 42339752; Offset : -4310869364
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1307813285390; DSPS: 42995167; Offset : -4310876536
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1327814855173; DSPS: 43650578; Offset : -4310863228
,I/[SystemUI]LGPowerUI( 1466): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1466): On Skip Timer : true
,D/LEDHandler( 1970): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1970): Battery Level Remaining: 100%
D/LEDHandler( 1970): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
,D/WifiController( 1035): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1466): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1466): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1466): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3799): Disconnected process message: 10, size: 0
D/LGDMClient( 4300): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4300): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1347816386572; DSPS: 44305988; Offset : -4310857735
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1367817872086; DSPS: 44961397; Offset : -4310867581
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1387819422338; DSPS: 45616808; Offset : -4310873648
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1407821865144; DSPS: 46272248; Offset : -4310872326
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1427823544407; DSPS: 46927663; Offset : -4310871504
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1447825081535; DSPS: 47583073; Offset : -4310860177
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1467826567985; DSPS: 48238482; Offset : -4310869088
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1487828345269; DSPS: 48893900; Offset : -4310861928
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated(),
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1507829894741; DSPS: 49549311; Offset : -4310868748
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1527832059838; DSPS: 50204742; Offset : -4310870425
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1547833867016; DSPS: 50860161; Offset : -4310863889
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1567835446958; DSPS: 51515573; Offset : -4310870704
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1587836963825; DSPS: 52170983; Offset : -4310879691
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1607838705328; DSPS: 52826400; Offset : -4310877767
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1627840900841; DSPS: 53481832; Offset : -4310879442
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1647842687032; DSPS: 54137250; Offset : -4310863375
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1667843749263; DSPS: 54792645; Offset : -4310869362
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1687844880506; DSPS: 55448042; Offset : -4310867349
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1707846417580; DSPS: 56103452; Offset : -4310855971
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1727847913199; DSPS: 56758861; Offset : -4310855609
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1747849463347; DSPS: 57414272; Offset : -4310862066
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1767851698445; DSPS: 58069706; Offset : -4310885191
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1787853542291; DSPS: 58725126; Offset : -4310872217
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
,I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/PowerManagerServiceEx( 1035): acquireWakeLockInternal: lock=650587568, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1035
,D/[Concierge]Service( 2621): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7750): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7750): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@9820b76
D/PowerManagerServiceEx( 1035): releaseWakeLockInternal: lock=650587568 [*alarm*], flags=0x0
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1807854500564; DSPS: 59380517; Offset : -4310859702
,I/[SystemUI]LGPowerUI( 1466): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1466): On Skip Timer : true
,D/LEDHandler( 1970): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1970): Battery Level Remaining: 100%
D/LEDHandler( 1970): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1466): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1466): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1466): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1035): battery changed pluggedType: 2
W/Settings( 1035): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1035): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3799): Disconnected process message: 10, size: 0
D/LGDMClient( 4300): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4300): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1827856126286; DSPS: 60035931; Offset : -4310882321
,V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{184b6b89 type 2 when 1842739 com.android.bluetooth} when 1842739
,W/bt-smp  ( 3799): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3799): Plain text(LSB ~ MSB) = c0 d9 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3799): Encrypted text(LSB ~ MSB) = 1b fe 55 a1 5e cf d1 83 c0 d1 7a 97 3f 9a 87 29 
W/bt-btm  ( 3799): Stopping oneshot timer
I/ProcessStatsService( 1035): Prepared write state in 11ms
,I/ProcessStatsService( 1035): Prepared write state in 13ms
I/ProcessStatsService( 1035): Pruning old procstats: /data/system/procstats/state-2015-12-21-01-32-17.bin
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1847857827944; DSPS: 60691346; Offset : -4310859103
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1867859419760; DSPS: 61346758; Offset : -4310854305
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1887861682097; DSPS: 62002193; Offset : -4310880630
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1907863184172; DSPS: 62657602; Offset : -4310874047
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1927865033122; DSPS: 63313022; Offset : -4310856125
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1947866525146; DSPS: 63968431; Offset : -4310859490
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1967868198782; DSPS: 64623846; Offset : -4310864319
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 1987869757734; DSPS: 65279257; Offset : -4310861868
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2007872207728; DSPS: 65934697; Offset : -4310853072
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2027873784855; DSPS: 66590109; Offset : -4310862807
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2047875378597; DSPS: 67245521; Offset : -4310856162
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2067877101298; DSPS: 67900938; Offset : -4310872963
,D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2087878846185; DSPS: 68556355; Offset : -4310867420
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
,I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/sensors_hal_Time( 1035): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1035): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1035): tsOffsetIs: Apps: 2107881533209; DSPS: 69211803; Offset : -4310866282
,TIME-OUT KILL (timeout was 1800000ms),I/ActivityManager( 1035): Killing 6497:com.wsandroid.suite.lge/1000 (adj 15): empty for 1813s
I/ActivityManager( 1035): Killing 7337:com.lge.formmanager/u0a26 (adj 15): empty for 1813s
I/ActivityManager( 1035): Killing 7310:com.lge.email/u0a23 (adj 15): empty for 1813s
I/ActivityManager( 1035): Killing 7265:com.lge.appbox.client/u0a11 (adj 15): empty for 1813s
I/ActivityManager( 1035): Killing 7105:com.android.settings/1000 (adj 15): empty for 1817s
I/ActivityManager( 1035): Killing 7140:com.lge.sync/1000 (adj 15): empty for 1817s
W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_6497/cgroup.procs: No such file or directory
W/libprocessgroup( 1035): failed to open /acct/uid_10026/pid_7337/cgroup.procs: No such file or directory
W/libprocessgroup( 1035): failed to open /acct/uid_10023/pid_7310/cgroup.procs: No such file or directory
W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_7105/cgroup.procs: No such file or directory
W/libprocessgroup( 1035): failed to open /acct/uid_1000/pid_7140/cgroup.procs: No such file or directory
W/libprocessgroup( 1035): failed to open /acct/uid_10011/pid_7265/cgroup.procs: No such file or directory
V/AlarmManager( 1035): RTC_WAKEUP set : Alarm{82d9baf type 0 when 1450740493385 com.google.android.gms} when 1450740493385
V/AlarmManager( 1035): ELAPSED_WAKEUP set : Alarm{3934cbbc type 2 when 2112495 com.google.android.gms} when 2112495
D/[Concierge]Service( 2621): onStartCommand(). Type : 9
I/Icing   ( 2375): Performing maintenance.
D/LocationManagerService( 1035): getAllProviders()=[passive, gps, network]
I/GLSUser ( 2142): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 2142): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2142): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2142): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2142): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
I/Icing   ( 2375): updateResources: need to parse f{com.google.android.gms}
I/art     ( 1035): Explicit concurrent mark sweep GC freed 43297(2MB) AllocSpace objects, 18(1166KB) LOS objects, 33% free, 44MB/66MB, paused 1.498ms total 145.325ms
I/Icing   ( 2375): Performing maintenance usage 2083701 budget 12001619386 free 99.983% index free 99.908% purge? false target 1584915234
I/art     ( 2142): Explicit concurrent mark sweep GC freed 39239(2MB) AllocSpace objects, 29(4MB) LOS objects, 51% free, 30MB/62MB, paused 1.146ms total 29.164ms
D/GCM     ( 2142): Message class com.google.f.a.a.i
I/ActivityManager( 1035): Killing 7366:com.android.chrome/u0a57 (adj 15): empty for 1813s
W/libprocessgroup( 1035): failed to open /acct/uid_10057/pid_7366/cgroup.procs: No such file or directory
D/AndroidRuntime( 7987): 
D/AndroidRuntime( 7987): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7987): CheckJNI is OFF
D/AndroidRuntime( 7987): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1035): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1035): Killing 7004:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
I/WindowState( 1035): WIN DEATH: Window{2edd6a73 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1035): Client connection lost with reason: 4
D/InputDispatcher( 1035): Window went away: Window{2edd6a73 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings( 1035): Skipping PackageSetting{32ec70e5 com.example.hello/10319} due to missing metadata
I/ActivityManager( 1035):   Force finishing activity ActivityRecord{2d2d1ffc u0 com.test.thalitest/.MainActivity t4}
E/GBMv2   (  340): DFP En is all cleared set to be enabled
W/ActivityManager( 1035): Spurious death for ProcessRecord{1260024a 7004:com.test.thalitest/u0a311}, curProc for 7004: null
I/ActivityManager( 1035): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1035):   Force finishing activity ActivityRecord{2d2d1ffc u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1035): Duplicate finish request for ActivityRecord{2d2d1ffc u0 com.test.thalitest/.MainActivity t4 f}
I/[LGHome]EVENT( 2089): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{2f5bb35d co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{319fe4d2 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2089): [Launcher.java:903:onResume()]onResume
I/[LGHome]EVENT( 2089): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1925): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3743): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2089): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2089): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2089): [Launcher.java:1056:onResume()]onResume end
I/art     ( 4588): Explicit concurrent mark sweep GC freed 16924(944KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 502us total 44.476ms
I/[LGHome]EVENT( 2089): [Launcher.java:1114:onPause()]onPause
E/LGBluetoothAvrcpQcomAdapter( 3799): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3799): [BTUI] [+] updateMediaPlayerInfo
D/LIA_MrGDBLogger_PackageInfoDetector( 3743): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/KeyguardModel( 1466): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_Service_RemotePackageHandler( 2046): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
I/InputReader( 1035): Reconfiguring input devices.  changes=0x00000010
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
D/administrator( 1035): Handling package changes for user 0
W/GeofencerStateMachine( 1838): Ignoring removeGeofence because network location is disabled.
W/System.err( 4544): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4544): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4544): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4544): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4544): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4544): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4544): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4544): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4544): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4544): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4544): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4544): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/ActivityManager( 1035): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8016 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/ActionManagerService( 1925): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3743): handleMessage: what(1000) actionID(0x1000004)
I/[LGHome]GBoardWebView( 2089): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
I/[SystemUI]QSlideListController( 1466): onReceive = android.intent.action.PACKAGE_REMOVED
V/BoardContentProvider( 3743): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2089): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2089): , create_time: 1430558575574
I/GBoardWebViewUtils( 2089): , expire_time: 0
I/GBoardWebViewUtils( 2089): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2089): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2089): , display: false
I/GBoardWebViewUtils( 2089): , animation: false }
I/GBoardWebViewUtils( 2089): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2089): , create_time: 1430558575600
I/GBoardWebViewUtils( 2089): , expire_time: 0
I/GBoardWebViewUtils( 2089): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2089): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2089): , display: false
I/GBoardWebViewUtils( 2089): , animation: false }
I/GBoardWebViewUtils( 2089): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1450367114146
I/GBoardWebViewUtils( 2089): , create_time: 1450367114951
I/GBoardWebViewUtils( 2089): , expire_time: 0
I/GBoardWebViewUtils( 2089): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1450367114146&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2089): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2089): , display: false
I/GBoardWebViewUtils( 2089): , animation: false }
I/SystemUI[Framework]( 1035): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1035): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1035): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1035): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2d4c3277,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1035): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1466): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/WallpaperManager( 2089): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/[LGHome]GBoardWebView( 2089): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
I/ActivityManager( 1035): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8037 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
D/KeyguardModel( 1466): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/SplitUIManager( 1890): split_name #11 / not available #0
D/SplitUIService( 1890): removed split : 
D/SplitUIManager( 1890): split_name #11 / not available #0
I/SplitUIService( 1890): split app #11
W/ActivityManager( 1035): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3799): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3799): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3799): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3799): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3799): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3799): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3799): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3799): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3799): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3799): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3799): [BTUI] [-] updateMediaPlayerInfo
I/NotificationService( 1035): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1035): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1035): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister( 1035): removeObsoleteFile: deleting file=4_task.xml
I/[LGHome]EVENT( 2089): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/PhoneStatusBar( 1466): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1466): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1466):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1466): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]EVENT( 2089): [Launcher.java:5349:onStop()]onStop
V/SIM_STK ( 1035): Menu title from STK is T-Mobile
W/ResourcesManager( 8016): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/LockScreenSettings( 8037): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/KeyguardModel( 1466): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1466): createShortcutInfo...
D/PluginManager( 8016): init()
D/KeyguardModel( 1466): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
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
D/KeyguardModel( 1466): handleShortcutListChanged...
I/ThermalEngine(  324): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3134): Thermal-Lib-Client: Client request sent
D/KeyguardModel( 1466): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1466): createShortcutInfo...
D/KeyguardModel( 1466): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1466): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1466): createShortcutInfo...
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/KeyguardModel( 1466): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1466): createShortcutInfo...
I/ActivityManager( 1035): Killing 7401:com.lge.drmservice/u0a62 (adj 15): empty for 1816s
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2089): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2089): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/art     ( 1035): Explicit concurrent mark sweep GC freed 18827(1321KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 5.649ms total 219.448ms
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2089): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/KeyguardModel( 1466): handleShortcutListChanged...
W/libprocessgroup( 1035): failed to open /acct/uid_10062/pid_7401/cgroup.procs: No such file or directory
I/Timeline( 1035): Timeline: Activity_windows_visible id: ActivityRecord{1f74a634 u0 com.lge.launcher2/.Launcher t3} time:2119793
D/[Concierge]Service( 2621): onStartCommand(). Type : 8
D/[Concierge]Service( 2621): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2621): Update widget ID : 11
D/[Concierge]WidgetView( 2089): change position of spinner
D/[Concierge]Service( 2621): onStartCommand(). Type : 0
I/[Concierge]WidgetView( 2089): initWebView(). Time : 1450740913894
W/ResourcesManager( 1035): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1035): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/AndroidRuntime( 7987): Shutting down VM
I/[Concierge]WebView( 2089): Return exist ConciergeWebView. Reuse : 175731831
D/[Concierge]WidgetView( 2089): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2089): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2089): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@25c62bca
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2089): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2089): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2089): Widget kill message received. Destory myself. My : 1450738822342, New one : 1450740913894
D/[Concierge]WidgetView( 2089): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2089): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]EVENT( 2089): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 2089): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2089): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/Timeline( 2089): Timeline: Activity_idle id: android.os.BinderProxy@2ec450d4 time:2119907
W/ExternalStrings( 8016): load override strings
W/ExternalStrings( 8016): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 8016): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 8016): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 8016): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 8016): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 8016): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 8016): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 8016): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 8016): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 8016): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 8016): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 8016): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 8016): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 8016): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 8016): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 8016): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 8016): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 8016): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 8016): onCreate
V/Signer  ( 8016): override build config not found
D/Signer  ( 8016): value of property debug is false
D/LGMDMWrapper( 8016): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/LGMDMWrapper( 8016): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 8016): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 8016): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 8016): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 8016): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 8016): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 8016): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 8016): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 8016): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 8016): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 8016): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 8016): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 8016): Create singleton instance
I/chromium( 2089): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
D/LGMDMWrapper( 8016): LG MDM library v4.0.0 is available on this device.
D/PostponalbeReceiver( 8016): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
W/ContextImpl( 8016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/GBoardtInterface( 2089): onReloaded()
I/GBoardWebViewClient( 2089): onPageFinished url:file:///android_asset/www/main.html
I/ActivityManager( 1035): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8065 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager( 1035): Killing 7429:com.lge.sizechangable.weather/u0a85 (adj 15): empty for 1816s
W/libprocessgroup( 1035): failed to open /acct/uid_10085/pid_7429/cgroup.procs: No such file or directory
V/BoardContentProvider( 3743): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
W/ActivityThread( 8016): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
V/BoardContentProvider( 3743): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1925): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3743): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3743): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1925): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3743): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3743): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3743): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3743): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3743): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2089): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2089): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2089): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2089): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/AppUp4:AppBoxCP( 8065): onCreate
W/AppUp4:DB( 8065):  [AppBoxDatabaseHelper] construct
D/GBoardUriUtils( 2089): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1450367114146&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2089): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1450367114146&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
E/SQLiteDatabase( 8065): Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
E/SQLiteDatabase( 8065): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 8065): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 8065): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8065): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8065): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/SQLiteDatabase( 8065): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 8065): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 8065): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/SQLiteDatabase( 8065): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/SQLiteDatabase( 8065): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/SQLiteDatabase( 8065): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/SQLiteDatabase( 8065): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/SQLiteDatabase( 8065): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8065): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8065): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/SQLiteDatabase( 8065): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8065): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8065): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/SQLiteDatabase( 8065): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/AndroidRuntime( 8065): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 8065): FATAL EXCEPTION: main
E/AndroidRuntime( 8065): Process: com.lge.appbox.client, PID: 8065
E/AndroidRuntime( 8065): java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8065): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
E/AndroidRuntime( 8065): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
E/AndroidRuntime( 8065): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
E/AndroidRuntime( 8065): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
E/AndroidRuntime( 8065): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
E/AndroidRuntime( 8065): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8065): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 8065): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/AndroidRuntime( 8065): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8065): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8065): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/AndroidRuntime( 8065): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/AndroidRuntime( 8065): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 8065): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/AndroidRuntime( 8065): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8065): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8065): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/AndroidRuntime( 8065): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/AndroidRuntime( 8065): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/AndroidRuntime( 8065): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
E/AndroidRuntime( 8065): 	... 11 more
E/DropBoxManagerService( 1035): Can't write: system_app_crash
E/DropBoxManagerService( 1035): java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1035): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1035): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1035): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1035): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1035): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1035): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
E/DropBoxManagerService( 1035): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1035): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1035): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1035): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1035): 	... 5 more
I/ActivityManager( 1035): Killing 7450:com.google.android.apps.magazines/u0a93 (adj 15): empty for 1816s
E/SQLiteDatabase( 8016): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 8016): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 8016): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 8016): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8016): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.wsstorage.ConfigManager.ab(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.fw.ws.WSLicenseService.a(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.g.b.a(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 8016): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 8016): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 8016): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 8016): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 8016): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 8016): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 8016): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 8016): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
E/SQLiteDatabase( 8016): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 8016): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 8016): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 8016): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 8016): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 8016): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 8016): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 8016): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 8016): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 8016): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 8016): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 8016): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteOpenHelper( 8016): Couldn't open lockedapplications for writing (will try read-only):
E/SQLiteOpenHelper( 8016): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 8016): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 8016): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 8016): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 8016): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 8016): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 8016): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 8016): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 8016): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 8016): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 8016): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 8016): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 8016): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 8016): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 8016): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteOpenHelper( 8016): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 8016): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 8016): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 8016): 	at com.mcafee.d.c.run(Unknown Source)
W/SQLiteOpenHelper( 8016): Opened lockedapplications in read-only mode
W/libprocessgroup( 1035): failed to open /acct/uid_10093/pid_7450/cgroup.procs: No such file or directory

```
