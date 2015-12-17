#### Test 539786639813e59_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 157774482245; DSPS: 5310548; Offset : -4302585864
,I/[SystemUI]LGPowerUI( 1466): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1466): On Skip Timer : true
--------- beginning of system
D/LEDHandler( 1970): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1970): Battery Level Remaining: 100%
D/LEDHandler( 1970): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/WifiController( 1038): battery changed pluggedType: 2
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3822): Disconnected process message: 10, size: 0
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/KeyguardUpdateMonitor( 1466): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1466): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]BatterySaverHandler( 1466): onReceive = android.intent.action.BATTERY_CHANGED
D/AndroidRuntime( 6971): 
D/AndroidRuntime( 6971): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6971): CheckJNI is OFF
D/AndroidRuntime( 6971): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1970): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{36e3efbe #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{36e3efbe #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  337): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7001 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6971): Shutting down VM
V/ActivityManager( 1038): Display changed displayId=0
D/DSDPConnection( 1870): Display #0 changed.
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{331166c co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{1443a435 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 7001): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 7001): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 7001): Loading: webviewchromium
I/LibraryLoader( 7001): Time to load native libraries: 5 ms (timestamps 9245-9250)
I/LibraryLoader( 7001): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7001): Binding Chromium to main looper Looper (main, tid 1) {711e11c}
I/LibraryLoader( 7001): Expected native library version number "",actual native library version number ""
I/chromium( 7001): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7001): Initializing chromium process, renderers=0
W/art     ( 7001): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  317): registerClient() client 0xb57bc6a0, uid 10311
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d94de58:true
W/chromium( 7001): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7001): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 7001): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 7001): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7001): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7001): Build Date: 12/12/14 금
I/Adreno-EGL( 7001): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7001): Remote Branch: 
I/Adreno-EGL( 7001): Local Patches: 
I/Adreno-EGL( 7001): Reconstruct Branch: 
W/chromium( 7001): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7001): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7001): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7001): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7001): CordovaWebView is running on device made by: LGE
W/art     ( 7001): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7001): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 7001): Render dirty regions requested: true
I/OpenGLRenderer( 7001): Initialized EGL, version 1.4
D/OpenGLRenderer( 7001): Enabling debug mode 0
D/Atlas   ( 7001): Validating map...
D/SplitWindow( 1038): check instance of lgWin Window{2f09fdd2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1466): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1466): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1466):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1466): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3174c1ef,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LgDataFeature( 7001): LgDataFeature() Constructor: none
D/LgDataFeature( 7001): LgDataFeature() Constructor Done, null
I/ActivityManager( 1038): Displayed com.test.thalitest/.MainActivity: +593ms (total +709ms)
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{3d0d281f u0 com.test.thalitest/.MainActivity t4} time:159668
I/Timeline( 7001): Timeline: Activity_idle id: android.os.BinderProxy@299dc94c time:159672
I/chromium( 7001): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7001): 
D/JsMessageQueue( 7001): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 7001): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 7001): 
D/jxcore_app_log( 7001): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435098880
,D/JX-Cordova( 7001): jxcore cordova android initializing
E/GBMv2   (  337): DFP En is all cleared set to be enabled
E/GBMv2   (  337): Set value is all cleared set the max
I/GBMv2   (  337): DFP Enabled. Ignore VFP set
,W/jxcore-log( 7001): Initializing JXcore engine
W/jxcore-log( 7001): JXcore engine is ready
W/jxcore-log( 7001): Starting JXcore engine
,W/.test.thalitest( 7001): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8341]" dev="sockfs" ino=8341 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7001): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 7001): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9572]" dev="sockfs" ino=9572 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 7001): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 7001): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31736]" dev="sockfs" ino=31736 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 7001): Platform android
W/jxcore-log( 7001): 
W/jxcore-log( 7001): Process ARCH arm
W/jxcore-log( 7001): 
,I/jxcore-log( 7001): JXcore Cordova bridge is ready!
I/jxcore-log( 7001): 
,W/jxcore-log( 7001): JXcore engine is started
I/jxcore-log( 7001): Toggling radios to true
I/jxcore-log( 7001): 
,D/BluetoothAdapter( 7001): enable(): BT is already enabled..!
D/WifiService( 1038): New client listening to asynchronous messages
D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=7001, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: true pid=7001, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiServiceImplEx( 1038): disconnect pid=7001, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECT 0 0
E/WifiNative: ( 1038): [162,292,655 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1038): reconnect pid=7001, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7001): Radios toggled
I/jxcore-log( 7001): 
I/wpa_supplicant( 2751): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiNative-wlan0( 1038): DISCONNECT: returned true
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/Tethering( 1038): InitialState.processMessage what=4
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2751): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/DhcpStateMachine( 1038): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  313): Clearing all IP addresses on wlan0
V/NativeCrypto( 2133): Read error: ssl=0xaa709400: I/O error during system call, Connection timed out
,D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,V/NativeCrypto( 2133): SSL shutdown failed: ssl=0xaa709400: I/O error during system call, Broken pipe
I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=7079 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,E/WifiStateMachine( 1038): Start Disconnecting Watchdog 1
E/WifiStateMachine( 1038):  DisconnectingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1038): [162,425,040 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
I/wpa_supplicant( 2751): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiHS20( 1038): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/WifiNative-wlan0( 1038): RECONNECT: returned true
V/WfdStateTracker( 1970): handleWifiStateChangedEvent: 0
E/WifiStateMachine( 1038):  DisconnectingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=162429
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=162430
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2751): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1038): hidePasspointNotification off =false
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/CommandListener(  313): Clearing all IP addresses on wlan0
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1038): hidePasspointNotification off =false
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=162460  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=162461  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524292
D/NetworkManagementService( 1038): Removing idletimer
D/TelephonyNetworkFactory-1( 1870): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1466): networkInfo,=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1038): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=162476  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=162481  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ResourcesManager( 7079): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7079): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7079): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7079): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7079): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7079): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7079): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7079): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7079): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7079): [AUTORUN] setTetherStatus() : status=false
,D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-210ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7112 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 2212:com.lge.music/u0a34 (adj 15): empty #17
,V/AudioFlinger(  317): 2212 died, releasing its sessions
V/AudioFlinger(  317):  pid 1870 @ 0
V/AudioFlinger(  317):  pid 3377 @ 1
V/AudioFlinger(  317):  pid 3377 @ 2
,W/libprocessgroup( 1038): failed to open /acct/uid_10034/pid_2212/cgroup.procs: No such file or directory
,I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 7112): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 7079): LgDataFeature() Constructor: none
,D/LgDataFeature( 7079): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
I/ActivityManager( 1038): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7136 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1038): Killing 6672:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,I/art     (  343): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 459us total 25.118ms
,I/art     (  343): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 436us total 19.703ms
,I/art     (  343): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 431us total 19.527ms
,W/libprocessgroup( 1038): failed to open /acct/uid_10008/pid_6672/cgroup.procs: No such file or directory
,W/ResourcesManager( 7136): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 7136): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 7136): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,I/QRemote ( 7136): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 7136): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 7136): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 7136): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 7136): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 7136): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/QRemote ( 7136): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 7136): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7112): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7112): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
,D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7112): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
,D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 7136): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7136): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,D/QRemote ( 7136): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 7136): LgDataFeature() Constructor: none
D/LgDataFeature( 7136): LgDataFeature() Constructor Done, null
,V/SoundPool( 7136): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 7136): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 7136): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 7136): doLoad: loading sample sampleID=1
I/QRemote ( 7136): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,V/SoundPool( 7136): Start decode
V/MediaPlayer[Native]( 7136): decode(31, 10857164, 17813)
V/MediaPlayerService(  317): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  317): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  317): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  317): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  317): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  317): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  317): player type = 3
V/AwesomePlayer(  317): AwesomePlayer create()
V/AwesomePlayer(  317): reset_l() 
V/AwesomePlayer(  317): cancelPlayerEvents
V/AwesomePlayer(  317): setAudioSink() 
V/AwesomePlayer(  317): reset_l() 
,V/AudioCache(  317): notify(0xb5474b80, 8, 0, 0)
V/AudioCache(  317): ignored
V/AwesomePlayer(  317): cancelPlayerEvents,
D/Utils   (  317): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
,V/AwesomePlayer(  317): setDataSource_l dataSource
V/LGParserOSAL(  317): SniffLGParser start
,V/LGParserOSAL(  317): MainType:5, SubType=0
V/LGParserOSAL(  317): #### check Mime : application/ogg
,V/LGParserOSAL(  317): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  317): Use LGExtractor :application/ogg ,
,D/UEI.SmartControl( 6876): QS Service created
D/QRemote ( 7136): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 7136): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7136): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,V/LGParserOSAL(  317): supported mime: application/ogg
V/AwesomePlayer(  317): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  317): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  317): mBitrate = -1 bits/sec
V/AwesomePlayer(  317): AudioTrack Setting
V/AwesomePlayer(  317): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  317): setAudioSource() 
V/MediaPlayerService(  317): prepare
V/AwesomePlayer(  317): prepareAsync_l() 
I/UEI.SmartControl( 6876): Service initServices...
V/MediaPlayerService(  317): wait for prepare
D/UEI.SmartControl( 6876): QS start get config
V/AwesomePlayer(  317): onPrepareAsyncEvent() 
V/AwesomePlayer(  317): initAudioDecoder() 
W/Utils   (  317): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  317): isOffloadSupported()
V/AudioPolicyManager(  317): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  317): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  317): isAudioPlaybackHookOn() false
V/AwesomePlayer(  317): getUseOffload() = 0 
V/OMXCodec(  317): OMXCodec::Create
V/OMXCodec(  317): findMatchingCodecs()
V/OMXCodec(  317): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  317): matchingCodecs.size()=1
V/OMXCodec(  317): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  317): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  317): LG Codec Adapter start
V/OMXCodec(  317): OMXCodec Createtor
V/OMXCodec(  317): setComponentRole
V/OMXCodec(  317): configureCodec protected=0
V/LGCodecAdapter(  317): called getLGCodecSpecificData
V/LGCodecOSAL(  317): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  317): Called LGconfigureCodecMETA
V/LGCodecOSAL(  317): Called LGconfigureCodecMSG
V/LGCodecOSAL(  317): Not support LGCodec
V/OMXCodec(  317): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  317): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  317): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  317): Could not offload audio decode, try pcm offload
W/Utils   (  317): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  317): isOffloadSupported()
V/AudioPolicyManager(  317): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  317): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  317): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  317): init()
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  317): allocateBuffers
V/OMXCodec(  317): allocateBuffersOnPort portIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc0b0 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on input port
V/OMXCodec(  317): allocateBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] ,allocated buffer 0xb14fca10 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcba0 on output port
V/OMXCodec(  317): init() mAsyncCompletion wait!!! 
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  317): init() mAsyncCompletion wait!!! 
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/LGMDMManager( 7136): Create singleton instance
V/OMXCodec(  317): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  317): finishAsyncPrepare_l() 
V/AudioCache(  317): notify(0xb5474b80, 5, 0, 0)
V/AudioCache(  317): ignored
V/AudioCache(  317): notify(0xb5474b80, 1, 0, 0)
V/AudioCache(  317): prepared
V/AudioCache(  317): wait - success
V/MediaPlayerService(  317): start
V/AwesomePlayer(  317): play_l() 
V/AwesomePlayer(  317): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  317): createAudioPlayer_l
V/AwesomePlayer(  317): seekAudioIfNecessary_l() 
V/AwesomePlayer(  317): startAudioPlayer_l() 
D/AudioPlayer(  317): start of Playback, useOffload 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  317): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  317): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  317): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795904
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796064
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796304
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796704
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  317): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  317): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  317): allocateBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca10 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc920 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on output port
V/OMXCodec(  317): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  317): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  317): notify(0xb5474b80, 6, 0, 0)
V/AudioCache(  317): ignored
V/MediaPlayerService(  317): wait for playback complete
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac700000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac701000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac702000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac703000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac704000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac705000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac706000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac707000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac708000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac709000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac70a000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac70b000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac70c000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac70d000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac70e000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac70f000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac710000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac711000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac712000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac713000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac714000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac715000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac716000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac717000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac718000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac719000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac71a000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac71b000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac71c000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac71d000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac71e000, 0xb57e0000, 4096)
,V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac71f000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac720000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac721000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac722000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac723000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac724000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac725000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac726000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac727000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac728000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac729000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac72a000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac72b000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac72c000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac72d000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac72e000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac72f000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac730000, 0xb57e0000, 4096)
V/AudioCache(  317): write(0xb57e0000, 4096)
V/AudioCache(  317): memcpy(0xac731000, 0xb57e0000, 4096)
V/OMXCodec(  317): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  317): postAudioEOS() 
V/AudioCache(  317): write(0xb57e0000, 280)
V/AudioCache(  317): memcpy(0xac732000, 0xb57e0000, 280)
V/AwesomePlayer(  317): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  317): onStreamDone
V/AwesomePlayer(  317): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  317): notify(0xb5474b80, 2, 0, 0)
V/AudioCache(  317): playback complete
V/AwesomePlayer(  317): pause_l() 
V/AudioCache(  317): wait - success
V/AudioCache(  317): notify(0xb5474b80, 7, 0, 0)
V/AudioCache(  317): ignored
V/MediaPlayerService(  317): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  317): cancelPlayerEvents
D/AudioPlayer(  317): Pause Playback at 1068125
V/AwesomePlayer(  317): reset_l() 
V/AudioCache(  317): notify(0xb5474b80, 8, 0, 0)
V/AudioCache(  317): ignored
V/AwesomePlayer(  317): cancelPlayerEvents
D/AudioPlayer(  317): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  317): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc830 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc0b0 on port 0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc920 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeing buffer 0xb14fca10 on port 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  317): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  317): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  317): AudioPlayer releasing audio source
D/AudioPlayer(  317): AudioPlayer done releasing audio source
V/AwesomePlayer(  317): reset_l() 
V/AwesomePlayer(  317): cancelPlayerEvents
V/AwesomePlayer(  317): ~AwesomePlayer call
V/AwesomePlayer(  317): reset_l() 
V/AwesomePlayer(  317): cancelPlayerEvents
V/SoundPool( 7136): close(31)
V/SoundPool( 7136): pointer = 0x9ffb9000, size = 205080, sampleRate = 48000, numChannels = 2
,D/QRemote ( 7136): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 7136): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 7136): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2099
I/UEI.SmartControl( 6876): Supports setup maps: true
,D/UEI.SmartControl( 6876): QS start statue = true Error code = 0
,I/UEI.SmartControl( 6876): QS version = v2.7.10.1_RC1
,I/UEI.SmartControl( 6876): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6876): ### init IR Blaster...
D/serial_port( 6876): Configuring serial port
E/UEI.SmartControl( 6876): UEIBLaster setting for 616
I/UEI.SmartControl( 6876): Setting serial record hearder size = 2
,I/UEI.SmartControl( 6876): configuring settings for MAXQ616
I/UEI.SmartControl( 6876): Get version...
D/UEI.SmartControl( 6876): serial port data available: 21
,D/UEI.SmartControl( 6876): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6876): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6876): QS saving settings...
,D/UEI.SmartControl( 6876): IR Blaster version: 25672567
,D/UEI.SmartControl( 6876): serial port data available: 4
,I/UEI.SmartControl( 6876): Device manager: loading config....
W/ContextImpl( 6876): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,D/UEI.SmartControl( 6876): ----------- loading internal config...
E/UEI.SmartControl( 6876): Services init done
D/UEI.SmartControl( 6876): QS Service init finished
D/UEI.SmartControl( 6876): QS Service version name: 2.1.91
D/UEI.SmartControl( 6876): QS Service version code: 201091
D/UEI.SmartControl( 6876): Service requested: Control
D/UEI.SmartControl( 6876): Request IControl service: devices are loaded...
E/UEI.SmartControl( 6876): Loading SETTINGS...
,I/QRemote ( 7136): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6876): Internal service binding...
I/UEI.SmartControl( 6876): ------ IControl API: 11
D/UEI.SmartControl( 6876): File observer start...
E/UEI.SmartControl( 6876): IR Port is disabled: false
D/UEI.SmartControl( 6876): Starting file observer...
I/UEI.SmartControl( 6876): Registering callback...
,I/UEI.SmartControl( 6876): ------ IControl API: 19
I/UEI.SmartControl( 6876): Registering Services Ready callback...
,D/UEI.SmartControl( 6876): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6876): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6876): -----service ready thread exits
I/QRemote ( 7136): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 7136): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 7136): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 7136): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 7136): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,I/UEI.SmartControl( 6876): ------ IControl API: 8
D/QRemote ( 7136): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 7136): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 7136): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 7136): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 7136): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 7136): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 7136): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,V/QRemote ( 7136): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 7136): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 7136): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,D/QRemote ( 7136): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 7136): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 7136): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 7136): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 7136): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1450361539393]
D/QRemote ( 7136): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1038): Killing 6159:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/QRemote ( 7136): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_6159/cgroup.procs: No such file or directory
,V/QRemote ( 7136): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 7136): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 7136): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 7136): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 7136): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 7136): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 7136): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 7136): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 7001): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 7001): 
I/jxcore-log( 7001): my name is : LGE-LG-D855_PT1108
I/jxcore-log( 7001): 
I/wpa_supplicant( 2751): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=164575  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=164576  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/jxcore-log( 7001): attempting to connect to test coordinator
I/jxcore-log( 7001): 
I/jxcore-log( 7001): check test folder
I/jxcore-log( 7001): 
I/jxcore-log( 7001): found test : ./testFindPeers.js
I/jxcore-log( 7001): 
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/jxcore-log( 7001): found test : ./testReConnect.js
I/jxcore-log( 7001): 
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
I/jxcore-log( 7001): found test : ./testSendData.js
I/jxcore-log( 7001): 
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
,D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/jxcore-log( 7001): Test app app.js loaded
I/jxcore-log( 7001): 
I/wpa_supplicant( 2751): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=164680  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=164681  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=164682
E/WifiStateMachine( 1038):  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=164682
E/WifiStateMachine( 1038):  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=164682
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=164683
E/WifiStateMachine( 1038):  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=164683
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=164683  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
,I/wpa_supplicant( 2751): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2751): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/Tethering( 1038): sendTetherStateChangedBroadcast 1, 0, 0
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7079): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7079): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : activeList=[]
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
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7079): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : TetherState Changed=wlan0
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
I/chromium( 7001): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/UsbSettingsControl( 7079): [AUTORUN] setTetherStatus() : status=false
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=164699  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=164708  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=164709  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=164710
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=164710
D/WifiNative-wlan0( 1038): doString: [STATUS]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
I/chromium( 7001): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/WifiNative-wlan0( 1038):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
I/WifiServiceExtension( 1038): setVHTCapabilityType  : false
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
I/WifiServerServiceExt( 1038): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1038): setKeepAlivePacketInterval msec : 60
,D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=1038524618, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{1aac88ef type 0 when 1450361539684 com.android.vending} when 1450361539684
,D/ConnectivityService( 1038): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1038): Got NetworkAgent Messenger
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,D/ConnectivityService( 1038): NetworkAgent connected
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
,D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/[Concierge]Service( 2583): onStartCommand(). Type : 9
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/CommandListener(  313): Setting iface cfg
E/WifiStateMachine( 1038): Start Dhcp Watchdog 2
D/DhcpStateMachine( 1038): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=164768  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=164768  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=164769  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=164771  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=164771  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=164772  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=1038524618 [*alarm*], flags=0x0
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
I/wpa_supplicant( 2751): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 0
D/WifiNative-wlan0( 1038): SET ps 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2751): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1038): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a546203 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a546203 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1038): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): DHCP Start wake lock is acquired.
D/CommandListener(  313): Setting iface cfg
D/CommandListener(  313): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1038): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1038):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2751): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2751): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1038): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1038): Adding iface wlan0 to network 101
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1038): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,V/WfdStateTracker( 1970): handleWifiStateChangedEvent: 1
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
E/ConnectivityService( 1038): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1038): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService( 1038): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/Netd    (  313): netlink response contains error (File exists)
,D/ConnectivityService( 1038): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService( 1038): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1038): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService( 1038): Setting Dns servers for network 101 to [/192.168.1.1]
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Connected
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1038): currentScore = 0, newScore = 20
D/ConnectivityService( 1038):    accepting network in place of null
D/ConnectivityService( 1038): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1870): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1038): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1038): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1,038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1038): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1038): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1038): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 28
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService( 1038): validation of new default Network = false
D/ConnectivityService( 1038): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1038): enableDataServiceNotify 
D/DSQN    ( 1038): start dsqn bin
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,V/NetworkPolicy( 1038): [LG_RESTRICTED] checkMobilePolicy_type()
,D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524290
W/dsqn    ( 7197): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 7197): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/DSQN    ( 7197): DSQN ssw
,V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
,D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
,D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 1
D/QRemote ( 7136): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7136): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7136): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7136): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 7136): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 7136): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  313): res_queryN name = clients3.google.com succeed
,D/LGDataListener(  313): argv[0]=dsqncommand
D/LGDataListener(  313): argv[1]=wlan0
D/LGDataListener(  313): argv[2]=1
D/LGDataListener(  313): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1038): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1038): start to monitor internet connection
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 17 Dec 2015 14:12:20 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450361540440], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450361540423]}
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
,D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524290
D/ConnectivityService( 1038): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1870): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DhcpStateMachine( 1038): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1038): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1038): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/dhcpcd  ( 7203): type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 7203): type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dhcpcd  ( 7203): version 5.5.6 starting
E/dhcpcd  ( 7203): get_duid: m
D/dhcpcd  ( 7203): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 7203): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/Finsky  ( 6264): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6264): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6264): [1] 5.onFinished: Scheduling replication attempt 4.
,D/dhcpcd  ( 7203): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 7203): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 7203): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 7203): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 7203): wlan0: sending REQUEST (xid 0xfd3a4b77), next in 4.97 seconds
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5933): type=WIFI subType= reason=null isConnected=true
,W/ContextImpl( 6644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,I/NetworkMonitor( 5933): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7220 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppUp4:AppBoxCP( 7220): onCreate
,W/AppUp4:DB( 7220):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7220):  setFingerPrint start
I/AppUp4:DB( 7220):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 7220):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 7220):  SDK version = 21
I/AppUp4:DB( 7220):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7220): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7220): onReceive
D/LgDataFeature( 7220): LgDataFeature() Constructor: none
D/LgDataFeature( 7220): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7220): Context : android.app.ReceiverRestrictedContext@275442fa
D/AppUp4:CustFacade( 7220): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7220): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7220): begin check event
I/AppUp4:CustModeStarterReceiver( 7220): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7220): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 7220): call method handleAsyncCustNotification.
,D/AppUp4:CustModeStarterReceiver( 7220): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 7220): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1038): Killing 6179:com.android.contacts/u0a19 (adj 15): empty #17
I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/libprocessgroup( 1038): failed to open /acct/uid_10019/pid_6179/cgroup.procs: No such file or directory
,W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/DownloadManager( 3427): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,V/DownloadManager( 3427): DownloadService onCreate
I/LGDMClient( 4326): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3427): in removeSpuriousFiles
V/DownloadManager( 3427): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@c82ff5f on behalf of 3427
V/DownloadManager( 3427): DownloadService onStartCommand
V/DownloadManager( 3427): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@248f7a0a on behalf of 3427
I/DownloadManager( 3427): in trimDatabase
V/DownloadManager( 3427): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
E/LGDMClient( 4326): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
,D/LGDMClient( 4326): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4326): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@3602327b on behalf of 3427
V/DownloadManager( 3427): processing inserted download 1
,V/DownloadManager( 3427): processing inserted download 4
V/DownloadManager( 3427): processing inserted download 7
V/DownloadManager( 3427): processing inserted download 8
V/DownloadManager( 3427): processing inserted download 9
V/DownloadManager( 3427): processing inserted download 10
V/DownloadManager( 3427): processing inserted download 16
V/DownloadManager( 3427): processing inserted download 17
V/DownloadManager( 3427): processing inserted download 18
V/DownloadManager( 3427): processing inserted download 21
,V/DownloadManager( 3427): DownloadService onDestroy
D/eas_req ( 6697): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager( 1038): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7267 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/HubEmail( 6697): JNI_OnLoad()
I/HubEmail( 6697): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6697): registerNatives()
I/HubEmail( 6697): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6697): registerNativeMethods()
I/HubEmail( 6697): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6697): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6697): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 6697): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LgeMiscReceiver( 3377): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3377): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3377): networkInfo.isConnected() = false
,I/ActivityManager( 1038): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7290 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  313): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,I/dhcpcd  ( 7203): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
I/dhcpcd  ( 7203): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 7203): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 7203): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 7203): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 7203): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/dhcpcd  ( 7203): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 7203): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 7203): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,D/libc-netbsd(  313): res_queryN name = static-avc.lglime.com succeed
,V/FormManager( 7267): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7267): Alarm would be updated, because LastCheckTime has been updated.
I/ActivityManager( 1038): Killing 6727:com.android.gallery3d/u0a27 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10027/pid_6727/cgroup.procs: No such file or directory
,I/ActivityManager( 1038): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7335 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 6579:com.android.defcontainer/u0a4 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10004/pid_6579/cgroup.procs: No such file or directory
D/DhcpStateMachine( 1038): DHCPV4 succeeded on wlan0
E/WifiStateMachine( 1038):  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/LgDhcpStateMachineHelper( 1038): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1038): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1038): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper( 1038): bShouldSendDhcpAction Result: false
D/DhcpStateMachine( 1038): DHCP Start/Renew wake lock is released.
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/DhcpStateMachine( 1038): RunningState
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService( 1038): identical MTU - not setting
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524295
,I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7356 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6751:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6751/cgroup.procs: No such file or directory
,I/art     ( 7356): Almond Protected OAT
,D/WeatherApplication( 7356): removeAccount
,D/WeatherApplication( 7356): Account.length = 0
,E/WeatherApplication( 7356): OPERATOR:OPEN
D/WeatherAncestor( 7356): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:12:22
,D/Weather.Utils( 7356): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7356): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7356): 2 : This is isUpdating : false
D/WeatherAncestor( 7356): connectivity changed - connection : true
D/WeatherService( 7356): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 7356): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7356): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 7356): 2 : Cache is not up-to-date, count: 0
D/Weather_cast( 7356): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7356): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:12:22
,I/ActivityManager( 1038): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7374 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6783:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10080/pid_6783/cgroup.procs: No such file or directory
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7374): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7374): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7374): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7374): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/WifiStateMachine( 1038):  ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  L2ConnectedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  ConnectModeState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DriverStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1,
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
E/WifiStateMachine( 1038):  DefaultState CMD_DISCONNECTING_WATCHDOG_TIMER 1 0 cur=1
,I/WebViewFactory( 7374): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 7374): Loading: webviewchromium
,I/LibraryLoader( 7374): Time to load native libraries: 13 ms (timestamps 7490-7503)
I/LibraryLoader( 7374): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7374): Binding Chromium to main looper Looper (main, tid 1) {13615a4d}
,I/LibraryLoader( 7374): Expected native library version number "",actual native library version number ""
I/chromium( 7374): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7374): Initializing chromium process, renderers=0
,W/art     ( 7374): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7374): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7374): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,V/AudioPolicyService(  317): registerClient() client 0xb57bc2c0, uid 10093
I/chromium( 7374): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
W/AudioManagerAndroid( 7374): Requires BLUETOOTH permission
I/Adreno-EGL( 7374): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7374): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7374): Build Date: 12/12/14 금
I/Adreno-EGL( 7374): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 7374): Remote Branch: 
I/Adreno-EGL( 7374): Local Patches: 
I/Adreno-EGL( 7374): Reconstruct Branch: 
,I/NSApplication( 7374): Starting up...
,I/ActivityManager( 1038): Killing 6829:com.lge.eula/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6829/cgroup.procs: No such file or directory
,V/WifiInternetCheck( 1038): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 5933): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7220): onReceive
D/AppUp4:CustFacade( 7220): Context : android.app.ReceiverRestrictedContext@275442fa
D/AppUp4:CustFacade( 7220): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7220): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7220): begin check event
I/AppUp4:CustModeStarterReceiver( 7220): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 105179(4MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 2.927ms total 171.431ms
,W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,V/DownloadManager( 3427): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3427): DownloadService onCreate
I/DownloadManager( 3427): in removeSpuriousFiles
V/DownloadManager( 3427): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@34f6c8f1 on behalf of 3427
I/LGDMClient( 4326): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
,I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
,I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,I/DownloadManager( 3427): in trimDatabase
V/DownloadManager( 3427): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@19b32cd6 on behalf of 3427
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3427): DownloadService onStartCommand
V/DownloadManager( 3427): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@c1e032d on behalf of 3427
,E/LGDMClient( 4326): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4326): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4326): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LgeMiscReceiver( 3377): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3377): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3377): networkInfo.isConnected() = false
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/DownloadManager( 3427): processing inserted download 1
V/DownloadManager( 3427): processing inserted download 4
V/DownloadManager( 3427): processing inserted download 7
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
V/DownloadManager( 3427): processing inserted download 8
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/DownloadManager( 3427): processing inserted download 9
W/Settings( 6697): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3427): processing inserted download 10
D/LgeQuickCoverNLService( 1417): onNotificationPosted
W/Kids    ( 2365): [AccountUtils] Account not ready
W/Kids    ( 2365): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2365): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2365): 	at java.lang.Thread.run(Thread.java:818)
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
W/Settings( 6697): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/WeatherAncestor( 7356): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:12:23
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
D/Weather.Utils( 7356): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7356): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7356): 2 : This is isUpdating : false
D/WeatherAncestor( 7356): connectivity changed - connection : true
D/WeatherService( 7356): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3be9f308
D/ForecastDataCache( 7356): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7356): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7356): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7356): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7356): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:12:23
V/DownloadManager( 3427): processing inserted download 16
V/DownloadManager( 3427): processing inserted download 17
V/DownloadManager( 3427): processing inserted download 18
V/DownloadManager( 3427): processing inserted download 21
,D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2f8d4062 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
V/DownloadManager( 3427): DownloadService onDestroy
D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
W/ContextImpl( 6644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7220): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7220): onReceive
,D/AppUp4:CustFacade( 7220): Context : android.app.ReceiverRestrictedContext@275442fa
D/AppUp4:CustFacade( 7220): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7220): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7220): begin check event
I/AppUp4:CustModeStarterReceiver( 7220): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
V/DownloadManager( 3427): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/DownloadManager( 3427): DownloadService onCreate
I/LGDMClient( 4326): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/FormManager( 7267): There are no updated forms. The schedule will be deleted.
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3427): in removeSpuriousFiles
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/DownloadManager( 3427): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@368e75f3 on behalf of 3427
V/FormManager( 7267): Alarm would be updated, because LastCheckTime has been updated.
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3427): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3427): in trimDatabase
V/DownloadManager( 3427): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@f8a72b0 on behalf of 3427
E/LGDMClient( 4326): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
D/LGDMClient( 4326): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
D/LGDMClient( 4326): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LgeMiscReceiver( 3377): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3377): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3377): networkInfo.isConnected() = true
D/PhoneState( 3377): setPdpRejectCasuse : false
,W/Settings( 6697): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/DownloadManager( 3427): DownloadService onStartCommand
V/DownloadManager( 3427): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3427): created cursor android.database.sqlite.SQLiteCursor@10107e4f on behalf of 3427
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Settings( 6697): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/WeatherAncestor( 7356): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:12:23
,D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2365): [AccountUtils] Account not ready
W/Kids    ( 2365): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2365): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2365): 	at java.lang.Thread.run(Thread.java:818)
D/Weather.Utils( 7356): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7356): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7356): 2 : This is isUpdating : false
D/WeatherAncestor( 7356): connectivity changed - connection : true
D/WeatherService( 7356): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3be9f308
D/ForecastDataCache( 7356): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7356): 2 : currentPackageVersion: 4.40.4
V/DownloadManager( 3427): processing inserted download 1
D/ForecastDataCache( 7356): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7356): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7356): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:12:23
,D/LgeQuickCoverNLService( 1417): onNotificationPosted
V/DownloadManager( 3427): processing inserted download 4
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
V/DownloadManager( 3427): processing inserted download 7
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
V/DownloadManager( 3427): processing inserted download 8
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
V/DownloadManager( 3427): processing inserted download 9
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
V/DownloadManager( 3427): processing inserted download 10
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
V/DownloadManager( 3427): processing inserted download 16
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
V/DownloadManager( 3427): processing inserted download 17
V/DownloadManager( 3427): processing inserted download 18
V/DownloadManager( 3427): processing inserted download 21
V/DownloadManager( 3427): DownloadService onDestroy
D/QuickStatusbarLayout( 1417): Notification difference=198
,D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2f8d4062 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/FormManager( 7267): There are no updated forms. The schedule will be deleted.
,V/FormManager( 7267): Alarm would be updated, because LastCheckTime has been updated.
I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/Kids    ( 2365): [AccountUtils] Account not ready
W/Kids    ( 2365): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2365): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2365): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2365): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2365): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2365): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 1417): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1417): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
,D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0,
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
W/ResourcesManager( 1417): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1417): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2f8d4062 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/UEI.SmartControl( 6876): Internal timer expired: 2
D/UEI.SmartControl( 6876): unbind internal service
,D/serial_port( 6876): close(fd = 24)
,I/UEI.SmartControl( 6876): Serial port is closed.
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  313): res_queryN name = www.google.com, class = 1, type = 1
D/libc-netbsd(  313): res_queryN name = www.google.com succeed
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{3eb0cd4c type 2 when 169089 com.google.android.gms} when 169089
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  313): res_queryN name = clients3.google.com succeed
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = mtalk.google.com, class = 1, type = 1
V/QRemote ( 7136): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 7136): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2099
D/libc-netbsd(  313): res_queryN name = mtalk.google.com succeed
,V/WifiInternetCheck( 1038): isHttpConnectionAvailable - We got a valid response : 204
,D/GCM     ( 2133): Connected
,D/GCM     ( 2133): Message class com.google.f.a.a.p
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 7001): BLE supported!!
I/jxcore-log( 7001): 
V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{249cc195 type 2 when 169888 android} when 169888
,I/ActivityManager( 1038): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7485 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ReaderUtils( 7485): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,W/GAV2    ( 7485): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7485): Created application version: 3.2.35 (30235)
,I/BooksSync( 7485): Starting books sync
,D/BooksSync( 7485): started syncMyEbooks
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2133): Explicit concurrent mark sweep GC freed 29141(1692KB) AllocSpace objects, 13(1872KB) LOS objects, 51% free, 30MB/62MB, paused 1.838ms total 67.919ms
,V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
,D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/BooksAccountManager( 7485): Authentication error
E/BooksAccountManager( 7485): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7485): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7485): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7485): null auth token
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
,D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2f8d4062 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  313): res_queryN name = www.googleapis.com succeed
,W/ApiaryClient( 7485): Error response from books API: {
W/ApiaryClient( 7485):  "error": {
W/ApiaryClient( 7485):   "errors": [
W/ApiaryClient( 7485):    {
W/ApiaryClient( 7485):     "domain": "global",
W/ApiaryClient( 7485):     "reason": "required",
W/ApiaryClient( 7485):     "message": "Login Required",
W/ApiaryClient( 7485):     "locationType": "header",
W/ApiaryClient( 7485):     "location": "Authorization"
W/ApiaryClient( 7485):    }
W/ApiaryClient( 7485):   ],
W/ApiaryClient( 7485):   "code": 401,
W/ApiaryClient( 7485):   "message": "Login Required"
W/ApiaryClient( 7485):  }
W/ApiaryClient( 7485): }
,W/ApiaryClient( 7485): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7485): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4096802863370143052&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7485): Headers:
W/ApiaryClient( 7485): accept-encoding: [gzip]
W/ApiaryClient( 7485): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7485): gdata-version: 2
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7485): Authentication error
E/BooksAccountManager( 7485): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7485): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7485): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7485): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2f8d4062 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/GAV4    ( 7374): Thread[GAThread,5,main]: No campaign data found.
W/ApiaryClient( 7485): Error response from books API: {
W/ApiaryClient( 7485):  "error": {
W/ApiaryClient( 7485):   "errors": [
W/ApiaryClient( 7485):    {
W/ApiaryClient( 7485):     "domain": "global",
W/ApiaryClient( 7485):     "reason": "required",
W/ApiaryClient( 7485):     "message": "Login Required",
W/ApiaryClient( 7485):     "locationType": "header",
W/ApiaryClient( 7485):     "location": "Authorization"
W/ApiaryClient( 7485):    }
W/ApiaryClient( 7485):   ],
W/ApiaryClient( 7485):   "code": 401,
W/ApiaryClient( 7485):   "message": "Login Required"
W/ApiaryClient( 7485):  }
W/ApiaryClient( 7485): }
,W/ApiaryClient( 7485): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7485): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4096802863370143052&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7485): Headers:
W/ApiaryClient( 7485): accept-encoding: [gzip]
W/ApiaryClient( 7485): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7485): gdata-version: 2
I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
,D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2f8d4062 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 7485): Authentication error
E/BooksAccountManager( 7485): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7485): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7485): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7485): null auth token
W/ApiaryClient( 7485): Error response from books API: {
W/ApiaryClient( 7485):  "error": {
W/ApiaryClient( 7485):   "errors": [
W/ApiaryClient( 7485):    {
W/ApiaryClient( 7485):     "domain": "global",
W/ApiaryClient( 7485):     "reason": "required",
W/ApiaryClient( 7485):     "message": "Login Required",
W/ApiaryClient( 7485):     "locationType": "header",
W/ApiaryClient( 7485):     "location": "Authorization"
W/ApiaryClient( 7485):    }
W/ApiaryClient( 7485):   ],
W/ApiaryClient( 7485):   "code": 401,
W/ApiaryClient( 7485):   "message": "Login Required"
W/ApiaryClient( 7485):  }
W/ApiaryClient( 7485): }
W/ApiaryClient( 7485): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7485): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4096802863370143052&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7485): Headers:
W/ApiaryClient( 7485): accept-encoding: [gzip]
W/ApiaryClient( 7485): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7485): gdata-version: 2
,E/BooksSync( 7485): Soft error: 
E/BooksSync( 7485): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7485): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4096802863370143052&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7485): Headers:
E/BooksSync( 7485): accept-encoding: [gzip]
E/BooksSync( 7485): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7485): gdata-version: 2
E/BooksSync( 7485): 
E/BooksSync( 7485): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7485): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7485): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7485): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7485): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7485): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7485): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7485): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7485): {
E/BooksSync( 7485):  "error": {
E/BooksSync( 7485):   "errors": [
E/BooksSync( 7485):    {
E/BooksSync( 7485):     "domain": "global",
E/BooksSync( 7485):     "reason": "required",
E/BooksSync( 7485):     "message": "Login Required",
E/BooksSync( 7485):     "locationType": "header",
E/BooksSync( 7485):     "location": "Authorization"
E/BooksSync( 7485):    }
E/BooksSync( 7485):   ],
E/BooksSync( 7485):   "code": 401,
E/BooksSync( 7485):   "message": "Login Required"
E/BooksSync( 7485):  }
E/BooksSync( 7485): }
E/BooksSync( 7485): 
E/BooksSync( 7485): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7485): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7485): 	... 8 more
,E/BooksSync( 7485): Sync error
E/BooksSync( 7485): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7485): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-4096802863370143052&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7485): Headers:
E/BooksSync( 7485): accept-encoding: [gzip]
E/BooksSync( 7485): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7485): gdata-version: 2
E/BooksSync( 7485): 
E/BooksSync( 7485): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7485): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7485): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7485): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7485): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7485): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7485): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7485): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7485): {
E/BooksSync( 7485):  "error": {
E/BooksSync( 7485):   "errors": [
E/BooksSync( 7485):    {
E/BooksSync( 7485):     "domain": "global",
E/BooksSync( 7485):     "reason": "required",
E/BooksSync( 7485):     "message": "Login Required",
E/BooksSync( 7485):     "locationType": "header",
E/BooksSync( 7485):     "location": "Authorization"
E/BooksSync( 7485):    }
E/BooksSync( 7485):   ],
E/BooksSync( 7485):   "code": 401,
E/BooksSync( 7485):   "message": "Login Required"
E/BooksSync( 7485):  }
E/BooksSync( 7485): }
E/BooksSync( 7485): 
E/BooksSync( 7485): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7485): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7485): 	... 8 more
I/BooksSync( 7485): Finished books sync
I/ActivityManager( 1038): Killing 6857:com.lge.bnr/1000 (adj 15): empty #17
,D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 169888, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6857/cgroup.procs: No such file or directory
,I/GAV2    ( 7485): Thread[GAThread,5,main]: No campaign data found.
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 177775770665; DSPS: 5965950; Offset : -4302579235
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{30a9fc47 type 0 when 1450361560526 com.android.vending} when 1450361560526
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{29283c74 type 2 when 186901 com.google.android.gms} when 186901
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
I/[SystemUI]LGPowerUI( 1466): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1466): On Skip Timer : true
,D/WifiController( 1038): battery changed pluggedType: 2
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1466): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/[SystemUI]LGPowerUI( 1466): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 3822): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1466): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1970): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1970): Battery Level Remaining: 100%
,D/LEDHandler( 1970): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/VacuumService( 2133): Vacuum at: now=1450361563847 tag=VacuumService
,I/GoogleURLConnFactory( 2133): Using platform SSLCertificateSocketFactory
,W/Uploader( 2133): No account for auth token provided
I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  313): res_queryN name = play.googleapis.com, class = 1, type = 1
,D/libc-netbsd(  313): res_queryN name = play.googleapis.com succeed
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 27364(1278KB) AllocSpace objects, 8(896KB) LOS objects, 33% free, 44MB/66MB, paused 1.907ms total 123.645ms
,W/Uploader( 2133): No account for auth token provided
I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6264): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6264): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6264): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 2133): No account for auth token provided
,W/Uploader( 2133): No account for auth token provided
,W/Uploader( 2133):  no longer exists, so no auth token.
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 197781092376; DSPS: 6621484; Offset : -4302567452
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{999aa3c type 2 when 200006 android} when 200006
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
E/WifiStateMachine( 1038):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
E/WifiStateMachine( 1038):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 217783068150; DSPS: 7276909; Offset : -4302575295
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=1038524618, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{2643011a type 0 when 1450361584184 com.android.vending} when 1450361584184
,D/[Concierge]Service( 2583): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=1038524618 [*alarm*], flags=0x0
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6264): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6264): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6264): [1] 5.onFinished: Giving up after 6 failures.
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 237784271892; DSPS: 7932309; Offset : -4302592204
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{4ba1a6c type 2 when 239260 android} when 239260
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,I/[SystemUI]LGPowerUI( 1466): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1466): On Skip Timer : true
,D/LEDHandler( 1970): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1970): Battery Level Remaining: 100%
,D/LEDHandler( 1970): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1466): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1466): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController( 1038): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1466): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 3822): Disconnected process message: 10, size: 0
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 257786238186; DSPS: 8587733; Offset : -4302579218
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 277788349533; DSPS: 9243162; Offset : -4302573453
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 297790879890; DSPS: 9898605; Offset : -4302576108
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=1038524618, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{12d25835 type 2 when 300394 android} when 300394
D/[Concierge]Service( 2583): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=1038524618 [*alarm*], flags=0x0
,I/BooksSync( 7485): Starting books sync
,D/BooksSync( 7485): started syncMyEbooks
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
,D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
,D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7485): Authentication error
E/BooksAccountManager( 7485): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7485): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7485): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7485): null auth token
,D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2f8d4062 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7485): Error response from books API: {
W/ApiaryClient( 7485):  "error": {
W/ApiaryClient( 7485):   "errors": [
W/ApiaryClient( 7485):    {
W/ApiaryClient( 7485):     "domain": "global",
W/ApiaryClient( 7485):     "reason": "required",
W/ApiaryClient( 7485):     "message": "Login Required",
W/ApiaryClient( 7485):     "locationType": "header",
W/ApiaryClient( 7485):     "location": "Authorization"
W/ApiaryClient( 7485):    }
W/ApiaryClient( 7485):   ],
W/ApiaryClient( 7485):   "code": 401,
W/ApiaryClient( 7485):   "message": "Login Required"
W/ApiaryClient( 7485):  }
W/ApiaryClient( 7485): }
W/ApiaryClient( 7485): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7485): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6942645628764907678&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7485): Headers:
W/ApiaryClient( 7485): accept-encoding: [gzip]
W/ApiaryClient( 7485): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7485): gdata-version: 2
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7485): Authentication error
E/BooksAccountManager( 7485): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7485): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7485): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7485): null auth token
D/QuickStatusbarLayout( 1417): Notification difference=198
,D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2f8d4062 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7485): Error response from books API: {
W/ApiaryClient( 7485):  "error": {
W/ApiaryClient( 7485):   "errors": [
W/ApiaryClient( 7485):    {
W/ApiaryClient( 7485):     "domain": "global",
W/ApiaryClient( 7485):     "reason": "required",
W/ApiaryClient( 7485):     "message": "Login Required",
W/ApiaryClient( 7485):     "locationType": "header",
W/ApiaryClient( 7485):     "location": "Authorization"
W/ApiaryClient( 7485):    }
W/ApiaryClient( 7485):   ],
W/ApiaryClient( 7485):   "code": 401,
W/ApiaryClient( 7485):   "message": "Login Required"
W/ApiaryClient( 7485):  }
W/ApiaryClient( 7485): }
,W/ApiaryClient( 7485): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7485): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6942645628764907678&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7485): Headers:
W/ApiaryClient( 7485): accept-encoding: [gzip]
W/ApiaryClient( 7485): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7485): gdata-version: 2
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
,D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
,D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 7485): Authentication error
E/BooksAccountManager( 7485): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 7485): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 7485): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 7485): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 7485): null auth token
,D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2f8d4062 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 7485): Error response from books API: {
W/ApiaryClient( 7485):  "error": {
W/ApiaryClient( 7485):   "errors": [
W/ApiaryClient( 7485):    {
W/ApiaryClient( 7485):     "domain": "global",
W/ApiaryClient( 7485):     "reason": "required",
W/ApiaryClient( 7485):     "message": "Login Required",
W/ApiaryClient( 7485):     "locationType": "header",
W/ApiaryClient( 7485):     "location": "Authorization"
W/ApiaryClient( 7485):    }
W/ApiaryClient( 7485):   ],
W/ApiaryClient( 7485):   "code": 401,
W/ApiaryClient( 7485):   "message": "Login Required"
W/ApiaryClient( 7485):  }
W/ApiaryClient( 7485): }
,W/ApiaryClient( 7485): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7485): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6942645628764907678&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7485): Headers:
W/ApiaryClient( 7485): accept-encoding: [gzip]
W/ApiaryClient( 7485): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 7485): gdata-version: 2
I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,E/BooksSync( 7485): Soft error: 
E/BooksSync( 7485): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7485): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6942645628764907678&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7485): Headers:
E/BooksSync( 7485): accept-encoding: [gzip]
E/BooksSync( 7485): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7485): gdata-version: 2
E/BooksSync( 7485): 
E/BooksSync( 7485): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7485): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7485): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7485): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7485): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7485): 	at com.google.android.apps.books.data.NetworkTaskQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7485): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7485): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7485): {
E/BooksSync( 7485):  "error": {
E/BooksSync( 7485):   "errors": [
E/BooksSync( 7485):    {
E/BooksSync( 7485):     "domain": "global",
E/BooksSync( 7485):     "reason": "required",
E/BooksSync( 7485):     "message": "Login Required",
E/BooksSync( 7485):     "locationType": "header",
E/BooksSync( 7485):     "location": "Authorization"
E/BooksSync( 7485):    }
E/BooksSync( 7485):   ],
E/BooksSync( 7485):   "code": 401,
E/BooksSync( 7485):   "message": "Login Required"
E/BooksSync( 7485):  }
E/BooksSync( 7485): }
E/BooksSync( 7485): 
E/BooksSync( 7485): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7485): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7485): 	... 8 more
E/BooksSync( 7485): Sync error
E/BooksSync( 7485): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7485): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=-6942645628764907678&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7485): Headers:
E/BooksSync( 7485): accept-encoding: [gzip]
E/BooksSync( 7485): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
E/BooksSync( 7485): gdata-version: 2
E/BooksSync( 7485): 
E/BooksSync( 7485): 	at com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:211)
E/BooksSync( 7485): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:224)
E/BooksSync( 7485): 	at com.google.android.apps.books.api.ApiaryClientImpl.execute(ApiaryClientImpl.java:147)
E/BooksSync( 7485): 	at com.google.android.apps.books.net.NetworkBooksServer.syncVolumeLicenses(NetworkBooksServer.java:272)
E/BooksSync( 7485): 	at com.google.android.apps.books.data.MyEbooksSubcontroller$3.run(MyEbooksSubcontroller.java:180)
E/BooksSync( 7485): 	at com.google.android.apps.books.data.NetworkTas,kQueue$1.run(NetworkTaskQueue.java:204)
E/BooksSync( 7485): 	at com.google.android.apps.books.util.LazyThreadPool$2.run(LazyThreadPool.java:84)
E/BooksSync( 7485): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/BooksSync( 7485): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/BooksSync( 7485): 	at java.lang.Thread.run(Thread.java:818)
E/BooksSync( 7485): Caused by: com.google.api.client.http.HttpResponseException: 401 Unauthorized
E/BooksSync( 7485): {
E/BooksSync( 7485):  "error": {
E/BooksSync( 7485):   "errors": [
E/BooksSync( 7485):    {
E/BooksSync( 7485):     "domain": "global",
E/BooksSync( 7485):     "reason": "required",
E/BooksSync( 7485):     "message": "Login Required",
E/BooksSync( 7485):     "locationType": "header",
E/BooksSync( 7485):     "location": "Authorization"
E/BooksSync( 7485):    }
E/BooksSync( 7485):   ],
E/BooksSync( 7485):   "code": 401,
E/BooksSync( 7485):   "message": "Login Required"
E/BooksSync( 7485):  }
E/BooksSync( 7485): }
E/BooksSync( 7485): 
E/BooksSync( 7485): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:1054)
E/BooksSync( 7485): 	at com.google.android.apps.books.api.ApiaryClientImpl.executeOnce(ApiaryClientImpl.java:193)
E/BooksSync( 7485): 	... 8 more
I/BooksSync( 7485): Finished books sync
D/SyncManager( 1038): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 300394, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect called
I/jxcore-log( 7001): 
I/jxcore-log( 7001): Coordinator is now connected to the server!
I/jxcore-log( 7001): 
,I/chromium( 7001): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 317792809101; DSPS: 10554028; Offset : -4302569503
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=1038524618, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,I/ActivityManager( 1038): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7670 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,D/[Concierge]Service( 2583): onStartCommand(). Type : 9
,I/DigitalAppWidgetProvider( 7670): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7670): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@25662a8f
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=1038524618 [*alarm*], flags=0x0
I/ActivityManager( 1038): Killing 6895:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10005/pid_6895/cgroup.procs: No such file or directory
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{95dc0f7 type 2 when 330618 android} when 330618
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 337794515916; DSPS: 11209444; Offset : -4302571542
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 357796126950; DSPS: 11864857; Offset : -4302577940
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2133): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2133): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2133): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2133): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2133): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1038): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1038): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1038): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1038): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1038): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1417): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1417): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1417): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1417): handleNotificationPosted(true)
D/QuickCircle( 1417): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1417): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): post do just update job
D/LgeQuickCoverNotificationData( 1417): showAll3
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1417): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
E/LgeQuickCoverOverlayWindow( 1417): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1417): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1417): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1417): updateNotificationData: count=3
W/GLSActivity( 2133): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2133): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2133): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2133): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2133): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6264): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6264): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6264): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 6264): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6264): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 6264): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6264): 	at android.os.Binder.execTransact(Binder.java:446)
D/QuickStatusbarLayout( 1417): Notification difference=198
D/QuickStatusbarLayout( 1417): child = android.widget.LinearLayout{2f8d4062 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,W/System  ( 6264): Ignoring header User-Agent because its value was null.
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  313): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  313): res_queryN name = play.googleapis.com succeed
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 377798083140; DSPS: 12520281; Offset : -4302575005
,D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=1038524618, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,D/[Concierge]Service( 2583): onStartCommand(). Type : 9
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged(),
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=1038524618 [*alarm*], flags=0x0
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 397799450945; DSPS: 13175686; Offset : -4302580309
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 417801624011; DSPS: 13831117; Offset : -4302574174
,W/bt-l2cap( 3822): l2c_link_hci_conn_req:current link_role= 1
,W/bt-btm  ( 3822): btm_acl_created hci_handle=1 link_role=1  transport=1
W/bt-btm  ( 3822): btm_acl_created hci_handle=1 link_role=1  transport=1
,W/bt-btm  ( 3822): btm_read_remote_version_complete: BDA: f8-95-c7-87-85-54
,W/bt-btm  ( 3822): btm_read_remote_version_complete lmp_version 6 manufacturer 15 lmp_subversion 16653
,W/bt-btm  ( 3822): btm_process_remote_ext_features_page 0: BDA: f8-95-c7-87-85-54
W/bt-btm  ( 3822): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3822): btm_process_remote_ext_features_page 1: BDA: f8-95-c7-87-85-54
W/bt-btif ( 3822): info:x10
W/bt-l2cap( 3822): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/        ( 3822): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 3822): aclStateChangeCallback: Device is NULL
D/LGBluetoothServiceUtil( 3822): [BTUI] sendBroadcastAclConnection: Connected, but device is null, sendBroadcast
W/bt-l2cap( 3822): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3822): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3822): L2CA_ErtmConnectRsp()  CID: 0x0040  Result: 0  Status: 0  BDA: f895c7878554  p_ertm_info:0x00000000
W/bt-l2cap( 3822): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3822): L2CAP-Upper layer Config_Rsp,Local CID: 0x0040,Remote CID: 0x0040,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3822): L2CAP-peer_Config_Rsp,Local CID: 0x0040,Remote CID: 0x0040,PSM: 1,peer MTU present: 0,peer MTU: 672
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36c817a6:true
,D/LGBluetoothFeatureConfig( 7079): isPrivacyLogsEnabled : true
,D/LGBluetoothUtils( 7079): [BTUI] FileNotFound: readProperty
D/LGBluetoothUtils( 7079): [BTUI] FileNotFound: storeHashmapFromFile
D/LGBluetoothPowerSaveListener( 7079): [BTUI] ACL connected => AclLinkCount = 1
W/bt-l2cap( 3822): L2CA_DisconnectRsp()  CID: 0x0040
W/bt-l2cap( 3822): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,I/jxcore-log( 7001): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 7001): 
,E/bt-btm  ( 3822): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3822): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/WifiServerServiceExt( 1038): Connected BT device : -1
I/BluetoothMapService( 3822): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothPbapReceiver( 3822): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3822): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3822): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3822): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3822): state: -2147483648
I/jxcore-log( 7001): DBG, CoordinatorConnector command called
I/jxcore-log( 7001): 
I/jxcore-log( 7001): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":14,"addressList":[{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0}]}
I/jxcore-log( 7001): 
I/jxcore-log( 7001): Start now : testSendData.js
I/jxcore-log( 7001): 
,I/jxcore-log( 7001): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 14
I/jxcore-log( 7001): 
I/jxcore-log( 7001): check server
I/jxcore-log( 7001): 
I/jxcore-log( 7001): serverPort is 40202
I/jxcore-log( 7001): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): setDiscoveryMode: Mode set to WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): setDiscoveryMode: Failed to set discovery mode to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7001): start: Peer ID: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT1108
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7001): bind: Binding a new listener
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7001): initialize: My bluetooth address is 58:3F:54:73:64:C0
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7001): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT1108","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7001): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 7001): getBluetoothService() called with no BluetoothManagerCallback
,D/LGBluetoothServiceAdapter( 3822): [BTUI] createSocketChannel FD=84 mFd=82
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7001): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7001): start: OK
I/io.jxcore.node.ConnectionHelper( 7001): start: Using peer discovery mode: WIFI
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): start: Peer ID: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT1108
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7001): verifyIdentityString: Identity string created: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT1108","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7001): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7001): start: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT1108","ra":"58:3F:54:73:64:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7001): start: Identity string: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT1108","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3e4754c4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3e4754c4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState add service
D/LGWifiP2pService( 1038): add a new client
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a224c47452d4c472d443835355f505431313038222c227261223a2235383a33463a35343a37333a36343a4330227dc027
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 0a436f72646f7661703270c00c000c01 4d7b227069223a2235383a33463a35343a37333a36343a4330222c22706e223a224c47452d4c472d443835355f505431313038222c227261223a2235383a33463a35343a37333a36343a4330227dc027: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_ADD bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707431313038222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65
D/WifiNative-p2p0( 1038): P2P_SERVICE_ADD bonjour 4d7b227069223a2235383a33663a35343a37333a36343a6330222c22706e223a226c67652d6c672d643835355f707431313038222c227261223a2235383a33663a35343a37333a36343a6330227d0a636f72646f7661703270c00c001001 11617661696c61626c653d76697369626c65: returned true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7001): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7001): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 7001): start: OK
I/jxcore-log( 7001): StartBroadcasting started ok
I/jxcore-log( 7001): 
I/jxcore-log( 7001): do fake peer & start
I/jxcore-log( 7001): 
I/jxcore-log( 7001): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 7001): 
I/jxcore-log( 7001): 2015-12-17T14:16:48.175Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 7001): 
I/jxcore-log( 7001): 2015-12-17T14:16:48.175Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 7001): 
I/jxcore-log( 7001): 2015-12-17T14:16:48.175Z SendDataConnector.js: do connect now
I/jxcore-log( 7001): 
I/io.jxcore.node.ConnectionHelper( 7001): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 7001): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 7001): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7001): connect: [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7001): Waiting for incoming connections...
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: P2P_FIND 120
I/wpa_supplicant( 2751): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1970): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1038): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7001): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7001): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7001): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 7001): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@107a6b8a:true
D/WifiNative-p2p0( 1038): P2P_FIND 120: returned true
D/LGWifiP2pService( 1038): discovery change broadcast true
I/jxcore-log( 7001): 2015-12-17T14:16:48.195Z SendDataTCPServer.js: TCP/IP server is bound to port: 40202
I/jxcore-log( 7001): 
I/io.jxcore.node.ConnectionHelper( 7001): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 7001): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 7001): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7001): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7001): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7001): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/chromium( 7001): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7001): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 831)
,D/LGBluetoothPowerSaveListener( 7079): [BTUI] ACL disconnected => AclLinkCount = 0
D/BluetoothManagerService( 1038): Message: 20
,D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c173618:true
I/BTConnectionReceiver( 4624): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=0, deviceClass=0]
I/BluetoothClassifier( 4624): Bluetooth Device Name: G3s-1
,W/LGMDMUISystemServiceAdapter( 7001): checkBluetoothPairing btPolicy: false
W/BluetoothAdapter( 7001): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3822): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
W/bt-l2cap( 3822): L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: e0db1014e2c0  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
D/LGBluetoothServiceAdapter( 3822): [BTUI] connectSocket FD=85 mFd=84
,I/wpa_supplicant( 2751): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2751): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/WifiMonitor( 1038): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=36 dispatchEvent: P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1038):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1038):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1038):  secondary type: null
D/LGWifiP2pService( 1038):  wps: 392
D/LGWifiP2pService( 1038):  grpcapab: 0
D/LGWifiP2pService( 1038):  devcapab: 37
D/LGWifiP2pService( 1038):  status: 3
D/LGWifiP2pService( 1038):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/LGWifiP2pService( 1038):  deviceAddress: 0a:ec:a9:50:76:28
D/LGWifiP2pService( 1038):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1038):  secondary type: null
D/LGWifiP2pService( 1038):  wps: 392
D/LGWifiP2pService( 1038):  grpcapab: 0
D/LGWifiP2pService( 1038):  devcapab: 37
D/LGWifiP2pService( 1038):  status: 3
D/LGWifiP2pService( 1038):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1970): WIFI_P2P_PEERS_CHANGED_ACTION
,D/WfdsMonitor( 1970): Event [P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0]
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1038): No p2p device connected
D/LGWifiP2pService( 1038): InactiveState{ when=-2ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-2ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-2ms what=139283 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): InactiveState{ when=-2ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-2ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-2ms what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7001): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState add service request
D/WifiP2pManager( 7001): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7001): Service request added successfully
I/wpa_supplicant( 2751): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WfdsMonitor( 1970): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiMonitor( 1038): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2751): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/WfdsMonitor( 1970): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
D/WifiMonitor( 1038): Event [P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=38 dispatchEvent: P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
D/LGWifiP2pService( 1038): InactiveState{ when=-2ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1038):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1038):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1038):  secondary type: null
D/LGWifiP2pService( 1038):  wps: 392
D/LGWifiP2pService( 1038):  grpcapab: 0
D/LGWifiP2pService( 1038):  devcapab: 33
D/LGWifiP2pService( 1038):  status: 3
D/LGWifiP2pService( 1038):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-2ms what=147477 obj=Device: XT1072_23d5
D/LGWifiP2pService( 1038):  deviceAddress: 44:80:eb:7b:5a:07
D/LGWifiP2pService( 1038):  primary type: 10-0050F204-5
D/LGWifiP2pService( 1038):  secondary type: null
D/LGWifiP2pService( 1038):  wps: 392
D/LGWifiP2pService( 1038):  grpcapab: 0
D/LGWifiP2pService( 1038):  devcapab: 33
D/LGWifiP2pService( 1038):  status: 3
D/LGWifiP2pService( 1038):  wfdInfo: null target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1970): WIFI_P2P_PEERS_CHANGED_ACTION
I/wpa_supplicant( 2751): wpa_driver_nl80211_ext_driver_cmd SET_AP_WPS_P2P_IE 2
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1038): DefaultState{ when=0 what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1038): No p2p device connected
D/LGWifiP2pService( 1038): InactiveState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-2ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/btif_config_util( 3822): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=139310 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=139310 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState discover services
D/WifiNative-p2p0( 1038): doString: [P2P_SERV_DISC_REQ 00:00:00:00:00:00 120001010a436f72646f7661703270c00c000c01]
D/WifiNative-p2p0( 1038):    returned b6037688
D/WifiNative-p2p0( 1038): doBoolean: P2P_FIND 120
,I/wpa_supplicant( 2751): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1038): Event [IFNAME=p2p0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=39 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1970): Event [CTRL-EVENT-SCAN-STARTED ]
D/WifiNative-p2p0( 1038): P2P_FIND 120: returned true
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 7001): Service discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7001): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 437803602024; DSPS: 14486542; Offset : -4302579387
,I/wpa_supplicant( 2751): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=1
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=1
D/WifiMonitor( 1038): handleNetworkStateChange: Could not parse disconnect string
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: null reason=0
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=441206
E/WifiStateMachine( 1038):  L2ConnectedState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=441206
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_DISCONNECTION_EVENT nid=0 reason=0 lastbssid=c0:ff:d4:d3:aa:48 rt=441206
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/Tethering( 1038): InitialState.processMessage what=4
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
,D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7079): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7079): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : errorList=[]
,D/UsbSettingsControl( 7079): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7079): [AUTORUN] setTetherStatus() : status=false
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2751): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/CommandListener(  313): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1038): RunningState{ when=-11ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,V/NativeCrypto( 2133): Read error: ssl=0xaa708c00: I/O error during system call, Connection timed out
I/jxcore-log( 7001): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 7001): 
I/jxcore-log( 7001): The Coordinator has disconnected!
I/jxcore-log( 7001): 
,I/wpa_supplicant( 2751): [LGE_P2P] is_hs20_enable() skip!! hs20 while in p2p_in_progress
V/NativeCrypto( 2133): SSL shutdown failed: ssl=0xaa708c00: I/O error during system call, Broken pipe
,D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,D/WifiHS20( 1038): hidePasspointNotification off =false
V/WfdStateTracker( 1970): handleWifiStateChangedEvent: 0
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
,D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiHS20( 1038): hidePasspointNotification off =false
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=441370  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=441371  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
,I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7112): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1038): Removing idletimer
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
E/ConnectivityService( 1038): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1870): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7112): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/DhcpStateMachine( 1038): StoppedState
,I/jxcore-log( 7001): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 7001): 
,I/jxcore-log( 7001): Error type "connect_error" when connecting to the test server
I/jxcore-log( 7001): 
D/WifiServiceImplEx( 1038): setWifiEnabled: false pid=7001, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: false pid=7001, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
,D/LocationManagerService( 1038): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1038): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
E/WifiStateMachine( 1038):  DisconnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
D/Ulp_jni ( 1038): JNI:system_update. Event-4
,D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=7001, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: true pid=7001, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
D/WifiScanningService( 1038): SCAN_AVAILABLE : 1
D/RttService( 1038): SCAN_AVAILABLE : 1
D/WifiScanningService( 1038): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1038): EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1038): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1038): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@10320a80
D/LGWifiP2pService( 1038): discovery change broadcast false
D/LGWifiP2pService( 1038): P2pDisablingState
D/LGWifiP2pService( 1038): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): p2p socket connection lost
D/LGWifiP2pService( 1038): P2pDisabledState
D/WfdsService( 1970): WIFI_P2P_PEERS_CHANGED_ACTION
V/WfdStateTracker( 1970): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1970): WifiP2pState is changed : false
D/WfdsService( 1970): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1970): Set the WFDS Monitor: false
,D/WfdsMonitor( 1970): WFDS Monitor is stopped
D/WfdsService( 1970): STATE : WfdsDisabledState - enter
D/CtrlSupplicant( 1970): Received on exit socket, terminate
E/CtrlSupplicant( 1970): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
W/WfdsSession:Controller( 1970): DefaultState - msg [9441355] is not handled
D/WfdsMonitor( 1970): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1970): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1970): DefaultState - msg [9445378] is not handled
D/LGWifiP2pService( 1038): P2pDisabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1038): P2pDisabledState{ when=-2ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-2ms what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pDisabledState{ when=-4ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-4ms what=139287 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pDisabledState{ when=-4ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-4ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiServerServiceExt( 1038): No p2p device connected
D/WifiController( 1038): WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 446ms
D/LocationManagerService( 1038): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1038): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1038): JNI:system_update. Event-4
D/WifiServiceImplEx( 1038): disconnect pid=7001, uid=10311, packageName=com.test.thalitest
D/WifiServiceImplEx( 1038): reconnect pid=7001, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 7001): Wifi toggled for connection repairment
I/jxcore-log( 7001): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7001): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7001): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7001): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7001): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7001): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 7001): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7001): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
I/io.jxcore.node.ConnectionHelper( 7001): onDiscoveryManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
I/chromium( 7001): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
D/LGWifiP2pService( 1038): P2pDisabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 7001): onP2pDeviceListChanged: 0 device(s) discovered
D/AndroidRuntime( 7001): Shutting down VM
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): Uncaught exception: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer.onP2pDeviceListChanged(WifiPeerDiscoverer.java:164)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer$MyPeerListListener.onPeersAvailable(WifiP2pDeviceDiscoverer.java:285)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): 	at android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler.handleMessage(WifiP2pManager.java:754)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): 	at android.os.Looper.loop(Looper.java:135)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): 	at java.lang.reflect.Method.invoke(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/WifiStateMachine( 1038):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2751): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1038): P2pDisabledState{ when=-10ms what=139268 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-10ms what=139268 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pDisabledState{ when=-11ms what=139298 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-11ms what=139298 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pDisabledState{ when=-11ms what=139268 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-11ms what=139268 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pDisabledState{ when=-12ms what=139307 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-12ms what=139307 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/DhcpStateMachine( 1038): StoppedState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  313): Clearing all IP addresses on wlan0
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-p2p0( 1038): doBoolean: TERMINATE
D/WifiNative-p2p0( 1038): TERMINATE: returned true
E/WifiStateMachine( 1038): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1038): useWiFiOffloading() : false
E/WifiStateMachine( 1038): CONFIG_LGE_WLAN_PATH : true
E/WifiStateMachine( 1038):  SupplicantStoppingState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1038):  SupplicantStoppingState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_ON_QUIT 0 0
V/WfdStateTracker( 1970): WfdStateTracker handleDirectStateChangedEvent: 6
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
I/WifiServerServiceExt( 1038): WIFI_STATE_CHANGED_ACTION [0]
I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7112): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
W/FormManager( 7267): Network not available. Please check & try again.
V/FormManager( 7267): Network unavailable.
,V/FormManager( 7267): Network unavailable.
,I/wpa_supplicant( 2751): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2751): monitor socket send errors count : 1
I/wpa_supplicant( 2751): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1970-2\x00 that cannot receive messages
I/wpa_supplicant( 2751): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2751): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
D/WifiMonitor( 1038): Event [P2P-FIND-STOPPED ]
D/WifiMonitor( 1038): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1038): Event [P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07]
D/WifiMonitor( 1038): Dropping event because (p2p0) is stopped
D/WifiMonitor( 1038): Event [P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28]
D/WifiMonitor( 1038): Dropping event because (p2p0) is stopped
I/wpa_supplicant( 2751): p2p0: CTRL-EVENT-TERMINATING 
W/wpa_supplicant( 2751): USIM:  scard_deinit function
D/WifiMonitor( 1038): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1038): Dropping event because (p2p0) is stopped
I/wpa_supplicant( 2751): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1038): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1038):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 42 0
,D/WfdsService( 1970): Supplicant Connection state is changed : false
,D/WfdsService( 1970): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
,D/WfdsService( 1970): Set the WFDS Monitor: false
D/WfdsMonitor( 1970): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed( 1038): stopMonitoring
E/WifiStateMachine( 1038): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1038): useWiFiOffloading() : false
E/WifiStateMachine( 1038): CONFIG_LGE_WLAN_PATH : true
,D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1970): WfdStateTracker handleDirectStateChangedEvent: 0
,W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/WifiServerServiceExt( 1038): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1038): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1038): batteryPsActivateMsgHandler : this is not treated
W/Settings( 1835): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
I/PCSuite ( 7112): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,D/PCSuite ( 7112): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
W/FormManager( 7267): Network not available. Please check & try again.
V/FormManager( 7267): Network unavailable.
,V/FormManager( 7267): Network unavailable.
D/WifiController( 1038): DEFERRED_TOGGLE handled
,E/WifiStateMachine( 1038):  InitialState CMD_START_SUPPLICANT 0 0
I/LGFTMITEM( 1038): [GET_FTM][id=6], offset=12288
,E/WifiUtil( 1038): wfc_util_ffile_check_copy(): pid[1038] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
E/WifiUtil( 1038): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
E/WifiUtil( 1038): wfc_util_ffile_check_copy(): pid[1038] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
E/WifiUtil( 1038): wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
I/WifiUtil( 1038): Intf0MacAddress=C49A027B60AC
E/WifiHW  ( 1038): unknown target_country: EU , set to default
E/WifiHW  ( 1038): [wifi_ensure_config_files] default country1 = GB
E/WifiHW  ( 1038): [wifi_ensure_config_files] default country2 = GB
I/WifiUtil( 1038): gEnableBmps=1
D/SoftapController(  313): Softap fwReload - Ok
,D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1038): InitialState.processMessage what=4
,D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
,D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7079): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,E/NetdConnector( 1038): NDC Command {73 softap fwreload wlan0 STA} took too long (668ms)
D/CommandListener(  313): Setting iface cfg
D/CommandListener(  313): Trying to bring down wlan0
D/CommandListener(  313): Clearing all IP addresses on wlan0
,E/WifiHW  ( 1038): Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
W/wpa_supplicant( 7863): type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,E/WifiStateMachine( 1038): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1038): useWiFiOffloading() : false
E/WifiStateMachine( 1038): CONFIG_LGE_WLAN_PATH : true
W/wpa_supplicant( 7863): type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/WifiMonitor( 1038): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor( 1038): connecting to supplicant
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : app userid = 0, current userid = 0
V/WfdStateTracker( 1970): WfdStateTracker handleDirectStateChangedEvent: 1
I/WifiServerServiceExt( 1038): WIFI_STATE_CHANGED_ACTION [2]
D/UsbSettingsControl( 7079): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7079): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7079): [AUTORUN] setTetherStatus() : status=false
,D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7079): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7079): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7079): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7079): [AUTORUN] setTetherStatus() : status=false
I/wpa_supplicant( 7863): Successfully initialized wpa_supplicant
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
V/FormManager( 7267): Network unavailable.
,W/FormManager( 7267): Network not available. Please check & try again.
V/FormManager( 7267): Network unavailable.
I/wpa_supplicant( 7863): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 7863): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,I/wpa_supplicant( 7863): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 7863): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,I/wpa_supplicant( 7863): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine( 1038):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine( 1038):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1038):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine( 1038):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/WifiNative-wlan0( 1038): doString: [DRIVER MACADDR]
,D/WifiNative-wlan0( 1038):    returned Macaddr = c4:9a:02:7b:60:ac,
D/WifiStateMachine( 1038): MAC Addr from driver = c4:9a:02:7b:60:ac
D/WifiOffDelayIfNotUsed( 1038): setPowerSaveActivated(false)
E/WifiStateMachine( 1038): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1038): useWiFiOffloading() : false
E/WifiStateMachine( 1038): CONFIG_LGE_WLAN_PATH : true
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WfdService( 1970): Waiting for WifiP2p enabling
D/WifiNative-wlan0( 1038): doBoolean: SET update_config 1
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-wlan0( 1038): SET update_config 1: returned true
D/WifiConfigStore( 1038): Loading config and enabling all networks 
D/WifiNative-wlan0( 1038): doString: [LIST_NETWORKS]
D/WifiNative-wlan0( 1038):    returned network id / ssid / bssid / flags 0	NG700	any	
I/WifiServerServiceExt( 1038): WIFI_STATE_CHANGED_ACTION [3]
I/WifiServerServiceExt( 1038): batteryPsActivateMsgHandler : state:0 event:3
,E/WifiConfigStore( 1038): readNetworkVariablesFromSupplicantFile key=psk
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,E/WifiConfigStore( 1038): readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
E/WifiConfigStore( 1038): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WifiStateMachine( 1038): enableVerboseLogging : level 2
D/WifiNative-wlan0( 1038): doBoolean: SET device_name g3_global_com
,D/WifiNative-wlan0( 1038): SET device_name g3_global_com: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET manufacturer LGE
D/WifiNative-wlan0( 1038): SET manufacturer LGE: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET model_name LG-D855
D/WifiNative-wlan0( 1038): SET model_name LG-D855: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET model_number LG-D855
D/WifiNative-wlan0( 1038): SET model_number LG-D855: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET serial_number LGD8553bed2d08
D/WifiNative-wlan0( 1038): SET serial_number LGD8553bed2d08: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET config_methods physical_display virtual_push_button
W/FormManager( 7267): Network not available. Please check & try again.
D/WifiNative-wlan0( 1038): SET config_methods physical_display virtual_push_button: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-wlan0( 1038): SET device_type 10-0050F204-5: returned true
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
,D/WfdsService( 1970): Supplicant Connection state is changed : true
,D/WifiStateMachine( 1038): Setting OUI to DA-A1-19
D/WfdsService( 1970): DefaultState - WIFI_SUPPLICANT_CONNECTED
D/WifiNative-wlan0( 1038): doBoolean: SCAN_INTERVAL 120
D/WfdsService( 1970): Set the WFDS Monitor: true
D/WfdsMonitor( 1970): WfdsMonitorThread create
D/WfdsMonitor( 1970): WFDS Monitor is created and started
D/WfdsService( 1970): WiFi: Supplicant connection re-established
,D/WifiNative-wlan0( 1038): SCAN_INTERVAL 120: returned true
D/WifiNative-HAL( 1038): Setting external_sim to 1
D/WifiNative-wlan0( 1038): doBoolean: SET external_sim 1
D/WifiNative-wlan0( 1038): SET external_sim 1: returned true
I/WifiNative-HAL( 1038): startHal
D/wifi    ( 1038): setting scan oui 0xaf6d1160
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/WifiStateMachine( 1038): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1038): startHal
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/wifi    ( 1038): setting scan oui 0xaf6d1160
V/FormManager( 7267): Network unavailable.
D/WifiNative-wlan0( 1038): doBoolean: STA_AUTOCONNECT 1
D/WifiNative-wlan0( 1038): STA_AUTOCONNECT 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXSCAN-STOP
I/wpa_supplicant( 7863): wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
D/WifiNative-wlan0( 1038): DRIVER BTCOEXSCAN-STOP: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 7863): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
V/FormManager( 7267): Network unavailable.
D/WifiNative-wlan0( 1038): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER RXFILTER-REMOVE 3
I/wpa_supplicant( 7863): wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
E/CtrlSupplicant( 1970): Access OK "@android:wpa_wlan0"
D/WifiNative-wlan0( 1038): DRIVER RXFILTER-REMOVE 3: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 7863): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
E/CtrlSupplicant( 1970): Succeed to open control connection
E/CtrlSupplicant( 1970): Succeed to open monitor connection
D/WifiNative-wlan0( 1038): DRIVER RXFILTER-START: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER RXFILTER-STOP
I/wpa_supplicant( 7863): wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
D/WfdsMonitor( 1970): Supplicant connection established
D/WifiNative-wlan0( 1038): DRIVER RXFILTER-STOP: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER RXFILTER-REMOVE 2
I/wpa_supplicant( 7863): android_multicast_filter_startstop : multicast filter set
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/WfdsService( 1970): Connected to the supplicant for wfds
D/WifiNative-wlan0( 1038): DRIVER RXFILTER-REMOVE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER RXFILTER-START
I/wpa_supplicant( 7863): wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
D/WifiNative-wlan0( 1038): DRIVER RXFILTER-START: returned true
E/WifiNative: ( 1038): [443,635,962 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/WifiNative-wlan0( 1038): RECONNECT: returned true
D/WifiNative-wlan0( 1038): doString: [STATUS]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/WifiNative-wlan0( 1038):    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/LGWifiP2pService( 1038): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  313): Setting iface cfg
D/CommandListener(  313): Trying to bring up p2p0
D/WifiMonitor( 1038): startMonitoring(p2p0) with mConnected = true
D/LGWifiP2pService( 1038): P2pEnablingState
D/LGWifiP2pService( 1038): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2p socket connection successful
D/LGWifiP2pService( 1038): P2pEnabledState
D/LGWifiP2pService( 1038): sending p2p connection changed broadcast
V/WfdStateTracker( 1970): WfdStateTracker handleDirectStateChangedEvent: 2
D/WfdsService( 1970): WifiP2pState is changed : true
D/WfdsService( 1970): Receive the WFDS_ENABLE Method
D/WfdsService( 1970): Set the WFDS Monitor: true
D/WfdsService( 1970): Connected to the supplicant for wfds
D/WfdsJNI ( 1970): doCommand: WFDS_SET TRUE
I/wpa_supplicant( 7863): WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
D/WfdsService( 1970): selectPreferredScanChannel [36]
,D/WfdsService( 1970): STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1038): doBoolean: SET persistent_reconnect 1
D/WifiNative-p2p0( 1038): SET persistent_reconnect 1: returned true
D/WifiNative-p2p0( 1038): doBoolean: SET device_name G3-1
D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
D/WfdsService( 1970): WIFI_P2P_CONNECTION_CHANGED_ACTION
D/WfdsService( 1970): isConnected: false
D/WifiNative-p2p0( 1038): SET device_name G3-1: returned true
D/LGWifiP2pService( 1038): [LGE_P2P] initializeP2pSettings() check postfix
D/LGWifiP2pService( 1038): before postfix = G3-1
D/WifiServerServiceExt( 1038): postfix byte check : 4
D/LGWifiP2pService( 1038): after postfix = G3-1
D/WifiNative-p2p0( 1038): doBoolean: SET p2p_ssid_postfix -G3-1
D/WifiNative-p2p0( 1038): SET p2p_ssid_postfix -G3-1: returned true
D/WifiNative-p2p0( 1038): doBoolean: SET device_type 10-0050F204-5
D/WifiNative-p2p0( 1038): SET device_type 10-0050F204-5: returned true
D/WifiNative-p2p0( 1038): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiNative-p2p0( 1038): SET config_methods virtual_push_button physical_display keypad: returned true
D/WifiNative-p2p0( 1038): doBoolean: P2P_SET conc_pref p2p
D/WifiNative-p2p0( 1038): P2P_SET conc_pref p2p: returned true
D/WifiNative-HAL( 1038): p2pGetDeviceAddress
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/WifiNative-HAL( 1038): p2pGetDeviceAddress returning 02:9a:02:7b:60:ac
,I/ActivityManager( 1038): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7891 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,D/LGWifiP2pService( 1038): DeviceAddress: 02:9a:02:7b:60:ac
D/WifiNative-p2p0( 1038): doBoolean: P2P_FLUSH
D/WifiScanningService( 1038): SCAN_AVAILABLE : 3
D/WifiNative-p2p0( 1038): P2P_FLUSH: returned true
D/RttService( 1038): SCAN_AVAILABLE : 3
D/WifiNative-p2p0( 1038): doBoolean: P2P_SERVICE_FLUSH
D/RttService( 1038): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1038): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): P2P_SERVICE_FLUSH: returned true
I/WifiNative-HAL( 1038): startHal
D/WifiNative-p2p0( 1038): doString: [LIST_NETWORKS]
D/wifi    ( 1038): getting scan capabilities on interface[1] = 0xaf6d1160
D/wifi    ( 1038): failed to get capabilities : -3
E/WifiScanningService( 1038): could not get scan capabilities
I/WfdStateTracker( 1970): handleP2pThisDeviceChanged
D/WfdsService( 1970): WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
D/WfdsService( 1970): Update P2p Interface State: 3
D/WifiNative-p2p0( 1038):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0( 1038): doBoolean: SAVE_CONFIG
E/WifiStateMachine( 1038):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine( 1038):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine( 1038):  DisconnectedState what:132106 1 0
E/WifiStateMachine( 1038):  ConnectModeState what:132106 1 0
E/WifiStateMachine( 1038):  DriverStartedState what:132106 1 0
I/WifiServerServiceExt( 1038): setWifiDualbandAPConnection band : 1
,E/wpa_supplicant( 7863): nWIFIDualbandAPConnection: 1
D/WifiNative-p2p0( 1038): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1038): sending p2p persistent groups changed broadcast
E/WifiStateMachine( 1038):  DisconnectedState what:132096 -100 0
D/LGWifiP2pService( 1038): InactiveState
D/LGWifiP2pService( 1038): InactiveState{ when=-23ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-23ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-p2p0( 1038): doBoolean: DRIVER COUNTRY CZ
E/WifiStateMachine( 1038):  ConnectModeState what:132096 -100 0
E/WifiStateMachine( 1038):  DriverStartedState what:132096 -100 0
I/WifiServerServiceExt( 1038): set CMD_DISCONNECT_RSSI_LVL : -100
I/wpa_supplicant( 7863): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 7863): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,I/wpa_supplicant( 7863): [LGE_PATCH] driver_cmd() country:CZ
D/WifiMonitor( 1038): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/wpa_supplicant( 7863): disconnect_rssi_lvl: -100
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 7863): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1038): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/wpa_supplicant( 7863): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1038): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1970): Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
D/WfdsMonitor( 1970): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiNative-p2p0( 1038): DRIVER COUNTRY CZ: returned true
D/WfdsMonitor( 1970): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/LGWifiP2pService( 1038): InactiveState{ when=-5ms what=139287 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-5ms what=139287 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-5ms what=139287 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): InactiveState{ when=-5ms what=139285 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-6ms what=139285 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-6ms what=139285 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): InactiveState{ when=-6ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-6ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService( 1038): DefaultState{ when=-6ms what=139287 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): InactiveState{ when=-6ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-6ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-7ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1038):  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
W/WfdsService( 1970): DefaultState - msg [9441285] is not handled
E/WifiStateMachine( 1038):  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
E/WifiServerServiceExt( 1038): No p2p device connected
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1038):  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
D/WifiNative-wlan0( 1038): doBoolean: DRIVER COUNTRY CZ
,I/wpa_supplicant( 7863): wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
I/wpa_supplicant( 7863): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,I/wpa_supplicant( 7863): [LGE_PATCH] driver_cmd() country:CZ
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
I/wpa_supplicant( 7863): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiNative-wlan0( 1038): DRIVER COUNTRY CZ: returned true
I/wpa_supplicant( 7863): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1970): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WfdsMonitor( 1970): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/WifiMonitor( 1038): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WifiMonitor( 1038): Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine( 1038):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETBAND 0
,I/wpa_supplicant( 7863): wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
I/wpa_supplicant( 7863): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
D/WifiNative-wlan0( 1038): DRIVER SETBAND 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: BSS_FLUSH 0
D/WifiNative-wlan0( 1038): BSS_FLUSH 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SCAN
,D/WifiNative-wlan0( 1038): SCAN: returned false
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=443743  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=443744  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1038):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1038):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1038):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1038):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine( 1038):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateSCANNING
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
V/[BNRBootReceiver]( 7891): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 7891): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,V/[BNRBootReceiver]( 7891): Boot Receiver Return
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,I/ActivityManager( 1038): Killing 7220:com.lge.appbox.client/u0a11 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_7220/cgroup.procs: No such file or directory
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
I/wpa_supplicant( 7863): [LGE_PATCH]scan interval[0] = 2 sec.
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,D/WfdsMonitor( 1970): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1970): Event [WPS-AP-AVAILABLE ]
,E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=52 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1038): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 7079): Not supported operator for automatic switch
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{399953c7 type 0 when 1450361819379 android} when 1450361819379
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{10b97df4 type 2 when 444327 com.google.android.gms} when 444327
E/WifiStateMachine( 1038):  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):4 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:379869] from screen [on:0 period:-1337126216]
E/WifiStateMachine( 1038):  ConnectModeState CMD_START_SCAN -2 -2 ic=1 proc(ms):18 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1337126216]
E/WifiStateMachine( 1038):  DriverStartedState CMD_START_SCAN -2 -2 ic=1 proc(ms):19 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1337126215]
D/WifiNative-wlan0( 1038): doBoolean: SCAN
I/wpa_supplicant( 7863): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,D/WifiNative-wlan0( 1038): SCAN: returned true
D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1038): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/Tethering( 1038): MasterInitialState.processMessage what=3
I/NetworkMonitor( 5933): type=WIFI subType= reason=null isConnected=false
,I/NetworkMonitor( 5933): type=WIFI subType= reason=null isConnected=false
I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7922 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[SystemUI]TimeTickManager( 1466): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1466): called onTimeUpdated()
I/[SystemUI]KeyguardIndicationController( 1466): called onTimeUpdated()
I/[SystemUI]Clock( 1466): called onTimeUpdated()
I/LgeClockWidgetControlView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
I/[SystemUI]DateView( 1466): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1466): handleTimeUpdate
,D/GpsLocationProvider( 1038): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider( 1038): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/AppUp4:AppBoxCP( 7922): onCreate
,W/AppUp4:DB( 7922):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7922):  setFingerPrint start
I/AppUp4:DB( 7922):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 7922):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 7922):  SDK version = 21
I/AppUp4:DB( 7922):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7922): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 7922): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7922): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7922): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7922): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7922): onReceive
,D/LgDataFeature( 7922): LgDataFeature() Constructor: none
,D/LgDataFeature( 7922): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 7922): Context : android.app.ReceiverRestrictedContext@275442fa
D/AppUp4:CustFacade( 7922): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7922): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7922): begin check event
I/AppUp4:CustModeStarterReceiver( 7922): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7922): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7922): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7922): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7922): handleAsyncCustNotification do not startCustService
I/ActivityManager( 1038): Killing 6697:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_6697/cgroup.procs: No such file or directory
,D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7962 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  343): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 486us total 22.336ms
,I/art     (  343): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 439us total 20.545ms
I/art     (  343): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 20.095ms
W/ResourcesManager( 7962): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7962): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7962): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7962): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,I/LGEmail ( 7962): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7962): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 7962): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 7962): LgDataFeature() Constructor: none
D/LgDataFeature( 7962): LgDataFeature() Constructor Done, null
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 78144(3MB) AllocSpace objects, 6(608KB) LOS objects, 33% free, 44MB/66MB, paused 2.552ms total 170.125ms
,D/eas_req ( 7962): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/LgeMiscReceiver( 3377): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3377): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3377): networkInfo.isConnected() = false
,I/HubEmail( 7962): JNI_OnLoad()
I/HubEmail( 7962): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7962): registerNatives()
I/HubEmail( 7962): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7962): registerNativeMethods()
I/HubEmail( 7962): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7962): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/WeatherAncestor( 7356): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:1
,D/Weather.Utils( 7356): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7356): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7356): 2 : This is isUpdating : false
D/WeatherAncestor( 7356): connectivity changed - connection : true
D/WeatherService( 7356): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3be9f308
W/Settings( 7962): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ForecastDataCache( 7356): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7356): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7356): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7356): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7356): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:1
W/FormManager( 7267): Network not available. Please check & try again.
V/FormManager( 7267): Network unavailable.
,V/FormManager( 7267): Network unavailable.
I/ActivityManager( 1038): Killing 6264:com.android.vending/u0a44 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10044/pid_6264/cgroup.procs: No such file or directory
,I/iu.Environment( 2365): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2365): num queued entries: 0
I/iu.UploadsManager( 2365): num updated entries: 0
I/iu.SyncManager( 2365): NEXT; no task
D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
I/NetworkStateForAutoUpdateMonitor( 7922): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7922): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7922): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7922): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7922): onReceive
,D/AppUp4:CustFacade( 7922): Context : android.app.ReceiverRestrictedContext@275442fa
D/AppUp4:CustFacade( 7922): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7922): isPhone : true
D/AppUp4:CustModeStarterReceiver( 7922): begin check event
I/AppUp4:CustModeStarterReceiver( 7922): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/eas_req ( 7962): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LgeMiscReceiver( 3377): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3377): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3377): networkInfo.isConnected() = false
W/FormManager( 7267): Network not available. Please check & try again.
W/Settings( 7962): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WeatherAncestor( 7356): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:1
D/Weather.Utils( 7356): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 7356): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 7356): 2 : This is isUpdating : false
D/WeatherAncestor( 7356): connectivity changed - connection : true
D/WeatherService( 7356): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3be9f308
D/ForecastDataCache( 7356): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 7356): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 7356): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 7356): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 7356): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:17:1
,V/FormManager( 7267): Network unavailable.
,V/FormManager( 7267): Network unavailable.
D/ChimeraCfgMgr( 2365): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ProcessCpuTracker( 1038): Skipping unknown process pid 7933
,W/ProcessCpuTracker( 1038): Skipping unknown process pid 7934
W/ProcessCpuTracker( 1038): Skipping unknown process pid 7953
W/ProcessCpuTracker( 1038): Skipping unknown process pid 7971
W/ProcessCpuTracker( 1038): Skipping unknown process pid 8019
I/wpa_supplicant( 7863): [LGE_PATCH]scan interval[1] = 3 sec.
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=57 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=58 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=59 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
D/LGWifiP2pService( 1038): InactiveState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-4ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsMonitor( 1970): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1970): Event [WPS-AP-AVAILABLE ]
,V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 7079): Not supported operator for automatic switch
D/LGWifiP2pService( 1038): InactiveState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-2ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 1038):  DisconnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/WifiStateMachine( 1038):  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
,E/WifiStateMachine( 1038):  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
E/WifiStateMachine( 1038):  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,I/wpa_supplicant( 7863): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/PowerManagerServiceEx( 1038): acquireWakeLockInternal: lock=1038524618, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1038
,V/AlarmManager( 1038): ELAPSED_WAKEUP set : Alarm{70433c0 type 2 when 450256 com.google.android.gms} when 450256
D/[Concierge]Service( 2583): onStartCommand(). Type : 9
,D/libc-netbsd(  313): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/PowerManagerServiceEx( 1038): releaseWakeLockInternal: lock=1038524618 [*alarm*], flags=0x0
,I/wpa_supplicant( 7863): [LGE_PATCH]scan interval[2] = 15 sec.
,D/WfdsMonitor( 1970): Event [CTRL-EVENT-SCAN-RESULTS ]
D/WfdsMonitor( 1970): Event [WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=62 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=63 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/LGWifiP2pService( 1038): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1038): Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:p2p0 cnt=64 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 dur:2145 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 dur:2145 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 dur:2145 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 dur:2145 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 457805128179; DSPS: 15141952; Offset : -4302579189
,W/bt-l2cap( 3822): L2CAP - st: CLOSED evt: 1
W/bt-sdp  ( 3822): SDP - Rcvd conn cnf with error: 0x22  CID 0x41
E/bt-btif ( 3822): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
W/bt-l2cap( 3822): l2c_link_hci_conn_req:current link_role= 0
,W/bt-btif ( 3822): invalid rfc slot id: 7
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7001): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 831)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 7001): Maximum number of allowed retries (0) reached, giving up... (thread ID: 831)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): Uncaught exception: Thread starting during runtime shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): java.lang.InternalError: Thread starting during runtime shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): 	at java.lang.Thread.nativeCreate(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): 	at java.lang.Thread.start(Thread.java:1063)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector.shutdownClientThread(BluetoothConnector.java:478)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector.onConnectionFailed(BluetoothConnector.java:408)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7001): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:167)
W/bt-btm  ( 3822): btm_acl_role_changed: BDA: f8-95-c7-87-85-54
W/bt-btm  ( 3822): btm_acl_role_changed: New role: 0
,W/bt-btm  ( 3822): btm_acl_created hci_handle=2 link_role=1  transport=1
,W/bt-btm  ( 3822): btm_acl_created hci_handle=2 link_role=0  transport=1
W/bt-btif ( 3822): info:x10
D/        ( 3822): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
W/bt-l2cap( 3822): L2CA_SetDesireRole() new:x0, disallow_switch:0
,D/WifiServerServiceExt( 1038): Connected BT device : 0
D/LGBluetoothPowerSaveListener( 7079): [BTUI] ACL connected => AclLinkCount = 1
,W/bt-btm  ( 3822): btm_read_remote_version_complete: BDA: f8-95-c7-87-85-54
W/bt-btm  ( 3822): btm_read_remote_version_complete lmp_version 6 manufacturer 15 lmp_subversion 16653
I/BTConnectionReceiver( 4624): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=0, deviceClass=0]
,I/BluetoothClassifier( 4624): Bluetooth Device Name: G3s-1
W/bt-btm  ( 3822): btm_process_remote_ext_features_page 0: BDA: f8-95-c7-87-85-54
W/bt-btm  ( 3822): ext_features_complt page_num:1 f[0]:x07, sm4:11, pend:0
W/bt-btm  ( 3822): btm_process_remote_ext_features_page 1: BDA: f8-95-c7-87-85-54
W/bt-l2cap( 3822): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3822): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3822): L2CA_ErtmConnectRsp()  CID: 0x0042  Result: 0  Status: 0  BDA: f895c7878554  p_ertm_info:0x00000000
W/bt-l2cap( 3822): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 24
,W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 25
,W/bt-l2cap( 3822): L2CAP-Upper layer Config_Rsp,Local CID: 0x0042,Remote CID: 0x0041,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3822): L2CAP-peer_Config_Rsp,Local CID: 0x0042,Remote CID: 0x0041,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-l2cap( 3822): L2CA_DisconnectRsp()  CID: 0x0042
W/bt-l2cap( 3822): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-l2cap( 3822): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3822): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3822): L2CA_ErtmConnectRsp()  CID: 0x0043  Result: 0  Status: 0  BDA: f895c7878554  p_ertm_info:0x00000000
W/bt-l2cap( 3822): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 25
,W/bt-l2cap( 3822): L2CAP-Upper layer Config_Rsp,Local CID: 0x0043,Remote CID: 0x0043,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3822): L2CAP-peer_Config_Rsp,Local CID: 0x0043,Remote CID: 0x0043,PSM: 1,peer MTU present: 0,peer MTU: 672
,W/bt-l2cap( 3822): L2CA_DisconnectRsp()  CID: 0x0043
W/bt-l2cap( 3822): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
,W/bt-l2cap( 3822): L2CAP - st: CLOSED evt: 10
,W/bt-l2cap( 3822): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3822): L2CA_ErtmConnectRsp()  CID: 0x0044  Result: 0  Status: 0  BDA: f895c7878554  p_ertm_info:0x00000000
W/bt-l2cap( 3822): L2CAP - st: W4_L2CA_CON_RSP evt: 22
,W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 25
,W/bt-l2cap( 3822): L2CAP-Upper layer Config_Rsp,Local CID: 0x0044,Remote CID: 0x0044,PSM: 1,our MTU present:1,our MTU:672
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3822): L2CAP-peer_Config_Rsp,Local CID: 0x0044,Remote CID: 0x0044,PSM: 1,peer MTU present: 0,peer MTU: 672
W/bt-l2cap( 3822): L2CA_DisconnectRsp()  CID: 0x0044
W/bt-l2cap( 3822): L2CAP - st: W4_L2CA_DISC_RSP evt: 28
I/BluetoothBondStateMachine( 3822): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3822): check_cod: remote_cod = 0x5a020c
,W/LGMDMUISystemServiceAdapter( 3822): checkBluetoothPairing btPolicy: false
I/BluetoothBondStateMachine( 3822): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3822): Entering PendingCommandState State
,I/ActivityManager( 1038): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=8026 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 8026): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 8026): No ProfileInfo entries
I/LG Account v2.2( 8026): isEnabled: false
I/Feature ( 8026): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 8026): [Lifetracker]Country: EU
I/Feature ( 8026): [Lifetracker]Operator: OPEN
I/Feature ( 8026): [Lifetracker]Ranking support: false
I/Feature ( 8026): [Lifetracker]Comfort support: false
I/Feature ( 8026): [Lifetracker]Accessory: true
I/Feature ( 8026): [Lifetracker]Health device: true
I/Feature ( 8026): [Lifetracker]Extra Pedometer: false
I/Feature ( 8026): [Lifetracker]Blood glucose device: false
I/Feature ( 8026): [Lifetracker]Device Number: 3
,I/ActivityManager( 1038): Killing 7485:com.google.android.apps.books/u0a54 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10054/pid_7485/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 3822): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothRemoteDevices( 3822): [BTUI] setTrustState : false
D/BluetoothAdapterProperties( 3822): Failed to remove device: F8:95:C7:87:85:54
I/BluetoothBondStateMachine( 3822): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
W/bt-btm  ( 3822): Security Manager: encrypt_change status:0 State:0, encr_enable = 1
,W/bt-l2cap( 3822): L2CAP - st: CLOSED evt: 10
W/bt-l2cap( 3822): L2CAP - st: TERM_W4_SEC_COMP evt: 7
W/bt-l2cap( 3822): L2CA_ErtmConnectRsp()  CID: 0x0045  Result: 0  Status: 0  BDA: f895c7878554  p_ertm_info:0x00000000
W/bt-l2cap( 3822): L2CAP - st: W4_L2CA_CON_RSP evt: 22
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 24
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 14
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 25
W/bt-l2cap( 3822): L2CAP-Upper layer Config_Rsp,Local CID: 0x0045,Remote CID: 0x0042,PSM: 3,our MTU present:1,our MTU:1691
W/bt-l2cap( 3822): L2CAP - st: CONFIG evt: 15
W/bt-l2cap( 3822): L2CAP-peer_Config_Rsp,Local CID: 0x0045,Remote CID: 0x0042,PSM: 3,peer MTU present: 0,peer MTU: 1691
I/BluetoothBondStateMachine( 3822): StableState(): Entering Off State
,I/wpa_supplicant( 7863): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1038): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
W/bt-l2cap( 3822): L2CA_SetDesireRole() new:x0, disallow_switch:0
W/bt-btif ( 3822): new conn_srvc id:26, app_id:255
W/bt-btif ( 3822): new conn_srvc id:26, app_id:255 count:1
W/bt-btif ( 3822): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3822): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7001): Incoming connection accepted
--------- beginning of crash
F/libc    ( 7001): Fatal signal 11 (SIGSEGV), code 2, fault addr 0x946ddff0 in tid 7755 (Thread-830)
I/libc    ( 7001): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
I/WindowState( 1038): WIN DEATH: Window{2f09fdd2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 1038): Client connection lost with reason: 4
D/InputDispatcher( 1038): Window went away: Window{2f09fdd2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/bt-l2cap( 3822): L2CA_SetDesireRole() new:x0, disallow_switch:0
,W/bt-rfcomm( 3822): rfc_port_closed
W/bt-btif ( 3822): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
E/bt-btif ( 3822): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
I/Zygote  (  343): Process 7001 exited due to signal (11)
,I/ActivityManager( 1038): Process com.test.thalitest (pid 7001) has died
,I/ActivityManager( 1038): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=8051 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
,D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{32d340ca co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{27ec523b co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
,D/ContextHelper( 8051): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 8051): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 8051): Loading: webviewchromium
,I/LibraryLoader( 8051): Time to load native libraries: 3 ms (timestamps 7187-7190)
I/LibraryLoader( 8051): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 8051): Binding Chromium to main looper Looper (main, tid 1) {711e11c}
,I/LibraryLoader( 8051): Expected native library version number "",actual native library version number ""
,I/chromium( 8051): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 8051): Initializing chromium process, renderers=0
W/art     ( 8051): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 8051): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 8051): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 8051): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,V/AudioPolicyService(  317): registerClient() client 0xb14fd600, uid 10311
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37bdbe9f:true
,I/Adreno-EGL( 8051): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8051): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 8051): Build Date: 12/12/14 금
I/Adreno-EGL( 8051): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 8051): Remote Branch: 
I/Adreno-EGL( 8051): Local Patches: 
I/Adreno-EGL( 8051): Reconstruct Branch: 
,W/chromium( 8051): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 8051): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 8051): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 8051): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 8051): CordovaWebView is running on device made by: LGE
,W/art     ( 8051): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 8051): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1038): Activity pause timeout for ActivityRecord{3d0d281f u0 com.test.thalitest/.MainActivity t4}
,D/OpenGLRenderer( 8051): Render dirty regions requested: true
,I/OpenGLRenderer( 8051): Initialized EGL, version 1.4
,D/OpenGLRenderer( 8051): Enabling debug mode 0
,D/Atlas   ( 8051): Validating map...
,D/SplitWindow( 1038): check instance of lgWin Window{15f965a1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/LgDataFeature( 8051): LgDataFeature() Constructor: none
D/LgDataFeature( 8051): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1038): Displayed com.test.thalitest/.MainActivity: +776ms (total +880ms)
,I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{3d0d281f u0 com.test.thalitest/.MainActivity t4} time:467764
,I/Timeline( 8051): Timeline: Activity_idle id: android.os.BinderProxy@84c0d95 time:467765
,I/chromium( 8051): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 8051): 
,D/JsMessageQueue( 8051): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 8051): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435098880
,D/JX-Cordova( 8051): jxcore cordova android initializing
W/bt-l2cap( 3822): L2CA_DisconnectReq()  CID: 0x0045
W/bt-l2cap( 3822): L2CAP - st: W4_L2CAP_DISC_RSP evt: 17
,W/jxcore-log( 8051): Initializing JXcore engine
W/jxcore-log( 8051): JXcore engine is ready
,W/jxcore-log( 8051): Starting JXcore engine
W/.test.thalitest( 8051): type=1400 audit(0.0:175): avc: denied { ioctl } for path="socket:[8341]" dev="sockfs" ino=8341 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 8051): type=1400 audit(0.0:176): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 8051): type=1400 audit(0.0:177): avc: denied { ioctl } for path="socket:[9572]" dev="sockfs" ino=9572 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 8051): type=1400 audit(0.0:178): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 8051): type=1400 audit(0.0:179): avc: denied { ioctl } for path="socket:[36651]" dev="sockfs" ino=36651 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,E/wpa_supplicant( 7863): USIM:  scard_init function
I/wpa_supplicant( 7863): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=66 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1038): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=67 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1038): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=68 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 dur:2145 bcn=0
E/WifiStateMachine( 1038):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 dur:2145 bcn=0
E/WifiStateMachine( 1038):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 dur:2145 bcn=0
E/WifiStateMachine( 1038):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=1 known=0 got=1 dur:2145 bcn=0
D/WifiNative-wlan0( 1038): doString: [BSS RANGE=0- MASK=0x21987]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 68 0 rt=469446  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 68 0 rt=469462  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
,D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
W/jxcore-log( 8051): Platform android
W/jxcore-log( 8051): 
,W/jxcore-log( 8051): Process ARCH arm
W/jxcore-log( 8051): 
I/jxcore-log( 8051): JXcore Cordova bridge is ready!
I/jxcore-log( 8051): 
W/jxcore-log( 8051): JXcore engine is started
,I/jxcore-log( 8051): Toggling radios to true
I/jxcore-log( 8051): 
,D/BluetoothAdapter( 8051): enable(): BT is already enabled..!
D/WifiService( 1038): New client listening to asynchronous messages
D/WifiServiceImplEx( 1038): setWifiEnabled: true pid=8051, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1038): setWifiEnabled: true pid=8051, uid=10311
,E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1038): disconnect pid=8051, uid=10311, packageName=com.test.thalitest
,E/WifiStateMachine( 1038):  DisconnectedState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1038): reconnect pid=8051, uid=10311, packageName=com.test.thalitest
,E/WifiStateMachine( 1038):  ConnectModeState CMD_DISCONNECT 0 0
E/WifiConfigStore( 1038): setLastSelectedConfiguration -1
I/jxcore-log( 8051): Radios toggled
I/jxcore-log( 8051): 
E/WifiNative: ( 1038): [470,581,431 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: DISCONNECT
I/wpa_supplicant( 7863): wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
I/wpa_supplicant( 7863): wlan0: CTRL-EVENT-ASSOC-REJECT status_code=1
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=69 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: 00:00:00:00:00:00 reason=3
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=70 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-ASSOC-REJECT status_code=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=71 dispatchEvent: CTRL-EVENT-ASSOC-REJECT status_code=1
,D/WifiMonitor( 1038): Assoc Reject: Could not parse assoc reject string
,D/WifiNative-wlan0( 1038): DISCONNECT: returned true
E/WifiStateMachine( 1038):  DisconnectedState CMD_RECONNECT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1038): [471,518,828 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1038): doBoolean: RECONNECT
D/WifiNative-wlan0( 1038): RECONNECT: returned true
I/wpa_supplicant( 7863): Trying to associate with SSID 'NG700'
E/WifiStateMachine( 1038):  DisconnectedState NETWORK_DISCONNECTION_EVENT 00:00:00:00:00:00 nid=1 reason=3 rt=471520
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 70 0 rt=471520  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 70 0 rt=471521  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  DisconnectedState ASSOCIATION_REJECTION_EVENT 71 -1 blacklist=false rt=471522
E/WifiStateMachine( 1038):  ConnectModeState ASSOCIATION_REJECTION_EVENT 71 -1 blacklist=false rt=471522
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=72 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 72 0 rt=471526  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,D/WifiHS20( 1038): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 72 0 rt=471544  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiHS20( 1038): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATING
I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7112): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7112): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 7863): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=73 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1038): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=74 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=75 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 73 0 rt=471761  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 73 0 rt=471762  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1038):  DisconnectedState CMD_ASSOCIATED_BSSID 74 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=471762
E/WifiStateMachine( 1038):  ConnectModeState CMD_ASSOCIATED_BSSID 74 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=471763
E/WifiStateMachine( 1038):  DriverStartedState CMD_ASSOCIATED_BSSID 74 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=471763
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_ASSOCIATED_BSSID 74 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=471764
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine( 1038):  DefaultState CMD_ASSOCIATED_BSSID 74 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=471764
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 75 0 rt=471765  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/Tethering( 1038): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 75 0 rt=471767  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
,E/WifiStateMachine( 1038):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1038):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateASSOCIATED
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateFOUR_WAY_HANDSHAKE
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7079): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 7079): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7079): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 7079): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/btif_config_util( 3822): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=76 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 7863): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 7863): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=77 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1038): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=78 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1038): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiStateMachine( 1038):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 76 0 rt=471884  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=79 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 76 0 rt=471885  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1038):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=471887
E/WifiStateMachine( 1038):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=471888
D/WifiNative-wlan0( 1038): doString: [STATUS]
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=80 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1038):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1038): setVHTCapabilityType  : false
,I/WifiServerServiceExt( 1038): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1038): setKeepAlivePacketInterval msec : 60
,W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
E/bt-btm  ( 3822): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3822): L2CA_SetDesireRole() new:x0, disallow_switch:0
D/WifiServerServiceExt( 1038): Connected BT device : -1
I/BluetoothMapService( 3822): onReceive: android.bluetooth.device.action.ACL_DISCONNECTED
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/ConnectivityService( 1038): Got NetworkAgent Messenger
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1038): NetworkAgent connected
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/CommandListener(  313): Setting iface cfg
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1038): Start Dhcp Watchdog 3
D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 79 0 rt=471942  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 79 0 rt=471942  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 79 0 rt=471943  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 80 0 rt=471944  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 80 0 rt=471944  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 80 0 rt=471945  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:27586] from screen [on:0 period:-1337098621] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1038): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1038):  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1337098620] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
D/WifiNative-wlan0( 1038): doString: [SIGNAL_POLL]
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1038): updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=346,0,0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=346,0,0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 0
I/wpa_supplicant( 7863): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 0
D/WifiNative-wlan0( 1038): SET ps 0: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 7863): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 1: returned true
,D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@20b64881 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@20b64881 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1038): DHCP Start wake lock is acquired.
E/WifiStateMachine( 1038): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1038): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1038): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  313): Setting iface cfg
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/CommandListener(  313): Trying to bring up wlan0
V/LgDhcpStateMachineHelper( 1038): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
E/WifiStateMachine( 1038):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
E/WifiStateMachine( 1038):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1038): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 7863): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateCOMPLETED
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 7863): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1038): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
W/WindowManager( 1038): App freeze timeout expired.
,V/BluetoothPbapReceiver( 3822): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3822): ***********action = android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapReceiver( 3822): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3822): action: android.bluetooth.device.action.ACL_DISCONNECTED
V/BluetoothPbapService( 3822): state: -2147483648
D/LGBluetoothPowerSaveListener( 7079): [BTUI] ACL disconnected => AclLinkCount = 0
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
D/ConnectivityService( 1038): Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
E/WifiStateMachine( 1038):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1038): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1038): ignoring duplicate network state non-change
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1038): Adding iface wlan0 to network 102
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine( 1038): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = true, mWifiLevel = 3
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1970): handleWifiStateChangedEvent: 1
,E/ConnectivityService( 1038): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1038): Adding Route [fe80::/64 -> :: wlan0] to network 102
D/ConnectivityService( 1038): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Netd    (  313): netlink response contains error (File exists)
D/WifiHS20( 1038): [PASSPOINT] passpointNotification: hs20AP list is checked
D/ConnectivityService( 1038): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
D/ConnectivityService( 1038): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1038): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
D/ConnectivityService( 1038): Setting Dns servers for network 102 to [/192.168.1.1]
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1038): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 102]
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
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1870): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
E/ConnectivityService( 1038): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan,0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1038): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI    ( 1038): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 28
,D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1038): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1038): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1038): validation of new default Network = false
D/ConnectivityService( 1038): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1038): enableDataServiceNotify 
D/DSQN    ( 1038): start dsqn bin
D/LocSvc_java( 1038): Sending msg: 4 arg1:1 arg2:1
W/dsqn    ( 8165): type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 8165): type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524290
V/NetworkPolicy( 1038): [LG_RESTRICTED] checkMobilePolicy_type()
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
,I/BTConnectionReceiver( 4624): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = true, mWifiLevel = 3
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
I/BluetoothClassifier( 4624): Bluetooth Device Name: G3s-1
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/DSQN    ( 8165): DSQN ssw
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/libc-netbsd(  313): res_queryN name = clients3.google.com, class = 1, type = 1
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7136): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7136): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7136): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/libc-netbsd(  313): res_queryN name = clients3.google.com succeed
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 7136): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 7136): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 7136): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/LGDataListener(  313): argv[0]=dsqncommand
D/LGDataListener(  313): argv[1]=wlan0
D/LGDataListener(  313): argv[2]=1
D/LGDataListener(  313): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1038): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1038): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 17 Dec 2015 14:17:27 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450361847631], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450361847604]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Validated
D/ConnectivityService( 1038): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1038): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1038):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1038):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1038): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService( 1038): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524290
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1038): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1870): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/DhcpStateMachine( 1038): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper( 1038): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1038): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 8171): type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 8171): type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 8171): version 5.5.6 starting
,E/dhcpcd  ( 8171): get_duid: m
D/dhcpcd  ( 8171): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 8171): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/dhcpcd  ( 8171): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 8171): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
,D/dhcpcd  ( 8171): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 8171): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 8171): wlan0: sending REQUEST (xid 0xb57fa855), next in 4.97 seconds
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 8051): Got Device Bluetooth address: 58:3F:54:73:64:C0
I/jxcore-log( 8051): 
I/jxcore-log( 8051): my name is : LGE-LG-D855_PT1570
I/jxcore-log( 8051): 
I/jxcore-log( 8051): attempting to connect to test coordinator
I/jxcore-log( 8051): 
,I/jxcore-log( 8051): check test folder
I/jxcore-log( 8051): 
I/jxcore-log( 8051): found test : ./testFindPeers.js
I/jxcore-log( 8051): 
I/jxcore-log( 8051): found test : ./testReConnect.js
I/jxcore-log( 8051): 
,I/jxcore-log( 8051): found test : ./testSendData.js
I/jxcore-log( 8051): 
,I/jxcore-log( 8051): Test app app.js loaded
I/jxcore-log( 8051): 
,I/chromium( 8051): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 8051): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 8051): 
,I/chromium( 8051): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 8051): DBG, CoordinatorConnector connect called
I/jxcore-log( 8051): 
I/jxcore-log( 8051): Coordinator is now connected to the server!
I/jxcore-log( 8051): 
,I/chromium( 8051): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 8051): DBG, CoordinatorConnector too_late called
I/jxcore-log( 8051): 
I/jxcore-log( 8051): got too_late message
I/jxcore-log( 8051): 
I/jxcore-log( 8051): stop tests now !
I/jxcore-log( 8051): 
,I/jxcore-log( 8051): CoordinatorConnector close called
I/jxcore-log( 8051): 
I/jxcore-log( 8051): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 8051): 
I/jxcore-log( 8051): The Coordinator has disconnected!
I/jxcore-log( 8051): 
I/jxcore-log( 8051): The Coordinator has closed!
I/jxcore-log( 8051): 
I/jxcore-log( 8051): stop tests now !
I/jxcore-log( 8051): 
I/jxcore-log( 8051): turning Radios off
I/jxcore-log( 8051): 
I/jxcore-log( 8051): Toggling radios to false
I/jxcore-log( 8051): 
D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1038): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@9df6d67 mBinding = false
,D/BluetoothManagerService( 1038): Message: 2
D/LocationManagerService( 1038): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1038): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1038): JNI:system_update. Event-4
D/BluetoothManagerService( 1038): Sending off request.
,D/LGBluetoothServiceAdapter( 3822): [BTUI] Precleanup
D/BluetoothAdapterState( 3822): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3822): Setting state to 13
I/BluetoothAdapterState( 3822): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3822): onBluetoothDisable()
D/WifiServiceImplEx( 1038): setWifiEnabled: false pid=8051, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
I/BluetoothAdapterState( 3822): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/WifiService( 1038): setWifiEnabled: false pid=8051, uid=10311
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothManagerService( 1038): Message: 60
D/BluetoothManagerService( 1038): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1038): Bluetooth State Change Intent: 12 -> 13
D/LGBluetoothAPIService( 1970): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1466): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,I/BluetoothMapService( 3822): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3822): STATE_TURNING_OFF
V/BluetoothMapService( 3822): Handler(): got msg=4
D/BluetoothMapService( 3822): MAP Service closeService in
D/BluetoothMapMasInstance( 3822): MAP Service shutdown
V/BluetoothMapMasInstance( 3822): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3822): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3822): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3822): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3822): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3822): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3822): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3822): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/LGBluetoothMapAdapter( 3822): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3822): MAP Service closeService out
D/BluetoothAdapterProperties( 3822): Scan Mode:20
,D/BluetoothAdapterState( 3822): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BluetoothPbapService( 3822): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 3822): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/btif_config_util( 3822): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothFtpService:RfcommSocketAcceptThread( 3822): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3822): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 3822): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3822): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3822): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3822): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x0011
I/dhcpcd  ( 8171): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3822): bta_gattc_deregister Deregister Failedm unknown client cif
V/BtOppService( 3822): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 3822): stopping Accept Thread
V/BtOppRfcommListener( 3822): close mBtServerSocket
I/BtOppRfcommListener( 3822): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3822): waiting for thread to terminate
V/BtOppRfcommListener( 3822): done waiting for thread to terminate
,V/BtOppService( 3822): onDestroy
D/LGBluetoothOppAdapter( 3822): [BTUI] LGBluetoothOppAdapter cleanup
W/ContextImpl( 7079): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/LocationManagerService( 1038): getAllProviders()=[passive, gps, network]
,D/Ulp_jni ( 1038): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1038): JNI:system_update. Event-4
,E/WifiStateMachine( 1038):  ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
I/jxcore-log( 8051): Radios toggled
I/jxcore-log( 8051): 
I/jxcore-log( 8051): ****TEST TOOK:  ms ****
I/jxcore-log( 8051): 
I/jxcore-log( 8051): ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
I/jxcore-log( 8051): 
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
V/BluetoothPbapReceiver( 3822): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3822): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3822): ***********state = 13
V/BluetoothPbapReceiver( 3822): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3822): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3822): state: 13
V/BluetoothPbapService( 3822): Pbap Service closeService in
D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1038): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 7863): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
I/dhcpcd  ( 8171): wlan0: leased 192.168.1.141 for 86400 seconds
D/dhcpcd  ( 8171): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 8171): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 8171): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 8171): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 8171): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 8171): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 8171): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
V/BluetoothPbapService( 3822): successfully stopped pbap service
V/BluetoothPbapService( 3822): Pbap Service closeService out
V/BluetoothPbapService( 3822): Pbap Service onDestroy
,V/BluetoothPbapService( 3822): Pbap Service closeService in
V/BluetoothPbapService( 3822): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3822): [BTUI] cleanup
D/WifiNative-wlan0( 1038): SET ps 1: returned true
,D/CommandListener(  313): Clearing all IP addresses on wlan0
I/chromium( 8051): [INFO:CONSOLE(63)] "logCallback got too_late message", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 8051): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 2
,D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService( 1038): SCAN_AVAILABLE : 1
D/RttService( 1038): SCAN_AVAILABLE : 1
,D/WifiScanningService( 1038): DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1038): EnabledState got{ when=-4ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
V/WfdStateTracker( 1970): handleWifiStateChangedEvent: 0
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/LGWifiP2pService( 1038): InactiveState{ when=-19ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-19ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1038): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@10320a80
E/WifiStateMachine( 1038):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
,D/BluetoothManagerService( 1038): Message: 30
D/LGWifiP2pService( 1038): P2pDisablingState
D/LGWifiP2pService( 1038): P2pDisablingState{ when=-12ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): p2p socket connection lost
D/LGWifiP2pService( 1038): P2pDisabledState
E/WifiStateMachine( 1038):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1038): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 7863): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
V/WfdStateTracker( 1970): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1970): WifiP2pState is changed : false
D/WfdsService( 1970): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1970): Set the WFDS Monitor: false
D/BluetoothManagerService( 1038): Message: 30
,D/WfdsMonitor( 1970): WFDS Monitor is stopped
D/WfdsService( 1970): STATE : WfdsDisabledState - enter
D/CtrlSupplicant( 1970): Received on exit socket, terminate
E/CtrlSupplicant( 1970): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1970): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1970): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1970): DefaultState - msg [9445378] is not handled
W/WfdsSession:Controller( 1970): DefaultState - msg [9441355] is not handled
D/LocalBluetoothProfileManager( 7079): Adding local MAP profile
D/BluetoothMap( 7079): Create BluetoothMap proxy object
D/BluetoothManagerService( 1038): Message: 30
D/CommandListener(  313): Clearing all IP addresses on wlan0
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
,D/BluetoothManagerService( 1038): Message: 30
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1466): CM callback handler got msg 524292
I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/WifiHS20( 1038): hidePasspointNotification off =false
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/PCSuite ( 7112): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-p2p0( 1038): doBoolean: TERMINATE
D/WifiNative-p2p0( 1038): TERMINATE: returned true
E/WifiStateMachine( 1038): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1038): useWiFiOffloading() : false
E/WifiStateMachine( 1038): CONFIG_LGE_WLAN_PATH : true
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1038): Removing idletimer
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1038): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/LocalBluetoothProfileManager( 7079): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 7079):  get() - isFeatureLoaded : false
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/TelephonyNetworkFactory-1( 1870): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/TelephonyNetworkFactory-1( 1870):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
V/WfdStateTracker( 1970): WfdStateTracker handleDirectStateChangedEvent: 6
I/WifiServerServiceExt( 1038): WIFI_STATE_CHANGED_ACTION [0]
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
,D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1466): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1466): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGBluetoothUserBindClient( 7079): [BTUI] initUserBindClient
W/ContextImpl( 7079): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 7079): finishStartingService: stopping service
D/BluetoothInputDevice( 7079): Proxy object connected
,D/HidProfile( 7079): Bluetooth service connected
D/BluetoothPan( 7079): BluetoothPAN Proxy object connected
D/PanProfile( 7079): Bluetooth service connected
D/BluetoothMap( 7079): Proxy object connected
D/MapProfile( 7079): Bluetooth service connected
D/BluetoothMap( 7079): getConnectedDevices()
D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/BluetoothMap( 7079): Bluetooth is Not enabled
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/LGBluetoothUserBindClient( 7079): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 7079): [BTUI] cancel All Notification
,D/TelephonyIcons( 1466): null signal icon name: drawable/stat_sys_signal_null
D/BluetoothPermissionRequest( 7079): onReceive
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LGBluetoothAuthorization( 7079): [BTUI] cancel All Notification
V/BluetoothOppReceiver( 3822): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 3822): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 3822): [BTUI] cancel opp active transfer file notification
,D/LGBluetoothResetSettingReceiver( 7079): return without doing reset settings.
,V/BluetoothFtpReceiver( 3822): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3822): BluetoothFtpReceiver Start Service
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/BluetoothFtpService( 3822): Ftp Service onStartCommand
V/BluetoothFtpService( 3822): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3822): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3822): Shutdown
V/BluetoothFtpService( 3822): successfully stopped ftp service
I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/BluetoothSapReceiver( 3822): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 3822): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3822): SapReceiver onReceive 
V/BluetoothSapReceiver( 3822): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3822):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3822): Calling SAP service start service with action = null
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/BluetoothFtpService( 3822): Ftp Service onDestroy
V/BluetoothFtpService( 3822): Ftp Service closeService
V/BluetoothSapService( 3822): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3822): state: 13
V/BluetoothSapService( 3822): Stopping SAP server process
V/BluetoothSapService( 3822): Sap Service closeSapService in
V/BluetoothSapService( 3822): Close listen Socket : 
V/BluetoothSapService( 3822): Close rfcomm Socket : 
V/BluetoothSapService( 3822): Close sapd  Socket : 
I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7112): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/AndroidRuntime( 8211): 
D/AndroidRuntime( 8211): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8211): CheckJNI is OFF
,I/wpa_supplicant( 7863): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 7863): monitor socket send errors count : 1
I/wpa_supplicant( 7863): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1970-4\x00 that cannot receive messages
D/WifiMonitor( 1038): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1038): Dropping event because (p2p0) is stopped
I/ActivityManager( 1038): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=8239 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BluetoothSapService( 3822): Sap Service closeSapService out
V/BluetoothSapService( 3822): Sap Service onDestroy
V/BluetoothSapService( 3822): Sap Service closeSapService in
V/BluetoothSapService( 3822): Close listen Socket : 
V/BluetoothSapService( 3822): Close rfcomm Socket : 
V/BluetoothSapService( 3822): Close sapd  Socket : 
V/BluetoothSapService( 3822): Sap Service closeSapService out
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 7863): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=81 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
W/wpa_supplicant( 7863): USIM:  scard_deinit function
E/WifiStateMachine( 1038):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=473271
E/WifiStateMachine( 1038):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=473271
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=82 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1038): InitialState.processMessage what=4
E/WifiStateMachine( 1038):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 82 0 rt=473272  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1038):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 82 0 rt=473273  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1038):  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 7112): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7112): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/ResourcesManager( 8239): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
,D/AuthorizationBluetoothService( 2133): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/QRemote ( 7136): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 7136): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 7136): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 7079): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 7079): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 7079): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 7079): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 7079): [AUTORUN] setTetherStatus() : status=false
W/FormManager( 7267): Network not available. Please check & try again.
V/FormManager( 7267): Network unavailable.
,V/FormManager( 7267): Network unavailable.
D/AndroidRuntime( 8211): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1038): Killing 7670:com.lge.clock/u0a10 (adj 15): empty #17
D/DhcpStateMachine( 1038): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1038): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1038): [getKeyforDhcp] getBSSID, getSSID is null 
D/DhcpStateMachine( 1038): DHCP Start/Renew wake lock is released.
E/WifiStateMachine( 1038):  SupplicantStoppingState CMD_POST_DHCP_ACTION 1 0 OK 
D/DhcpStateMachine( 1038): RunningState
D/DhcpStateMachine( 1038): RunningState{ when=-347ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1038):  DefaultState CMD_POST_DHCP_ACTION 1 0 OK 
,I/wpa_supplicant( 7863): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=83 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1038): Disconnecting from the supplicant, no more events
,E/WifiStateMachine( 1038):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 83 0
W/PackageSettings( 1038): Skipping PackageSetting{1421c4b2 com.example.hello/10319} due to missing metadata
W/libprocessgroup( 1038): failed to open /acct/uid_10010/pid_7670/cgroup.procs: No such file or directory
,I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1038): Killing 8051:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
D/WifiService( 1038): Client connection lost with reason: 4
I/WindowState( 1038): WIN DEATH: Window{15f965a1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher( 1038): Window went away: Window{15f965a1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-469ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager( 1038):   Force finishing activity ActivityRecord{3d0d281f u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  337): DFP En is all cleared set to be enabled
,D/WifiOffDelayIfNotUsed( 1038): stopMonitoring
E/WifiStateMachine( 1038): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1038): useWiFiOffloading() : false
E/WifiStateMachine( 1038): CONFIG_LGE_WLAN_PATH : true
W/ActivityManager( 1038): Spurious death for ProcessRecord{312630dc 8051:com.test.thalitest/u0a311}, curProc for 8051: null
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{154f2d58 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/ActivityManager( 1038): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
D/SplitWindowPolicy( 1970): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1970): topRunningActivity=ActivityInfo{1c974eb1 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/ActivityManager( 1038):   Force finishing activity ActivityRecord{3d0d281f u0 com.test.thalitest/.MainActivity t4 f}
,W/ActivityManager( 1038): Duplicate finish request for ActivityRecord{3d0d281f u0 com.test.thalitest/.MainActivity t4 f}
,D/WfdsService( 1970): Supplicant Connection state is changed : false
D/WfdsService( 1970): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1970): Set the WFDS Monitor: false
D/WfdsMonitor( 1970): WFDS Monitor is stopped
D/StatusBar.NetworkController( 1466): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WfdStateTracker( 1970): WfdStateTracker handleDirectStateChangedEvent: 0
,W/Settings( 1835): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardModel( 1466): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 2088): [Launcher.java:5338:onStart()]onStart
I/InputReader( 1038): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 2088): [Launcher.java:903:onResume()]onResume
,I/[SystemUI]QSlideListController( 1466): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2088): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
W/GeofencerStateMachine( 1835): Ignoring removeGeofence because network location is disabled.
I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
E/LGBluetoothAvrcpQcomAdapter( 3822): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3822): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2049): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 3672): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 4326): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/System.err( 4571): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4571): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4571): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4571): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4571): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4571): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4571): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4571): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4571): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4571): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4571): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4571): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,I/art     ( 4624): Explicit concurrent mark sweep GC freed 20636(1098KB) AllocSpace objects, 1(16KB) LOS objects, 34% free, 30MB/46MB, paused 553us total 136.856ms
I/ActivityManager( 1038): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8287 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
D/ActionManagerService( 1924): notifyUserLog: 1000003
,D/LIA_Informant_ActionManagerMessageHandler( 3672): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2088): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[LGHome]LGActivityUtil( 2088): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2088): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2088): [Launcher.java:1114:onPause()]onPause
W/ContextImpl( 4326): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1466): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
E/WifiStateMachine( 1038):  InitialState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_ON_QUIT 0 0
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,D/ActionManagerService( 1924): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2088): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/KeyguardModel( 1466): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
V/BoardContentProvider( 3672): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
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
I/GBoardWebViewUtils( 2088): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1449757673225
I/GBoardWebViewUtils( 2088): , create_time: 1449757673771
I/GBoardWebViewUtils( 2088): , expire_time: 0
I/GBoardWebViewUtils( 2088): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1449757673225&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2088): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2088): , display: false
I/GBoardWebViewUtils( 2088): , animation: false }
D/LIA_Informant_ActionManagerMessageHandler( 3672): handleMessage: what(1000) actionID(0x1000004)
,I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3174c1ef,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/WallpaperManager( 2088): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
D/LGDMClient( 4326): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
,I/[LGHome]EVENT( 2088): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2088): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4326): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/bt_hci_bdroid( 3822): cleanup
I/bt_lpm  ( 3822): LPM is already off!!!
I/bt_userial_mct( 3822): exiting userial_read_thread
D/bt_userial_mct( 3822): Leaving userial_evt_read_thread()
W/bt-btif ( 3822): ag scb idx 1 not allocated
E/bt-btif ( 3822): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3822): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3822): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3822): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3822): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3822): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial_mct( 3822): userial_close_reader Joined userial reader thread: 0
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3822): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3822): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3822): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3822): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3822): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3822): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt_vendor( 3822): hw_epilog_process
D/bt_hci_bdroid( 3822): cleanup Finalizing cleanup
D/bt_userial_mct( 3822): userial_close
E/bt_userial_mct( 3822): pthread_join() FAILED result:3
,I/bt_vendor( 3822): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
W/ActivityManager( 1038): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
I/art     ( 1038): Explicit concurrent mark sweep GC freed 98077(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 4.815ms total 245.923ms
I/PCSuite ( 7112): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 7112): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7112): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/LGBluetoothAvrcpQcomAdapter( 3822): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3822): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3822): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3822): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3822): [BTUI]          packageName: com.lge.music
,D/LGBluetoothAvrcpQcomAdapter( 3822): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3822): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3822): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3822): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3822): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3822): [BTUI] [-] updateMediaPlayerInfo
I/art     ( 1038): WaitForGcToComplete blocked for 69.909ms for cause Explicit
V/WiFiOffLoadBroadcast( 7079): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 7079): MCCMNC not supported: null
D/PostponalbeReceiver( 6644): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
I/WifiServerServiceExt( 1038): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1038): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1038): batteryPsActivateMsgHandler : this is not treated
I/LockScreenSettings( 8287): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
D/SplitUIManager( 1888): split_name #11 / not available #0
,D/SplitUIService( 1888): removed split : 
I/[LGHome]EVENT( 2088): [Launcher.java:5349:onStop()]onStop
W/FormManager( 7267): Network not available. Please check & try again.
D/administrator( 1038): Handling package changes for user 0
,V/FormManager( 7267): Network unavailable.
V/FormManager( 7267): Network unavailable.
D/SplitUIManager( 1888): split_name #11 / not available #0
,I/SplitUIService( 1888): split app #11
D/KeyguardModel( 1466): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1466): createShortcutInfo...
,D/KeyguardModel( 1466): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
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
,W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1466): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/NotificationService( 1038): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1038): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1466): createShortcutInfo...
D/JobSchedulerService( 1038): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister( 1038): removeObsoleteFile: deleting file=4_task.xml
D/KeyguardModel( 1466): handleShortcutListChanged...
D/PhoneStatusBar( 1466): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1466): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1466):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1466): , Keyguard show=false, IME shown=false, Panel expanded=false
D/KeyguardModel( 1466): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1466): createShortcutInfo...
D/KeyguardModel( 1466): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1466): createShortcutInfo...
,W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/AppUp4:PreloadHelper( 7922): added Exclude : com.test.thalitest
D/KeyguardModel( 1466): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1466): createShortcutInfo...
W/ResourceType( 1466): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1466): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1466): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1466): createShortcutInfo...
I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/ActivityManager( 1038): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8315 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 7891:com.lge.bnr/1000 (adj 15): empty #17
I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2088): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2088): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/ThermalEngine(  326): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3125): Thermal-Lib-Client: Client request sent
,I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/bt_hci_bdroid( 3822): set_power 0
I/bt_vendor( 3822): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3822): bluetooth satus is on
I/bt_vendor( 3822): bt-vendor : resetting BT status
I/bt_vendor( 3822): Starting hciattach daemon
I/bt_vendor( 3822): try to set false
I/bt_vendor( 3822): Starting hciattach daemon
I/bt_vendor( 3822): try to set false
I/bt_vendor( 3822): cleanup
I/GKI_LINUX( 3822): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3822): GKI_exit_task 0 done
I/GKI_LINUX( 3822): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3822): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
I/[Concierge]WidgetView( 2088): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,W/ResourcesManager( 1038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1038): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/art     ( 1038): Explicit concurrent mark sweep GC freed 13810(778KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.064ms total 202.076ms
,D/KeyguardModel( 1466): handleShortcutListChanged...
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_7891/cgroup.procs: No such file or directory
D/[Concierge]Service( 2583): onStartCommand(). Type : 8
D/[Concierge]Service( 2583): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/HeadsetService( 3822): Received stop request...Stopping profile...
D/[Concierge]Service( 2583): Update widget ID : 11
,D/[Concierge]WidgetView( 2088): change position of spinner
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{b085d35 u0 com.lge.launcher2/.Launcher t3} time:474238
I/LGBluetoothHfpAdapter( 3822): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3822): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3822): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a4e0ab
D/HeadsetStateMachine( 3822): Exit Disconnected: -1
D/BluetoothHeadset( 1870): Proxy object disconnected
D/BluetoothHeadset( 1038): Proxy object disconnected
D/AudioService( 1038): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1870): Proxy object disconnected
D/BluetoothHeadset( 1870): Proxy object disconnected
D/A2dpService( 3822): Received stop request...Stopping profile...
D/LGBluetoothAvrcpQcomAdapter( 3822): [BTUI] cleanup
D/BluetoothAdapterState( 3822): Stopping profile services that were post enabled
D/LGBluetoothA2dpAdapter( 3822): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3822): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3822): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a4e0ab
D/BluetoothA2dp( 1038): Proxy object disconnected
D/AudioService( 1038): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 3822): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3822): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a4e0ab
D/BluetoothInputDevice( 7079): Proxy object disconnected
D/HeadsetStateMachine( 3822): Unbinding service...
D/A2dpStateMachine( 3822): Exit Disconnected: -1
I/[Concierge]WidgetView( 2088): initWebView(). Time : 1450361849716
D/[Concierge]Service( 2583): onStartCommand(). Type : 0
D/HidProfile( 7079): Bluetooth service disconnected
,D/HeadsetPhoneState( 3822): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3822): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3822): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3822): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3822): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3822): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3822): [BTUI] LGBluetoothHfpAdapter cleanup
D/HealthService( 3822): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3822): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a4e0ab
D/PanService( 3822): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3822): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a4e0ab
D/BtGatt.DebugUtils( 3822): handleDebugAction() action=null
D/BtGatt.GattService( 3822): Received stop request...Stopping profile...
D/BtGatt.GattService( 3822): stop()
D/BluetoothPan( 7079): BluetoothPAN Proxy object disconnected
D/PanProfile( 7079): Bluetooth service disconnected
D/BtGatt.AdvertiseManager( 3822): advertise clients cleared
D/BluetoothAdapterService( 3822): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a4e0ab
D/BluetoothMapService( 3822): Received stop request...Stopping profile...
D/BluetoothMapService( 3822): stop()
D/BluetoothMapEmailAppObserver( 3822): deinitObservers()
D/BluetoothMapEmailAppObserver( 3822): removeReceiver()
D/BluetoothAdapterService( 3822): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a4e0ab
D/BluetoothMap( 7079): Proxy object disconnected
D/MapProfile( 7079): Bluetooth service disconnected
I/BluetoothA2dpServiceJni( 3822): cleanupNative
I/GKI_LINUX( 3822): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3822): GKI_exit_task 2 done
I/GKI_LINUX( 3822): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3822): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3822): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3822): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3822): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3822): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3822): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3822): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 3822): Handler(): got msg=4
D/BluetoothMapService( 3822): MAP Service closeService in
D/LGBluetoothMapAdapter( 3822): [BTUI] LGBluetoothMapAdapter cleanup
W/ResourcesManager( 8315): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/BluetoothMapService( 3822): MAP Service closeService out
D/BluetoothMapService( 3822): cleanup()
D/BluetoothMapService( 3822): MAP Service closeService in
D/LGBluetoothMapAdapter( 3822): [BTUI] LGBluetoothMapAdapter cleanup
W/ResourcesManager( 8315): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/BluetoothMapService( 3822): MAP Service closeService out
D/BluetoothAdapterState( 3822): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3822): Setting state to 10
I/BluetoothAdapterState( 3822): Bluetooth adapter state changed: 13-> 10
W/ResourcesManager( 8315): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
D/BluetoothManagerService( 1038): Message: 60
I/BluetoothAdapterState( 3822): Entering OffState
D/BluetoothManagerService( 1038): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1038): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothPbap( 7079): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1038): onBluetoothStateChange: up=false
W/R,esourcesManager( 8315): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
D/BluetoothHeadset( 1870): onBluetoothStateChange: up=false
W/ResourcesManager( 8315): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/BluetoothHeadset( 1870): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7079): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1038): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1870): onBluetoothStateChange: up=false
D/BluetoothPan( 7079): onBluetoothStateChange on: false
D/BluetoothMap( 7079): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1038): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1038): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothManagerService( 1038): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1038): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1038): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@9df6d67 mBinding = false
D/BluetoothManagerService( 1038): Sending unbind request.
,D/BluetoothManagerService( 1038): Bluetooth State Change Intent: 13 -> 10
I/[SystemUI]BluetoothHandler( 1466): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1970): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1970): Message: 2
D/LGBluetoothAPIService( 1970): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@144c9f96 mBinding = false
D/LGBluetoothAPIService( 1970): Sending unbind request.
D/LGBluetoothUtils( 7079): [BTUI] resetProperty - success
E/LGBluetoothEventManager( 7079): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7079): [BTUI] clear device connection state
I/GKI_LINUX( 3822): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3822): GKI_exit_task 1 done
I/GKI_LINUX( 3822): GKI_shutdown(): task [BTIF] terminated
W/ContextImpl( 7079): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/BluetoothServiceJni( 3822): cleanupNative: return from cleanup
I/art     ( 3822): --- WEIRD: removing null entry 246
W/art     ( 3822): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3822): Cleaning up Bluetooth Service callback object
D/BluetoothAdapter( 1466): 19655261: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1466): 19655261: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothSettingsDBObserver( 3822): [BTUI] unregister observer for LG device name DB
I/art     ( 3822): System.exit called, status: 0
I/AndroidRuntime( 3822): VM exiting with result code 0, cleanup skipped.
D/DockEventReceiver( 7079): finishStartingService: stopping service
I/[Concierge]WebView( 2088): Return exist ConciergeWebView. Reuse : 280066085
,D/[Concierge]WidgetView( 2088): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2088): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2088): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@acb230d
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2088): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
V/AudioFlinger(  317): 3822 died, releasing its sessions
V/AudioFlinger(  317):  pid 1870 @ 0
V/AudioFlinger(  317):  pid 3377 @ 1
V/AudioFlinger(  317):  pid 3377 @ 2
D/LGBluetoothUserBindClient( 7079): [BTUI] onServiceDisconnected
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2088): isWidgetUpdateSkippable ? true
I/[LGHome]EVENT( 2088): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/[Concierge]WidgetBroadcastReceiver( 2088): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
D/AndroidRuntime( 8211): Shutting down VM
,I/ActivityManager( 1038): Process com.android.bluetooth (pid 3822) has died
W/ActivityManager( 1038): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,D/BluetoothPermissionRequest( 7079): onReceive
D/LGBluetoothUtils( 7079): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 7079): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 7079): return without doing reset settings.
W/[Concierge]WidgetView( 2088): Widget kill message received. Destory myself. My : 1450361403146, New one : 1450361849716
D/[Concierge]WidgetView( 2088): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2088): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/SystemConfig( 8315): BUILD Country: EU
I/SystemConfig( 8315): BUILD Operator: OPEN
,I/ActivityManager( 1038): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=8338 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 8338): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 8338): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8338): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 8338): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/BluetoothAdapterApp( 8338): Loading JNI Library
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2088): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/ActivityManager( 1038): Killing 7962:com.lge.email/u0a23 (adj 15): empty #17
E/[LgeWidgetLib]LgeAppWidgetHostView( 2088): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2088): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2088): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/BluetoothAdapterApp( 8338): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@161555f0 Instance Count = 1
I/Timeline( 2088): Timeline: Activity_idle id: android.os.BinderProxy@2633993f time:474426
,W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_7962/cgroup.procs: No such file or directory
,D/BluetoothAdapterApp( 8338): onCreate
I/SystemConfig( 8315): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 8315): existFile = false
I/SystemConfig( 8315): canReadFile = false
I/SystemConfig( 8315): systemFeature RCS result false
D/SystemConfig( 8315): refreshRcsSupport() :false
D/VoicemailCleanupService( 2194): Cleaning up data for package: com.test.thalitest
D/ProfileConfigQcom( 8338): [BTUI] HeadsetService is supported
,D/ProfileConfigQcom( 8338): Adding HeadsetService
D/ProfileConfigQcom( 8338): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 8338): Adding A2dpService
D/ProfileConfigQcom( 8338): [BTUI] HidService is supported
D/ProfileConfigQcom( 8338): Adding HidService
D/ProfileConfigQcom( 8338): [BTUI] HealthService is supported
D/ProfileConfigQcom( 8338): Adding HealthService
D/LGBluetoothFeatureConfig( 8338): isSupportPan() :  mTargetOp=OPEN
D/ProfileConfigQcom( 8338): [BTUI] PanService is supported
D/ProfileConfigQcom( 8338): Adding PanService
D/ProfileConfigQcom( 8338): [BTUI] GattService is supported
D/ProfileConfigQcom( 8338): Adding GattService
D/ProfileConfigQcom( 8338): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 8338): Adding BluetoothMapService
D/ProfileConfigQcom( 8338): [BTUI] HeadsetClientService is NOT supported
D/LGBluetoothOppAdapter( 8338): [BTUI] getInstance : create [LGBluetoothOppAdapter]
I/ActivityManager( 1038): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8359 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/LGBluetoothUserBindClient( 7079): [BTUI] onServiceConnected
,V/LGMDMManagerInternal( 8338): Create singleton instance
,W/ResourcesManager( 8359): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8359): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 8359): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8359): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
V/BluetoothFtpReceiver( 8338): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 8338): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 8338): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 8338): SapReceiver onReceive 
V/BluetoothSapReceiver( 8338): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 8338):  Bluetooth Adapter state = 10
D/LGBluetoothProfileConnectionReceiver_EasySetting( 8239): [BTUI] STATE_OFF : reset connected device information EasySettings
I/ActivityManager( 1038): Killing 7290:com.android.chrome/u0a57 (adj 15): empty #17
I/chromium( 2088): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,D/AuthorizationBluetoothService( 2133): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/libprocessgroup( 1038): failed to open /acct/uid_10057/pid_7290/cgroup.procs: No such file or directory
I/LGEmail ( 8359): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8359): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
I/GBoardtInterface( 2088): onReloaded()
,W/ResourceType( 8359): No package identifier when getting value for resource number 0x00000000
I/GBoardWebViewClient( 2088): onPageFinished url:file:///android_asset/www/main.html
,V/BoardContentProvider( 3672): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 3672): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1924): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3672): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3672): onEvent() : ACTION_BOARD_ENABLED
,D/ActionManagerService( 1924): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3672): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3672): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3672): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3672): onSettingEvent() : GBoard On - add scheduler - 0,
V/BoardContentProvider( 3672): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2088): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2088): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2088): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2088): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2088): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1449757673225&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2088): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1449757673225&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/LgDataFeature( 8359): LgDataFeature() Constructor: none
D/LgDataFeature( 8359): LgDataFeature() Constructor Done, null
,I/PackageChangeReceiver( 8359): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager( 1038): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8382 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 7335:com.lge.drmservice/u0a62 (adj 15): empty #17

```
