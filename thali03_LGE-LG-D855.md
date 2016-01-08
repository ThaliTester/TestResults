#### Test 549702610b97681_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 258144644221; DSPS: 8599653; Offset : -4310129199
,D/AndroidRuntime( 6430): 
D/AndroidRuntime( 6430): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6430): CheckJNI is OFF
D/AndroidRuntime( 6430): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager( 1047): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1983): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1047): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1047): setTaskToReturnTo : TaskRecord{158b97eb #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1047): setTaskToReturnTo : TaskRecord{158b97eb #4 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1047): AppWindowTokenEx init.. 
E/GBMv2   (  333): DFP En is all cleared set to be enabled
I/ActivityManager( 1047): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6449 uid=10311 gids={50311, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6430): Shutting down VM
V/ActivityManager( 1047): Display changed displayId=0
D/DSDPConnection( 1887): Display #0 changed.
D/SplitWindowPolicy( 1983): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1983): topRunningActivity=ActivityInfo{37d08db6 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1983): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1983): topRunningActivity=ActivityInfo{1fbdfab7 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 6449): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 6449): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6449): Loading: webviewchromium
I/LibraryLoader( 6449): Time to load native libraries: 3 ms (timestamps 5370-5373)
I/LibraryLoader( 6449): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6449): Binding Chromium to main looper Looper (main, tid 1) {13f01541}
,I/LibraryLoader( 6449): Expected native library version number "",actual native library version number ""
I/chromium( 6449): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6449): Initializing chromium process, renderers=0
W/art     ( 6449): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6449): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6449): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6449): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6449): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  312): registerClient() client 0xb1004c60, uid 10311
D/BluetoothManagerService( 1047): Message: 20
D/BluetoothManagerService( 1047): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@267abd1d:true
,I/Adreno-EGL( 6449): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6449): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6449): Build Date: 12/12/14 금
I/Adreno-EGL( 6449): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6449): Remote Branch: 
I/Adreno-EGL( 6449): Local Patches: 
I/Adreno-EGL( 6449): Reconstruct Branch: 
,W/chromium( 6449): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6449): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6449): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6449): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6449): CordovaWebView is running on device made by: LGE
,W/art     ( 6449): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6449): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6449): Render dirty regions requested: true
I/OpenGLRenderer( 6449): Initialized EGL, version 1.4
D/OpenGLRenderer( 6449): Enabling debug mode 0
D/Atlas   ( 6449): Validating map...
D/SplitWindow( 1047): check instance of lgWin Window{12fc7faf u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/LgDataFeature( 6449): LgDataFeature() Constructor: none
D/LgDataFeature( 6449): LgDataFeature() Constructor Done, null
I/SystemUI[Framework]( 1047): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1047): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1047): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1047): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ca6d806,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1490): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1490): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1490):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1490): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager( 1047): Displayed com.test.thalitest/.MainActivity: +587ms (total +668ms)
I/Timeline( 1047): Timeline: Activity_windows_visible id: ActivityRecord{1f7b7948 u0 com.test.thalitest/.MainActivity t4} time:275813
I/Timeline( 6449): Timeline: Activity_idle id: android.os.BinderProxy@2047d0b1 time:275818
I/chromium( 6449): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6449): 
D/JsMessageQueue( 6449): Set native->JS mode to OnlineEventsBridgeMode
I/chromium( 6449): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6449): 
D/jxcore_app_log( 6449): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1434856064
D/JX-Cordova( 6449): jxcore cordova android initializing
E/GBMv2   (  333): DFP En is all cleared set to be enabled
E/GBMv2   (  333): Set value is all cleared set the max
I/GBMv2   (  333): DFP Enabled. Ignore VFP set
,W/jxcore-log( 6449): Initializing JXcore engine
,W/jxcore-log( 6449): JXcore engine is ready
W/jxcore-log( 6449): Starting JXcore engine
W/.test.thalitest( 6449): type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7458]" dev="sockfs" ino=7458 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 6449): type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 6449): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8418]" dev="sockfs" ino=8418 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 6449): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/.test.thalitest( 6449): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[29580]" dev="sockfs" ino=29580 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 6449): Background sticky concurrent mark sweep GC freed 124661(12MB) AllocSpace objects, 23(7MB) LOS objects, 28% free, 39MB/55MB, paused 1.615ms total 117.605ms
,W/jxcore-log( 6449): Platform android
W/jxcore-log( 6449): 
W/jxcore-log( 6449): Process ARCH arm
W/jxcore-log( 6449): 
D/sensors_hal_Time( 1047): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1047): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1047): tsOffsetIs: Apps: 278145953386; DSPS: 9255056; Offset : -4310132003
,I/jxcore-log( 6449): JXcore Cordova bridge is ready!
I/jxcore-log( 6449): 
W/jxcore-log( 6449): JXcore engine is started
,I/jxcore-log( 6449): Toggling radios to true
I/jxcore-log( 6449): 
,D/BluetoothAdapter( 6449): enable(): BT is already enabled..!
D/WifiService( 1047): New client listening to asynchronous messages
D/WifiServiceImplEx( 1047): setWifiEnabled: true pid=6449, uid=10311, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService( 1047): setWifiEnabled: true pid=6449, uid=10311
,E/WifiService( 1047): Invoking mWifiStateMachine.setWifiEnabled
D/WifiServiceImplEx( 1047): disconnect pid=6449, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1047):  DisconnectedState CMD_DISCONNECT 0 0
D/WifiServiceImplEx( 1047): reconnect pid=6449, uid=10311, packageName=com.test.thalitest
E/WifiStateMachine( 1047):  ConnectModeState CMD_DISCONNECT 0 0
I/jxcore-log( 6449): Radios toggled
I/jxcore-log( 6449): 
E/WifiConfigStore( 1047): setLastSelectedConfiguration -1
I/jxcore-log( 6449): My device name is: LGE-LG-D855
I/jxcore-log( 6449): 
E/WifiNative: ( 1047): [278,296,288 us] DISCONNECT  stack:logDbg - disconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1047): doBoolean: DISCONNECT
I/wpa_supplicant( 2652): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/Tethering( 1047): InitialState.processMessage what=4
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1047): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1047): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering( 1047): sendTetherStateChangedBroadcast 0, 0, 0
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
D/WifiNative-wlan0( 1047): DISCONNECT: returned true
E/WifiStateMachine( 1047):  DisconnectedState CMD_RECONNECT 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_RECONNECT 0 0
D/DSQN    ( 1047): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/WifiNative: ( 1047): [278,367,331 us] RECONNECT  stack:logDbg - reconnect - processMessage - processMsg - handleMessage
D/WifiNative-wlan0( 1047): doBoolean: RECONNECT
I/wpa_supplicant( 2652): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1047): handleEvent 14  CTRL-EVENT-SCAN-STARTED 
E/WifiMonitor( 1047): handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
D/WifiNative-wlan0( 1047): RECONNECT: returned true
E/WifiStateMachine( 1047):  DisconnectedState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=278374
E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=278374  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,I/ActivityManager( 1047): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=6531 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1490): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1490): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
I/art     (  337): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 193us total 15.945ms
,D/WifiHS20( 1047): hidePasspointNotification off =false
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1490): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1490): mWifiConnected = false, mWifiLevel = 0
I/art     (  337): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 183us total 8.644ms
D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
,E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 17 0 rt=278427  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 8.557ms
E/WifiStateMachine( 1047):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=278429  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/StatusBar.NetworkController( 1490): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1490): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 18 0 rt=278433  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateSCANNING
,W/ResourcesManager( 6531): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6531): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6531): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6531): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6531): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6531): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/UsbSettingsReceiver( 6531): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6531): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6531): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6531): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6531): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 6531): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6531): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 6531): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6531): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6531): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 6531): [AUTORUN] setTetherStatus() : status=false
D/PostponalbeReceiver( 6047): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/ActivityManager( 1047): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6561 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1047): Killing 6076:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1047): failed to open /acct/uid_10008/pid_6076/cgroup.procs: No such file or directory
V/WiFiOffLoadBroadcast( 6531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LgDataFeature( 6531): LgDataFeature() Constructor: none
D/LgDataFeature( 6531): LgDataFeature() Constructor Done, null
D/WiFiOffLoadBroadcast( 6531): MCCMNC not supported: null
I/ActivityManager( 1047): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6585 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager( 1047): Killing 5599:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1047): failed to open /acct/uid_10011/pid_5599/cgroup.procs: No such file or directory
W/ResourcesManager( 6585): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/QRemote ( 6585): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 6585): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6585): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6585): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6585): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6585): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6585): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6585): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6585): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6585): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6585): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6047): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6561): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/QRemote ( 6585): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/PCSuite ( 6561): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6561): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/QRemote ( 6585): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
D/WiFiOffLoadBroadcast( 6531): MCCMNC not supported: null
D/QRemote ( 6585): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6585): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6585): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6047): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6531): MCCMNC not supported: null
D/QRemote ( 6585): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6585): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6585): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
V/QRemote ( 6585): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6585): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6585): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
D/LgDataFeature( 6585): LgDataFeature() Constructor: none
D/LgDataFeature( 6585): LgDataFeature() Constructor Done, null
V/SoundPool( 6585): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6585): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 6585): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 6585): doLoad: loading sample sampleID=1
V/SoundPool( 6585): Start decode
V/MediaPlayer[Native]( 6585): decode(31, 10857164, 17813)
V/MediaPlayerService(  312): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  312): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  312): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  312): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  312): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  312): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  312): player type = 3
V/AwesomePlayer(  312): AwesomePlayer create()
V/AwesomePlayer(  312): reset_l() 
V/AwesomePlayer(  312): cancelPlayerEvents
V/AwesomePlayer(  312): setAudioSink() 
V/AwesomePlayer(  312): reset_l() 
V/AudioCache(  312): notify(0xb14323c0, 8, 0, 0)
V/AudioCache(  312): ignored
V/AwesomePlayer(  312): cancelPlayerEvents
D/Utils   (  312): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  312): setDataSource_l dataSource
V/LGParserOSAL(  312): SniffLGParser start
V/LGParserOSAL(  312): MainType:5, SubType=0
V/LGParserOSAL(  312): #### check Mime : application/ogg
V/LGParserOSAL(  312): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  312): Use LGExtractor :application/ogg 
I/QRemote ( 6585): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
D/UEI.SmartControl( 6123): QS Service created
D/QRemote ( 6585): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6585): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6585): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/LGParserOSAL(  312): supported mime: application/ogg
V/AwesomePlayer(  312): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  312): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  312): mBitrate = -1 bits/sec
V/AwesomePlayer(  312): AudioTrack Setting
V/AwesomePlayer(  312): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  312): setAudioSource() 
V/MediaPlayerService(  312): prepare
V/AwesomePlayer(  312): prepareAsync_l() 
V/MediaPlayerService(  312): wait for prepare
V/AwesomePlayer(  312): onPrepareAsyncEvent() 
V/AwesomePlayer(  312): initAudioDecoder() 
W/Utils   (  312): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  312): isOffloadSupported()
V/AudioPolicyManager(  312): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  312): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  312): isAudioPlaybackHookOn() false
V/AwesomePlayer(  312): getUseOffload() = 0 
V/OMXCodec(  312): OMXCodec::Create
V/OMXCodec(  312): findMatchingCodecs()
V/OMXCodec(  312): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  312): matchingCodecs.size()=1
V/OMXCodec(  312): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  312): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  312): LG Codec Adapter start
V/OMXCodec(  312): OMXCodec Createtor
V/OMXCodec(  312): setComponentRole
V/OMXCodec(  312): configureCodec protected=0
V/LGCodecAdapter(  312): called getLGCodecSpecificData
V/LGCodecOSAL(  312): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  312): Called LGconfigureCodecMETA
V/LGCodecOSAL(  312): Called LGconfigureCodecMSG
V/LGCodecOSAL(  312): Not support LGCodec
V/OMXCodec(  312): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  312): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  312): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  312): Could not offload audio decode, try pcm offload
W/Utils   (  312): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  312): isOffloadSupported()
V/AudioPolicyManager(  312): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  312): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  312): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  312): init()
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  312): allocateBuffers
V/OMXCodec(  312): allocateBuffersOnPort portIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on input port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14343d0 on input port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb1434420 on input port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb1434470 on input port
V/OMXCodec(  312): allocateBuffersOnPort portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb1434830 on output port
V/OMXCodec(  312): init() mAsyncCompletion wait!!! 
V/LGMDMManager( 6585): Create singleton instance
V/OMXCodec(  312): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  312): init() mAsyncCompletion wait!!! 
V/OMXCodec(  312): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  312): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  312): finishAsyncPrepare_l() 
V/AudioCache(  312): notify(0xb14323c0, 5, 0, 0)
V/AudioCache(  312): ignored
V/AudioCache(  312): notify(0xb14323c0, 1, 0, 0)
V/AudioCache(  312): prepared
V/AudioCache(  312): wait - success
V/MediaPlayerService(  312): start
V/AwesomePlayer(  312): play_l() 
V/AwesomePlayer(  312): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  312): createAudioPlayer_l
V/AwesomePlayer(  312): seekAudioIfNecessary_l() 
V/AwesomePlayer(  312): startAudioPlayer_l() 
D/AudioPlayer(  312): start of Playback, useOffload 0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  312): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  312): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  312): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975744
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973975984
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976384
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976624
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  312): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  312): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  312): allocateBuffersOnPort portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] allocated buffer 0xb15350b0 on output port
V/OMXCodec(  312): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  312): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  312): notify(0xb14323c0, 6, 0, 0)
V/AudioCache(  312): ignored
V/MediaPlayerService(  312): wait for playback complete
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab500000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab501000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab502000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab503000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab504000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab505000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab506000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab507000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab508000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab509000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab50a000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab50b000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab50c000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab50d000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab50e000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab50f000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab510000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab511000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab512000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab513000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab514000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab515000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab516000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab517000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab518000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab519000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab51a000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab51b000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab51c000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab51d000, 0xb124d000, 4096)
I/UEI.SmartControl( 6123): Service initServices...
D/UEI.SmartControl( 6123): QS start get config
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab51e000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab51f000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab520000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab521000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab522000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab523000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab524000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab525000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab526000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab527000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab528000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab529000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab52a000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab52b000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab52c000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab52d000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab52e000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab52f000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab530000, 0xb124d000, 4096)
V/AudioCache(  312): write(0xb124d000, 4096)
V/AudioCache(  312): memcpy(0xab531000, 0xb124d000, 4096)
V/OMXCodec(  312): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  312): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  312): postAudioEOS() 
V/AudioCache(  312): write(0xb124d000, 280)
V/AudioCache(  312): memcpy(0xab532000, 0xb124d000, 280)
V/AwesomePlayer(  312): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  312): onStreamDone
V/AwesomePlayer(  312): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  312): notify(0xb14323c0, 2, 0, 0)
V/AudioCache(  312): playback complete
V/AwesomePlayer(  312): pause_l() 
V/AudioCache(  312): notify(0xb14323c0, 7, 0, 0)
V/AudioCache(  312): ignored
V/AwesomePlayer(  312): cancelPlayerEvents
V/AudioCache(  312): wait - success
V/MediaPlayerService(  312): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  312): Pause Playback at 1068125
V/AwesomePlayer(  312): reset_l() 
V/AudioCache(  312): notify(0xb14323c0, 8, 0, 0)
V/AudioCache(  312): ignored
V/AwesomePlayer(  312): cancelPlayerEvents
D/AudioPlayer(  312): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  312): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  312): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  312): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb1434470 on port 0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb1434420 on port 0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb14343d0 on port 0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb14342e0 on port 0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb15350b0 on port 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeing buffer 0xb1434740 on port 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  312): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  312): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  312): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  312): AudioPlayer releasing audio source
D/AudioPlayer(  312): AudioPlayer done releasing audio source
V/AwesomePlayer(  312): reset_l() 
V/AwesomePlayer(  312): cancelPlayerEvents
V/AwesomePlayer(  312): ~AwesomePlayer call
V/AwesomePlayer(  312): reset_l() 
V/AwesomePlayer(  312): cancelPlayerEvents
V/SoundPool( 6585): close(31)
V/SoundPool( 6585): pointer = 0x9fe7a000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6585): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,D/QRemote ( 6585): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,D/QRemote ( 6585): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7718
I/UEI.SmartControl( 6123): Supports setup maps: true
,D/UEI.SmartControl( 6123): QS start statue = true Error code = 0
I/UEI.SmartControl( 6123): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6123): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6123): ### init IR Blaster...
D/serial_port( 6123): Configuring serial port
E/UEI.SmartControl( 6123): UEIBLaster setting for 616
I/UEI.SmartControl( 6123): Setting serial record hearder size = 2
I/UEI.SmartControl( 6123): configuring settings for MAXQ616
I/UEI.SmartControl( 6123): Get version...
D/UEI.SmartControl( 6123): serial port data available: 21
,D/UEI.SmartControl( 6123): MAXQ616 A2-X4 software.
,I/UEI.SmartControl( 6123): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 6123): QS saving settings...
D/UEI.SmartControl( 6123): IR Blaster version: 25672567
D/UEI.SmartControl( 6123): serial port data available: 4
,I/UEI.SmartControl( 6123): Device manager: loading config....
D/UEI.SmartControl( 6123): ----------- loading internal config...
,W/ContextImpl( 6123): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,E/UEI.SmartControl( 6123): Services init done
D/UEI.SmartControl( 6123): QS Service init finished
D/UEI.SmartControl( 6123): QS Service version name: 2.1.91
D/UEI.SmartControl( 6123): QS Service version code: 201091
D/UEI.SmartControl( 6123): Service requested: Control
E/UEI.SmartControl( 6123): Loading SETTINGS...
D/UEI.SmartControl( 6123): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6123): Internal service binding...
I/QRemote ( 6585): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6123): ------ IControl API: 11
D/UEI.SmartControl( 6123): File observer start...
E/UEI.SmartControl( 6123): IR Port is disabled: false
D/UEI.SmartControl( 6123): Starting file observer...
I/UEI.SmartControl( 6123): Registering callback...
I/UEI.SmartControl( 6123): ------ IControl API: 19
I/UEI.SmartControl( 6123): Registering Services Ready callback...
,D/UEI.SmartControl( 6123): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6123): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6123): -----service ready thread exits
I/QRemote ( 6585): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6585): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6585): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6585): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6585): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,I/UEI.SmartControl( 6123): ------ IControl API: 8
D/QRemote ( 6585): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6585): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6585): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6585): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6585): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6585): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 6585): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
V/QRemote ( 6585): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6585): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6585): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6585): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6585): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6585): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6585): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6585): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452294508155]
D/QRemote ( 6585): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1047): Killing 5620:com.android.contacts/u0a19 (adj 15): empty #17
,D/QRemote ( 6585): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,W/libprocessgroup( 1047): failed to open /acct/uid_10019/pid_5620/cgroup.procs: No such file or directory
,V/QRemote ( 6585): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6585): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6585): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6585): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,D/QRemote ( 6585): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
,D/QRemote ( 6585): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6585): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6585): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,I/wpa_supplicant( 2652): Trying to associate with SSID 'NG700'
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
E/WifiMonitor( 1047): handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
D/WifiMonitor( 1047): Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=21 dispatchEvent: WPS-AP-AVAILABLE 
,W/WifiMonitor( 1047): couldn't identify event type - WPS-AP-AVAILABLE 
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine( 1047):  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 dur:3241 bcn=0
E/WifiStateMachine( 1047):  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 dur:3241 bcn=0
E/WifiStateMachine( 1047):  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 dur:3241 bcn=0
E/WifiStateMachine( 1047):  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=5 known=0 got=5 dur:3241 bcn=0
D/WifiNative-wlan0( 1047): doString: [BSS RANGE=0- MASK=0x21987]
,E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=280486  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PostponalbeReceiver( 6047): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [SCANNING]
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=280494  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
I/StatusBar.NetworkController( 1490): networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1490): mWifiConnected = false, mWifiLevel = 0
,W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1047): setSupplicantStateASSOCIATING
D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1490): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1490): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6531): MCCMNC not supported: null
D/QRemote ( 6585): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6585): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6585): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 6047): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,V/WiFiOffLoadBroadcast( 6531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6531): MCCMNC not supported: null
D/QRemote ( 6585): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6585): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6585): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,I/wpa_supplicant( 2652): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/WifiMonitor( 1047): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=24 dispatchEvent: Associated with c0:ff:d4:d3:aa:48
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=280576  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=280577  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
E/WifiStateMachine( 1047):  DisconnectedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=280577
D/Tethering( 1047): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=280578
E/WifiStateMachine( 1047):  DriverStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=280579
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=280579
E/WifiStateMachine( 1047):  DefaultState CMD_ASSOCIATED_BSSID 24 0 BSSID=c0:ff:d4:d3:aa:48 Target=any roam=0 rt=280580
I/wpa_supplicant( 2652): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 2652): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/WifiMonitor( 1047): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=27 dispatchEvent: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
W/WifiMonitor( 1047): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
E/WifiMonitor( 1047): handleEvent 1  Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/UsbSettingsReceiver( 6531): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 6531): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6531): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 6531): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 6531): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=280582  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
D/UsbSettingsControl( 6531): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 6531): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 6531): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 6531): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 6531): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 6531): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
I/StatusBar.NetworkController( 1490): networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1490): mWifiConnected = false, mWifiLevel = 0
D/DSQN    ( 1047): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/UsbSettingsControl( 6531): [AUTORUN] setTetherStatus() : status=false
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=280589  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: FOUR_WAY_HANDSHAKE
I/StatusBar.NetworkController( 1490): networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1490): mWifiConnected = false, mWifiLevel = 0
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1047):  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
D/PostponalbeReceiver( 6047): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1047):  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1047):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=280593  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=280594  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: GROUP_HANDSHAKE
E/WifiStateMachine( 1047):  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=280594
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateASSOCIATED
E/WifiStateMachine( 1047):  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=280594
D/WifiNative-wlan0( 1047): doString: [STATUS]
D/WifiNative-wlan0( 1047):    returned bssid=c0:ff:d4:d3:aa:48 ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7b:60:ac address=c4:9a:02:7b:60:ac uuid=530d3fd0-1ba3-5409-a336-ff4e42af59a2
D/WifiMonitor( 1047): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1047): WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/WifiServiceExtension( 1047): setVHTCapabilityType  : false
V/WiFiOffLoadBroadcast( 6531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/WifiServerServiceExt( 1047): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt( 1047): setKeepAlivePacketInterval msec : 60
D/WiFiOffLoadBroadcast( 6531): MCCMNC not supported: null
I/StatusBar.NetworkController( 1490): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1490): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/StatusBar.NetworkController( 1490): networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1490): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1047): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1047): Got NetworkAgent Messenger
D/ConnectivityService( 1047): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService( 1047): NetworkAgent connected
D/QRemote ( 6585): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
E/WifiConfigStore( 1047): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1047): doBoolean: SET_NETWORK 0 bssid any
D/QRemote ( 6585): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiNative-wlan0( 1047): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1047): doBoolean: SAVE_CONFIG
I/QRemote ( 6585): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6047): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/WifiNative-wlan0( 1047): SAVE_CONFIG: returned true
E/WifiConfigStore( 1047): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1047): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1047): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1047): doBoolean: SAVE_CONFIG
V/WiFiOffLoadBroadcast( 6531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6531): MCCMNC not supported: null
D/WifiNative-wlan0( 1047): SAVE_CONFIG: returned true
D/QRemote ( 6585): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/CommandListener(  308): Setting iface cfg
D/QRemote ( 6585): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6585): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6047): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
E/WifiStateMachine( 1047): Start Dhcp Watchdog 1
D/DhcpStateMachine( 1047): StoppedState
D/DhcpStateMachine( 1047): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1047): WaitBeforeStartState
E/WifiStateMachine( 1047):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=280634  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=280634  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=280635  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
,D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt( 1047): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateGROUP_HANDSHAKE
E/WifiStateMachine( 1047):  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=280639  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=280639  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=280639  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: COMPLETED
E/WifiStateMachine( 1047):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1047): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1047):  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
E/WifiStateMachine( 1047):  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=0,0,0
D/WifiNative-wlan0( 1047): doBoolean: DRIVER SETSUSPENDMODE 0
V/WiFiOffLoadBroadcast( 6531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6531): MCCMNC not supported: null
D/QRemote ( 6585): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6585): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6585): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6047): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
V/WiFiOffLoadBroadcast( 6531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6531): MCCMNC not supported: null
D/QRemote ( 6585): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6585): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6585): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/wpa_supplicant( 2652): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,D/WifiNative-wlan0( 1047): DRIVER SETSUSPENDMODE 0: returned true
D/WifiNative-wlan0( 1047): doBoolean: SET ps 0
D/WifiNative-wlan0( 1047): SET ps 0: returned true
D/WifiNative-wlan0( 1047): doBoolean: DRIVER BTCOEXMODE 1
I/wpa_supplicant( 2652): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
D/WifiNative-wlan0( 1047): DRIVER BTCOEXMODE 1: returned true
E/WifiStateMachine( 1047): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine( 1047): Current State is mWaitBeforeStartState.
D/LGWifiP2pService( 1047): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@35414edd target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1047): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@35414edd target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper( 1047): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine( 1047): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine( 1047): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper( 1047): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateCOMPLETED
D/WifiServerServiceExt( 1047): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1047): setSupplicantStateCOMPLETED
,D/DhcpStateMachine( 1047): DHCPV4 request on wlan0,
,V/LgDhcpStateMachineHelper( 1047): [bssid] hash key :c0:ff:d4:d3:aa:48,
D/LgDhcpStateMachineHelper( 1047): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
W/dhcpcd  ( 6645): type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dhcpcd  ( 6645): type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,I/dhcpcd  ( 6645): version 5.5.6 starting
,E/dhcpcd  ( 6645): get_duid: m
D/dhcpcd  ( 6645): wlan0: using ClientID 01:c4:9a:02:7b:60:ac
D/dhcpcd  ( 6645): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
D/dhcpcd  ( 6645): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6645): [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6645): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/dhcpcd  ( 6645): wlan0: rebinding lease of 192.168.1.141
D/dhcpcd  ( 6645): wlan0: sending REQUEST (xid 0xeda6a89d), next in 4.45 seconds
E/WifiStateMachine( 1047):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1047): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,I/dhcpcd  ( 6645): wlan0: acknowledged 192.168.1.141 from 192.168.1.1
,I/dhcpcd  ( 6645): wlan0: leased 192.168.1.141 for 86400 seconds
,D/dhcpcd  ( 6645): wlan0: adding IP address 192.168.1.141/24
D/dhcpcd  ( 6645): wlan0: adding route to 192.168.1.0/24
D/dhcpcd  ( 6645): wlan0: adding default route via 192.168.1.1
D/dhcpcd  ( 6645): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/dhcpcd  ( 6645): getUsingAPMacAddress: c0:ff:d4:d3:aa:48 , return 1
D/dhcpcd  ( 6645): write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-c0:ff:d4:d3:aa:48.lease2
D/dhcpcd  ( 6645): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine( 1047):  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1047):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,E/WifiStateMachine( 1047):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1047): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
D/DhcpStateMachine( 1047): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper( 1047): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper( 1047): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper( 1047): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.141
V/LgDhcpStateMachineHelper( 1047): Add DhcpResults: IP address 192.168.1.141/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine( 1047): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper( 1047): bShouldSendDhcpAction Result: true
E/WifiStateMachine( 1047):  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,E/WifiStateMachine( 1047):  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4,
D/WifiNative-wlan0( 1047): doBoolean: DRIVER BTCOEXMODE 2
,I/wpa_supplicant( 2652): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,D/WifiNative-wlan0( 1047): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1047): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 2652): wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
D/WifiNative-wlan0( 1047): DRIVER SETSUSPENDMODE 1: returned true
D/WifiNative-wlan0( 1047): doBoolean: SET ps 1
D/DhcpStateMachine( 1047): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine( 1047): RunningState
D/LGWifiP2pService( 1047): InactiveState{ when=-7ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1047): P2pEnabledState{ when=-8ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1047): SET ps 1: returned true
,D/ConnectivityService( 1047): Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
E/WifiStateMachine( 1047):  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1047):  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
E/WifiStateMachine( 1047): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService( 1047): ignoring duplicate network state non-change
,W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService( 1047): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService( 1047): Adding iface wlan0 to network 100
E/WifiStateMachine( 1047): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20( 1047): [PASSPOINT] passpointNotification: hs20AP list is checked
E/ConnectivityService( 1047): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1047): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService( 1047): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService( 1047): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService( 1047): addLocalRoutetoDefaultNetwork
D/ConnectivityService( 1047): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
D/ConnectivityService( 1047): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat( 1047): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService( 1047): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1047): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1047): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1047):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1047):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1047):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Connected
D/ConnectivityService( 1047): currentScore = 0, newScore = 20
D/ConnectivityService( 1047):    accepting network in place of null
D/ConnectivityService( 1047): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
V/WfdStateTracker( 1983): handleWifiStateChangedEvent: 1
D/TelephonyNetworkFactory-1( 1887): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Checking http://clients3.google.com/generate_204 on "NG700"
D/TelephonyNetworkFactory-1( 1887):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20( 1047): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings( 1047): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1047): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1047): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,D/WIFI    ( 1047): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1047):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/StatusBar.NetworkController( 1490): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1490): mWifiConnected = false, mWifiLevel = 0
E/ConnectivityService( 1047): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1047): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/LocSvc_java( 1047): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java( 1047): getAGpsConnectionInfo connType - 4
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
D/libc-netbsd(  308): res_queryN name = 2.android.pool.ntp.org., class = 1, type = 1
D/LocSvc_java( 1047): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1047): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1047): Sending msg: 5 arg1:0 arg2:1
D/DSQN    ( 1047): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 28
D/ConnectivityService( 1047): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker( 1047): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( 1047): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1047): validation of new default Network = false
D/ConnectivityService( 1047): Default network via Wi-Fi connected. start DSQN
,I/StatusBar.NetworkController( 1490): networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1490): mWifiConnected = false, mWifiLevel = 0
D/DSQN    ( 1047): enableDataServiceNotify 
D/DSQN    ( 1047): start dsqn bin
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = europe.pool.ntp.org, class = 1, type = 1
D/PostponalbeReceiver( 6047): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1490): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/WiFiOffLoadBroadcast( 6531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/StatusBar.NetworkController( 1490): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WiFiOffLoadBroadcast( 6531): MCCMNC not supported: null
V/NetworkPolicy( 1047): [LG_RESTRICTED] checkMobilePolicy_type()
D/QRemote ( 6585): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6585): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6585): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/PostponalbeReceiver( 6047): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,I/StatusBar.NetworkController( 1490): networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1490): mWifiConnected = true, mWifiLevel = 0
D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
V/WiFiOffLoadBroadcast( 6531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 1
,D/WiFiOffLoadBroadcast( 6531): MCCMNC not supported: null
D/QRemote ( 6585): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6585): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 6585): [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/TelephonyIcons( 1490): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
D/PostponalbeReceiver( 6047): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6561): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6561): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6531): MCCMNC not supported: null
D/QRemote ( 6585): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6585): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6585): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6585): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6585): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
D/libc-netbsd(  308): res_queryN name = clients3.google.com succeed
,D/PostponalbeReceiver( 6047): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
I/PCSuite ( 6561): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6561): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/libc-netbsd(  308): res_queryN name = europe.pool.ntp.org succeed
,V/WiFiOffLoadBroadcast( 6531): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6531): MCCMNC not supported: null
D/QRemote ( 6585): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
D/QRemote ( 6585): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 6585): [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
I/QRemote ( 6585): [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 6585): [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 23:08:30 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452294511047], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452294511027]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Don't send network conditions - lacking user consent.
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1047): Validated
D/ConnectivityService( 1047): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1490): CM callback handler got msg 524290
D/ConnectivityService( 1047): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1047): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1047):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1047):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService( 1047): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService( 1047): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1047): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1047): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1047):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/dsqn    ( 6695): type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
W/dsqn    ( 6695): type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6843 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
D/ConnectivityManager.CallbackHandler( 1490): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1887): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory-1( 1887):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,E/DSQN    ( 6695): DSQN ssw
,D/TelephonyIcons( 1490): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1490): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LocSvc_java( 1047): NTP server : europe.pool.ntp.org
D/LocSvc_java( 1047): NTP server returned: 1452294510476 (Sat Jan 09 00:08:30 GMT+01:00 2016) reference: 282777 certainty: 31 system time offset: -606
D/LocSvc_java( 1047): Sending msg: 10 arg1:0 arg2:1
I/rmt_storage(  306): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  306): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  306): wakelock acquired: 1, error no: 42
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  306): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  306): 
I/rmt_storage(  306): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/Diag_Lib(  921): [IMS_FATAL]| 3347 | 928 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,W/ProcessCpuTracker( 1047): Skipping unknown process pid 6523
W/ProcessCpuTracker( 1047): Skipping unknown process pid 6524
W/ProcessCpuTracker( 1047): Skipping unknown process pid 6526
W/ProcessCpuTracker( 1047): Skipping unknown process pid 6527
W/ProcessCpuTracker( 1047): Skipping unknown process pid 6705
,D/PowerManagerServiceEx( 1047): acquireWakeLockInternal: lock=224150897, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1047
,V/QRemote ( 6585): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6585): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7718
D/[Concierge]Service( 2660): onStartCommand(). Type : 9
D/PowerManagerServiceEx( 1047): releaseWakeLockInternal: lock=224150897 [*alarm*], flags=0x0
,D/UEI.SmartControl( 6123): Internal timer expired: 4
D/UEI.SmartControl( 6123): unbind internal service
,D/serial_port( 6123): close(fd = 24)
,I/UEI.SmartControl( 6123): Serial port is closed.
V/WifiInternetCheck( 1047): Single check msg out of sync, ignoring.
,D/ConnectivityService( 1047): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering( 1047): MasterInitialState.processMessage what=3
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
,D/PostponalbeReceiver( 6047): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,W/ContextImpl( 6047): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
D/GpsLocationProvider( 1047): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5350): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager( 1047): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6743 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/libc-netbsd(  308): res_queryN name = 2.android.pool.ntp.org succeed
I/ActivityManager( 1047): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6763 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 2151): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AppUp4:AppBoxCP( 6743): onCreate
W/AppUp4:DB( 6743):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6743):  setFingerPrint start
I/AppUp4:DB( 6743):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 6743):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6743):  SDK version = 21
I/AppUp4:DB( 6743):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6743): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6743): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6743): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6743): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6743): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6743): onReceive
D/AlarmManagerService( 1047): Setting time of day to sec=1452294513
,W/AlarmManagerService( 1047): Unable to set rtc to 1452294513: Invalid argument
,D/LgDataFeature( 6743): LgDataFeature() Constructor: none
D/LgDataFeature( 6743): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 6743): Context : android.app.ReceiverRestrictedContext@233fe827
D/AppUp4:CustFacade( 6743): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6743): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6743): begin check event
I/AppUp4:CustModeStarterReceiver( 6743): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6743): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6743): call method handleAsyncCustNotification.
,I/[SystemUI]Clock( 1490): onReceive = android.intent.action.TIME_SET
I/LgeClockWidgetControlView( 1490): time changed, timezoneChanged : false
D/LIA_Informant_Tips_DateChangeManager( 2754): onReceive() : ACTION_TIME_CHANGED
I/LIA_Informant_Tips_LogTracer( 2754): [Log Tracer - Schedule Transition] Time Change Event Received : 2016-01-09 00:08:33...... Request
I/SecureClockService( 1983): Intent.ACTION_TIME_CHANGED 
I/LIA_Informant_Tips_LogTracer( 2754): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 3, total count : 139, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2754): DateInfo : SmartTips Total Working Day Count = 139
D/LIA_Informant_Tips_DateChangeManager( 2754): DateInfo : UserGuide Working Duration Count = 3
D/LIA_Informant_Tips_DateChangeManager( 2754): DateInfo : Last Date Check Time = 2016-01-09 00:08:33
W/ActivityManager( 1047): getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
I/[LGHome]LGDateChangeReceiver( 2102): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=9 currentDate=-1 dayofweek=7 currentDayOfWeek=-1
D/KeyguardUpdateMonitor( 1490): handleTimeUpdate
I/[LGHome]LGCalendarIcon( 2102): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Sat date= 9
D/AppUp4:CustModeStarterReceiver( 6743): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6743): handleAsyncCustNotification do not startCustService
,D/LGDMClient( 4142): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4142): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/[LGHome]LGCalendarIcon( 2102): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Sat date= 9
I/[LGHome]Launcher( 2102): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ContextImpl( 4142): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 4142): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
D/LGDMClient( 4142): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=3, isUserType=1
I/LGDMClient( 4142): [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/[Concierge]Service( 2660): onStartCommand(). Type : 9
,V/DownloadManager( 3340): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/ReaderUtils( 6763): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
V/DownloadManager( 3340): DownloadService onCreate
I/DownloadManager( 3340): in removeSpuriousFiles
,V/DownloadManager( 3340): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
W/ContextImpl( 4142): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
D/LGDMClient( 4142): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4142): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
V/DownloadManager( 3340): DownloadService onStartCommand
V/DownloadManager( 3340): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3340): created cursor android.database.sqlite.SQLiteCursor@95da59 on behalf of 3340
V/DownloadManager( 3340): processing inserted download 1
V/DownloadManager( 3340): processing inserted download 4
V/DownloadManager( 3340): processing inserted download 7
,E/LGDMClient( 4142): [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
V/DownloadManager( 3340): processing inserted download 8
D/LGDMClient( 4142): [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
V/DownloadManager( 3340): processing inserted download 9
D/LGDMClient( 4142): [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/DownloadManager( 3340): processing inserted download 10
V/DownloadManager( 3340): processing inserted download 16
V/DownloadManager( 3340): processing inserted download 17
V/DownloadManager( 3340): processing inserted download 18
D/eas_req ( 6107): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
V/DownloadManager( 3340): processing inserted download 21
I/ThermalEngine(  324): Thermal-Server: Thermal received msg from  override
I/Thermal-Lib( 3156): Thermal-Lib-Client: Client request sent
V/DownloadManager( 3340): created cursor android.database.sqlite.SQLiteCursor@222b461e on behalf of 3340
I/DownloadManager( 3340): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
I/DownloadManager( 3340): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_4.50.37_COM_COM_20150608234245157.apk
I/DownloadManager( 3340): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
I/DownloadManager( 3340): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
I/DownloadManager( 3340): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.10_COM_COM_20150521235426173_RELG-D855.apk
I/DownloadManager( 3340): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
I/DownloadManager( 3340): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
I/DownloadManager( 3340): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
I/DownloadManager( 3340): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
I/DownloadManager( 3340): in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
I/DownloadManager( 3340): in trimDatabase
V/DownloadManager( 3340): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3340): created cursor android.database.sqlite.SQLiteCursor@14fe2eff on behalf of 3340
I/ActivityManager( 1047): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6793 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/DownloadManager( 3340): DownloadService onDestroy
I/ActivityManager( 1047): Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6811 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,I/VacuumService( 2151): Vacuum at: now=1452294513755 tag=VacuumService
I/GoogleURLConnFactory( 2151): Using platform SSLCertificateSocketFactory
I/HubEmail( 6107): JNI_OnLoad()
I/HubEmail( 6107): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6107): registerNatives()
I/HubEmail( 6107): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6107): registerNativeMethods()
I/HubEmail( 6107): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6107): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/GAV2    ( 6763): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/jxcore-log( 6449): Test app app.js loaded
I/jxcore-log( 6449): 
W/Settings( 6107): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/GpsLocationProvider( 1047): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/Settings( 6107): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Uploader( 2151): No account for auth token provided
I/chromium( 6449): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/BooksApp( 6763): Created application version: 3.2.35 (30235)
I/chromium( 6449): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
W/DriveInitializer( 2376): Background init thread started
,E/GpsLocationProvider( 1047): No APN found to select.
,I/LgeMiscReceiver( 3292): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3292): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3292): networkInfo.isConnected() = true
D/PhoneState( 3292): setPdpRejectCasuse : false
,I/art     ( 2151): Explicit concurrent mark sweep GC freed 22566(1279KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 30MB/62MB, paused 1.355ms total 31.554ms
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2376): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = play.googleapis.com, class = 1, type = 1
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = static-avc.lglime.com, class = 1, type = 1
,W/DriveInitializer( 2376): Background init thread ended
,I/art     ( 1047): Explicit concurrent mark sweep GC freed 65398(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 1.329ms total 133.295ms
,I/ActivityManager( 1047): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6863 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1047): Killing 5985:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1047): failed to open /acct/uid_10004/pid_5985/cgroup.procs: No such file or directory
,I/BooksSync( 6763): Starting books sync
D/DelayedSyncController( 6793): Delaying sync.
,D/libc-netbsd(  308): res_queryN name = play.googleapis.com succeed
D/libc-netbsd(  308): res_queryN name = static-avc.lglime.com succeed
D/LGDataListener(  308): argv[0]=dsqncommand
D/LGDataListener(  308): argv[1]=wlan0
D/LGDataListener(  308): argv[2]=1
D/LGDataListener(  308): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    ( 1047): DSQM DsqnNotification wlan0  1
D/DSQN    ( 1047): start to monitor internet connection
,I/ActivityManager( 1047): Killing 5672:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
D/DrmBroadcastReceiver( 6863): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 6863): 1  network is available. Sync DRM Time with NTP
W/libprocessgroup( 1047): failed to open /acct/uid_10080/pid_5672/cgroup.procs: No such file or directory
,V/DrmService( 6863): Service onCreate
,D/DrmService( 6863): Received new request = 2
I/DrmSntpClient( 6863): Start Sync process
D/DrmSntpClient( 6863): Server : 0
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = pool.ntp.org, class = 1, type = 1
I/ActivityManager( 1047): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6890 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  308): res_queryN name = pool.ntp.org succeed
,V/GLSActivity( 2151): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2151): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2151): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2151): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2151): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2151): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 6890): Almond Protected OAT
D/BooksSync( 6763): started syncMyEbooks
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ZenLog  ( 1047): intercepted: 0|com.google.android.gms|1|null|10005,none
V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,W/ResourcesManager( 1490): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1490): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GLSActivity( 2151): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2151): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2151): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2151): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2151): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2151): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2151): 	at android.os.Binder.execTransact(Binder.java:446)
W/ResourcesManager( 1433): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/ContactsSyncAdapter( 2151): innerSync failed
D/ContactsSyncAdapter( 2151): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2151): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2151): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2151): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2151): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2151): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2151): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2151): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2151): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2151): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2151): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2151): 	at android.os.Binder.execTransact(Binder.java:446)
D/WeatherApplication( 6890): removeAccount
D/WeatherApplication( 6890): Account.length = 0
E/WeatherApplication( 6890): OPERATOR:OPEN
W/ResourcesManager( 1433): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/WeatherAncestor( 6890): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:8:34
D/LgeQuickCoverNLService( 1433): onNotificationPosted
D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do add job
D/LgeQuickCoverNotificationData( 1433): add : 2
D/LgeQuickCoverNotificationData( 1433): do add job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
D/Weather.Utils( 6890): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6890): 2 : All the weather widget is gone.
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/UpdateThreadPoolManager( 6890): 2 : This is isUpdating : false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/WeatherAncestor( 6890): connectivity changed - connection : true
E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
D/SyncManager( 1047): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 87075, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
D/WeatherService( 6890): 2 : isServiceAlived():false forecastCache:null
D/ForecastDataCache( 6890): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6890): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6890): 2 : Cache is not up-to-date, count: 0
,V/GLSActivity( 2151): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Weather_cast( 6890): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 6890): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 0:8:34
I/GLSUser ( 2151): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2151): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2151): [GLSUser] Extracting token using key: Auth
D/QuickStatusbarLayout( 1433): Notification difference=198
W/GLSActivity( 2151): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{3a06d5ef V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/ActivityManager( 1047): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6919 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1047): Killing 6175:com.google.android.apps.docs/u0a61 (adj 15): empty #17
W/libprocessgroup( 1047): failed to open /acct/uid_10061/pid_6175/cgroup.procs: No such file or directory
,V/GLSActivity( 2151): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LGDrmClient( 6863): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  317): eDRM_SetDRMTime +++
I/LGDRM   (  317): [DRM] SET TIME : YR=2016, MON=1, DAY=8
I/LGDRM   (  317): [DRM] SET TIME : HR=23, MIN=8, SEC=34
V/ILGDrmService(  317): eDRM_SetDRMTime ---
I/DrmSntpClient( 6863): Synched
D/DrmService( 6863): Completed !! request = 2
D/DrmService( 6863): Request count = 0
V/DrmService( 6863): Service onDestroy
,I/ActivityManager( 1047): Killing 5698:com.google.android.apps.plus/u0a97 (adj 15): empty #17
W/libprocessgroup( 1047): failed to open /acct/uid_10097/pid_5698/cgroup.procs: No such file or directory
,I/jxcore-log( 6449): --= Surplus to requirements =--
I/jxcore-log( 6449): 
I/jxcore-log( 6449): ****TEST TOOK:  ms ****
I/jxcore-log( 6449): 
I/jxcore-log( 6449): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6449): 
V/FormManager( 6811): There are no updated forms. The schedule will be deleted.
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/FormManager( 6811): Alarm would be updated, because LastCheckTime has been updated.
V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2151): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2151): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2151): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2151): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2151): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2151): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2151): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1433): onNotificationPosted
D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do just update job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
,E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
E/BooksAccountManager( 6763): Authentication error
E/BooksAccountManager( 6763): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6763): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6763): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6763): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6763): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6763): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6763): null auth token
I/ActivityManager( 1047): Killing 6225:com.lge.eula/1000 (adj 15): empty #17
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  308): res_queryN name = www.googleapis.com, class = 1, type = 1
D/QuickStatusbarLayout( 1433): Notification difference=198
D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{3a06d5ef V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6919): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6919): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6919): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  277): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  277): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6919): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = www.google.com, class = 1, type = 1
W/libprocessgroup( 1047): failed to open /acct/uid_1000/pid_6225/cgroup.procs: No such file or directory
,D/libc-netbsd(  308): res_queryN name = www.googleapis.com succeed
,D/libc-netbsd(  308): res_queryN name = www.google.com succeed
,D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = clients3.google.com, class = 1, type = 1
D/libc-netbsd(  308): res_queryN name = clients3.google.com succeed
,W/Uploader( 2151): No account for auth token provided
I/WebViewFactory( 6919): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/LibraryLoader( 6919): Loading: webviewchromium
I/LibraryLoader( 6919): Time to load native libraries: 2 ms (timestamps 6932-6934)
I/LibraryLoader( 6919): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6919): Binding Chromium to main looper Looper (main, tid 1) {3414a56e}
I/LibraryLoader( 6919): Expected native library version number "",actual native library version number ""
,I/chromium( 6919): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6919): Initializing chromium process, renderers=0
W/art     ( 6919): Attempt to remove local handle scope entry from IRT, ignoring
V/WifiInternetCheck( 1047): isHttpConnectionAvailable - We got a valid response : 204
,W/Uploader( 2151):  no longer exists, so no auth token.
W/chromium( 6919): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6919): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
I/chromium( 6919): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
V/AudioPolicyService(  312): registerClient() client 0xb14277a0, uid 10093
W/AudioManagerAndroid( 6919): Requires BLUETOOTH permission
I/Adreno-EGL( 6919): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6919): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6919): Build Date: 12/12/14 금
I/Adreno-EGL( 6919): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6919): Remote Branch: 
I/Adreno-EGL( 6919): Local Patches: 
I/Adreno-EGL( 6919): Reconstruct Branch: 
,D/AndroidRuntime( 6948): 
D/AndroidRuntime( 6948): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6948): CheckJNI is OFF
I/NSApplication( 6919): Starting up...
,I/ActivityManager( 1047): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6993 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1047): Killing 6242:com.lge.bnr/1000 (adj 15): empty #17
,D/AndroidRuntime( 6948): Calling main entry com.android.commands.pm.Pm
,W/libprocessgroup( 1047): failed to open /acct/uid_1000/pid_6242/cgroup.procs: No such file or directory
W/PackageSettings( 1047): Skipping PackageSetting{276b4ff com.example.hello/10319} due to missing metadata
,I/ActivityManager( 1047): Force stopping com.test.thalitest appid=10311 user=-1: uninstall pkg
I/ActivityManager( 1047): Killing 6449:com.test.thalitest/u0a311 (adj 0): stop com.test.thalitest
W/ResourcesManager( 6993): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WindowState( 1047): WIN DEATH: Window{12fc7faf u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService( 1047): Client connection lost with reason: 4
,D/InputDispatcher( 1047): Window went away: Window{12fc7faf u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/ApiaryClient( 6763): Error response from books API: {
W/ApiaryClient( 6763):  "error": {
W/ApiaryClient( 6763):   "errors": [
W/ApiaryClient( 6763):    {
W/ApiaryClient( 6763):     "domain": "global",
W/ApiaryClient( 6763):     "reason": "required",
W/ApiaryClient( 6763):     "message": "Login Required",
W/ApiaryClient( 6763):     "locationType": "header",
W/ApiaryClient( 6763):     "location": "Authorization"
W/ApiaryClient( 6763):    }
W/ApiaryClient( 6763):   ],
W/ApiaryClient( 6763):   "code": 401,
W/ApiaryClient( 6763):   "message": "Login Required"
W/ApiaryClient( 6763):  }
W/ApiaryClient( 6763): }
W/ApiaryClient( 6763): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6763): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=7433482535904024745&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6763): Headers:
W/ApiaryClient( 6763): accept-encoding: [gzip]
W/ApiaryClient( 6763): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6763): gdata-version: 2
,I/ActivityManager( 1047):   Force finishing activity ActivityRecord{1f7b7948 u0 com.test.thalitest/.MainActivity t4}
,E/GBMv2   (  333): DFP En is all cleared set to be enabled
,I/ActivityManager( 1047): Force stopping com.test.thalitest appid=10311 user=0: pkg removed
I/ActivityManager( 1047):   Force finishing activity ActivityRecord{1f7b7948 u0 com.test.thalitest/.MainActivity t4 f}
W/ActivityManager( 1047): Duplicate finish request for ActivityRecord{1f7b7948 u0 com.test.thalitest/.MainActivity t4 f}
,W/ActivityManager( 1047): Spurious death for ProcessRecord{2361d015 6449:com.test.thalitest/u0a311}, curProc for 6449: null
D/SplitWindowPolicy( 1983): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,D/SplitWindowPolicy( 1983): topRunningActivity=ActivityInfo{6d1b224 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1983): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1983): topRunningActivity=ActivityInfo{3768018d co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,I/[LGHome]EVENT( 2102): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2102): [Launcher.java:903:onResume()]onResume
I/art     ( 4348): Explicit concurrent mark sweep GC freed 21740(1261KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 298us total 22.693ms
D/KeyguardModel( 1490): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
E/LGBluetoothAvrcpQcomAdapter( 3725): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3725): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2047): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
D/LIA_MrGDBLogger_PackageInfoDetector( 2754): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
I/[LGHome]EVENT( 2102): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2102): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/InputReader( 1047): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1852): Ignoring removeGeofence because network location is disabled.
,V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,W/System.err( 4285): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 4285): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4285): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4285): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4285): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4285): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4285): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4285): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
,W/System.err( 4285): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4285): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4285): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4285): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/administrator( 1047): Handling package changes for user 0
D/SplitUIManager( 1904): split_name #11 / not available #0
D/SplitUIService( 1904): removed split : 
,I/ActivityManager( 1047): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7017 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
D/ActionManagerService( 1938): notifyUserLog: 1000003
I/[LGHome]GBoardWebView( 2102): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/LIA_Informant_ActionManagerMessageHandler( 2754): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]LGActivityUtil( 2102): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[SystemUI]QSlideListController( 1490): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 2102): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2102): [Launcher.java:1114:onPause()]onPause
I/art     (  337): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 214us total 9.663ms
I/[LGHome]GBoardWebView( 2102): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
V/BoardContentProvider( 2754): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2102): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2102): , create_time: 1430558575574
I/GBoardWebViewUtils( 2102): , expire_time: 0
I/GBoardWebViewUtils( 2102): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2102): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2102): , display: false
I/GBoardWebViewUtils( 2102): , animation: false }
I/GBoardWebViewUtils( 2102): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2102): , create_time: 1430558575600
I/GBoardWebViewUtils( 2102): , expire_time: 0
I/GBoardWebViewUtils( 2102): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2102): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2102): , display: false
I/GBoardWebViewUtils( 2102): , animation: false }
I/GBoardWebViewUtils( 2102): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2102): , create_time: 1452175675684
I/GBoardWebViewUtils( 2102): , expire_time: 0
I/GBoardWebViewUtils( 2102): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2102): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2102): , display: false
I/GBoardWebViewUtils( 2102): , animation: false }
D/ActionManagerService( 1938): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2754): handleMessage: what(1000) actionID(0x1000004)
I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 187us total 8.837ms
D/WallpaperManager( 2102): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,I/art     (  337): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 195us total 8.856ms
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1490): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1490): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
V/SIM_STK ( 1047): Menu title from STK is T-Mobile
V/SIM_STK ( 1047): Menu title from STK is T-Mobile
,I/SystemUI[Framework]( 1047): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1047): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1047): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1047): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ca6d806,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1047): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[LGHome]EVENT( 2102): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2102): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,D/SplitUIManager( 1904): split_name #11 / not available #0
I/SplitUIService( 1904): split app #11
,I/LockScreenSettings( 7017): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,W/ActivityManager( 1047): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/LGBluetoothAvrcpQcomAdapter( 3725): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3725): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3725): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3725): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3725): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3725): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3725): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3725): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3725): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3725): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3725): [BTUI] [-] updateMediaPlayerInfo
D/KeyguardModel( 1490): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1490): createShortcutInfo...
,D/KeyguardModel( 1490): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1490): createShortcutInfo...
V/SIM_STK ( 1047): Menu title from STK is T-Mobile
I/[LGHome]EVENT( 2102): [Launcher.java:5349:onStop()]onStop
W/ResourcesManager( 1490): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1490): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1490): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1490): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1490): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1490): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1490): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1490): createShortcutInfo...
W/ResourcesManager( 1490): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1490): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1490): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1490): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1490): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1490): createShortcutInfo...
W/ResourcesManager( 1490): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1490): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1490): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1490): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1490): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1490): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1490): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1490): createShortcutInfo...
,I/ActivityManager( 1047): Killing 6272:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
I/NotificationService( 1047): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService( 1047): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1047): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     ( 1047): Explicit concurrent mark sweep GC freed 30610(1867KB) AllocSpace objects, 5(208KB) LOS objects, 33% free, 44MB/66MB, paused 2.472ms total 271.146ms
,D/AndroidRuntime( 6948): Shutting down VM
,I/[LGHome]Launcher.Model( 2102): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2102): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2102): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2102): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2102): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2102): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 2102): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2102): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]Launcher( 2102): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2102): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,W/libprocessgroup( 1047): failed to open /acct/uid_10005/pid_6272/cgroup.procs: No such file or directory
D/KeyguardModel( 1490): handleShortcutListChanged...
D/PhoneStatusBar( 1490): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
,I/[SystemUI]NavigationThemeResource( 1490): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1490):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1490): , Keyguard show=false, IME shown=false, Panel expanded=false
D/KeyguardModel( 1490): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1490): createShortcutInfo...
I/[LGHome]EVENT( 2102): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2102): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
D/TaskPersister( 1047): removeObsoleteFile: deleting file=4_task.xml
I/[LGHome]Launcher( 2102): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1490): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1490): createShortcutInfo...
W/ResourceType( 1490): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1490): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1490): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1490): createShortcutInfo...
W/ResourceType( 1490): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1490): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1490): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
,D/KeyguardModel( 1490): createShortcutInfo...
W/ResourceType( 1490): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1490): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[Concierge]WidgetView( 2102): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
D/KeyguardModel( 1490): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1490): createShortcutInfo...
D/[Concierge]Service( 2660): onStartCommand(). Type : 8
D/[Concierge]Service( 2660): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2660): Update widget ID : 11
D/[Concierge]WidgetView( 2102): change position of spinner
I/Timeline( 1047): Timeline: Activity_windows_visible id: ActivityRecord{2ddc22b6 u0 com.lge.launcher2/.Launcher t3} time:287621
D/KeyguardModel( 1490): handleShortcutListChanged...
I/[Concierge]WidgetView( 2102): initWebView(). Time : 1452294515283
,D/[Concierge]Service( 2660): onStartCommand(). Type : 0
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
,D/libc-netbsd(  308): res_queryN name = mtalk.google.com, class = 1, type = 1
I/[Concierge]WebView( 2102): Return exist ConciergeWebView. Reuse : 375818437
D/[Concierge]WidgetView( 2102): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2102): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2102): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@445afad
I/[LGHome]EVENT( 2102): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2102): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2102): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/iu.SyncManager( 2376): SYNC; picasa accounts
I/[LGHome]EVENT( 2102): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2102): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2102): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,I/GLSActivity( 2151): [ac] getting account id
W/[Concierge]WidgetView( 2102): Widget kill message received. Destory myself. My : 1452294256710, New one : 1452294515283
D/[Concierge]WidgetView( 2102): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2102): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2102): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/GLSUser ( 2151): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,I/[LGHome]EVENT( 2102): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
D/NetworkLogImpl( 2376): Loaded NetworkSpeedPredictor
I/[LGHome]EVENT( 2102): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/iu.Environment( 2376): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/[LGHome]EVENT( 2102): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2102): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2102): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/iu.UploadsManager( 2376): num queued entries: 0
I/[LGHome]Launcher( 2102): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2102): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/iu.UploadsManager( 2376): num updated entries: 0
,I/iu.SyncManager( 2376): NEXT; no task
D/ChimeraCfgMgr( 2376): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/ChimeraCfgMgr( 2376): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/libc-netbsd(  308): res_queryN name = mtalk.google.com succeed
D/PostponalbeReceiver( 6047): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 2102): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,I/ActivityManager( 1047): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=7051 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,E/[LgeWidgetLib]LgeAppWidgetHostView( 2102): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2102): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2102): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 2102): Timeline: Activity_idle id: android.os.BinderProxy@25713c18 time:287757
I/GLSUser ( 2151): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 2151): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2151): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2151): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2151): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1047): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1047): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1047): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1047): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1047): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1433): onNotificationPosted
D/SmartCoverUpdateMonitor( 1433): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1433): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1433): handleNotificationPosted(true)
D/QuickCircle( 1433): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1433): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): post do just update job
D/LgeQuickCoverNotificationData( 1433): showAll3
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1433): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/LgeQuickCoverOverlayWindow( 1433): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
W/Kids    ( 2376): [AccountUtils] Account not ready
W/Kids    ( 2376): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2376): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2376): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2376): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2376): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2376): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2376): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2376): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2376): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2376): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2376): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2376): 	at java.lang.Thread.run(Thread.java:818)
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1433): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1433): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1433): updateNotificationData: count=3
W/ResourcesManager( 1047): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ALBootInit( 7051): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 7051): Alarm ALBootInit: TIME_SET
W/ResourceType( 1047): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/Alarms  ( 7051): [setNextAlert] start
D/QuickStatusbarLayout( 1433): Notification difference=198
D/QuickStatusbarLayout( 1433): child = android.widget.LinearLayout{3a06d5ef V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
I/[LGHome]EVENT( 2102): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/Alarms  ( 7051): [setNextAlert] (1)
,D/Alarms  ( 7051):  minTime  = 0
D/Alarms  ( 7051):  -- OK multi -- 0
E/jeny.kim( 7051): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 7051): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/CommonUtil( 7051): BUILD Country: EU
,D/Alarms  ( 7051): broadcastToWidgetProvider : false
D/Alarms  ( 7051): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,V/SettingsProvider( 1047): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
I/DigitalAppWidgetProvider( 7051): onReceive: android.intent.action.TIME_SET
V/DigitalAppWidgetProvider( 7051): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@301bead4
V/DigitalAppWidgetProvider( 7051): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@301bead4
D/QuickCoverProvider( 7051): onReceiver
I/indal   ( 1433): SmartCoverWidgetContext createApplicationContext
I/indal   ( 1433): SmartCoverWidgetContext createApplicationContext
,D/WeatherAncestor( 6890): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 0:8:35
,D/Weather.Utils( 6890): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6890): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 6890): 2 : This is isUpdating : false
D/WeatherService( 6890): 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3167c47d
,D/ForecastDataCache( 6890): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 6890): 2 : currentPackageVersion: 4.40.4
D/ForecastDataCache( 6890): 2 : Cache is up-to-date, count: 0
D/Weather_cast( 6890): 2 : set auto-update time : 1/9 3:8
I/chromium( 2102): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
D/WeatherAncestor( 6890): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 0:8:35
E/SQLiteLog( 4285): (3850) statement aborts at 11: [INSERT INTO t010(f004,f002,f003) VALUES (?,?,?)] disk I/O error
E/SQLiteDatabase( 4285): Error inserting f004=1812552 f002=1452294515567 f003=69
E/SQLiteDatabase( 4285): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4285): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4285): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
E/SQLiteDatabase( 4285): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 4285): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4285): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
E/SQLiteDatabase( 4285): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
E/SQLiteDatabase( 4285): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
E/SQLiteDatabase( 4285): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 4285): 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
E/SQLiteDatabase( 4285): 	at com.lge.mlt.MltMonitorService.insertResourceInfo(MltMonitorService.java:2996)
E/SQLiteDatabase( 4285): 	at com.lge.mlt.MltMonitorService.access$3200(MltMonitorService.java:38)
E/SQLiteDatabase( 4285): 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3451)
E/SQLiteDatabase( 4285): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4285): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4285): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
,I/ActivityManager( 1047): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7081 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1047): Killing 5720:com.android.vending/u0a44 (adj 15): empty #17
,I/GBoardtInterface( 2102): onReloaded()
I/GBoardWebViewClient( 2102): onPageFinished url:file:///android_asset/www/main.html

```
