#### Test 51517283e387105_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 257364935011; DSPS: 8574310; Offset : -4313808404
,D/AndroidRuntime( 7094): 
D/AndroidRuntime( 7094): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7094): CheckJNI is OFF
D/AndroidRuntime( 7094): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1039): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1967): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1039): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
V/ActivityStackEx( 1039): create ActivityStackEx
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{309cb006 #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1039): setTaskToReturnTo : TaskRecord{309cb006 #2 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1039): AppWindowTokenEx init.. 
E/GBMv2   (  339): DFP En is all cleared set to be enabled
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{25f17803 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LgeAbsQuickCoverView( 1419): mCoverXPos: 0 ,mCoverYPos: 0
D/LgeAbsQuickCoverView( 1419): mCoverWidth: 0 ,mCoverHeight: 0
I/ActivityManager( 1039): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7114 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7094): Shutting down VM
V/ActivityManager( 1039): Display changed displayId=0
D/DSDPConnection( 1874): Display #0 changed.
D/SplitWindowPolicy( 1967): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1967): topRunningActivity=ActivityInfo{2915a1c5 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1967): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1967): topRunningActivity=ActivityInfo{38de171a co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/ContextHelper( 7114): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7114): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7114): Loading: webviewchromium
,I/LibraryLoader( 7114): Time to load native libraries: 3 ms (timestamps 4631-4634)
,I/LibraryLoader( 7114): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7114): Binding Chromium to main looper Looper (main, tid 1) {3b97f2b5}
,I/LibraryLoader( 7114): Expected native library version number "",actual native library version number ""
I/chromium( 7114): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7114): Initializing chromium process, renderers=0
W/art     ( 7114): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7114): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,V/AudioPolicyService(  316): registerClient() client 0xb1427460, uid 10311
I/chromium( 7114): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7114): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1039): Message: 20
D/BluetoothManagerService( 1039): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1805c60:true
I/Adreno-EGL( 7114): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7114): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7114): Build Date: 12/12/14 금
I/Adreno-EGL( 7114): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7114): Remote Branch: 
I/Adreno-EGL( 7114): Local Patches: 
I/Adreno-EGL( 7114): Reconstruct Branch: 
,W/chromium( 7114): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7114): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7114): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7114): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7114): CordovaWebView is running on device made by: LGE
,W/art     ( 7114): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7114): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7114): Render dirty regions requested: true
I/OpenGLRenderer( 7114): Initialized EGL, version 1.4
,D/OpenGLRenderer( 7114): Enabling debug mode 0
D/Atlas   ( 7114): Validating map...
,D/SplitWindow( 1039): check instance of lgWin Window{7f4d9a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1039): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1464): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1464): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1464):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1464): , Keyguard show=false, IME shown=false, Panel expanded=false
,W/PhoneWindowManagerEx( 1039): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1039): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1039): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@33386fc6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1039): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LgDataFeature( 7114): LgDataFeature() Constructor: none
D/LgDataFeature( 7114): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1039): Displayed com.test.thalitest/.MainActivity: +576ms (total +659ms)
I/Timeline( 1039): Timeline: Activity_windows_visible id: ActivityRecord{1afcf6c7 u0 com.test.thalitest/.MainActivity t2} time:265031
,I/Timeline( 7114): Timeline: Activity_idle id: android.os.BinderProxy@14ebf325 time:265032
I/chromium( 7114): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7114): 
,D/JsMessageQueue( 7114): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7114): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435226368
,D/JX-Cordova( 7114): jxcore cordova android initializing
E/GBMv2   (  339): DFP En is all cleared set to be enabled
E/GBMv2   (  339): Set value is all cleared set the max
I/GBMv2   (  339): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7114): Initializing JXcore engine
,W/jxcore-log( 7114): JXcore engine is ready
,W/jxcore-log( 7114): Starting JXcore engine
,W/.test.thalitest( 7114): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7491]" dev="sockfs" ino=7491 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 7114): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 7114): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8684]" dev="sockfs" ino=8684 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7114): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7114): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[34105]" dev="sockfs" ino=34105 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 7114): Background sticky concurrent mark sweep GC freed 122331(11MB) AllocSpace objects, 21(7MB) LOS objects, 28% free, 39MB/55MB, paused 2.315ms total 116.604ms
,W/jxcore-log( 7114): Platform android
W/jxcore-log( 7114): 
W/jxcore-log( 7114): Process ARCH arm
W/jxcore-log( 7114): 
I/jxcore-log( 7114): JXcore Cordova bridge is ready!
I/jxcore-log( 7114): 
W/jxcore-log( 7114): JXcore engine is started
I/jxcore-log( 7114): Turning radios to true
I/jxcore-log( 7114): 
D/BluetoothAdapter( 7114): enable(): BT is already enabled..!
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/WifiService( 1039): New client listening to asynchronous messages
D/WifiServiceImplEx( 1039): setWifiEnabled: true pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: true pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1039): disconnect pid=7114, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1039):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1039): [267,883,227 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1039): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1039): reconnect pid=7114, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/wpa_supplicant( 2693): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1039): DISCONNECT: returned true
E/WifiStateMachine( 1039): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1039): InitialState.processMessage what=4
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1039): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1039): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
D/Tethering( 1039): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2693): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): RunningState{ when=-3ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  312): Clearing all IP addresses on wlan0
V/NativeCrypto( 2135): Read error: ssl=0xaa6f3200: I/O error during system call, Connection timed out
V/NativeCrypto( 2135): SSL shutdown failed: ssl=0xaa6f3200: I/O error during system call, Broken pipe
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/ActivityManager( 1039): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7194 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/WifiHS20( 1039): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1967): handleWifiStateChangedEvent: 0
E/WifiStateMachine( 1039): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1039):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_RECONNECT 0 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiNative: ( 1039): [268,045,447 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1039): doBoolean: RECONNECT
I/wpa_supplicant( 2693): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1039): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1039): hidePasspointNotification off =false
D/WifiNative-wlan0( 1039): RECONNECT: returned true
E/WifiStateMachine( 1039):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=268049
E/WifiStateMachine( 1039):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=268050
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2693): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/WifiNative-wlan0( 1039): SET ps 1: returned true
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService( 1039): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  312): Clearing all IP addresses on wlan0
D/ConnectivityService( 1039): Default network via Wi-Fi disconnect. stop DSQN
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1039): disableDataServiceNotify
D/DSQN    ( 1039): stop dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=268079  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=268080  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1039):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1039):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/ConnectivityService( 1039): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/WifiStateMachine( 1039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Disconnected - quitting
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/CSLegacyTypeTracker( 1039): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1039): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524292
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
E/WifiStateMachine( 1039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNetworkAgent( 1039): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1039):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=268094  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=268098  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/ConnectivityService( 1039): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1039): Removing idletimer
W/Settings( 1039): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1039): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1039): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1874): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/WIFI    ( 1039): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateSCANNING
D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
W/ResourcesManager( 7194): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7194): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7194): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7194): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
W/ResourcesManager( 7194): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 7194): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7194): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7194): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7194): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7194): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : availableList=[]
,D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7194): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7194): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/DhcpStateMachine( 1039): StoppedState
D/DhcpStateMachine( 1039): StoppedState{ when=-203ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1039): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7229 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1039): Killing 6672:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10008/pid_6672/cgroup.procs: No such file or directory
,I/PCSuite ( 7229): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7229): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7194): LgDataFeature() Constructor: none
,D/LgDataFeature( 7194): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
,I/ActivityManager( 1039): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7250 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1039): Killing 6168:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/art     (  343): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 20.561ms
,I/art     (  343): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 360us total 17.454ms
,I/art     (  343): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 432us total 36.051ms
,W/libprocessgroup( 1039): failed to open /acct/uid_10011/pid_6168/cgroup.procs: No such file or directory
W/ResourcesManager( 7250): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7250): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7250): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 7250): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7250): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7250): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7250): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 7250): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7250): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7250): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/QRemote ( 7250): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7229): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7229): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 7250): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
,D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7250): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7229): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7229): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7250): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7229): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7229): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7250): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7250): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7250): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 7250): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 7250): LgDataFeature() Constructor: none
D/LgDataFeature( 7250): LgDataFeature() Constructor Done, null
,V/SoundPool( 7250): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7250): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7250): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7250): doLoad: loading sample sampleID=1
I/QRemote ( 7250): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 7250): Start decode
V/MediaPlayer[Native]( 7250): decode(31, 10857164, 17813)
V/MediaPlayerService(  316): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  316): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  316): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  316): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  316): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  316): player type = 3
V/AwesomePlayer(  316): AwesomePlayer create()
,V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/AwesomePlayer(  316): setAudioSink() 
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb1432280, 8, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/Utils   (  316): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  316): setDataSource_l dataSource
V/LGParserOSAL(  316): SniffLGParser start
V/LGParserOSAL(  316): MainType:5, SubType=0
V/LGParserOSAL(  316): #### check Mime : application/ogg
V/LGParserOSAL(  316): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  316): Use LGExtractor :application/ogg 
D/QRemote ( 7250): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
D/UEI.SmartControl( 6842): QS Service created
,E/QRemote ( 7250): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 7250): Create singleton instance
I/UEI.SmartControl( 6842): Service initServices...
D/UEI.SmartControl( 6842): QS start get config
,V/LGParserOSAL(  316): supported mime: application/ogg
V/AwesomePlayer(  316): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  316): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  316): mBitrate = -1 bits/sec
V/AwesomePlayer(  316): AudioTrack Setting
V/AwesomePlayer(  316): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  316): setAudioSource() 
V/MediaPlayerService(  316): prepare
V/AwesomePlayer(  316): prepareAsync_l() 
V/MediaPlayerService(  316): wait for prepare
V/AwesomePlayer(  316): onPrepareAsyncEvent() 
V/AwesomePlayer(  316): initAudioDecoder() 
W/Utils   (  316): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  316): isOffloadSupported()
V/AudioPolicyManager(  316): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  316): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  316): isAudioPlaybackHookOn() false
V/AwesomePlayer(  316): getUseOffload() = 0 
V/OMXCodec(  316): OMXCodec::Create
V/OMXCodec(  316): findMatchingCodecs()
V/OMXCodec(  316): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  316): matchingCodecs.size()=1
V/OMXCodec(  316): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/OMXCodec(  316): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  316): LG Codec Adapter start
V/OMXCodec(  316): OMXCodec Createtor
V/OMXCodec(  316): setComponentRole
V/OMXCodec(  316): configureCodec protected=0
V/LGCodecAdapter(  316): called getLGCodecSpecificData
V/LGCodecOSAL(  316): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  316): Called LGconfigureCodecMETA
V/LGCodecOSAL(  316): Called LGconfigureCodecMSG
V/LGCodecOSAL(  316): Not support LGCodec
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  316): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  316): Could not offload audio decode, try pcm offload
W/Utils   (  316): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  316): isOffloadSupported()
V/AudioPolicyManager(  316): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  316): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  316): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  316): init()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  316): allocateBuffers
V/OMXCodec(  316): allocateBuffersOnPort portIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on input port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434920 on input port
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434970 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434f60 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14e10b0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14e1100 on output port
V/OMXCodec(  316): init() mAsyncCompletion wait!!! 
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  316): init() mAsyncCompletion wait!!! 
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  316): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  316): finishAsyncPrepare_l() 
V/AudioCache(  316): notify(0xb1432280, 5, 0, 0)
V/AudioCache(  316): ignored
V/AudioCache(  316): notify(0xb1432280, 1, 0, 0)
V/AudioCache(  316): prepared
V/AudioCache(  316): wait - success
V/MediaPlayerService(  316): start
V/AwesomePlayer(  316): play_l() 
V/AwesomePlayer(  316): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  316): createAudioPlayer_l
V/AwesomePlayer(  316): seekAudioIfNecessary_l() 
V/AwesomePlayer(  316): startAudioPlayer_l() 
D/AudioPlayer(  316): start of Playback, useOffload 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  316): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  316): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OM,XCodec(  316): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  316): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976944
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973978464
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974683312
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974683392
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  316): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  316): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  316): allocateBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14e10b0 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434f60 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb1434970 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] allocated buffer 0xb14e1290 on output port
V/OMXCodec(  316): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  316): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  316): notify(0xb1432280, 6, 0, 0)
V/AudioCache(  316): ignored
V/MediaPlayerService(  316): wait for playback complete
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf406000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf407000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf408000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf409000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf40a000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf40b000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf40c000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf40d000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf40e000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf40f000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf410000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf411000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf412000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf413000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf414000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf415000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf416000, 0xb123a000, 4096)
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf417000, 0xb123a000, 4096)
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf418000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf419000, 0xb123a000, 4096)
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:466
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf41a000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf41b000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf41c000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf41d000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf41e000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf41f000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf420000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf421000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf422000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf423000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf424000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf425000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf426000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf427000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf428000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf429000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf42a000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf42b000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf42c000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf42d000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf42e000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf42f000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf430000, 0xb123a000, 4096)
,V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf431000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf432000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf433000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf434000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf435000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf436000, 0xb123a000, 4096)
V/AudioCache(  316): write(0xb123a000, 4096)
V/AudioCache(  316): memcpy(0xaf437000, 0xb123a000, 4096)
V/OMXCodec(  316): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  316): postAudioEOS() 
V/AudioCache(  316): write(0xb123a000, 280)
V/AudioCache(  316): memcpy(0xaf438000, 0xb123a000, 280)
V/AwesomePlayer(  316): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  316): onStreamDone
V/AwesomePlayer(  316): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  316): notify(0xb1432280, 2, 0, 0)
V/AudioCache(  316): playback complete
V/AwesomePlayer(  316): pause_l() 
V/AudioCache(  316): notify(0xb1432280, 7, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/AudioPlayer(  316): Pause Playback at 1068125
V/AudioCache(  316): wait - success
V/MediaPlayerService(  316): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  316): reset_l() 
V/AudioCache(  316): notify(0xb1432280, 8, 0, 0)
V/AudioCache(  316): ignored
V/AwesomePlayer(  316): cancelPlayerEvents
D/AudioPlayer(  316): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434920 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434740 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434600 on port 0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14e1290 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434970 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb1434f60 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeing buffer 0xb14e10b0 on port 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  316): [,OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  316): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  316): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  316): AudioPlayer releasing audio source
D/AudioPlayer(  316): AudioPlayer done releasing audio source
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/AwesomePlayer(  316): ~AwesomePlayer call
V/AwesomePlayer(  316): reset_l() 
V/AwesomePlayer(  316): cancelPlayerEvents
V/SoundPool( 7250): close(31)
V/SoundPool( 7250): pointer = 0x9fe7f000, size = 205080, sampleRate = 48000, numChannels = 2
I/UEI.SmartControl( 6842): Supports setup maps: true
D/UEI.SmartControl( 6842): QS start statue = true Error code = 0
I/UEI.SmartControl( 6842): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6842): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6842): ### init IR Blaster...
,D/serial_port( 6842): Configuring serial port,
E/UEI.SmartControl( 6842): UEIBLaster setting for 616
I/UEI.SmartControl( 6842): Setting serial record hearder size = 2
I/UEI.SmartControl( 6842): configuring settings for MAXQ616,
I/UEI.SmartControl( 6842): Get version...
D/UEI.SmartControl( 6842): serial port data available: 21,
,D/UEI.SmartControl( 6842): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6842): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6842): QS saving settings...
,D/UEI.SmartControl( 6842): IR Blaster version: 25672567
D/UEI.SmartControl( 6842): serial port data available: 4
,I/UEI.SmartControl( 6842): Device manager: loading config....
,D/UEI.SmartControl( 6842): ----------- loading internal config...
W/ContextImpl( 6842): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6842): Services init done
D/UEI.SmartControl( 6842): QS Service init finished
D/UEI.SmartControl( 6842): QS Service version name: 2.1.91
D/UEI.SmartControl( 6842): QS Service version code: 201091
,D/UEI.SmartControl( 6842): Service requested: Control
E/UEI.SmartControl( 6842): Loading SETTINGS...
D/UEI.SmartControl( 6842): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6842): Internal service binding...
I/QRemote ( 7250): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6842): ------ IControl API: 11
D/UEI.SmartControl( 6842): File observer start...
,E/UEI.SmartControl( 6842): IR Port is disabled: false
D/UEI.SmartControl( 6842): Starting file observer...
D/UEI.SmartControl( 6842): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6842): Registering callback...
I/UEI.SmartControl( 6842): ------ IControl API: 19
I/UEI.SmartControl( 6842): Registering Services Ready callback...
I/UEI.SmartControl( 6842): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6842): -----service ready thread exits
I/QRemote ( 7250): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
,D/QRemote ( 7250): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7250): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7250): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7250): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6842): ------ IControl API: 8
D/QRemote ( 7250): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7250): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7250): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7250): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7250): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7250): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7250): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 7250): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 7250): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7250): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1448282987380]
D/QRemote ( 7250): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,I/ActivityManager( 1039): Killing 6187:com.android.contacts/u0a19 (adj 15): empty #17
,D/QRemote ( 7250): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1039): failed to open /acct/uid_10019/pid_6187/cgroup.procs: No such file or directory
,V/QRemote ( 7250): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7250): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
,D/QRemote ( 7250): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1039): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1039): couldn't identify event type - WPS-AP-AVAILABLE 
,I/wpa_supplicant( 2693): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1039):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1039):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1039):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
E/WifiStateMachine( 1039):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 bcn=0
D/WifiNative-wlan0( 1039): doString: [BSS RANGE=0- MASK=0x21987]
,D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=270199  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=270214  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7250): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7250): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2693): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1039): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,I/wpa_supplicant( 2693): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2693): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=270307  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1039): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1039): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=270313  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1039): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1039): sendTetherStateChangedBroadcast 1, 0, 0
,D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7194): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7194): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7194): [AUTORUN] persist.sys.usb.config = ptp_only,adb
E/WifiStateMachine( 1039):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=270326
E/WifiStateMachine( 1039):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=270327
E/WifiStateMachine( 1039):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=270327
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=270327
E/WifiStateMachine( 1039):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=270328
D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=270329  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=270334  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
E/WifiStateMachine( 1039):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=270334  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=270335  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
E/WifiStateMachine( 1039):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=270339
E/WifiStateMachine( 1039):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=270339
D/WifiNative-wlan0( 1039): doString: [STATUS]
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1039):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateASSOCIATED
D/UsbSettingsControl( 7194): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : activeList=[]
I/WifiServiceExtension( 1039): setVHTCapabilityType  : false
D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7194): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7194): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/WifiServerServiceExt( 1039): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1039): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/ConnectivityService( 1039): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1039): Got NetworkAgent Messenger
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1039): NetworkAgent connected
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7250): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
D/CommandListener(  312): Setting iface cfg
E/WifiStateMachine( 1039): Start Dhcp Watchdog 2
E/WifiStateMachine( 1039):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=270390  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=270390  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=270390  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/DhcpStateMachine( 1039): StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): WaitBeforeStartState
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1039):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=270394  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=270395  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1039):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=270395  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1039):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETSUSPENDMODE 0
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateCOMPLETED
,D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7250): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7250): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2693): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/WifiNative-wlan0( 1039): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 0
D/WifiNative-wlan0( 1039): SET ps 0: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2693): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1039): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1039): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LGWifiP2pService( 1039): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1daea438 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1daea438 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1039): DHCP Start wake lock is acquired.
D/CommandListener(  312): Setting iface cfg
D/CommandListener(  312): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1039): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.122/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1039):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1039):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1039):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2693): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2693): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1039): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
,D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7250): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1039):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1039): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1039): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1039): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1039): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
V/WfdStateTracker( 1967): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1039): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1039): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/ConnectivityService( 1039): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1039): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1039): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  312): netlink response contains error (File exists)
D/ConnectivityService( 1039): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/ConnectivityService( 1039): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1039): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1039): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1039): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 1039): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1039): currentScore = 0, newScore = 20
D/ConnectivityService( 1039):    accepting network in place of null
D/ConnectivityService( 1039): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1874): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/libc-netbsd(  312): res_queryN name = clients3.google.com, class = 1, type = 28
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1039): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1039): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1039): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1039): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1039): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roa,ming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
,D/ConnectivityService( 1039): validation of new default Network = false
D/ConnectivityService( 1039): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1039): enableDataServiceNotify 
D/DSQN    ( 1039): start dsqn bin
V/NetworkPolicy( 1039): [LG_RESTRICTED] checkMobilePolicy_type()
I/jxcore-log( 7114): Attempting to connect to the test coordinator server
I/jxcore-log( 7114): 
,D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 1039): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
W/dsqn    ( 7307): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7307): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/QRemote ( 7250): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524290
D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.,
,E/DSQN    ( 7307): DSQN ssw
D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  312): res_queryN name = clients3.google.com, class = 1, type = 1
D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7250): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7229): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
,D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7250): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7250): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7250): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  312): res_queryN name = clients3.google.com succeed
,D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7229): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7250): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7250): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7250): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/LGDataListener(  312): argv[0]=dsqncommand
,D/LGDataListener(  312): argv[1]=wlan0
D/LGDataListener(  312): argv[2]=1
D/LGDataListener(  312): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1039): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1039): start to monitor internet connection
D/DhcpStateMachine( 1039): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1039): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1039): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 7313): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7313): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 23 Nov 2015 12:49:48 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448282988448], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448282988428]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Validated
D/ConnectivityService( 1039): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1039):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1039): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService( 1039): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1039): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524290
I/dhcpcd  ( 7313): version 5.5.6 starting
D/TelephonyNetworkFactory-1( 1874): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/dhcpcd  ( 7313): get_duid: m
D/dhcpcd  ( 7313): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7313): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/dhcpcd  ( 7313): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7313): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7313): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7313): wlan0: rebinding lease of 192.168.1.122
D/dhcpcd  ( 7313): wlan0: sending REQUEST (xid 0x949a470b), next in 3.12 seconds
,D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1039): MasterInitialState.processMessage what=3
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1039): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6642): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5943): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 5943): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager( 1039): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7340 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 7340): onCreate
W/AppUp4:DB( 7340):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7340):  setFingerPrint start
I/AppUp4:DB( 7340):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7340):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7340):  SDK version = 21
I/AppUp4:DB( 7340):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7340): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7340): onReceive
D/LgDataFeature( 7340): LgDataFeature() Constructor: none
D/LgDataFeature( 7340): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7340): Context : android.app.ReceiverRestrictedContext@2db984bb
D/AppUp4:CustFacade( 7340): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7340): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 7340): begin check event
I/AppUp4:CustModeStarterReceiver( 7340): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7340): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7340): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7340): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7340): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1039): Killing 6697:com.lge.email/u0a23 (adj 15): empty #17
,D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1039): failed to open /acct/uid_10023/pid_6697/cgroup.procs: No such file or directory
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3375): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3375): DownloadService onCreate
D/LGDMClient( 4319): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4319): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3375): in removeSpuriousFiles
,V/DownloadManager( 3375): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@2ad5c77c on behalf of 3375
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
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@25b5e805 on behalf of 3375
E/WifiStateMachine( 1039):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1039):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,D/ConnectivityService( 1039): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
,D/ConnectivityService( 1039): identical MTU - not setting
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1039): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1039): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524295
I/ActivityManager( 1039): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7368 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3375): DownloadService onStartCommand
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3375): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@1635428b on behalf of 3375
E/LGDMClient( 4319): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4319): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4319): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3375): processing inserted download 1
V/DownloadManager( 3375): processing inserted download 4
V/DownloadManager( 3375): processing inserted download 7
V/DownloadManager( 3375): processing inserted download 8
,V/DownloadManager( 3375): processing inserted download 9
V/DownloadManager( 3375): processing inserted download 10
V/DownloadManager( 3375): processing inserted download 16
V/DownloadManager( 3375): processing inserted download 17
V/DownloadManager( 3375): processing inserted download 18
V/DownloadManager( 3375): processing inserted download 21
V/DownloadManager( 3375): DownloadService onDestroy
W/ResourcesManager( 7368): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7368): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7368): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7368): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 7368): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7368): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
W/ResourceType( 7368): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7368): LgDataFeature() Constructor: none
,D/LgDataFeature( 7368): LgDataFeature() Constructor Done, null
,D/eas_req ( 7368): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1039): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7399 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 7368): JNI_OnLoad()
I/HubEmail( 7368): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7368): registerNatives()
I/HubEmail( 7368): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7368): registerNativeMethods()
I/HubEmail( 7368): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7368): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager( 1039): Killing 6210:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/dhcpcd  ( 7313): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,W/libprocessgroup( 1039): failed to open /acct/uid_10027/pid_6210/cgroup.procs: No such file or directory
W/Settings( 7368): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/dhcpcd  ( 7313): wlan0: leased 192.168.1.122 for 86400 seconds
D/dhcpcd  ( 7313): wlan0: adding IP address 192.168.1.122/24
D/dhcpcd  ( 7313): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7313): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7313): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 7313): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7313): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7313): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
W/Settings( 7368): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3318): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3318): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3318): networkInfo.isConnected() = false
,I/ActivityManager( 1039): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7438 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = static-avc.lglime.com, class = 1, type = 1
D/DhcpStateMachine( 1039): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1039): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1039): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1039): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.122
V/LgDhcpStateMachineHelper( 1039): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1039): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1039): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1039): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1039): RunningState
D/libc-netbsd(  312): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7399): There are no updated forms. The schedule will be deleted.
,I/ActivityManager( 1039): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7468 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6597:com.android.defcontainer/u0a4 (adj 15): empty #17
V/FormManager( 7399): Alarm would be updated, because LastCheckTime has been updated.
,W/libprocessgroup( 1039): failed to open /acct/uid_10004/pid_6597/cgroup.procs: No such file or directory
I/ActivityManager( 1039): Killing 6728:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10061/pid_6728/cgroup.procs: No such file or directory
,I/ActivityManager( 1039): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7486 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6777:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,E/WifiStateMachine( 1039):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,E/WifiStateMachine( 1039):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1039):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
W/libprocessgroup( 1039): failed to open /acct/uid_10080/pid_6777/cgroup.procs: No such file or directory
,I/art     ( 7486): Almond Protected OAT
,D/WeatherApplication( 7486): removeAccount
,D/WeatherApplication( 7486): Account.length = 0
E/WeatherApplication( 7486): OPERATOR:OPEN
D/WeatherAncestor( 7486): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:51
D/Weather.Utils( 7486): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7486): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7486): 2 : This is isUpdating : false
,D/WeatherAncestor( 7486): connectivity changed - connection : true
D/WeatherService( 7486): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 7486): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7486): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7486): 2 : Cache is not up-to-date, count: 0
,D/Weather_cast( 7486): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7486): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:51
,I/ActivityManager( 1039): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7507 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6822:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6822/cgroup.procs: No such file or directory
,V/WifiInternetCheck( 1039): Single check msg out of sync, ignoring.
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7507): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7507): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7507): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7507): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1039): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5943): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/WebViewFactory( 7507): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7507): Loading: webviewchromium
,I/LibraryLoader( 7507): Time to load native libraries: 4 ms (timestamps 3740-3744)
I/LibraryLoader( 7507): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7507): Binding Chromium to main looper Looper (main, tid 1) {2fb73152}
,I/LibraryLoader( 7507): Expected native library version number "",actual native library version number ""
I/chromium( 7507): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7507): Initializing chromium process, renderers=0
W/art     ( 7507): Attempt to remove local handle scope entry from IRT, ignoring
,V/AudioPolicyService(  316): registerClient() client 0xb1427d00, uid 10093
,W/AudioManagerAndroid( 7507): Requires BLUETOOTH permission
,W/chromium( 7507): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7507): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 7507): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
I/Adreno-EGL( 7507): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7507): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7507): Build Date: 12/12/14 금
I/Adreno-EGL( 7507): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7507): Remote Branch: 
I/Adreno-EGL( 7507): Local Patches: 
I/Adreno-EGL( 7507): Reconstruct Branch: 
,I/NSApplication( 7507): Starting up...
,I/ActivityManager( 1039): Killing 6870:com.lge.bnr/1000 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_1000/pid_6870/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2324): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/ChimeraCfgMgr( 2324): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
W/ContextImpl( 6642): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7340): onReceive
,D/AppUp4:CustFacade( 7340): Context : android.app.ReceiverRestrictedContext@2db984bb
D/AppUp4:CustFacade( 7340): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7340): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7340): begin check event
I/AppUp4:CustModeStarterReceiver( 7340): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3375): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4319): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/LGDMClient( 4319): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3375): DownloadService onCreate
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Settings( 7368): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DownloadManager( 3375): in removeSpuriousFiles
V/DownloadManager( 3375): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/Settings( 7368): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3375): DownloadService onStartCommand
V/DownloadManager( 3375): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@35694826 on behalf of 3375
I/LgeMiscReceiver( 3318): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3318): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3318): networkInfo.isConnected() = false
E/LGDMClient( 4319): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@57d8a14 on behalf of 3375
D/LGDMClient( 4319): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4319): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3375): processing inserted download 1
V/DownloadManager( 3375): processing inserted download 4
V/DownloadManager( 3375): processing inserted download 7
V/DownloadManager( 3375): processing inserted download 8
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
,I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
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
V/DownloadManager( 3375): processing inserted download 9
V/DownloadManager( 3375): processing inserted download 10
V/DownloadManager( 3375): processing inserted download 16
V/DownloadManager( 3375): processing inserted download 17
V/DownloadManager( 3375): processing inserted download 18
V/DownloadManager( 3375): processing inserted download 21
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@35fe12bd on behalf of 3375
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/WeatherAncestor( 7486): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:52
D/Weather.Utils( 7486): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7486): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7486): 2 : This is isUpdating : false
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
D/WeatherAncestor( 7486): connectivity changed - connection : true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/WeatherService( 7486): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@23220531
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ForecastDataCache( 7486): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7486): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7486): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7486): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7486): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:52
W/Kids    ( 2324): [AccountUtils] Account not ready
W/Kids    ( 2324): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2324): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2324): 	at com.google.android.gms.kids.account.k.d(SourceFile:103),
W/Kids    ( 2324): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2324): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2324): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2324): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2324): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2324): 	at java.lang.Thread.run(Thread.java:818)
V/DownloadManager( 3375): DownloadService onDestroy
,W/ResourcesManager( 1419): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
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
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1419): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2324): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{25f17803 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6642): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7340): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7340): onReceive
D/AppUp4:CustFacade( 7340): Context : android.app.ReceiverRestrictedContext@2db984bb
D/AppUp4:CustFacade( 7340): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7340): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7340): begin check event
I/AppUp4:CustModeStarterReceiver( 7340): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3375): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3375): DownloadService onCreate
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/art     ( 1039): Explicit concurrent mark sweep GC freed 86387(4MB) AllocSpace objects, 3(176KB) LOS objects, 33% free, 44MB/66MB, paused 2.112ms total 101.299ms
D/LGDMClient( 4319): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/LGDMClient( 4319): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3375): in removeSpuriousFiles
V/DownloadManager( 3375): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/LgeMiscReceiver( 3318): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3318): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3318): networkInfo.isConnected() = true
D/PhoneState( 3318): setPdpRejectCasuse : false
W/Settings( 7368): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 7368): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3375): DownloadService onStartCommand
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4319): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4319): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4319): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@1dfe1db9 on behalf of 3375
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
D/WeatherAncestor( 7486): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:52
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
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
,D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3375): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3375): in trimDatabase
D/Weather.Utils( 7486): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7486): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7486): 2 : This is isUpdating : false
D/WeatherAncestor( 7486): connectivity changed - connection : true
D/WeatherService( 7486): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@23220531
V/DownloadManager( 3375): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/ForecastDataCache( 7486): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7486): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7486): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7486): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7486): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:52
V/DownloadManager( 3375): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
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
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@285735fe on behalf of 3375
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
V/DownloadManager( 3375): created cursor android.database.sqlite.SQLiteCursor@9915f on behalf of 3375
V/DownloadManager( 3375): processing inserted download 1
V/DownloadManager( 3375): processing inserted download 4
V/DownloadManager( 3375): processing inserted download 7
V/DownloadManager( 3375): processing inserted download 8
V/DownloadManager( 3375): processing inserted download 9
,V/DownloadManager( 3375): processing inserted download 10
V/DownloadManager( 3375): processing inserted download 16
V/DownloadManager( 3375): processing inserted download 17
V/DownloadManager( 3375): processing inserted download 18
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{25f17803 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3375): processing inserted download 21
V/DownloadManager( 3375): DownloadService onDestroy
D/ChimeraCfgMgr( 2324): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
,D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{25f17803 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/UEI.SmartControl( 6842): Internal timer expired: 3
D/UEI.SmartControl( 6842): unbind internal service
,D/serial_port( 6842): close(fd = 24)
I/UEI.SmartControl( 6842): Serial port is closed.
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = www.google.com, class = 1, type = 1
,D/libc-netbsd(  312): res_queryN name = www.google.com succeed
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  312): res_queryN name = clients3.google.com succeed
V/WifiInternetCheck( 1039): isHttpConnectionAvailable - We got a valid response : 204
,V/FormManager( 7399): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7399): Alarm would be updated, because LastCheckTime has been updated.
V/FormManager( 7399): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7399): Alarm would be updated, because LastCheckTime has been updated.
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3731eed4 type 2 when 276160 com.google.android.gms} when 276160
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = mtalk.google.com, class = 1, type = 1
,V/QRemote ( 7250): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7250): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:466
D/libc-netbsd(  312): res_queryN name = mtalk.google.com succeed
,D/GCM     ( 2135): Connected
,D/GCM     ( 2135): Message class com.google.f.a.a.p
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 277365999429; DSPS: 9229705; Offset : -4313810332
,I/GAV4    ( 7507): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 7114): Attempting to connect to the test coordinator server
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): Attempting to connect to the test coordinator server
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): Attempting to connect to the test coordinator server
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): Attempting to connect to the test coordinator server
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): Attempting to connect to the test coordinator server
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): Attempting to connect to the test coordinator server
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): Attempting to connect to the test coordinator server
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): Attempting to connect to the test coordinator server
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): Test app app.js loaded
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":0}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): LogCallback not set !!!!
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/jxcore-log( 7114): DBG, CoordinatorConnector connect called
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): DBG, CoordinatorConnector connect called
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): DBG, CoordinatorConnector connect called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect called
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=1034035626, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3639b3c3 type 2 when 296221 android} when 296221
D/[Concierge]Service( 2631): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=1034035626 [*alarm*], flags=0x0
,I/BooksSync( 6967): Starting books sync
,D/BooksSync( 6967): started syncMyEbooks
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6967): Authentication error
E/BooksAccountManager( 6967): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6967): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6967): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6967): null auth token
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{25f17803 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  312): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6967): Error response from books API: {
W/ApiaryClient( 6967):  "error": {
W/ApiaryClient( 6967):   "errors": [
W/ApiaryClient( 6967):    {
W/ApiaryClient( 6967):     "domain": "global",
W/ApiaryClient( 6967):     "reason": "required",
W/ApiaryClient( 6967):     "message": "Login Required",
W/ApiaryClient( 6967):     "locationType": "header",
W/ApiaryClient( 6967):     "location": "Authorization"
W/ApiaryClient( 6967):    }
W/ApiaryClient( 6967):   ],
W/ApiaryClient( 6967):   "code": 401,
W/ApiaryClient( 6967):   "message": "Login Required"
W/ApiaryClient( 6967):  }
W/ApiaryClient( 6967): }
,W/ApiaryClient( 6967): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6967): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-253676899982519006&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6967): Headers:
W/ApiaryClient( 6967): accept-encoding: [gzip]
W/ApiaryClient( 6967): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6967): gdata-version: 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 297370446089; DSPS: 9885210; Offset : -4313790309
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6967): Authentication error
E/BooksAccountManager( 6967): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6967): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6967): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6967): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{25f17803 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6967): Error response from books API: {
W/ApiaryClient( 6967):  "error": {
W/ApiaryClient( 6967):   "errors": [
W/ApiaryClient( 6967):    {
W/ApiaryClient( 6967):     "domain": "global",
W/ApiaryClient( 6967):     "reason": "required",
W/ApiaryClient( 6967):     "message": "Login Required",
W/ApiaryClient( 6967):     "locationType": "header",
W/ApiaryClient( 6967):     "location": "Authorization"
W/ApiaryClient( 6967):    }
W/ApiaryClient( 6967):   ],
W/ApiaryClient( 6967):   "code": 401,
W/ApiaryClient( 6967):   "message": "Login Required"
W/ApiaryClient( 6967):  }
W/ApiaryClient( 6967): }
,W/ApiaryClient( 6967): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6967): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-253676899982519006&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6967): Headers:
W/ApiaryClient( 6967): accept-encoding: [gzip]
W/ApiaryClient( 6967): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6967): gdata-version: 2
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6967): Authentication error
E/BooksAccountManager( 6967): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6967): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6967): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6967): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
,D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{25f17803 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6967): Error response from books API: {
W/ApiaryClient( 6967):  "error": {
W/ApiaryClient( 6967):   "errors": [
W/ApiaryClient( 6967):    {
W/ApiaryClient( 6967):     "domain": "global",
W/ApiaryClient( 6967):     "reason": "required",
W/ApiaryClient( 6967):     "message": "Login Required",
W/ApiaryClient( 6967):     "locationType": "header",
W/ApiaryClient( 6967):     "location": "Authorization"
W/ApiaryClient( 6967):    }
W/ApiaryClient( 6967):   ],
W/ApiaryClient( 6967):   "code": 401,
W/ApiaryClient( 6967):   "message": "Login Required"
W/ApiaryClient( 6967):  }
W/ApiaryClient( 6967): }
,W/ApiaryClient( 6967): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6967): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-253676899982519006&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6967): Headers:
W/ApiaryClient( 6967): accept-encoding: [gzip]
W/ApiaryClient( 6967): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6967): gdata-version: 2
E/BooksSync( 6967): Soft error: 
E/BooksSync( 6967): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6967): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-253676899982519006&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6967): Headers:
E/BooksSync( 6967): accept-encoding: [gzip]
E/BooksSync( 6967): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6967): gdata-version: 2
E/BooksSync( 6967): 
E/BooksSync( 6967): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6967): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6967): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6967): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6967): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6967): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6967): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6967): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6967): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6967): {
E/BooksSync( 6967):  "error": {
E/BooksSync( 6967):   "errors": [
E/BooksSync( 6967):    {
E/BooksSync( 6967):     "domain": "global",
E/BooksSync( 6967):     "reason": "required",
E/BooksSync( 6967):     "message": "Login Required",
E/BooksSync( 6967):     "locationType": "header",
E/BooksSync( 6967):     "location": "Authorization"
E/BooksSync( 6967):    }
E/BooksSync( 6967):   ],
E/BooksSync( 6967):   "code": 401,
E/BooksSync( 6967):   "message": "Login Required"
E/BooksSync( 6967):  }
E/BooksSync( 6967): }
E/BooksSync( 6967): 
E/BooksSync( 6967): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6967): 	... 8 more
,E/BooksSync( 6967): Sync error
E/BooksSync( 6967): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6967): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-253676899982519006&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6967): Headers:
E/BooksSync( 6967): accept-encoding: [gzip]
E/BooksSync( 6967): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6967): gdata-version: 2
E/BooksSync( 6967): 
E/BooksSync( 6967): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6967): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6967): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6967): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6967): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6967): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6967): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6967): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6967): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6967): {
E/BooksSync( 6967):  "error": {
E/BooksSync( 6967):   "errors": [
E/BooksSync( 6967):    {
E/BooksSync( 6967):     "domain": "global",
E/BooksSync( 6967):     "reason": "required",
E/BooksSync( 6967):     "message": "Login Required",
E/BooksSync( 6967):     "locationType": "header",
E/BooksSync( 6967):     "location": "Authorization"
E/BooksSync( 6967):    }
E/BooksSync( 6967):   ],
E/BooksSync( 6967):   "code": 401,
E/BooksSync( 6967):   "message": "Login Required"
E/BooksSync( 6967):  }
E/BooksSync( 6967): }
E/BooksSync( 6967): 
E/BooksSync( 6967): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6967): 	... 8 more
I/BooksSync( 6967): Finished books sync
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 296221, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/WifiStateMachine( 1039):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,E/WifiStateMachine( 1039):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 317372498893; DSPS: 10540638; Offset : -4313812857
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{3344f715 type 2 when 326459 android} when 326459
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 337374691020; DSPS: 11196070; Offset : -4313817838
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=1034035626, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,D/[Concierge]Service( 2631): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=1034035626 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 357376773722; DSPS: 11851498; Offset : -4313810385
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 6280): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6280): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6280): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6280): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6280): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6280): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6280): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{25f17803 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/System  ( 6280): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  312): res_queryN name = play.googleapis.com succeed
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 377378655641; DSPS: 12506919; Offset : -4313790141
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 397380877457; DSPS: 13162352; Offset : -4313796056
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 417384277866; DSPS: 13817824; Offset : -4313813590
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 437386149628; DSPS: 14473245; Offset : -4313803452
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 457388422433; DSPS: 15128680; Offset : -4313819388
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 477390700760; DSPS: 15784114; Offset : -4313799413
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 497392476116; DSPS: 16439532; Offset : -4313794052
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 517394627150; DSPS: 17094963; Offset : -4313809818
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 537396726153; DSPS: 17750392; Offset : -4313816423
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=1034035626, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{2a87e9ef type 2 when 548640 android} when 548640
D/[Concierge]Service( 2631): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=1034035626 [*alarm*], flags=0x0
,I/BooksSync( 6967): Starting books sync
,D/BooksSync( 6967): started syncMyEbooks
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
,D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6967): Authentication error
E/BooksAccountManager( 6967): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6967): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6967): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6967): null auth token
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1419): Notification difference=198
D/libc-netbsd(  312): res_queryN name = www.googleapis.com succeed
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{25f17803 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6967): Error response from books API: {
W/ApiaryClient( 6967):  "error": {
W/ApiaryClient( 6967):   "errors": [
W/ApiaryClient( 6967):    {
W/ApiaryClient( 6967):     "domain": "global",
W/ApiaryClient( 6967):     "reason": "required",
W/ApiaryClient( 6967):     "message": "Login Required",
W/ApiaryClient( 6967):     "locationType": "header",
W/ApiaryClient( 6967):     "location": "Authorization"
W/ApiaryClient( 6967):    }
W/ApiaryClient( 6967):   ],
W/ApiaryClient( 6967):   "code": 401,
W/ApiaryClient( 6967):   "message": "Login Required"
W/ApiaryClient( 6967):  }
W/ApiaryClient( 6967): }
W/ApiaryClient( 6967): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6967): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5131949924853536282&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6967): Headers:
W/ApiaryClient( 6967): accept-encoding: [gzip]
W/ApiaryClient( 6967): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6967): gdata-version: 2
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6967): Authentication error
E/BooksAccountManager( 6967): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6967): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6967): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6967): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{25f17803 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6967): Error response from books API: {
W/ApiaryClient( 6967):  "error": {
W/ApiaryClient( 6967):   "errors": [
W/ApiaryClient( 6967):    {
W/ApiaryClient( 6967):     "domain": "global",
W/ApiaryClient( 6967):     "reason": "required",
W/ApiaryClient( 6967):     "message": "Login Required",
W/ApiaryClient( 6967):     "locationType": "header",
W/ApiaryClient( 6967):     "location": "Authorization"
W/ApiaryClient( 6967):    }
W/ApiaryClient( 6967):   ],
W/ApiaryClient( 6967):   "code": 401,
W/ApiaryClient( 6967):   "message": "Login Required"
W/ApiaryClient( 6967):  }
W/ApiaryClient( 6967): }
,W/ApiaryClient( 6967): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6967): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5131949924853536282&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6967): Headers:
W/ApiaryClient( 6967): accept-encoding: [gzip]
W/ApiaryClient( 6967): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6967): gdata-version: 2
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 30089(1362KB) AllocSpace objects, 9(1168KB) LOS objects, 33% free, 44MB/66MB, paused 2.809ms total 145.157ms
,V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6967): Authentication error
E/BooksAccountManager( 6967): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6967): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6967): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6967): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{25f17803 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6967): Error response from books API: {
W/ApiaryClient( 6967):  "error": {
W/ApiaryClient( 6967):   "errors": [
W/ApiaryClient( 6967):    {
W/ApiaryClient( 6967):     "domain": "global",
W/ApiaryClient( 6967):     "reason": "required",
W/ApiaryClient( 6967):     "message": "Login Required",
W/ApiaryClient( 6967):     "locationType": "header",
W/ApiaryClient( 6967):     "location": "Authorization"
W/ApiaryClient( 6967):    }
W/ApiaryClient( 6967):   ],
W/ApiaryClient( 6967):   "code": 401,
W/ApiaryClient( 6967):   "message": "Login Required"
W/ApiaryClient( 6967):  }
W/ApiaryClient( 6967): }
,W/ApiaryClient( 6967): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6967): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5131949924853536282&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6967): Headers:
W/ApiaryClient( 6967): accept-encoding: [gzip]
W/ApiaryClient( 6967): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6967): gdata-version: 2
E/BooksSync( 6967): Soft error: 
E/BooksSync( 6967): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6967): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5131949924853536282&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6967): Headers:
E/BooksSync( 6967): accept-encoding: [gzip]
E/BooksSync( 6967): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6967): gdata-version: 2
E/BooksSync( 6967): 
E/BooksSync( 6967): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6967): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6967): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6967): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6967): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6967): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6967): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6967): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6967): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6967): {
E/BooksSync( 6967):  "error": {
E/BooksSync( 6967):   "errors": [
E/BooksSync( 6967):    {
E/BooksSync( 6967):     "domain": "global",
E/BooksSync( 6967):     "reason": "required",
E/BooksSync( 6967):     "message": "Login Required",
E/BooksSync( 6967):     "locationType": "header",
E/BooksSync( 6967):     "location": "Authorization"
E/BooksSync( 6967):    }
E/BooksSync( 6967):   ],
E/BooksSync( 6967):   "code": 401,
E/BooksSync( 6967):   "message": "Login Required"
E/BooksSync( 6967):  }
E/BooksSync( 6967): }
E/BooksSync( 6967): 
E/BooksSync( 6967): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6967): 	... 8 more
,E/BooksSync( 6967): Sync error
E/BooksSync( 6967): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6967): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=5131949924853536282&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6967): Headers:
E/BooksSync( 6967): accept-encoding: [gzip]
E/BooksSync( 6967): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6967): gdata-version: 2
E/BooksSync( 6967): 
E/BooksSync( 6967): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6967): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6967): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6967): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6967): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6967): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6967): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6967): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6967): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6967): {
E/BooksSync( 6967):  "error": {
E/BooksSync( 6967):   "errors": [
E/BooksSync( 6967):    {
E/BooksSync( 6967):     "domain": "global",
E/BooksSync( 6967):     "reason": "required",
E/BooksSync( 6967):     "message": "Login Required",
E/BooksSync( 6967):     "locationType": "header",
E/BooksSync( 6967):     "location": "Authorization"
E/BooksSync( 6967):    }
E/BooksSync( 6967):   ],
E/BooksSync( 6967):   "code": 401,
E/BooksSync( 6967):   "message": "Login Required"
E/BooksSync( 6967):  }
E/BooksSync( 6967): }
E/BooksSync( 6967): 
E/BooksSync( 6967): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6967): 	... 8 more
I/BooksSync( 6967): Finished books sync
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 548640, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 557398825312; DSPS: 18405820; Offset : -4313792720
,I/jxcore-log( 7114): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log(, 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, ,CoordinatorConnector start_tests called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): got start_tests event with data : {"data":{"devices":{"ios":4,"android":20}}}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"end","test":0}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"test connectionTable table building and cleanup","id":1}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): DB value for ThaliReplicationManager is: "bogus"
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":1,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":1,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":1,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":1,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":{"muxPort":60,"time":1448283291284},"expected":true,"test":1,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":9,"ok":true,"name":"Cleanup was called, this table is no longer live.","operator":"throws","actual":{"message":"Cleanup was called, this table is no longer live."},"test":1,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"end","test":1}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":2}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: undefined : test connectionTable table building and cleanup", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : Cleanup was called, this table is no longer live.", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":2}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":3}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":3}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"test connectionTable emitting events for peerIds","id":4}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): DB value for ThaliReplicationManager is: "bogus"
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":30,"expected":30,"test":4,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":40,"expected":40,"test":4,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":50,"expected":50,"test":4,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":60,"expected":60,"test":4,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":true,"expected":true,"test":4,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"end","test":4}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"teardown","id":5}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 4 isOK: undefined : test connectionTable emitting events for peerIds", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 5 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 577401727284; DSPS: 19061276; Offset : -4313820332
,I/jxcore-log( 7114): {"type":"end","test":5}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":6}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 6 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{28eaf1e1 type 2 when 578842 android} when 578842
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
I/jxcore-log( 7114): {"type":"end","test":6}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"start with bad friendly names","id":7}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":3,"ok":true,"name":"should not be equal","operator":"notEqual","actual":{},"test":7,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"end","test":7}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":8}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 7 isOK: undefined : start with bad friendly names", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 8 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"type":"end","test":8}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":9}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 9 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"type":"end","test":9}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"make sure startIdentityExchange sets things up properly","id":10}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 10 isOK: undefined : make sure startIdentityExchange sets things up properly", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: dnrCxYXw5mZRxBHccTbASw==;Matt
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":34625,"expected":34625,"test":10,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":10,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"dnrCxYXw5mZRxBHccTbASw==;Matt","expected":"dnrCxYXw5mZRxBHccTbASw==;Matt","test":10,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"123","expected":"123","test":10,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":"bar1","expected":"bar1","test":10,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":10,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"456","expected":"456","test":10,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":"bar2","expected":"bar2","test":10,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"started","expected":"started","test":10,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"end","test":10}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":11}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 11 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":11}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":12}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 12 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":12}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"make sure we get an error if we call start and then immediately call stop","id":13}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state startIdentityExchangeCalledCB","test":13,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"end","test":13}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":14}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: P3hGFUKnVH0dUWhtj6iIpw==;Toby
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":53901,"expected":53901,"test":13,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":13,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"P3hGFUKnVH0dUWhtj6iIpw==;Toby","expected":"P3hGFUKnVH0dUWhtj6iIpw==;Toby","test":13,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":null,"expected":null,"test":13,"type":"assert"}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 13 isOK: undefined : make sure we get an error if we call start and then immediately call stop", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 14 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 597403824932; DSPS: 19716704; Offset : -4313797957
,I/jxcore-log( 7114): {"type":"end","test":14}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":15}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 15 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":15}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"Make sure stop is clean from start","id":16}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: oo8h2XDcFdlBdaIIXsjn5Q==;Luke
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":39388,"expected":39388,"test":16,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":16,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"oo8h2XDcFdlBdaIIXsjn5Q==;Luke","expected":"oo8h2XDcFdlBdaIIXsjn5Q==;Luke","test":16,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":3,"ok":true,"name":"Should not have gotten error on startIdentityExchange","operator":"notOk","actual":null,"expected":false,"test":16,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":4,"ok":true,"name":"Should not have gotten error on stopIdentityExchange","operator":"notOk","expected":false,"test":16,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":5,"ok":true,"name":"State should be Stopped","operator":"equal","actual":"stopped","expected":"stopped","test":16,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"end","test":16}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":17}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 16 isOK: undefined : Make sure stop is clean from start", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : Should not have gotten error on startIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : Should not have gotten error on stopIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : State should be Stopped", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 17 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"type":"end","test":17}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":18}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 18 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"type":"end","test":18}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"Make sure stop is clean from stop execute identity exchange","id":19}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: AC7qQLEvX0BKgN/p3pMH9A==;Jukka
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":54489,"expected":54489,"test":19,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":19,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"AC7qQLEvX0BKgN/p3pMH9A==;Jukka","expected":"AC7qQLEvX0BKgN/p3pMH9A==;Jukka","test":19,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":19,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":4,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":19,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"stopped","expected":"stopped","test":19,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"end","test":19}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":20}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 19 isOK: undefined : Make sure stop is clean from stop execute identity exchange", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 20 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"type":"end","test":20}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":21}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 21 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"type":"end","test":21}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange","id":22}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: bX7GIY7a8j0VCrQiTB1nGQ==;Doug
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":43129,"expected":43129,"test":22,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":22,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"bX7GIY7a8j0VCrQiTB1nGQ==;Doug","expected":"bX7GIY7a8j0VCrQiTB1nGQ==;Doug","test":22,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":4,"ok":true,"name":"should not throw","operator":"throws","test":22,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":false,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":22,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"end","test":22}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":23}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 22 isOK: undefined : make sure we do not have a race condition between startIdentityExchange and executeIdentityExchange", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should not throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 23 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 617406027112; DSPS: 20372136; Offset : -4313792834
,I/jxcore-log( 7114): {"type":"end","test":23}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":24}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 24 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"type":"end","test":24}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"illegal method combinations","id":25}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: XA9zIMttsMuFFxb0/XZJsg==;David
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":34629,"expected":34629,"test":25,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"XA9zIMttsMuFFxb0/XZJsg==;David","expected":"XA9zIMttsMuFFxb0/XZJsg==;David","test":25,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":6,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":7,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":8,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":9,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":25,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":10,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":11,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state wait","test":25,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: XA9zIMttsMuFFxb0/XZJsg==;David
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":34629,"expected":34629,"test":25,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":25,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":14,"ok":true,"name":"should be equal","operator":"equal","actual":"XA9zIMttsMuFFxb0/XZJsg==;David","expected":"XA9zIMttsMuFFxb0/XZJsg==;David","test":25,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":15,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":25,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":16,"ok":true,"name":"should throw","operator":"throws","actual":"event executeIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":17,"ok":true,"name":"should throw","operator":"throws","actual":"event stopIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":18,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state exchangeIdentity","test":25,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":19,"ok":true,"name":"should throw","operator":"throws","actual":"event stopExecutingIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":20,"ok":true,"name":"should throw","operator":"throws","actual":"event startIdentityExchangeCalled inappropriate in current state findPeersDoingIdentityExchange","test":25,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"end","test":25}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":26}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 25 isOK: undefined : illegal method combinations", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 26 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"type":"end","test":26}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":27}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 27 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":27}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"do an identity exchange and get code multiple times to make sure we do not hork state","id":28}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: P7g+Mjvnsb1hrqoAEXmE3Q==;John
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":57810,"expected":57810,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","expected":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: qtKCeffabaov5foGmq1xfw==;Srikanth
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":39199,"expected":39199,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"qtKCeffabaov5foGmq1xfw==;Srikanth","expected":"qtKCeffabaov5foGmq1xfw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":7,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/cb request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 28 isOK: undefined : do an identity exchange and get code multiple times to make sure we do not hork state", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/rnmine request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":9,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":10,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":11,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":134784,"expected":134784,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":13,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: P7g+Mjvnsb1hrqoAEXmE3Q==;John
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":57810,"expected":57810,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":17,"ok":true,"name":"should be equal","operator":"equal","actual":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","expected":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":18,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: qtKCeffabaov5foGmq1xfw==;Srikanth
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":39199,"expected":39199,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":20,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"qtKCeffabaov5foGmq1xfw==;Srikanth","expected":"qtKCeffabaov5foGmq1xfw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":22,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/cb request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 21 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 22 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/rnmine request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":24,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":25,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":26,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":239040,"expected":239040,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":28,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: P7g+Mjvnsb1hrqoAEXmE3Q==;John
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":57810,"expected":57810,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":32,"ok":true,"name":"should be equal","operator":"equal","actual":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","expected":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":33,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: qtKCeffabaov5foGmq1xfw==;Srikanth
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":39199,"expected":39199,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":35,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"qtKCeffabaov5foGmq1xfw==;Srikanth","expected":"qtKCeffabaov5foGmq1xfw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":37,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/cb request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 23 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 24 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 25 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 26 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 27 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 28 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 29 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 30 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/rnmine request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 31 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 32 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 33 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 34 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 35 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 36 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 37 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":39,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":40,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":41,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":825536,"expected":825536,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":43,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: P7g+Mjvnsb1hrqoAEXmE3Q==;John
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":57810,"expected":57810,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":47,"ok":true,"name":"should be equal","operator":"equal","actual":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","expected":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":48,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: qtKCeffabaov5foGmq1xfw==;Srikanth
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":39199,"expected":39199,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":50,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"qtKCeffabaov5foGmq1xfw==;Srikanth","expected":"qtKCeffabaov5foGmq1xfw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":52,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/cb request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 38 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 39 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 40 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 41 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 42 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 43 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 44 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 45 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 46 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 47 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 48 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 49 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 50 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 51 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 52 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/rnmine request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":54,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":55,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":56,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":877696,"expected":877696,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":58,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: P7g+Mjvnsb1hrqoAEXmE3Q==;John
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":57810,"expected":57810,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":62,"ok":true,"name":"should be equal","operator":"equal","actual":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","expected":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":63,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: qtKCeffabaov5foGmq1xfw==;Srikanth
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":39199,"expected":39199,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":65,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"qtKCeffabaov5foGmq1xfw==;Srikanth","expected":"qtKCeffabaov5foGmq1xfw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":67,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/cb request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 53 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 54 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 55 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 56 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 57 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 58 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 59 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 60 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 61 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 62 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 63 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 64 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 65 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 66 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 67 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/rnmine request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":69,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":70,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":71,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":562560,"expected":562560,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":73,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: P7g+Mjvnsb1hrqoAEXmE3Q==;John
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":75,"ok":true,"name":"should be equal","operator":"equal","actual":57810,"expected":57810,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":76,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":77,"ok":true,"name":"should be equal","operator":"equal","actual":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","expected":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":78,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: qtKCeffabaov5foGmq1xfw==;Srikanth
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":79,"ok":true,"name":"should be equal","operator":"equal","actual":39199,"expected":39199,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":80,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":81,"ok":true,"name":"should be equal","operator":"equal","actual":"qtKCeffabaov5foGmq1xfw==;Srikanth","expected":"qtKCeffabaov5foGmq1xfw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":82,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/cb request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 68 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 69 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 70 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 71 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 72 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 73 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 74 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/rnmine request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 75 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 76 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 77 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 78 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 79 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 80 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 81 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 82 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"id":83,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":84,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":85,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":86,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":87,"ok":true,"name":"should be equal","operator":"equal","actual":271488,"expected":271488,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":88,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":89,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: P7g+Mjvnsb1hrqoAEXmE3Q==;John
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":90,"ok":true,"name":"should be equal","operator":"equal","actual":57810,"expected":57810,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":91,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":92,"ok":true,"name":"should be equal","operator":"equal","actual":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","expected":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":93,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: qtKCeffabaov5foGmq1xfw==;Srikanth
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":94,"ok":true,"name":"should be equal","operator":"equal","actual":39199,"expected":39199,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":95,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":96,"ok":true,"name":"should be equal","operator":"equal","actual":"qtKCeffabaov5foGmq1xfw==;Srikanth","expected":"qtKCeffabaov5foGmq1xfw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":97,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/cb request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 83 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 84 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 85 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 86 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 87 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 88 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 89 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 90 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 91 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 92 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 93 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 94 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 95 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/rnmine request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 96 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 97 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"id":98,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":99,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":100,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":101,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":102,"ok":true,"name":"should be equal","operator":"equal","actual":829376,"expected":829376,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":103,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":104,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: P7g+Mjvnsb1hrqoAEXmE3Q==;John
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":105,"ok":true,"name":"should be equal","operator":"equal","actual":57810,"expected":57810,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":106,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":107,"ok":true,"name":"should be equal","operator":"equal","actual":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","expected":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":108,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: qtKCeffabaov5foGmq1xfw==;Srikanth
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":109,"ok":true,"name":"should be equal","operator":"equal","actual":39199,"expected":39199,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":110,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":111,"ok":true,"name":"should be equal","operator":"equal","actual":"qtKCeffabaov5foGmq1xfw==;Srikanth","expected":"qtKCeffabaov5foGmq1xfw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":112,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/cb request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 98 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 99 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 100 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 101 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 102 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 103 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 104 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 105 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 106 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 107 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 108 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/rnmine request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 109 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 110 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 111 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 112 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"id":113,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":114,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":115,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":116,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":117,"ok":true,"name":"should be equal","operator":"equal","actual":725248,"expected":725248,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":118,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":119,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: P7g+Mjvnsb1hrqoAEXmE3Q==;John
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":120,"ok":true,"name":"should be equal","operator":"equal","actual":57810,"expected":57810,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":121,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":122,"ok":true,"name":"should be equal","operator":"equal","actual":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","expected":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":123,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: qtKCeffabaov5foGmq1xfw==;Srikanth
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":124,"ok":true,"name":"should be equal","operator":"equal","actual":39199,"expected":39199,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":125,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":126,"ok":true,"name":"should be equal","operator":"equal","actual":"qtKCeffabaov5foGmq1xfw==;Srikanth","expected":"qtKCeffabaov5foGmq1xfw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":127,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/cb request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 113 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 114 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 115 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 116 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/rnmine request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 117 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 118 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 119 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 120 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 121 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 122 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 123 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"id":128,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":129,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 124 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 125 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 126 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 127 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"id":130,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":131,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":132,"ok":true,"name":"should be equal","operator":"equal","actual":136512,"expected":136512,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":133,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":134,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: P7g+Mjvnsb1hrqoAEXmE3Q==;John
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":135,"ok":true,"name":"should be equal","operator":"equal","actual":57810,"expected":57810,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":136,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":137,"ok":true,"name":"should be equal","operator":"equal","actual":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","expected":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":138,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: qtKCeffabaov5foGmq1xfw==;Srikanth
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":139,"ok":true,"name":"should be equal","operator":"equal","actual":39199,"expected":39199,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":140,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":141,"ok":true,"name":"should be equal","operator":"equal","actual":"qtKCeffabaov5foGmq1xfw==;Srikanth","expected":"qtKCeffabaov5foGmq1xfw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":142,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/cb request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 128 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 129 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 130 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 131 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 132 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 133 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 134 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 135 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 136 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 137 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 138 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 139 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 140 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 141 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 142 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO smallerHash Making /identity/rnmine request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":143,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":144,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":145,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":146,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":147,"ok":true,"name":"should be equal","operator":"equal","actual":557760,"expected":557760,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":148,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":149,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: P7g+Mjvnsb1hrqoAEXmE3Q==;John
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":150,"ok":true,"name":"should be equal","operator":"equal","actual":57810,"expected":57810,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":151,"ok":true,"name":"should be equal","operator":"equal","actual":"dbName","expected":"dbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":152,"ok":true,"name":"should be equal","operator":"equal","actual":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","expected":"P7g+Mjvnsb1hrqoAEXmE3Q==;John","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":153,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO identityExchange We will advertise the following device name as we start: qtKCeffabaov5foGmq1xfw==;Srikanth
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":154,"ok":true,"name":"should be equal","operator":"equal","actual":39199,"expected":39199,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":155,"ok":true,"name":"should be equal","operator":"equal","actual":"anotherDbName","expected":"anotherDbName","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":156,"ok":true,"name":"should be equal","operator":"equal","actual":"qtKCeffabaov5foGmq1xfw==;Srikanth","expected":"qtKCeffabaov5foGmq1xfw==;Srikanth","test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":157,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/cb request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 143 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 144 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 145 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 146 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 147 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 148 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 149 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 150 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 151 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 152 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 153 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 154 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 155 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 156 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): INFO smallerHash cbRequest Succeeded!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO smallerHash Making /identity/rnmine request to pkOther value qtKCeffabaov5foGmq1xfw==
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 157 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"id":158,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":159,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":160,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":161,"ok":true,"name":"We got a code, did it check out?","operator":"ok","actual":true,"expected":true,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":162,"ok":true,"name":"should be equal","operator":"equal","actual":656064,"expected":656064,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":163,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":164,"ok":true,"name":"(unnamed assert)","operator":"notOk","expected":false,"test":28,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"end","test":28}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":29}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 158 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 159 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 160 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 161 isOK: true : We got a code, did it check out?", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 162 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 163 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 164 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 29 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 637408169292; DSPS: 21027567; Offset : -4313817481
,I/jxcore-log( 7114): {"type":"end","test":29}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":30}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 30 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=1034035626, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,D/[Concierge]Service( 2631): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=1034035626 [*alarm*], flags=0x0
,I/ActivityManager( 1039): Killing 6895:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10005/pid_6895/cgroup.procs: No such file or directory
,I/jxcore-log( 7114): {"type":"end","test":30}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"test compareEqualSizeBuffers","id":31}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":2,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":3,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"buffer1 and buffer2 have to actually be buffers"},"test":31,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":4,"ok":true,"name":"should throw","operator":"throws","actual":{"message":"Buffers must be of the same size."},"test":31,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":5,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":-1,"expected":-1,"test":31,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":8,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":0,"expected":0,"test":31,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":11,"ok":true,"name":"should be equal","operator":"equal","actual":1,"expected":1,"test":31,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"end","test":31}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":32}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 31 isOK: undefined : test compareEqualSizeBuffers", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should throw", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 32 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":32}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":33}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 33 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 657410418816; DSPS: 21683000; Offset : -4313795661
,I/jxcore-log( 7114): {"type":"end","test":33}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"Make sure we return 404 before hitting start","id":34}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 34 isOK: undefined : Make sure we return 404 before hitting start", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":34,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"end","test":34}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":35}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 35 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":35}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":36}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 36 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":36}
I/jxcore-log( 7114): 
,E/jxcore-log( 7114): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 7114): 
,E/jxcore-log( 7114): Trace: 
E/jxcore-log( 7114):     at Console.prototype.trace@console.js:169:13
E/jxcore-log( 7114):     at addListener@events.js:140:7
E/jxcore-log( 7114):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:61:3
E/jxcore-log( 7114):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 7114):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 7114):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 7114):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 7114):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
E/jxcore-log( 7114): (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
E/jxcore-log( 7114): 
E/jxcore-log( 7114): Trace: 
E/jxcore-log( 7114):     at Console.prototype.trace@console.js:169:13
E/jxcore-log( 7114):     at addListener@events.js:140:7
E/jxcore-log( 7114):     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/pouchdb-all-dbs/index.js:85:3
E/jxcore-log( 7114):     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:138:9
E/jxcore-log( 7114):     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/util.js:26:16
E/jxcore-log( 7114):     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:507:13
E/jxcore-log( 7114):     at module.exports/Promise.prototype._settlePromiseAt@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/main/promise.js:581:13
E/jxcore-log( 7114):     at module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/
I/jxcore-log( 7114): {"type":"test","name":"Random path after start, need 404","id":37}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 37 isOK: undefined : Random path after start, need 404", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":37,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"end","test":37}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":38}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 38 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":38}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":39}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 39 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":39}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"Confirm we go to wrongPeer if our hash is smaller","id":40}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"WrongPeer","expected":"WrongPeer","test":40,"type":"assert"}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 40 isOK: undefined : Confirm we go to wrongPeer if our hash is smaller", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":40,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"ad45wQBTHU3Hl7TpWUcZMw==","expected":"ad45wQBTHU3Hl7TpWUcZMw==","test":40,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":40,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"end","test":40}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":41}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 41 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 677412525423; DSPS: 22338429; Offset : -4313794845
,I/jxcore-log( 7114): {"type":"end","test":41}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":42}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 42 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":42}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"Confirm we go to wrongPeer if our hash is smaller","id":43}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"WrongPeer","expected":"WrongPeer","test":43,"type":"assert"}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 43 isOK: undefined : Confirm we go to wrongPeer if our hash is smaller", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":43,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":"aHdf2RgEmBL8+HhZBKBoJg==","expected":"aHdf2RgEmBL8+HhZBKBoJg==","test":43,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":3,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":43,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"end","test":43}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":44}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 44 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":44}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":45}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 45 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 697415759842; DSPS: 22993895; Offset : -4313795289
,I/jxcore-log( 7114): {"type":"end","test":45}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"Confirm we get wrongPeer on cb if we give hash other than expected","id":46}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 46 isOK: undefined : Confirm we get wrongPeer on cb if we give hash other than expected", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"wrongPeer","expected":"wrongPeer","test":46,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"83aUrtlCFORfjq+GKjy73A==","expected":"83aUrtlCFORfjq+GKjy73A==","test":46,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":46,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"end","test":46}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":47}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 47 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":47}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":48}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 48 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
I/jxcore-log( 7114): {"type":"end","test":48}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"Confirm we get Skip Ahead even with a wrong peer on a rnMine request (and we can argue if this is a good choice)","id":49}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 49 isOK: undefined : Confirm we get Skip Ahead even with a wrong peer on a rnMine request (and we can argue if this is a good choice)", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"skippedAhead","expected":"skippedAhead","test":49,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"W81f9bgd9NOmfv/xA0bkZw==","expected":"W81f9bgd9NOmfv/xA0bkZw==","test":49,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":49,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"end","test":49}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":50}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":50}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"setup","id":51}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 50 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 51 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 717417351241; DSPS: 23649307; Offset : -4313790753
,I/jxcore-log( 7114): {"type":"end","test":51}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"NoIdentityExchange after start & stop","id":52}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 52 isOK: undefined : NoIdentityExchange after start & stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"9poKdHVa4Y4E5hTwLY7YpQ==","expected":"9poKdHVa4Y4E5hTwLY7YpQ==","test":52,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":2,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:53596/identity/cb","data":{"cbValue":"Z6zmsquQTpQmOB+fIhTKaprPf/BDD8KYuN9Q0G0LkSI=","pkMine":"HLmsrI+AS8813PX+Zj1O5A=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-YgwNXubLfJ7jfnvuqarlTw\"","date":"Mon, 23 Nov 2015 12:57:23 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"9poKdHVa4Y4E5hTwLY7YpQ==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"9poKdHVa4Y4E5hTwLY7YpQ==","expected":"9poKdHVa4Y4E5hTwLY7YpQ==","test":52,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":5,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:43531/identity/rnmine","data":{"rnMine":"tSKzIVy/LDp/N38ap6AJYg==","pkOther":"Yjq7lx1bo4AovImsB+aJaw=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-YgwNXubLfJ7jfnvuqarlTw\"","date":"Mon, 23 Nov 2015 12:57:23 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"9poKdHVa4Y4E5hTwLY7YpQ==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"9poKdHVa4Y4E5hTwLY7YpQ==","expected":"9poKdHVa4Y4E5hTwLY7YpQ==","test":52,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":8,"ok":true,"name":{"req":{"method":"post","url":"http://127.0.0.1:53555/identity/cb","data":{"cbValue":"P3ScMK51W5g/yjGiBQ8wfSmcvyZb14cgCrSrOQ1culc=","pkMine":"SMPvRXKf8jppbanp8oCQzw=="}},"header":{"x-powered-by":"Express","content-type":"application/json; charset=utf-8","content-length":"77","etag":"W/\"4d-YgwNXubLfJ7jfnvuqarlTw\"","date":"Mon, 23 Nov 2015 12:57:23 GMT","connection":"close"},"status":400,"text":"{\"errorCode\":\"notDoingIdentityExchange\",\"pkOther\":\"9poKdHVa4Y4E5hTwLY7YpQ==\"}"},"operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":"notDoingIdentityExchange","expected":"notDoingIdentityExchange","test":52,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"9poKdHVa4Y4E5hTwLY7YpQ==","expected":"9poKdHVa4Y4E5hTwLY7YpQ==","test":52,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":11,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":52,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"end","test":52}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":53}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : [object Object]", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 53 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":53}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":54}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 54 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":54}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"cbRequest - bad request bodies","id":55}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 55 isOK: undefined : cbRequest - bad request bodies", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":" ","pkMine":"XAxqMQQp8Sl+IG//0XgYzg=="}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"{@#{$@#{$","pkMine":"oSxEKxIHbhdRRGHq0G0/eA=="}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"salkDUoL623HgsXc+w6s8EEoTU2fMNdneuwF+TklaHXi","pkMine":"PZ/IZOr6Wj0H/7xbAnoQtw=="}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a cb request with a bum cbValue - {"cbValue":"C3RKzILWCjpO1ArApi0fnFyrXDgvxuLEBfvnOxZSAQ==","pkMine":"NF9PODn49814Y2NIAJYFng=="}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"RFcs7MYZuBCSWZ4wfTZQB6IHTLP7bfT/Zdcpof/YwDI=","pkMine":" "}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"FCww73+/4k2QqxgW4IWvhwUA6K/E85ByVgSWjFFYors=","pkMine":"{@#{$@#{$"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"st8Z/VBIvt9Z3IAV9ZZSE1oI8lf+8swLlUnrIEoOPgQ=","pkMine":"nD/2Wyolt4TH/wHsYt3wlM8="}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"b9HEJXdtAxQC1nhO/nWZLFnnGXnTeVyBubTMJQcLgX0=","pkMine":"voXSepTRC7OTMqLLP2pM"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":" "}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"{@#{$@#{$"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"nD/2Wyolt4TH/wHsYt3wlM8="}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":" ","pkMine":"voXSepTRC7OTMqLLP2pM"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":" "}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"{@#{$@#{$"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"nD/2Wyolt4TH/wHsYt3wlM8="}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"{@#{$@#{$","pkMine":"voXSepTRC7OTMqLLP2pM"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"salkDUoL623HgsXc+w6s8EEoTU2fMNdneuwF+TklaHXi","pkMine":" "}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"salkDUoL623HgsXc+w6s8EEoTU2fMNdneuwF+TklaHXi","pkMine":"{@#{$@#{$"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"salkDUoL623HgsXc+w6s8EEoTU2fMNdneuwF+TklaHXi","pkMine":"nD/2Wyolt4TH/wHsYt3wlM8="}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"salkDUoL623HgsXc+w6s8EEoTU2fMNdneuwF+TklaHXi","pkMine":"voXSepTRC7OTMqLLP2pM"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"C3RKzILWCjpO1ArApi0fnFyrXDgvxuLEBfvnOxZSAQ==","pkMine":" "}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"C3RKzILWCjpO1ArApi0fnFyrXDgvxuLEBfvnOxZSAQ==","pkMine":"{@#{$@#{$"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"C3RKzILWCjpO1ArApi0fnFyrXDgvxuLEBfvnOxZSAQ==","pkMine":"nD/2Wyolt4TH/wHsYt3wlM8="}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {"cbValue":"C3RKzILWCjpO1ArApi0fnFyrXDgvxuLEBfvnOxZSAQ==","pkMine":"voXSepTRC7OTMqLLP2pM"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): INFO largerHash Got a /identity/cb request with a bum pkMine - {}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":5,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":6,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":7,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":8,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":9,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":10,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":11,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":12,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":13,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":14,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":15,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":16,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":17,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":18,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":19,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":20,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":21,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":22,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":23,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): ,
,I/jxcore-log( 7114): {"id":24,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":25,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":26,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":27,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":28,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":29,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":30,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":31,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":32,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":33,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":34,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":35,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":36,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":37,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":38,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":39,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":40,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":41,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":42,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":43,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":44,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":45,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":46,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":47,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":48,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":49,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":50,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":51,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":52,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":53,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":54,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":55,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":56,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":57,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":58,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":59,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":60,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":61,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":62,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":63,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":64,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":65,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":66,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":67,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":68,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":69,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":70,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":71,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":72,"ok":true,"name":"should be equal","operator":"equal","actual":"malformed","expected":"malformed","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":73,"ok":true,"name":"should be equal","operator":"equal","actual":"2Z0pCGjSf/NZmvEDTiUt/g==","expected":"2Z0pCGjSf/NZmvEDTiUt/g==","test":55,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":74,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":55,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"end","test":55}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":56}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 5 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 6 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 7 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 8 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 9 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 10 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 11 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 12 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 13 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 14 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 15 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 16 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 17 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 18 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 19 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 20 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 21 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 22 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 23 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 24 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 25 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 26 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 27 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 28 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 29 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 30 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 31 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 32 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 33 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 34 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 35 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 36 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 37 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 38 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 39 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 40 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 41 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 42 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 43 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 44 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 45 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 46 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 47 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 48 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 49 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 50 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 51 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 52 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 53 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 54 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 55 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 56 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 57 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 58 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 59 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 60 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 61 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 62 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 63 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 64 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 65 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 66 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 67 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 68 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 69 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 70 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 71 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 72 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 73 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 74 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 56 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"type":"end","test":56}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":57}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 57 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 737419525556; DSPS: 24304739; Offset : -4313813859
,I/jxcore-log( 7114): {"type":"end","test":57}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"re-do cb (to check we can reset) and make sure rnOther changes","id":58}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 58 isOK: undefined : re-do cb (to check we can reset) and make sure rnOther changes", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 7114): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"1BLrdbpgf10ebifAU1cDYg==","expected":true,"test":58,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"0d8wcU3uZ5nbP4onqQSUNg==","expected":"0d8wcU3uZ5nbP4onqQSUNg==","test":58,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":2,"ok":true,"name":"should not be equal","operator":"notEqual","actual":"1BLrdbpgf10ebifAU1cDYg==","test":58,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":"0d8wcU3uZ5nbP4onqQSUNg==","expected":"0d8wcU3uZ5nbP4onqQSUNg==","test":58,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":4,"ok":true,"name":"should be equal","operator":"equal","actual":"0d8wcU3uZ5nbP4onqQSUNg==","expected":"0d8wcU3uZ5nbP4onqQSUNg==","test":58,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"end","test":58}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"teardown","id":59}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 4 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 59 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":59}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":60}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 60 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":60}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"good cb followed by good rnmine then repeat cb and finish up, make sure we have new rnOther","id":61}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 61 isOK: undefined : good cb followed by good rnmine then repeat cb and finish up, make sure we have new rnOther", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"NLRmw9ZuNUboXDpStnNhDw==","expected":true,"test":61,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should not be equal","operator":"notEqual","actual":"R7PDEk3TaLpIzSZcjF+zCA==","test":61,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":[71,179,195,18,77,211,104,186,72,205,38,92,140,95,179,8],"expected":true,"test":61,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":3,"ok":true,"name":"should be equal","operator":"equal","actual":243584,"expected":243584,"test":61,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"end","test":61}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":62}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should not be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 3 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 62 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":62}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":63}
I/jxcore-log( 7114): 
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 63 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":63}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"do a successful cb and successful rnmine and then repeat the rnmine","id":64}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 64 isOK: undefined : do a successful cb and successful rnmine and then repeat the rnmine", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"id":0,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":"rk+20dsV0Q+FdadL2g8Kdw==","expected":true,"test":64,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":1,"ok":true,"name":"(unnamed assert)","operator":"ok","actual":[174,79,182,209,219,21,209,15,133,117,167,75,218,15,10,119],"expected":true,"test":64,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":2,"ok":true,"name":"should be equal","operator":"equal","actual":710016,"expected":710016,"test":64,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"end","test":64}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":65}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 65 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/jxcore-log( 7114): {"type":"end","test":65}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"setup","id":66}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 66 isOK: undefined : setup", source: file:///android_asset/www/js/thali_main.js (63)
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 757422052736; DSPS: 24960182; Offset : -4313819560
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
I/jxcore-log( 7114): {"type":"end","test":66}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"type":"test","name":"do a rnmine without a cb","id":67}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 67 isOK: undefined : do a rnmine without a cb", source: file:///android_asset/www/js/thali_main.js (63)
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 777430157729; DSPS: 25615807; Offset : -4313799903
I/jxcore-log( 7114): {"id":0,"ok":true,"name":"should be equal","operator":"equal","actual":"skippedAhead","expected":"skippedAhead","test":67,"type":"assert"}
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): {"id":1,"ok":true,"name":"should be equal","operator":"equal","actual":"isBEvE4I11ifUSlI6L8rMQ==","expected":"isBEvE4I11ifUSlI6L8rMQ==","test":67,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"id":2,"ok":true,"name":"(unnamed assert)","operator":"notOk","actual":null,"expected":false,"test":67,"type":"assert"}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"end","test":67}
I/jxcore-log( 7114): 
I/jxcore-log( 7114): {"type":"test","name":"teardown","id":68}
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 1 isOK: true : should be equal", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 2 isOK: true : (unnamed assert)", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback undefined isOK: undefined : undefined", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 68 isOK: undefined : teardown", source: file:///android_asset/www/js/thali_main.js (63)
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 797431855898; DSPS: 26271223; Offset : -4313812540
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 817433940734; DSPS: 26926651; Offset : -4313802926
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 837436050153; DSPS: 27582080; Offset : -4313799221
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 857438579312; DSPS: 28237523; Offset : -4313802967
I/[SystemUI]LGPowerUI( 1464): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1464): On Skip Timer : true
,D/LEDHandler( 1967): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1967): Battery Level Remaining: 84%
D/LEDHandler( 1967): Battery Temp: 285, mChargingStatus=2, mChargingStop=false
,D/KeyguardUpdateMonitor( 1464): Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 84 ,temperature : 285
I/[SystemUI]LGPowerUI( 1464): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1039): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1464): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3774): Disconnected process message: 10, size: 0
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 877440624147; DSPS: 28892950; Offset : -4313802758
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=1034035626, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,I/ActivityManager( 1039): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7879 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2631): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7879): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7879): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@26038eec
D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=1034035626 [*alarm*], flags=0x0
I/ActivityManager( 1039): Killing 6280:com.android.vending/u0a44 (adj 15): empty #17
W/libprocessgroup( 1039): failed to open /acct/uid_10044/pid_6280/cgroup.procs: No such file or directory
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 897442525651; DSPS: 29548372; Offset : -4313793422
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 917444664966; DSPS: 30203802; Offset : -4313790260
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 937448135532; DSPS: 30859276; Offset : -4313798645
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{36c1bb06 type 2 when 941823 com.android.bluetooth} when 941823
,W/bt-smp  ( 3774): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3774): Plain text(LSB ~ MSB) = 97 b3 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3774): Encrypted text(LSB ~ MSB) = af 7e 63 75 0c 40 88 90 58 02 dc e1 35 a3 87 cc 
W/bt-btm  ( 3774): Stopping oneshot timer
I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 957450955524; DSPS: 31514729; Offset : -4313816892
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 977453085568; DSPS: 32170158; Offset : -4313792509
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 997455595301; DSPS: 32825601; Offset : -4313815553
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1017457618053; DSPS: 33481027; Offset : -4313807195
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1037459784712; DSPS: 34136458; Offset : -4313807206
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=1034035626, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{41ca5c7 type 2 when 1049399 android} when 1049399
D/[Concierge]Service( 2631): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=1034035626 [*alarm*], flags=0x0
,I/BooksSync( 6967): Starting books sync
,D/BooksSync( 6967): started syncMyEbooks
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
E/BooksAccountManager( 6967): Authentication error
E/BooksAccountManager( 6967): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6967): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6967): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6967): null auth token
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  312): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{25f17803 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/libc-netbsd(  312): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 6967): Error response from books API: {
W/ApiaryClient( 6967):  "error": {
W/ApiaryClient( 6967):   "errors": [
W/ApiaryClient( 6967):    {
W/ApiaryClient( 6967):     "domain": "global",
W/ApiaryClient( 6967):     "reason": "required",
W/ApiaryClient( 6967):     "message": "Login Required",
W/ApiaryClient( 6967):     "locationType": "header",
W/ApiaryClient( 6967):     "location": "Authorization"
W/ApiaryClient( 6967):    }
W/ApiaryClient( 6967):   ],
W/ApiaryClient( 6967):   "code": 401,
W/ApiaryClient( 6967):   "message": "Login Required"
W/ApiaryClient( 6967):  }
W/ApiaryClient( 6967): }
,W/ApiaryClient( 6967): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6967): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4336977037377914579&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6967): Headers:
W/ApiaryClient( 6967): accept-encoding: [gzip]
W/ApiaryClient( 6967): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6967): gdata-version: 2
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,D/LgeQuickCoverNLService( 1419): onNotificationPosted
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
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
,D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{25f17803 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,E/BooksAccountManager( 6967): Authentication error
E/BooksAccountManager( 6967): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6967): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6967): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6967): null auth token
W/ApiaryClient( 6967): Error response from books API: {
W/ApiaryClient( 6967):  "error": {
W/ApiaryClient( 6967):   "errors": [
W/ApiaryClient( 6967):    {
W/ApiaryClient( 6967):     "domain": "global",
W/ApiaryClient( 6967):     "reason": "required",
W/ApiaryClient( 6967):     "message": "Login Required",
W/ApiaryClient( 6967):     "locationType": "header",
W/ApiaryClient( 6967):     "location": "Authorization"
W/ApiaryClient( 6967):    }
W/ApiaryClient( 6967):   ],
W/ApiaryClient( 6967):   "code": 401,
W/ApiaryClient( 6967):   "message": "Login Required"
W/ApiaryClient( 6967):  }
W/ApiaryClient( 6967): }
,W/ApiaryClient( 6967): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6967): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4336977037377914579&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6967): Headers:
W/ApiaryClient( 6967): accept-encoding: [gzip]
W/ApiaryClient( 6967): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6967): gdata-version: 2
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2135): Explicit concurrent mark sweep GC freed 55504(3MB) AllocSpace objects, 28(3MB) LOS objects, 50% free, 30MB/62MB, paused 2.345ms total 68.052ms
,V/NotificationService( 1039): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1039): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1039): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1039): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1039): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
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
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1419): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1419): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1419): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1419): updateNotificationData: count=3
W/GLSActivity( 2135): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2135): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2135): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2135): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2135): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 6967): Authentication error
E/BooksAccountManager( 6967): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6967): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6967): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6967): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6967): null auth token
D/QuickStatusbarLayout( 1419): Notification difference=198
D/QuickStatusbarLayout( 1419): child = android.widget.LinearLayout{25f17803 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/ApiaryClient( 6967): Error response from books API: {
W/ApiaryClient( 6967):  "error": {
W/ApiaryClient( 6967):   "errors": [
W/ApiaryClient( 6967):    {
W/ApiaryClient( 6967):     "domain": "global",
W/ApiaryClient( 6967):     "reason": "required",
W/ApiaryClient( 6967):     "message": "Login Required",
W/ApiaryClient( 6967):     "locationType": "header",
W/ApiaryClient( 6967):     "location": "Authorization"
W/ApiaryClient( 6967):    }
W/ApiaryClient( 6967):   ],
W/ApiaryClient( 6967):   "code": 401,
W/ApiaryClient( 6967):   "message": "Login Required"
W/ApiaryClient( 6967):  }
W/ApiaryClient( 6967): }
,W/ApiaryClient( 6967): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized,
W/ApiaryClient( 6967): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4336977037377914579&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6967): Headers:
W/ApiaryClient( 6967): accept-encoding: [gzip]
W/ApiaryClient( 6967): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6967): gdata-version: 2
E/BooksSync( 6967): Soft error: 
E/BooksSync( 6967): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6967): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4336977037377914579&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6967): Headers:
E/BooksSync( 6967): accept-encoding: [gzip]
E/BooksSync( 6967): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6967): gdata-version: 2
E/BooksSync( 6967): 
E/BooksSync( 6967): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6967): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6967): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6967): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6967): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6967): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6967): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6967): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6967): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6967): {
E/BooksSync( 6967):  "error": {
E/BooksSync( 6967):   "errors": [
E/BooksSync( 6967):    {
E/BooksSync( 6967):     "domain": "global",
E/BooksSync( 6967):     "reason": "required",
E/BooksSync( 6967):     "message": "Login Required",
E/BooksSync( 6967):     "locationType": "header",
E/BooksSync( 6967):     "location": "Authorization"
E/BooksSync( 6967):    }
E/BooksSync( 6967):   ],
E/BooksSync( 6967):   "code": 401,
E/BooksSync( 6967):   "message": "Login Required"
E/BooksSync( 6967):  }
E/BooksSync( 6967): }
E/BooksSync( 6967): 
E/BooksSync( 6967): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6967): 	... 8 more
,E/BooksSync( 6967): Sync error
E/BooksSync( 6967): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 6967): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4336977037377914579&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 6967): Headers:
E/BooksSync( 6967): accept-encoding: [gzip]
E/BooksSync( 6967): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 6967): gdata-version: 2
E/BooksSync( 6967): 
E/BooksSync( 6967): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 6967): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 6967): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 6967): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 6967): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 6967): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 6967): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 6967): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 6967): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 6967): {
E/BooksSync( 6967):  "error": {
E/BooksSync( 6967):   "errors": [
E/BooksSync( 6967):    {
E/BooksSync( 6967):     "domain": "global",
E/BooksSync( 6967):     "reason": "required",
E/BooksSync( 6967):     "message": "Login Required",
E/BooksSync( 6967):     "locationType": "header",
E/BooksSync( 6967):     "location": "Authorization"
E/BooksSync( 6967):    }
E/BooksSync( 6967):   ],
E/BooksSync( 6967):   "code": 401,
E/BooksSync( 6967):   "message": "Login Required"
E/BooksSync( 6967):  }
E/BooksSync( 6967): }
E/BooksSync( 6967): 
E/BooksSync( 6967): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 6967): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 6967): 	... 8 more
I/BooksSync( 6967): Finished books sync
D/SyncManager( 1039): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1049399, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1057462500330; DSPS: 34791907; Offset : -4313807653
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1077464358187; DSPS: 35447328; Offset : -4313811472
,D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=1034035626, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{35307af9 type 2 when 1079785 android} when 1079785
D/[Concierge]Service( 2631): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=1034035626 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1097466511565; DSPS: 36102758; Offset : -4313794246
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1117468638067; DSPS: 36758188; Offset : -4313803949
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1464): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1464): On Skip Timer : true
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController( 1039): battery changed pluggedType: 2
D/LEDHandler( 1967): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1967): Battery Level Remaining: 84%
D/LEDHandler( 1967): Battery Temp: 284, mChargingStatus=2, mChargingStop=false
D/HeadsetStateMachine( 3774): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1464): Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 84 ,temperature : 284
I/[SystemUI]LGPowerUI( 1464): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1464): onReceive = android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1137471150716; DSPS: 37413630; Offset : -4313793793
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1157473103261; DSPS: 38069054; Offset : -4313794322
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1177475158253; DSPS: 38724482; Offset : -4313814551
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1197477369286; DSPS: 39379914; Offset : -4313800783
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1217479438550; DSPS: 40035342; Offset : -4313806767
,I/UsageStatsService( 1039): User[0] Flushing usage stats to disk
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1237481716042; DSPS: 40690777; Offset : -4313817989
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1257483963118; DSPS: 41346210; Offset : -4313798957
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1277486044621; DSPS: 42001638; Offset : -4313792492
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1297488186227; DSPS: 42657069; Offset : -4313817661
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1317490207314; DSPS: 43312495; Offset : -4313810630
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1337492194806; DSPS: 43967920; Offset : -4313806806
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1357493325319; DSPS: 44623317; Offset : -4313805627
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1377496528281; DSPS: 45278782; Offset : -4313806801
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1397497721710; DSPS: 45934181; Offset : -4313803558
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1417501439828; DSPS: 46589663; Offset : -4313808662
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1437502626904; DSPS: 47245062; Offset : -4313811720
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1457504725437; DSPS: 47900491; Offset : -4313818796
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1477506548555; DSPS: 48555910; Offset : -4313796319
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
,I/[SystemUI]Clock( 1464): called onTimeUpdated()
I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1497508367401; DSPS: 49211330; Offset : -4313808529
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1517511143279; DSPS: 49866781; Offset : -4313809594
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1537513293897; DSPS: 50522211; Offset : -4313795363
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=1034035626, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{b26a3e type 2 when 1176533 com.google.android.gms} when 1176533
,D/[Concierge]Service( 2631): onStartCommand(). Type : 9
,D/GCM     ( 2135): Message class com.google.f.a.a.i
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=1034035626 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1557515304618; DSPS: 51177637; Offset : -4313798775
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1577518546485; DSPS: 51833103; Offset : -4313791537
I/[SystemUI]LGPowerUI( 1464): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1464): On Skip Timer : true
,D/LEDHandler( 1967): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1967): Battery Level Remaining: 85%
I/LEDService( 1967): getCurrentHighestLGLedRecord() start. size = 1
V/LEDService( 1967): startInternal : pkg=batteryinfo, recordId=0 : LGLedRecord{19b5f24b flags=0 patternId=3 color=0 priority=-1 recordId=0 pkg=batteryinfo mExceptional=false mNativeNotification=false whichLedPlay=1 patternFilePath=null}
D/qdlights( 1967): set_light_notifications: 3,0,0,0,3
D/qdlights( 1967): [pattern_id] = 0
D/KeyguardUpdateMonitor( 1464): Intent.ACTION_BATTERY_CHANGED status : 2 ,plugged : 2 ,level : 85 ,temperature : 282
I/[SystemUI]LGPowerUI( 1464): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1039): battery changed pluggedType: 2
,W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3774): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1464): onReceive = android.intent.action.BATTERY_CHANGED
I/LEDService( 1967): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1967): set_light_notifications: 0,0,0,0,3
,I/LEDService( 1967): updateLightsLocked : turn on led
D/qdlights( 1967): set_light_notifications: 3,3,0,0,1
D/qdlights( 1967): [pattern_id] = 3
D/LEDHandler( 1967): Battery Temp: 282, mChargingStatus=2, mChargingStop=false
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1597520693978; DSPS: 52488534; Offset : -4313811234
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1617522906731; DSPS: 53143966; Offset : -4313795461
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1637525046932; DSPS: 53799397; Offset : -4313822008
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1657527321351; DSPS: 54454831; Offset : -4313805864
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1677529149207; DSPS: 55110251; Offset : -4313809218
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1697531347534; DSPS: 55765683; Offset : -4313808131
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1717539054244; DSPS: 56421295; Offset : -4313791903
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1737541026945; DSPS: 57076720; Offset : -4313802870
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1757543048032; DSPS: 57732146; Offset : -4313795892
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1777545130576; DSPS: 58387575; Offset : -4313819034
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/PowerManagerServiceEx( 1039): acquireWakeLockInternal: lock=1034035626, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1039
,D/[Concierge]Service( 2631): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7879): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7879): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@26038eec
,D/PowerManagerServiceEx( 1039): releaseWakeLockInternal: lock=1034035626 [*alarm*], flags=0x0
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1797547428276; DSPS: 59043010; Offset : -4313810179
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1817549546966; DSPS: 59698439; Offset : -4313797150
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1837552317949; DSPS: 60353890; Offset : -4313803319
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{b74cdb5 type 2 when 1841842 com.android.bluetooth} when 1841842
,W/bt-smp  ( 3774): Key(LSB ~ MSB) = 0a 3c a6 fe eb 17 6a 79 a6 1f 0a 0b f9 50 a0 5f 
W/bt-smp  ( 3774): Plain text(LSB ~ MSB) = b0 08 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3774): Encrypted text(LSB ~ MSB) = e4 25 54 08 96 66 95 e2 9f 26 4b 2f ac 10 23 a5 
W/bt-btm  ( 3774): Stopping oneshot timer
I/ProcessStatsService( 1039): Prepared write state in 9ms
,I/ProcessStatsService( 1039): Pruning old procstats: /data/system/procstats/state-2015-11-22-23-26-20.bin
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
,I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1857554256535; DSPS: 61009314; Offset : -4313817883
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1877556079600; DSPS: 61664733; Offset : -4313795329
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1897558058759; DSPS: 62320158; Offset : -4313799814
,I/[SystemUI]TimeTickManager( 1464): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1464): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1464): called onTimeUpdated()
I/[SystemUI]Clock( 1464): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
I/[SystemUI]DateView( 1464): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1464): handleTimeUpdate
D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1917560325523; DSPS: 62975592; Offset : -4313791168
,D/sensors_hal_Time( 1039): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1039): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1039): tsOffsetIs: Apps: 1937561793223; DSPS: 63631001; Offset : -4313819141
,I/jxcore-log( 7114): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
,D/LocationManagerService( 1039): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1039): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1039): JNI:system_update. Event-4
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterState( 3774): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3774): Setting state to 13
I/BluetoothAdapterState( 3774): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3774): onBluetoothDisable()
I/BluetoothAdapterState( 3774): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 3774): Scan Mode:20
,D/BluetoothAdapterState( 3774): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 3774): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothMapMasInstance( 3774): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3774): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3774): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3774): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3774): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3774): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3774): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3774): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
V/BluetoothPbapService( 3774): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 3774): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,V/BluetoothFtpService:RfcommSocketAcceptThread( 3774): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3774): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 3774): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3774): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3774): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3774): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3774): bta_gattc_deregister Deregister Failedm unknown client cif
D/BluetoothManagerService( 1039): Message: 60
,D/BluetoothManagerService( 1039): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1039): Bluetooth State Change Intent: 12 -> 13
,I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
I/art     (  343): Background concurrent mark sweep GC freed 789(33KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 10.673ms total 40.222ms
I/ActivityManager( 1039): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=8090 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/LGBluetoothAPIService( 1967): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/BluetoothMapService( 3774): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3774): STATE_TURNING_OFF
V/BluetoothMapService( 3774): Handler(): got msg=4
D/BluetoothMapService( 3774): MAP Service closeService in
D/BluetoothMapMasInstance( 3774): MAP Service shutdown
D/LGBluetoothMapAdapter( 3774): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3774): MAP Service closeService out
V/BtOppService( 3774): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 3774): stopping Accept Thread
V/BtOppRfcommListener( 3774): close mBtServerSocket
I/BtOppRfcommListener( 3774): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3774): waiting for thread to terminate
V/BtOppRfcommListener( 3774): done waiting for thread to terminate
,I/[SystemUI]BluetoothHandler( 1464): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
E/WifiStateMachine( 1039):  ConnectedState CMD_STOP_SUPPLICANT 0 0
D/LocationManagerService( 1039): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1039): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1039): JNI:system_update. Event-4
E/WifiStateMachine( 1039):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1039):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
E/WifiStateMachine( 1039):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
E/WifiStateMachine( 1039):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1039): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1039): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1039): doBoolean: SET_NETWORK 0 bssid any
V/BtOppService( 3774): onDestroy
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/LGBluetoothOppAdapter( 3774): [BTUI] LGBluetoothOppAdapter cleanup
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
W/ContextImpl( 7194): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
,D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/WifiNative-wlan0( 1039): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1039): doBoolean: SAVE_CONFIG
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiNative-wlan0( 1039): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2693): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/WifiNative-wlan0( 1039): SET ps 1: returned true
D/CommandListener(  312): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1039): RunningState{ when=-7ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/BluetoothPbapReceiver( 3774): PbapReceiver onReceive 
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,V/BluetoothPbapReceiver( 3774): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
V/BluetoothPbapReceiver( 3774): ***********state = 13
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
V/BluetoothPbapReceiver( 3774): ***********Calling start service!!!! with action = null
I/jxcore-log( 7114): {"id":0,"ok":false,"name":"Coordinator server got disconnected","operator":"fail","error":{},"test":68,"type":"assert"}
I/jxcore-log( 7114): 
V/BluetoothPbapService( 3774): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3774): state: 13
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
V/BluetoothPbapService( 3774): Pbap Service closeService in
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
V/BluetoothPbapService( 3774): successfully stopped pbap service
V/BluetoothPbapService( 3774): Pbap Service closeService out
V/BluetoothPbapService( 3774): Pbap Service onDestroy
V/BluetoothPbapService( 3774): Pbap Service closeService in
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
V/BluetoothPbapService( 3774): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3774): [BTUI] cleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/BluetoothManagerService( 1039): Message: 20
D/BluetoothManagerService( 1039): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23719031:true
,V/NativeCrypto( 2135): Read error: ssl=0xaf461200: I/O error during system call, Connection timed out
V/NativeCrypto( 2135): SSL shutdown failed: ssl=0xaf461200: I/O error during system call, Broken pipe
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1039): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
D/ConnectivityService( 1039): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Forcing reevaluation
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/WifiHS20( 1039): hidePasspointNotification off =false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,V/WfdStateTracker( 1967): handleWifiStateChangedEvent: 0
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiNetworkAgent( 1039): NetworkAgent: NetworkAgent channel lost
D/LGWifiP2pService( 1039): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1039): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@8379d49
D/LGWifiP2pService( 1039): P2pDisablingState
D/LGWifiP2pService( 1039): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): p2p socket connection lost
D/LGWifiP2pService( 1039): P2pDisabledState
D/WifiHS20( 1039): hidePasspointNotification off =false
E/WifiStateMachine( 1039):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1039): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2693): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1039): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1039): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1039): doBoolean: SET ps 1
D/WifiNative-wlan0( 1039): SET ps 1: returned true
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService( 1039): SCAN_AVAILABLE : 1
D/RttService( 1039): SCAN_AVAILABLE : 1
D/WifiScanningService( 1039): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1039): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
,I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
V/WfdStateTracker( 1967): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1967): WifiP2pState is changed : false
D/WfdsService( 1967): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1967): Set the WFDS Monitor: false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/WfdsMonitor( 1967): WFDS Monitor is stopped
D/WfdsService( 1967): STATE : WfdsDisabledState - enter
W/WfdsSession:Controller( 1967): DefaultState - msg [9441355] is not handled
D/CtrlSupplicant( 1967): Received on exit socket, terminate
E/CtrlSupplicant( 1967): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1967): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1967): WfdsMonitorThread is received the interrupt - closing
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/WfdsService( 1967): DefaultState - msg [9445378] is not handled
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/BluetoothManagerService( 1039): Message: 30
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/CommandListener(  312): Clearing all IP addresses on wlan0
D/ConnectivityService( 1039): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1039): disableDataServiceNotify
D/DSQN    ( 1039): stop dsqn bin
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
D/WifiNative-p2p0( 1039): doBoolean: TERMINATE
,D/WifiHS20( 1039): hidePasspointNotification off =false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
W/Settings( 1039): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1039): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1039): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/BluetoothManagerService( 1039): Message: 30
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
D/WifiNative-p2p0( 1039): TERMINATE: returned true
E/WifiStateMachine( 1039): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1039): useWiFiOffloading() : false
E/WifiStateMachine( 1039): CONFIG_LGE_WLAN_PATH : true
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
I/WifiServerServiceExt( 1039): WIFI_STATE_CHANGED_ACTION [0]
D/WifiServerServiceExt( 1039): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1039): setSupplicantStateDISCONNECTED
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/ConnectivityService( 1039): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/LocalBluetoothProfileManager( 7194): Adding local MAP profile
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/StatusBar.NetworkController( 1464): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1464): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1039): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
V/WfdStateTracker( 1967): WfdStateTracker handleDirectStateChangedEvent: 6
D/BluetoothMap( 7194): Create BluetoothMap proxy object
D/Nat464Xlat( 1039): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker( 1039): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1039): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1464): CM callback handler got msg 524292
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/BluetoothManagerService( 1039): Message: 30
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1039): Disconnected - quitting
D/Con,nectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1039): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1039): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1039): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1039): Removing idletimer
W/Settings( 1039): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1039): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1039): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1874): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy( 1039): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1039): Sending msg: 4 arg1:0 arg2:1
D/TelephonyNetworkFactory-1( 1874):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1039): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1039): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1039): ignore wifi update if we are not in OPENING or CLOSING
D/WIFI    ( 1039): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1039):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): Message: 30
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/LocalBluetoothProfileManager( 7194): LocalBluetoothProfileManager construction complete
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
D/LGBluetoothFeatureConfig( 7194):  get() - isFeatureLoaded : false
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothUserBindClient( 7194): [BTUI] initUserBindClient
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
W/ContextImpl( 7194): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/DockEventReceiver( 7194): finishStartingService: stopping service
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothInputDevice( 7194): Proxy object connected
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/HidProfile( 7194): Bluetooth service connected
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothPan( 7194): BluetoothPAN Proxy object connected
D/PanProfile( 7194): Bluetooth service connected
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
D/BluetoothMap( 7194): Proxy object connected
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/MapProfile( 7194): Bluetooth service connected
D/BluetoothMap( 7194): getConnectedDevices()
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
,D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/BluetoothMap( 7194): Bluetooth is Not enabled
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/LGBluetoothUserBindClient( 7194): [BTUI] onServiceConnected
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/TelephonyIcons( 1464): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/wpa_supplicant( 2693): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2693): monitor socket send errors count : 1
I/wpa_supplicant( 2693): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1967-2\x00 that cannot receive messages
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/WifiMonitor( 1039): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1039): Dropping event because (p2p0) is stopped
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
E/ActivityThread( 8090): Failed to find provider info for com.lge.lgaccount.provider
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
W/LG Account v2.2( 8090): No ProfileInfo entries
I/LG Account v2.2( 8090): isEnabled: false
I/Feature ( 8090): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 8090): [Lifetracker]Country: EU
I/Feature ( 8090): [Lifetracker]Operator: OPEN
I/Feature ( 8090): [Lifetracker]Ranking support: false
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
I/Feature ( 8090): [Lifetracker]Comfort support: false
I/Feature ( 8090): [Lifetracker]Accessory: true
I/Feature ( 8090): [Lifetracker]Health device: true
I/Feature ( 8090): [Lifetracker]Extra Pedometer: false
I/Feature ( 8090): [Lifetracker]Blood glucose device: false
I/Feature ( 8090): [Lifetracker]Device Number: 3
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
D/LGBluetoothAuthorization( 7194): [BTUI] cancel All Notification
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothPermissionRequest( 7194): onReceive
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/LGBluetoothAuthorization( 7194): [BTUI] cancel All Notification
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/wpa_supplicant( 2693): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
W/wpa_supplicant( 2693): USIM:  scard_deinit function
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1039): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1039): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1039):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=1940584
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
E/WifiStateMachine( 1039):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=1940585
E/WifiStateMachine( 1039):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=1940585  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1039):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=1940585  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/Tethering( 1039): InitialState.processMessage what=4
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7114): 
I/PCSuite ( 7229): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7229): [StartReceiver][getUpdateNecessity]update = false
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
D/PCSuite ( 7229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/Tethering( 1039): sendTetherStateChangedBroadcast 0, 0, 0
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
E/WifiStateMachine( 1039):  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LocationManagerService( 1039): getAllProviders()=[passive, gps, network]
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
V/BluetoothOppReceiver( 3774): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 3774): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 3774): [BTUI] cancel opp active transfer file notification
D/LGBluetoothResetSettingReceiver( 7194): return without doing reset settings.
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
V/BluetoothFtpReceiver( 3774): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3774): BluetoothFtpReceiver Start Service
,I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
V/BluetoothFtpService( 3774): Ftp Service onStartCommand
V/BluetoothFtpService( 3774): action: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
V/BluetoothFtpService( 3774): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3774): Shutdown
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
V/BluetoothFtpService( 3774): successfully stopped ftp service
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
V/BluetoothSapReceiver( 3774): [BTUI] checkServiceStart
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
V/BluetoothSapReceiver( 3774): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3774): SapReceiver onReceive 
V/BluetoothSapReceiver( 3774): action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService( 1039): Message: 2
V/BluetoothSapReceiver( 3774):  Bluetooth Adapter state = 13
D/BluetoothManagerService( 1039): Sending off request.
V/BluetoothSapReceiver( 3774): Calling SAP service start service with action = null
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
V/BluetoothFtpService( 3774): Ftp Service onDestroy
V/BluetoothFtpService( 3774): Ftp Service closeService
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/DhcpStateMachine( 1039): StoppedState
D/DhcpStateMachine( 1039): StoppedState{ when=-173ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager( 1039): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=8147 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/BluetoothSapService( 3774): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3774): state: 13
V/BluetoothSapService( 3774): Stopping SAP server process
V/BluetoothSapService( 3774): Sap Service closeSapService in
V/BluetoothSapService( 3774): Close listen Socket : 
V/BluetoothSapService( 3774): Close rfcomm Socket : 
V/BluetoothSapService( 3774): Close sapd  Socket : 
E/WifiStateMachine( 1039):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1039):  DefaultState CMD_ON_QUIT 0 0
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
V/BluetoothSapService( 3774): Sap Service closeSapService out
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
V/BluetoothSapService( 3774): Sap Service onDestroy
V/BluetoothSapService( 3774): Sap Service closeSapService in
V/BluetoothSapService( 3774): Close listen Socket : 
V/BluetoothSapService( 3774): Close rfcomm Socket : 
V/BluetoothSapService( 3774): Close sapd  Socket : 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
V/BluetoothSapService( 3774): Sap Service closeSapService out
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
I/QRemote ( 7250): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
,D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/PCSuite ( 7229): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7229): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
I/GLSUser ( 2135): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 2135): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/GLSUser ( 2135): [GLSUser] Extracting token using key: Auth
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
W/GLSActivity( 2135): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/wpa_supplicant( 2693): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1039): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1039): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-TERMINATING 
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
D/WifiMonitor( 1039): Disconnecting from the supplicant, no more events
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcor,e-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
E/WifiStateMachine( 1039):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 37 0
,V/GLSActivity( 2135): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
,D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
,D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/QRemote ( 7250): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
W/ResourcesManager( 8147): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/PCSuite ( 7229): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7229): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
,D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
,D/QRemote ( 7250): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7250): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
,D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/AuthorizationBluetoothService( 2135): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/QRemote ( 7250): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
,D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/PCSuite ( 7229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
,V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
W/FormManager( 7399): Network not available. Please check & try again.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
,D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/[Concierge]Service( 2631): onStartCommand(). Type : 9
D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7194): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7194): [AUTORUN] sys.usb.state = ptp_only,adb
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/UsbSettingsReceiver( 7194): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/FormManager( 7399): Network unavailable.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/UsbSettingsControl( 7194): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7194): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7194): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/UsbSettingsControl( 7194): [AUTORUN] setTetherStatus() : status=false
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
V/FormManager( 7399): Network unavailable.
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
I/ActivityManager( 1039): Killing 7340:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
W/libprocessgroup( 1039): failed to open /acct/uid_10011/pid_7340/cgroup.procs: No such file or directory
,D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/WfdsService( 1967): Supplicant Connection state is changed : false
D/WfdsService( 1967): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1967): Set the WFDS Monitor: false
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
D/WfdsMonitor( 1967): WFDS Monitor is stopped
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/WifiOffDelayIfNotUsed( 1039): stopMonitoring
E/WifiStateMachine( 1039): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1039): useWiFiOffloading() : false
E/WifiStateMachine( 1039): CONFIG_LGE_WLAN_PATH : true
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/StatusBar.NetworkController( 1464): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/WfdStateTracker( 1967): WfdStateTracker handleDirectStateChangedEvent: 0
W/Settings( 1838): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
I/WifiServerServiceExt( 1039): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1039): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1039): batteryPsActivateMsgHandler : this is not treated
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
,D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/ActivityManager( 1039): Killing 7368:com.lge.email/u0a23 (adj 15): empty #17
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
W/libprocessgroup( 1039): failed to open /acct/uid_10023/pid_7368/cgroup.procs: No such file or directory
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/LGDMClient( 4319): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/PCSuite ( 7229): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/PCSuite ( 7229): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7229): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
V/WiFiOffLoadBroadcast( 7194): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/WiFiOffLoadBroadcast( 7194): MCCMNC not supported: null
W/FormManager( 7399): Network not available. Please check & try again.
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
V/FormManager( 7399): Network unavailable.
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
V/FormManager( 7399): Network unavailable.
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
,I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
,D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
,D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
,D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Message: 2
D/BluetoothManagerService( 1039): Sending off request.
,I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
,D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/jxcore-log( 7114): The client has disconnected!
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): Turning radios to false
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1039): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
I/jxcore-log( 7114): toggleBluetooth - 
I/jxcore-log( 7114): 
D/BluetoothManagerService( 1039): Message: 2
,D/BluetoothManagerService( 1039): Sending off request.
,D/LGBluetoothServiceAdapter( 3774): [BTUI] Precleanup
D/WifiServiceImplEx( 1039): setWifiEnabled: false pid=7114, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1039): setWifiEnabled: false pid=7114, uid=10311
E/WifiService( 1039): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterService( 3774): disable() : BT State is not STATE_ON. Can't disable BT
E/BluetoothManagerService( 1039): IBluetooth.disable() returned false
I/jxcore-log( 7114): toggleWiFi
I/jxcore-log( 7114): 
I/chromium( 7114): [INFO:CONSOLE(63)] "logCallback 0 isOK: false : Coordinator server got disconnected", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3774): ag scb idx 1 not allocated
D/bt_hci_bdroid( 3774): cleanup
E/bt-btif ( 3774): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3774): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x0017
,W/bt-l2cap( 3774): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3774): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3774): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3774): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x001b
,W/bt-l2cap( 3774): L2CAP - PSM: 0x001b not found for deregistration
,W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3774): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3774): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3774): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3774): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3774): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt_lpm  ( 3774): LPM is already off!!!
I/bt_userial_mct( 3774): exiting userial_read_thread
D/bt_userial_mct( 3774): Leaving userial_evt_read_thread()
D/bt_userial_mct( 3774): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 3774): hw_epilog_process
D/bt_hci_bdroid( 3774): cleanup Finalizing cleanup
D/bt_userial_mct( 3774): userial_close
E/bt_userial_mct( 3774): pthread_join() FAILED result:3
I/bt_vendor( 3774): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/bt_hci_bdroid( 3774): set_power 0
I/bt_vendor( 3774): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3774): bluetooth satus is on
I/bt_vendor( 3774): bt-vendor : resetting BT status
I/bt_vendor( 3774): Starting hciattach daemon
I/bt_vendor( 3774): try to set false
I/bt_vendor( 3774): Starting hciattach daemon
I/bt_vendor( 3774): try to set false
,I/bt_vendor( 3774): cleanup
I/GKI_LINUX( 3774): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3774): GKI_exit_task 0 done
I/GKI_LINUX( 3774): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3774): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 3774): Received stop request...Stopping profile...
,I/LGBluetoothHfpAdapter( 3774): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3774): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3774): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2210add8
D/HeadsetStateMachine( 3774): Exit Disconnected: -1
D/BluetoothHeadset( 1874): Proxy object disconnected
D/BluetoothAdapterState( 3774): Stopping profile services that were post enabled
,D/A2dpService( 3774): Received stop request...Stopping profile...
D/A2dpStateMachine( 3774): Exit Disconnected: -1
D/BluetoothHeadset( 1874): Proxy object disconnected
D/LGBluetoothAvrcpQcomAdapter( 3774): [BTUI] cleanup
D/BluetoothHeadset( 1874): Proxy object disconnected
D/LGBluetoothA2dpAdapter( 3774): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3774): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3774): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2210add8
D/HeadsetStateMachine( 3774): Unbinding service...
D/HeadsetPhoneState( 3774): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3774): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3774): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3774): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3774): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3774): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3774): [BTUI] LGBluetoothHfpAdapter cleanup
,D/HidService( 3774): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3774): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2210add8
D/HealthService( 3774): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3774): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2210add8
D/PanService( 3774): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3774): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2210add8
D/BtGatt.DebugUtils( 3774): handleDebugAction() action=null
,D/BtGatt.GattService( 3774): Received stop request...Stopping profile...
D/BtGatt.GattService( 3774): stop()
D/BtGatt.AdvertiseManager( 3774): advertise clients cleared
D/BluetoothAdapterService( 3774): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2210add8
D/BluetoothMapService( 3774): Received stop request...Stopping profile...
D/BluetoothMapService( 3774): stop()
D/BluetoothMapEmailAppObserver( 3774): deinitObservers()
D/BluetoothMapEmailAppObserver( 3774): removeReceiver()
D/BluetoothAdapterService( 3774): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2210add8
I/BluetoothA2dpServiceJni( 3774): cleanupNative
I/GKI_LINUX( 3774): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3774): GKI_exit_task 2 done
I/GKI_LINUX( 3774): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3774): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3774): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3774): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3774): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3774): Cleaning up Bluetooth Health object
V/BluetoothMapService( 3774): Handler(): got msg=4
D/BluetoothMapService( 3774): MAP Service closeService in
D/LGBluetoothMapAdapter( 3774): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3774): MAP Service closeService out
D/BluetoothAdapterState( 3774): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3774): Setting state to 10
I/BluetoothAdapterState( 3774): Bluetooth adapter state changed: 13-> 10
,D/BluetoothManagerService( 1039): Message: 60
D/BluetoothManagerService( 1039): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1039): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 3774): Entering OffState
D/BluetoothHeadset( 1874): onBluetoothStateChange: up=false
D/BluetoothPan( 7194): onBluetoothStateChange on: false
W/BluetoothPanServiceJni( 3774): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3774): Cleaning up Bluetooth PAN callback object
D/BluetoothMapService( 3774): cleanup()
D/BluetoothMapService( 3774): MAP Service closeService in
D/LGBluetoothMapAdapter( 3774): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3774): MAP Service closeService out
D/BluetoothHeadset( 1039): Proxy object disconnected
D/AudioService( 1039): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothA2dp( 1039): Proxy object disconnected
D/AudioService( 1039): onServiceDisconnected: Bluetooth profile: 2
D/BluetoothHeadset( 1039): onBluetoothStateChange: up=false
D/BluetoothPbap( 7194): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1874): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 7194): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1874): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1039): onBluetoothStateChange: up=false
D/BluetoothMap( 7194): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1039): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1039): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService( 1039): Calling onQBluetoothServiceDown callbacks
,D/BluetoothManagerService( 1039): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1039): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@666ec4a mBinding = false
D/BluetoothManagerService( 1039): Sending unbind request.
I/GKI_LINUX( 3774): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3774): GKI_exit_task 1 done
I/GKI_LINUX( 3774): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3774): cleanupNative: return from cleanup
I/art     ( 3774): --- WEIRD: removing null entry 246
W/art     ( 3774): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3774): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 3774): [BTUI] unregister observer for LG device name DB
D/BluetoothManagerService( 1039): Bluetooth State Change Intent: 13 -> 10
I/art     ( 3774): System.exit called, status: 0
I/AndroidRuntime( 3774): VM exiting with result code 0, cleanup skipped.
V/AudioFlinger(  316): 3774 died, releasing its sessions
V/AudioFlinger(  316):  pid 1874 @ 0
V/AudioFlinger(  316):  pid 3318 @ 1
V/AudioFlinger(  316):  pid 3318 @ 2
,I/[SystemUI]BluetoothHandler( 1464): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1967): [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1967): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1967): Message: 101
E/LGBluetoothAPIService( 1967): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
D/LGBluetoothAPIService( 1967): Calling onBluetoothServiceDown callbacks
D/LGBluetoothAPIService( 1967): Broadcasting onBluetoothServiceDown() to 0 receivers.
D/LGBluetoothUserBindClient( 7194): [BTUI] onServiceDisconnected
D/LGBluetoothAPIService( 1967): Message: 2
D/LGBluetoothAPIService( 1967): unbindAndFinish(): null mBinding = false
,D/BluetoothAdapter( 1464): 845630576: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1464): 845630576: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothFeatureConfig( 7194): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 7194): [BTUI] resetProperty - success
E/LGBluetoothEventManager( 7194): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7194): [BTUI] clear device connection state
W/ContextImpl( 7194): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/ActivityManager( 1039): Process com.android.bluetooth (pid 3774) has died
W/ActivityManager( 1039): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
W/ActivityManager( 1039): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 11000ms
,I/ActivityManager( 1039): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=8202 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
D/DockEventReceiver( 7194): finishStartingService: stopping service
I/art     (  343): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 477us total 25.987ms
,I/art     (  343): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 507us total 20.669ms
,I/art     (  343): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 424us total 20.751ms
,W/ResourcesManager( 8202): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 8202): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8202): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 8202): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 8202): Loading JNI Library
,D/BluetoothAdapterApp( 8202): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2afb4ff9 Instance Count = 1
,D/BluetoothAdapterApp( 8202): onCreate
D/ProfileConfigQcom( 8202): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 8202): Adding HeadsetService
,D/ProfileConfigQcom( 8202): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 8202): Adding A2dpService
,D/ProfileConfigQcom( 8202): [BTUI] HidService is supported
D/ProfileConfigQcom( 8202): Adding HidService
D/ProfileConfigQcom( 8202): [BTUI] HealthService is supported
D/ProfileConfigQcom( 8202): Adding HealthService
D/LGBluetoothFeatureConfig( 8202): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 8202): [BTUI] PanService is supported
D/ProfileConfigQcom( 8202): Adding PanService
D/ProfileConfigQcom( 8202): [BTUI] GattService is supported
D/ProfileConfigQcom( 8202): Adding GattService
D/ProfileConfigQcom( 8202): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 8202): Adding BluetoothMapService
D/ProfileConfigQcom( 8202): [BTUI] HeadsetClientService is NOT supported
V/BluetoothPbapReceiver( 8202): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 8202): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 8202): ***********state = 10
V/LGMDMManagerInternal( 8202): Create singleton instance
,D/LGBluetoothUserBindClient( 7194): [BTUI] onServiceConnected
,D/LGBluetoothAPIServer( 8202): [BTUI] onCreate()
,D/BluetoothPermissionRequest( 7194): onReceive
D/LGBluetoothUtils( 7194): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7194): cancelDiscoverableAlarm(): Enter
,D/LGBluetoothResetSettingReceiver( 7194): return without doing reset settings.
D/LGBluetoothAPIServer( 8202): [BTUI] onBind()
D/LGBluetoothAPIService( 1967): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1967): Message: 100
D/LGBluetoothAPIService( 1967): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/LGBluetoothOppAdapter( 8202): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/BluetoothFtpReceiver( 8202): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 8202): [BTUI] checkServiceStart
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
V/BluetoothSapReceiver( 8202): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 8202): SapReceiver onReceive 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
V/BluetoothSapReceiver( 8202): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 8202):  Bluetooth Adapter state = 10
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports",:{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.i,o/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
V/AlarmManager( 1039): RTC_WAKEUP set : Alarm{1069558b type 0 when 1448284574627 com.google.android.gms} when 1448284574627
V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{96bf668 type 2 when 1941954 com.google.android.gms} when 1941954
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
D/LGBluetoothProfileConnectionReceiver_EasySetting( 8147): [BTUI] STATE_OFF : reset connected device information EasySettings
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
D/AuthorizationBluetoothService( 2135): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/EventLogService( 2324): Aggregate from 1448282774549 (log), 1448282774549 (data)
,D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1039): MasterInitialState.processMessage what=3
D/ConnectivityService( 1039): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1039): MasterInitialState.processMessage what=3
,D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6642): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5943): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5943): type=WIFI subType= reason=null isConnected=false
I/ActivityManager( 1039): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=8254 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1039): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1039): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppUp4:AppBoxCP( 8254): onCreate
W/AppUp4:DB( 8254):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 8254):  setFingerPrint start
,I/AppUp4:DB( 8254):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 8254):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 8254):  SDK version = 21
I/AppUp4:DB( 8254):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 8254): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 8254): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 8254): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 8254): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 8254): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 8254): onReceive
,D/LgDataFeature( 8254): LgDataFeature() Constructor: none
D/LgDataFeature( 8254): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 8254): Context : android.app.ReceiverRestrictedContext@2db984bb
D/AppUp4:CustFacade( 8254): isCustomizationCompleted : false
D/AppUp4:CustFacade( 8254): isPhone : true
D/AppUp4:CustModeStarterReceiver( 8254): begin check event
I/AppUp4:CustModeStarterReceiver( 8254): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 8254): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 8254): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 8254): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 8254): handleAsyncCustNotification do not startCustService
,I/ActivityManager( 1039): Killing 7438:com.android.chrome/u0a57 (adj 15): empty #17
,D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup( 1039): failed to open /acct/uid_10057/pid_7438/cgroup.procs: No such file or directory
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4319): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1039): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8296 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     ( 1039): Explicit concurrent mark sweep GC freed 96959(4MB) AllocSpace objects, 13(1012KB) LOS objects, 33% free, 44MB/67MB, paused 3.957ms total 219.215ms
,W/ResourcesManager( 8296): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8296): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 8296): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8296): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/LGEmail ( 8296): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8296): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 8296): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 8296): LgDataFeature() Constructor: none
D/LgDataFeature( 8296): LgDataFeature() Constructor Done, null
,I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","descrip,tion":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","descrip,tion":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeRecei,ved":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
,D/eas_req ( 8296): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3318): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3318): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3318): networkInfo.isConnected() = false
I/HubEmail( 8296): JNI_OnLoad()
I/HubEmail( 8296): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 8296): registerNatives()
I/HubEmail( 8296): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 8296): registerNativeMethods()
I/HubEmail( 8296): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 8296): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager( 1039): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8325 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/FormManager( 7399): Network not available. Please check & try again.
W/Settings( 8296): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/FormManager( 7399): Network unavailable.
V/FormManager( 7399): Network unavailable.
,I/ActivityManager( 1039): Killing 7468:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10062/pid_7468/cgroup.procs: No such file or directory
I/ActivityManager( 1039): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8355 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 7486:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10085/pid_7486/cgroup.procs: No such file or directory
,V/AlarmManager( 1039): ELAPSED_WAKEUP set : Alarm{236833b0 type 2 when 1945063 com.google.android.gms} when 1945063
,I/ActivityManager( 1039): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8373 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 7507:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10093/pid_7507/cgroup.procs: No such file or directory
,I/art     ( 8373): Almond Protected OAT
,D/LGWifiP2pService( 1039): P2pDisabledState{ when=-3ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1039): DefaultState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WeatherApplication( 8373): removeAccount
D/WeatherApplication( 8373): Account.length = 0
E/WeatherApplication( 8373): OPERATOR:OPEN
D/WeatherAncestor( 8373): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:17:43
D/Weather.Utils( 8373): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 8373): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 8373): 2 : This is isUpdating : false
D/WeatherAncestor( 8373): connectivity changed - connection : true
D/WeatherService( 8373): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 8373): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 8373): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 8373): 2 : Cache is not up-to-date, count: 0
,E/WifiStateMachine( 1039):  InitialState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1039):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
D/Weather_cast( 8373): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 8373): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:17:43
,I/ActivityManager( 1039): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8391 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6798:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10097/pid_6798/cgroup.procs: No such file or directory
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8391): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8391): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8391): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  281): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  281): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  281): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8391): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/WebViewFactory( 8391): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 8391): Loading: webviewchromium
I/LibraryLoader( 8391): Time to load native libraries: 5 ms (timestamps 6087-6092)
I/LibraryLoader( 8391): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8391): Binding Chromium to main looper Looper (main, tid 1) {24c721b4}
I/LibraryLoader( 8391): Expected native library version number "",actual native library version number ""
I/chromium( 8391): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 8391): Initializing chromium process, renderers=0
W/art     ( 8391): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 8391): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 8391): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,I/chromium( 8391): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  316): registerClient() client 0xb1427e40, uid 10093
W/AudioManagerAndroid( 8391): Requires BLUETOOTH permission
I/Adreno-EGL( 8391): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8391): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8391): Build Date: 12/12/14 금
I/Adreno-EGL( 8391): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 8391): Remote Branch: 
I/Adreno-EGL( 8391): Local Patches: 
I/Adreno-EGL( 8391): Reconstruct Branch: 
,I/NSApplication( 8391): Starting up...
,I/ActivityManager( 1039): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8449 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1039): Killing 6967:com.google.android.apps.books/u0a54 (adj 15): empty #17
,W/libprocessgroup( 1039): failed to open /acct/uid_10054/pid_6967/cgroup.procs: No such file or directory
,W/ResourcesManager( 8449): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.Environment( 2324): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2324): num queued entries: 0
,I/iu.UploadsManager( 2324): num updated entries: 0
I/iu.SyncManager( 2324): NEXT; no task
D/ChimeraCfgMgr( 2324): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6642): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6642): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 8254): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 8254): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 8254): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 8254): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 8254): onReceive
D/AppUp4:CustFacade( 8254): Context : android.app.ReceiverRestrictedContext@2db984bb
D/AppUp4:CustFacade( 8254): isCustomizationCompleted : false
D/AppUp4:CustFacade( 8254): isPhone : true
I/GLSActivity( 2135): [ac] getting account id
D/AppUp4:CustModeStarterReceiver( 8254): begin check event
I/AppUp4:CustModeStarterReceiver( 8254): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4319): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2135): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
D/LGDMClient( 4319): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/eas_req ( 8296): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4319): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LgeMiscReceiver( 3318): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3318): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3318): networkInfo.isConnected() = false
W/Settings( 8296): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/FormManager( 7399): Network not available. Please check & try again.
,D/WeatherAncestor( 8373): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:17:44
D/Weather.Utils( 8373): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 8373): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 8373): 2 : This is isUpdating : false
D/WeatherAncestor( 8373): connectivity changed - connection : true
D/WeatherService( 8373): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@23220531
D/ForecastDataCache( 8373): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 8373): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 8373): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 8373): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 8373): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:17:44
,V/FormManager( 7399): Network unavailable.
V/FormManager( 7399): Network unavailable.
,D/ChimeraCfgMgr( 2324): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/libc-netbsd(  312): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1039): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114,): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
,I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target,":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeRecei,ved":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_is,Server":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protoc,olVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 
I/jxcore-log( 7114): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 7114): 

```
