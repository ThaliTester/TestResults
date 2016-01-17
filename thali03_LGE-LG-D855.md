#### Test 5615109319b4771_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/[SystemUI]BatterySaverHandler( 1459): onReceive = android.intent.action.BATTERY_CHANGED
,D/AndroidRuntime( 6382): 
D/AndroidRuntime( 6382): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6382): CheckJNI is OFF
D/AndroidRuntime( 6382): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1945): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{16830e40 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{16830e40 #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  340): DFP En is all cleared set to be enabled
I/ActivityManager( 1037): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6402 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6382): Shutting down VM
V/ActivityManager( 1037): Display changed displayId=0
D/DSDPConnection( 1856): Display #0 changed.
D/SplitWindowPolicy( 1945): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1945): topRunningActivity=ActivityInfo{309a4446 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1945): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1945): topRunningActivity=ActivityInfo{6a09607 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6402): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
,I/WebViewFactory( 6402): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6402): Loading: webviewchromium
I/LibraryLoader( 6402): Time to load native libraries: 4 ms (timestamps 5289-5293)
,I/LibraryLoader( 6402): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6402): Binding Chromium to main looper Looper (main, tid 1) {4a00011}
I/LibraryLoader( 6402): Expected native library version number "",actual native library version number ""
I/chromium( 6402): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6402): Initializing chromium process, renderers=0
W/art     ( 6402): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6402): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,V/AudioPolicyService(  315): registerClient() client 0xb558a920, uid 10311
,W/chromium( 6402): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6402): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6402): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@306fb8ca:true
I/Adreno-EGL( 6402): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6402): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6402): Build Date: 12/12/14 금
I/Adreno-EGL( 6402): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6402): Remote Branch: 
I/Adreno-EGL( 6402): Local Patches: 
I/Adreno-EGL( 6402): Reconstruct Branch: 
,W/chromium( 6402): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6402): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6402): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6402): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6402): CordovaWebView is running on device made by: LGE
,W/art     ( 6402): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6402): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1037): Activity pause timeout for ActivityRecord{9a4c179 u0 com.test.thalitest/.MainActivity t4}
,D/OpenGLRenderer( 6402): Render dirty regions requested: true
I/OpenGLRenderer( 6402): Initialized EGL, version 1.4
D/OpenGLRenderer( 6402): Enabling debug mode 0
D/Atlas   ( 6402): Validating map...
,D/SplitWindow( 1037): check instance of lgWin Window{3931b134 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/PhoneStatusBar( 1459): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2eef847f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1459): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1459):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1459): , Keyguard show=false, IME shown=false, Panel expanded=false
I/Timeline( 6402): Timeline: Activity_idle id: android.os.BinderProxy@28700f81 time:255668
,D/LgDataFeature( 6402): LgDataFeature() Constructor: none
D/LgDataFeature( 6402): LgDataFeature() Constructor Done, null
I/ActivityManager( 1037): Displayed com.test.thalitest/.MainActivity: +631ms (total +725ms)
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{9a4c179 u0 com.test.thalitest/.MainActivity t4} time:255694
,D/JsMessageQueue( 6402): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6402): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6402): 
,D/jxcore_app_log( 6402): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435086592
,D/JX-Cordova( 6402): jxcore cordova android initializing
E/GBMv2   (  340): DFP En is all cleared set to be enabled
E/GBMv2   (  340): Set value is all cleared set the max
I/GBMv2   (  340): DFP Enabled. Ignore VFP set
W/jxcore-log( 6402): Initializing JXcore engine
W/jxcore-log( 6402): JXcore engine is ready
W/jxcore-log( 6402): Starting JXcore engine
W/.test.thalitest( 6402): type=1400 audit(0.0:158): avc: denied { ioctl } for path="socket:[10279]" dev="sockfs" ino=10279 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6402): type=1400 audit(0.0:159): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6402): type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[7552]" dev="sockfs" ino=7552 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6402): type=1400 audit(0.0:161): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6402): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[31357]" dev="sockfs" ino=31357 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 6402): Platform android
W/jxcore-log( 6402): 
W/jxcore-log( 6402): Process ARCH arm
W/jxcore-log( 6402): 
D/sensors_hal_Time( 1037): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1037): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1037): tsOffsetIs: Apps: 257649508759; DSPS: 8583387; Offset : -4310922061
,I/jxcore-log( 6402): JXcore Cordova bridge is ready!
I/jxcore-log( 6402): 
W/jxcore-log( 6402): JXcore engine is started
,I/jxcore-log( 6402): Toggling radios to true
I/jxcore-log( 6402): 
,D/BluetoothAdapter( 6402): enable(): BT is already enabled..!
D/WifiService( 1037): New client listening to asynchronous messages
D/WifiServiceImplEx( 1037): setWifiEnabled: true pid=6402, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService( 1037): setWifiEnabled: true pid=6402, uid=10311
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1037): disconnect pid=6402, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1037):  DisconnectedState CMD_DISCONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_DISCONNECT 0 0
E/WifiConfigStore( 1037): setLastSelectedConfiguration -1
E/WifiNative: ( 1037): [258,462,142 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: DISCONNECT
D/WifiServiceImplEx( 1037): reconnect pid=6402, uid=10311, packageName=com.test.thalitest
I/jxcore-log( 6402): Radios toggled
I/jxcore-log( 6402): 
I/jxcore-log( 6402): My device name is: LGE-LG-D855
I/jxcore-log( 6402): 
I/wpa_supplicant( 2664): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1037): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037): DISCONNECT: returned true
E/WifiStateMachine( 1037):  DisconnectedState CMD_RECONNECT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_RECONNECT 0 0
E/WifiNative: ( 1037): [258,502,445 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1037): doBoolean: RECONNECT
I/wpa_supplicant( 2664): wlan0: CTRL-EVENT-SCAN-STARTED 
D/Tethering( 1037): InitialState.processMessage what=4
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1037): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1037): RECONNECT: returned true
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=258505
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=258506  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6475 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=258551  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=258552  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=258553  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
,D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateSCANNING
,W/ResourcesManager( 6475): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6475): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 6475): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6475): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6475): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6475): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/UsbSettingsReceiver( 6475): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6475): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6475): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6475): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 6475): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6475): [AUTORUN] getUsbConnected() : connected=true
,D/UsbSettingsReceiver( 6475): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6475): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6475): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6475): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6475): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6027): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6505 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6055:com.google.android.partnersetup/u0a8 (adj 15): empty #17
I/art     (  344): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 267us total 13.203ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 230us total 12.032ms
,I/art     (  344): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 223us total 10.566ms
,W/libprocessgroup( 1037): failed to open /acct/uid_10008/pid_6055/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 6475): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LgDataFeature( 6475): LgDataFeature() Constructor: none
D/LgDataFeature( 6475): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 6475): MCCMNC not supported: null
I/ActivityManager( 1037): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6530 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager( 1037): Killing 5579:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10011/pid_5579/cgroup.procs: No such file or directory
,W/ResourcesManager( 6530): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/QRemote ( 6530): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 6530): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6530): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6530): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6530): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 6530): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6530): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6530): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6530): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6530): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6530): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6027): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/QRemote ( 6530): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 6530): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,I/PCSuite ( 6505): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6505): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6505): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6475): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6475): MCCMNC not supported: null
D/QRemote ( 6530): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6530): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6530): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,D/PostponalbeReceiver( 6027): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6475): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6475): MCCMNC not supported: null
D/QRemote ( 6530): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6530): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6530): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6530): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6530): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6530): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6530): LgDataFeature() Constructor: none
D/LgDataFeature( 6530): LgDataFeature() Constructor Done, null
,V/SoundPool( 6530): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6530): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6530): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6530): doLoad: loading sample sampleID=1
I/QRemote ( 6530): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6530): Start decode
V/MediaPlayer[Native]( 6530): decode(31, 10857164, 17813)
V/MediaPlayerService(  315): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  315): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  315): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  315): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  315): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  315): player type = 3
V/AwesomePlayer(  315): AwesomePlayer create()
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): setAudioSink() 
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb1432bc0, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/Utils   (  315): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  315): setDataSource_l dataSource
V/LGParserOSAL(  315): SniffLGParser start
V/LGParserOSAL(  315): MainType:5, SubType=0
V/LGParserOSAL(  315): #### check Mime : application/ogg
V/LGParserOSAL(  315): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  315): Use LGExtractor :application/ogg 
D/UEI.SmartControl( 6077): QS Service created
D/QRemote ( 6530): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,E/QRemote ( 6530): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6530): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGMDMManager( 6530): Create singleton instance
I/UEI.SmartControl( 6077): Service initServices...
D/UEI.SmartControl( 6077): QS start get config
,V/LGParserOSAL(  315): supported mime: application/ogg
V/AwesomePlayer(  315): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  315): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  315): mBitrate = -1 bits/sec
V/AwesomePlayer(  315): AudioTrack Setting
V/AwesomePlayer(  315): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  315): setAudioSource() 
V/MediaPlayerService(  315): prepare
V/AwesomePlayer(  315): prepareAsync_l() 
V/MediaPlayerService(  315): wait for prepare
V/AwesomePlayer(  315): onPrepareAsyncEvent() 
,V/AwesomePlayer(  315): initAudioDecoder() 
W/Utils   (  315): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  315): isOffloadSupported()
V/AudioPolicyManager(  315): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  315): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  315): isAudioPlaybackHookOn() false
V/AwesomePlayer(  315): getUseOffload() = 0 
V/OMXCodec(  315): OMXCodec::Create
V/OMXCodec(  315): findMatchingCodecs()
V/OMXCodec(  315): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  315): matchingCodecs.size()=1
V/OMXCodec(  315): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  315): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  315): LG Codec Adapter start
V/OMXCodec(  315): OMXCodec Createtor
V/OMXCodec(  315): setComponentRole
V/OMXCodec(  315): configureCodec protected=0
V/LGCodecAdapter(  315): called getLGCodecSpecificData
V/LGCodecOSAL(  315): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  315): Called LGconfigureCodecMETA
V/LGCodecOSAL(  315): Called LGconfigureCodecMSG
V/LGCodecOSAL(  315): Not support LGCodec
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  315): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  315): Could not offload audio decode, try pcm offload
W/Utils   (  315): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  315): isOffloadSupported()
V/AudioPolicyManager(  315): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  315): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  315): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  315): init()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  315): allocateBuffers
V/OMXCodec(  315): allocateBuffersOnPort portIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc100 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc790 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc7e0 on input port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc830 on input port
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca10 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcd80 on output port
V/OMXCodec(  315): init() mAsyncCompletion wait!!! 
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  315): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  315):, finishAsyncPrepare_l() 
V/AudioCache(  315): notify(0xb1432bc0, 5, 0, 0)
V/AudioCache(  315): ignored
V/AudioCache(  315): notify(0xb1432bc0, 1, 0, 0)
V/AudioCache(  315): prepared
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): start
V/AwesomePlayer(  315): play_l() 
V/AwesomePlayer(  315): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  315): createAudioPlayer_l
V/AwesomePlayer(  315): seekAudioIfNecessary_l() 
V/AwesomePlayer(  315): startAudioPlayer_l() 
D/AudioPlayer(  315): start of Playback, useOffload 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  315): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  315): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  315): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974795904
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796144
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974796304
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797184
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  315): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  315): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  315): allocateBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca10 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc880 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcec0 on output port
V/OMXCodec(  315): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  315): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  315): notify(0xb1432bc0, 6, 0, 0)
V/AudioCache(  315): ignored
V/MediaPlayerService(  315): wait for playback complete
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab700000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab701000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab702000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab703000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab704000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab705000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab706000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab707000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab708000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab709000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab70a000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab70b000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab70c000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab70d000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab70e000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab70f000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab710000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab711000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab712000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab713000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab714000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab715000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab716000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab717000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab718000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab719000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab71a000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab71b000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab71c000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab71d000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab71e000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab71f000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab720000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab721000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab722000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab723000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab724000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab725000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab726000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab727000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab728000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab729000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab72a000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab72b000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab72c000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab72d000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab72e000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab72f000, 0xb57d8000, 4096)
,V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab730000, 0xb57d8000, 4096)
V/AudioCache(  315): write(0xb57d8000, 4096)
V/AudioCache(  315): memcpy(0xab731000, 0xb57d8000, 4096)
V/OMXCodec(  315): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  315): postAudioEOS() 
V/AudioCache(  315): write(0xb57d8000, 280)
V/AudioCache(  315): memcpy(0xab732000, 0xb57d8000, 280)
V/AwesomePlayer(  315): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  315): onStreamDone
V/AwesomePlayer(  315): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  315): notify(0xb1432bc0, 2, 0, 0)
V/AudioCache(  315): playback complete
V/AwesomePlayer(  315): pause_l() 
V/AudioCache(  315): notify(0xb1432bc0, 7, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
V/AudioCache(  315): wait - success
V/MediaPlayerService(  315): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  315): Pause Playback at 1068125
V/AwesomePlayer(  315): reset_l() 
V/AudioCache(  315): notify(0xb1432bc0, 8, 0, 0)
V/AudioCache(  315): ignored
V/AwesomePlayer(  315): cancelPlayerEvents
D/AudioPlayer(  315): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc830 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc7e0 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc790 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc100 on port 0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcec0 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc880 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeing buffer 0xb14fca10 on port 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  315): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  315): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  315): AudioPlayer releasing audio source
D/AudioPlayer(  315): AudioPlayer done releasing audio source
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
V/AwesomePlayer(  315): ~AwesomePlayer call
V/AwesomePlayer(  315): reset_l() 
V/AwesomePlayer(  315): cancelPlayerEvents
,V/SoundPool( 6530): close(31)
,V/SoundPool( 6530): pointer = 0x9fe3c000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6530): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6530): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 6530): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2981
I/UEI.SmartControl( 6077): Supports setup maps: true
,D/UEI.SmartControl( 6077): QS start statue = true Error code = 0
I/UEI.SmartControl( 6077): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6077): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6077): ### init IR Blaster...
D/serial_port( 6077): Configuring serial port
E/UEI.SmartControl( 6077): UEIBLaster setting for 616
I/UEI.SmartControl( 6077): Setting serial record hearder size = 2
I/UEI.SmartControl( 6077): configuring settings for MAXQ616
I/UEI.SmartControl( 6077): Get version...
D/UEI.SmartControl( 6077): serial port data available: 21
,D/UEI.SmartControl( 6077): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6077): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6077): QS saving settings...
D/UEI.SmartControl( 6077): IR Blaster version: 25672567
,D/UEI.SmartControl( 6077): serial port data available: 4
,I/UEI.SmartControl( 6077): Device manager: loading config....
W/ContextImpl( 6077): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,D/UEI.SmartControl( 6077): ----------- loading internal config...
E/UEI.SmartControl( 6077): Services init done
D/UEI.SmartControl( 6077): QS Service init finished
D/UEI.SmartControl( 6077): QS Service version name: 2.1.91
D/UEI.SmartControl( 6077): QS Service version code: 201091
D/UEI.SmartControl( 6077): Service requested: Control
E/UEI.SmartControl( 6077): Loading SETTINGS...
D/UEI.SmartControl( 6077): Request IControl service: devices are loaded...
,I/QRemote ( 6530): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 6077): Internal service binding...
I/UEI.SmartControl( 6077): ------ IControl API: 11
D/UEI.SmartControl( 6077): File observer start...
E/UEI.SmartControl( 6077): IR Port is disabled: false
D/UEI.SmartControl( 6077): Starting file observer...
I/UEI.SmartControl( 6077): Registering callback...
,I/UEI.SmartControl( 6077): ------ IControl API: 19
I/UEI.SmartControl( 6077): Registering Services Ready callback...
D/UEI.SmartControl( 6077): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6077): Notify AllClients services are ready: 0
,I/QRemote ( 6530): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/UEI.SmartControl( 6077): -----service ready thread exits
D/QRemote ( 6530): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6530): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6530): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6530): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6077): ------ IControl API: 8
D/QRemote ( 6530): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6530): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6530): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6530): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6530): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6530): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6530): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6530): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6530): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6530): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6530): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6530): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6530): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6530): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6530): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1453045032061]
D/QRemote ( 6530): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1037): Killing 5601:com.android.contacts/u0a19 (adj 15): empty #17
,D/QRemote ( 6530): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1037): failed to open /acct/uid_10019/pid_5601/cgroup.procs: No such file or directory
,V/QRemote ( 6530): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6530): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6530): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6530): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6530): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6530): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6530): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6530): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2664): Trying to associate with SSID 'NG700'
,E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1037): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: WPS-AP-AVAILABLE 
W/WifiMonitor( 1037): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1037):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3283 bcn=0
E/WifiStateMachine( 1037):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3283 bcn=0
E/WifiStateMachine( 1037):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3283 bcn=0
E/WifiStateMachine( 1037):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=3 known=0 got=3 dur:3283 bcn=0
D/WifiNative-wlan0( 1037): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=260638  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=260659  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATING
D/PostponalbeReceiver( 6027): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6475): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6475): MCCMNC not supported: null
,D/QRemote ( 6530): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6530): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6530): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6027): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6475): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6475): MCCMNC not supported: null
I/wpa_supplicant( 2664): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1037): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=24 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
,E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=260723  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=260723  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=260724
E/WifiStateMachine( 1037):  ConnectModeState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=260724
E/WifiStateMachine( 1037):  DriverStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=260724
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=260725
E/WifiStateMachine( 1037):  DefaultState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=260725
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=260726  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/Tethering( 1037): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=260727  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=0
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/wpa_supplicant( 2664): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2664): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=260741  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=260742  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateGROUP_HANDSHAKE
D/WifiMonitor( 1037): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=27 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1037): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1037): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1037):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=260748
E/WifiStateMachine( 1037):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=260748
D/WifiNative-wlan0( 1037): doString: [STATUS]
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiNative-wlan0( 1037):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
I/WifiServiceExtension( 1037): setVHTCapabilityType  : false
D/QRemote ( 6530): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6530): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6530): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/UsbSettingsReceiver( 6475): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6475): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6475): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 6475): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6475): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,D/UsbSettingsControl( 6475): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6475): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6475): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6475): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6475): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6475): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 6475): [AUTORUN] setTetherStatus() : status=false
I/WifiServerServiceExt( 1037): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1037): setKeepAlivePacketInterval msec : 60
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/PostponalbeReceiver( 6027): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1037): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
V/WiFiOffLoadBroadcast( 6475): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
,D/ConnectivityService( 1037): Got NetworkAgent Messenger
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1037): NetworkAgent connected
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/WiFiOffLoadBroadcast( 6475): MCCMNC not supported: null
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/QRemote ( 6530): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6530): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6530): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/PostponalbeReceiver( 6027): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/CommandListener(  311): Setting iface cfg
V/WiFiOffLoadBroadcast( 6475): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/DhcpStateMachine( 1037): StoppedState
E/WifiStateMachine( 1037): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1037): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=260809  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=260810  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=260810  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=260811  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
D/WiFiOffLoadBroadcast( 6475): MCCMNC not supported: null
E/WifiStateMachine( 1037):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=260811  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=260812  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 0
D/QRemote ( 6530): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6530): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6530): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/PostponalbeReceiver( 6027): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6475): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6475): MCCMNC not supported: null
,D/QRemote ( 6530): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6530): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6530): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6027): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6475): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6475): MCCMNC not supported: null
I/wpa_supplicant( 2664): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 0
D/WifiNative-wlan0( 1037): SET ps 0: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2664): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1037): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@38703f8a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@38703f8a target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1037): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/QRemote ( 6530): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/DhcpStateMachine( 1037): DHCP Start wake lock is acquired.
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/QRemote ( 6530): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateCOMPLETED
I/QRemote ( 6530): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/jxcore-log( 6402): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6402): 
,D/DhcpStateMachine( 1037): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper( 1037): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper( 1037): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,W/dhcpcd  ( 6599): type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6599): type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6599): version 5.5.6 starting
,E/dhcpcd  ( 6599): get_duid: m
D/dhcpcd  ( 6599): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6599): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6599): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
,D/dhcpcd  ( 6599): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6599): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/dhcpcd  ( 6599): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6599): wlan0: sending REQUEST (xid 0xf383c270), next in 4.40 seconds
I/jxcore-log( 6402): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6402): 
,I/jxcore-log( 6402): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6402): 
,I/jxcore-log( 6402): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6402): 
,I/jxcore-log( 6402): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6402): 
,I/jxcore-log( 6402): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6402): 
,I/jxcore-log( 6402): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6402): 
,I/jxcore-log( 6402): Test app app.js loaded
I/jxcore-log( 6402): 
,I/chromium( 6402): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 6402): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6402): 
,I/chromium( 6402): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dhcpcd  ( 6599): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6599): wlan0: leased 192.168.1.141 for 86400 seconds
,D/dhcpcd  ( 6599): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6599): wlan0: adding route to 192.168.1.0/24
,D/dhcpcd  ( 6599): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6599): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6599): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6599): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6599): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/PowerManagerServiceEx( 1037): acquireWakeLockInternal: lock=576756015, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{29e349fb type 2 when 257760 android} when 257760
D/[Concierge]Service( 2599): onStartCommand(). Type : 9
,D/PowerManagerServiceEx( 1037): releaseWakeLockInternal: lock=576756015 [*alarm*], flags=0x0
,E/WifiStateMachine( 1037):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1037):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1037):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1037):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4
D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,D/DhcpStateMachine( 1037): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper( 1037): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1037): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1037): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1037): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1037): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1037): bShouldSendDhcpAction Result: true
D/DhcpStateMachine( 1037): DHCP Start/Renew wake lock is released.
E/WifiStateMachine( 1037):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
E/WifiStateMachine( 1037):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
D/DhcpStateMachine( 1037): RunningState
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2664): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2664): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1037): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
,D/ConnectivityService( 1037): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1037):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1037): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1037): ignoring duplicate network state non-change
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService( 1037): Adding iface wlan0 to network 100
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1037): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
D/PostponalbeReceiver( 6027): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/WfdStateTracker( 1945): handleWifiStateChangedEvent: 1
,W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1037): [PASSPOINT] passpointNotification: hs20AP list is checked
I/StatusBar.NetworkController( 1459): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/StatusBar.NetworkController( 1459): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1459): mWifiConnected = true, mWifiLevel = 0
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6475): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/ConnectivityService( 1037): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1037): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService( 1037): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1037): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1037): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1037): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1037): Setting Dns servers for network 100 to [/192.168.1.1]
D/WiFiOffLoadBroadcast( 6475): MCCMNC not supported: null
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1037): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService( 1037): currentScore = 0, newScore = 20
D/ConnectivityService( 1037):    accepting network in place of null
D/ConnectivityService( 1037): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1856): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1856):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/QRemote ( 6530): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6530): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/ConnectivityService( 1037): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1037): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java( 1037): Sending msg: 4 arg1:1 arg2:1
D/CSLegacyTypeTracker( 1037): [e] list.add(nai) empty : false size: 1
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/libc-netbsd(  311): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/ConnectivityService( 1037): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.141/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/libc-netbsd(  311): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1037): Sending msg: 5 arg1:0 arg2:1
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/ConnectivityService( 1037): validation of new default Network = false
I/QRemote ( 6530): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/libc-netbsd(  311): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  311): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
,D/ConnectivityService( 1037): Default network via Wi-Fi connected. start DSQN
D/DSQN    ( 1037): enableDataServiceNotify 
D/DSQN    ( 1037): start dsqn bin
D/PostponalbeReceiver( 6027): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524290
W/dsqn    ( 6659): type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6659): type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
V/WiFiOffLoadBroadcast( 6475): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/NetworkPolicy( 1037): [LG_RESTRICTED] checkMobilePolicy_type()
,D/WiFiOffLoadBroadcast( 6475): MCCMNC not supported: null
E/DSQN    ( 6659): DSQN ssw
D/QRemote ( 6530): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6530): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 6530): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/LGDataListener(  311): argv[0]=dsqncommand
D/LGDataListener(  311): argv[1]=wlan0
D/LGDataListener(  311): argv[2]=1
D/LGDataListener(  311): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1037): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1037): start to monitor internet connection
D/PostponalbeReceiver( 6027): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/PCSuite ( 6505): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/libc-netbsd(  311): res_queryN name = clients3.google.com, class = 1, type = 1
,D/PCSuite ( 6505): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6475): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6475): MCCMNC not supported: null
,D/QRemote ( 6530): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6530): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6530): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,I/QRemote ( 6530): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
D/libc-netbsd(  311): res_queryN name = europe.pool.ntp.org succeed
I/QRemote ( 6530): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/PostponalbeReceiver( 6027): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/PCSuite ( 6505): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6505): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  311): res_queryN name = clients3.google.com succeed
V/WiFiOffLoadBroadcast( 6475): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6475): MCCMNC not supported: null
D/QRemote ( 6530): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6530): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6530): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6530): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6530): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/LocSvc_java( 1037): NTP server : europe.pool.ntp.org
,D/LocSvc_java( 1037): NTP server returned: 1453045034967 (Sun Jan 17 16:37:14 GMT+01:00 2016) reference: 262924 certainty: 24 system time offset: 72
D/LocSvc_java( 1037): Sending msg: 10 arg1:0 arg2:1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 15:37:14 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453045034897], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453045034878]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Don't send network conditions - lacking user consent.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Validated
D/ConnectivityService( 1037): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1037):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1037): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1037): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1459): CM callback handler got msg 524290
D/ConnectivityService( 1037): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1856): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1856):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/TelephonyIcons( 1459): null signal icon name: drawable/stat_sys_signal_null
,D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1459): refreshViews: Data not connected!! Set no data type icon / Roaming
I/jxcore-log( 6402): --= Surplus to requirements =--
I/jxcore-log( 6402): 
I/jxcore-log( 6402): ****TEST TOOK:  ms ****
I/jxcore-log( 6402): 
I/jxcore-log( 6402): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6402): 
,I/rmt_storage(  305): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  305): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  305): wakelock acquired: 1, error no: 42
I/rmt_storage(  305): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/rmt_storage(  305): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  305): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  305): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  305): 
,I/rmt_storage(  305): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  906): [IMS_FATAL]| 3347 | 917 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/AndroidRuntime( 6674): 
D/AndroidRuntime( 6674): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6674): CheckJNI is OFF
,D/AndroidRuntime( 6674): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1037): Killing 6402:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
,W/PackageSettings( 1037): Skipping PackageSetting{366f264f com.example.hello/10319} due to missing metadata
,I/WindowState( 1037): WIN DEATH: Window{3931b134 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1037): Client connection lost with reason: 4
D/InputDispatcher( 1037): Window went away: Window{3931b134 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{9a4c179 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  340): DFP En is all cleared set to be enabled
,W/ActivityManager( 1037): Spurious death for ProcessRecord{257ccfc4 6402:com.test.thalitest/u0a311}, curProc for 6402: null
I/ActivityManager( 1037): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{9a4c179 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{9a4c179 u0 com.test.thalitest/.MainActivity t4 f}
,D/SplitWindowPolicy( 1945): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1945): topRunningActivity=ActivityInfo{10803334 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2072): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2072): [Launcher.java:903:onResume()]onResume
,D/SplitWindowPolicy( 1945): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1945): topRunningActivity=ActivityInfo{2467d55d co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2072): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2072): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/ActionManagerService( 1907): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2072): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 2721): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2072): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1459): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/art     ( 4340): Explicit concurrent mark sweep GC freed 23553(1324KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 532us total 73.252ms
E/LGBluetoothAvrcpQcomAdapter( 3736): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3736): [BTUI] [+] updateMediaPlayerInfo
,D/LIA_Service_RemotePackageHandler( 2017): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2721): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
W/GeofencerStateMachine( 1820): Ignoring removeGeofence because network location is disabled.
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
W/System.err( 4263): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4263): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4263): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4263): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4263): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4263): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4263): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4263): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4263): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4263): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4263): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4263): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/[LGHome]EVENT( 2072): [Launcher.java:1056:onResume()]onResume end
,D/PostponalbeReceiver( 6027): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/[LGHome]EVENT( 2072): [Launcher.java:1114:onPause()]onPause
,I/ActivityManager( 1037): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6705 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/ActionManagerService( 1907): notifyUserLog: 1000004
I/[SystemUI]QSlideListController( 1459): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]GBoardWebView( 2072): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 2721): handleMessage: what(1000) actionID(0x1000004)
D/KeyguardModel( 1459): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1459): createShortcutInfo...
V/BoardContentProvider( 2721): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/KeyguardModel( 1459): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1459): createShortcutInfo...
I/GBoardWebViewUtils( 2072): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2072): , create_time: 1430558575574
I/GBoardWebViewUtils( 2072): , expire_time: 0
I/GBoardWebViewUtils( 2072): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2072): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2072): , display: false
I/GBoardWebViewUtils( 2072): , animation: false }
I/GBoardWebViewUtils( 2072): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2072): , create_time: 1430558575600
I/GBoardWebViewUtils( 2072): , expire_time: 0
I/GBoardWebViewUtils( 2072): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2072): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2072): , display: false
I/GBoardWebViewUtils( 2072): , animation: false }
I/GBoardWebViewUtils( 2072): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452774038448
I/GBoardWebViewUtils( 2072): , create_time: 1452774039338
I/GBoardWebViewUtils( 2072): , expire_time: 0
I/GBoardWebViewUtils( 2072): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2072): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2072): , display: false
I/GBoardWebViewUtils( 2072): , animation: false }
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,D/WallpaperManager( 2072): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1459): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1459): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1459): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1459): createShortcutInfo...
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2eef847f,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/art     ( 1037): Explicit concurrent mark sweep GC freed 57845(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 44MB/66MB, paused 3.470ms total 211.644ms
I/art     ( 1037): WaitForGcToComplete blocked for 73.599ms for cause Explicit
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/SplitUIManager( 1873): split_name #11 / not available #0
D/KeyguardModel( 1459): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/SplitUIService( 1873): removed split : 
D/KeyguardModel( 1459): createShortcutInfo...
W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1459): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1459): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1459): createShortcutInfo...
,I/[LGHome]GBoardWebView( 2072): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,D/KeyguardModel( 1459): handleShortcutListChanged...
D/KeyguardModel( 1459): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1459): createShortcutInfo...
D/KeyguardModel( 1459): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1459): createShortcutInfo...
D/SplitUIManager( 1873): split_name #11 / not available #0
I/SplitUIService( 1873): split app #11
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1459): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1459): createShortcutInfo...
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1459): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1459): createShortcutInfo...
W/ResourceType( 1459): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1459): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1459): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1459): createShortcutInfo...
I/AppUp4:AppBoxCP( 6705): onCreate
D/KeyguardModel( 1459): handleShortcutListChanged...
W/AppUp4:DB( 6705):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6705):  setFingerPrint start
I/AppUp4:DB( 6705):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
I/AppUp4:DB( 6705):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6705):  SDK version = 21
I/AppUp4:DB( 6705):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6705): AppBoxApplication onCreate()
W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3736): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3736): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3736): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3736): [BTUI]          displayName: Music
,D/LGBluetoothAvrcpQcomAdapter( 3736): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3736): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3736): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3736): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3736): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3736): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3736): [BTUI] [-] updateMediaPlayerInfo
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/[LGHome]EVENT( 2072): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/administrator( 1037): Handling package changes for user 0
I/[LGHome]EVENT( 2072): [Launcher.java:5349:onStop()]onStop
,D/AppUp4:PreloadHelper( 6705): added Exclude : com.test.thalitest
I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6727 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 6105:com.lge.email/u0a23 (adj 15): empty #17
I/ThermalEngine(  326): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3146): Thermal-Lib-Client: Client request sent
,I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
,I/[LGHome]Launcher.Model( 2072): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/[LGHome]Launcher.Model( 2072): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2072): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2072): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 8610(497KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 3.611ms total 221.152ms
,I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2072): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[Concierge]WidgetView( 2072): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,W/libprocessgroup( 1037): failed to open /acct/uid_10023/pid_6105/cgroup.procs: No such file or directory
D/PhoneStatusBar( 1459): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1459): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1459):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1459): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
,D/[Concierge]WidgetView( 2072): change position of spinner
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{3f499946 u0 com.lge.launcher2/.Launcher t3} time:264230
D/[Concierge]Service( 2599): onStartCommand(). Type : 8
D/[Concierge]Service( 2599): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2599): Update widget ID : 11
I/[Concierge]WidgetView( 2072): initWebView(). Time : 1453045036190
D/[Concierge]Service( 2599): onStartCommand(). Type : 0
W/ResourcesManager( 6727): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6727): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6727): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6727): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6727): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[Concierge]WebView( 2072): Return exist ConciergeWebView. Reuse : 142153489
D/[Concierge]WidgetView( 2072): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2072): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/[LgeWidgetLib]ExtViewHost( 2072): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@32eef36c
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2072): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2072): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2072): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2072): Widget kill message received. Destory myself. My : 1453044800076, New one : 1453045036190
D/[Concierge]WidgetView( 2072): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2072): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/AndroidRuntime( 6674): Shutting down VM
,I/SystemConfig( 6727): BUILD Country: EU
I/SystemConfig( 6727): BUILD Operator: OPEN
W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2072): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2072): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 2072): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]EVENT( 2072): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 2072): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/ActivityManager( 1037): Killing 5631:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/Timeline( 2072): Timeline: Activity_idle id: android.os.BinderProxy@28535ae6 time:264340
W/libprocessgroup( 1037): failed to open /acct/uid_10027/pid_5631/cgroup.procs: No such file or directory
,I/SystemConfig( 6727): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6727): existFile = false
I/SystemConfig( 6727): canReadFile = false
I/SystemConfig( 6727): systemFeature RCS result false
D/SystemConfig( 6727): refreshRcsSupport() :false
D/VoicemailCleanupService( 2248): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1037): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6750 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/chromium( 2072): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
W/ResourcesManager( 6750): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6750): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6750): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6750): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/GBoardtInterface( 2072): onReloaded()
,I/GBoardWebViewClient( 2072): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 2721): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BoardContentProvider( 2721): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/ActionManagerService( 1907): notifyUserLog: 1000001
,D/LIA_Informant_ActionManagerMessageHandler( 2721): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2721): onEvent() : ACTION_BOARD_ENABLED
,D/ActionManagerService( 1907): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 2721): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 2721): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 2721): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 2721): onSettingEvent() : GBoard On - add scheduler - 0
I/LGEmail ( 6750): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
V/BoardContentProvider( 2721): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/GBoardUriUtils( 2072): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2072): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
D/GBoardUriUtils( 2072): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2072): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/GBoardUriUtils( 2072): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2072): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1452774038448&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
D/LGEmail ( 6750): user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,W/ResourceType( 6750): No package identifier when getting value for resource number 0x00000000
,D/LgDataFeature( 6750): LgDataFeature() Constructor: none
D/LgDataFeature( 6750): LgDataFeature() Constructor Done, null
,I/PackageChangeReceiver( 6750): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager( 1037): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6773 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a

```
