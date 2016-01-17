#### Test 56151093c886730_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,E/global frequency( 2845): no tags to log
D/Checkin ( 2845): publish the event [tag = MOT_CHECKIN event name = LOG]
D/BSUtils ( 2845): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/BSUtils ( 2845): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/art     ( 1471): Explicit concurrent mark sweep GC freed 55213(3MB) AllocSpace objects, 37(975KB) LOS objects, 39% free, 7MB/12MB, paused 778us total 45.346ms
I/BSUtils ( 2845): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2845): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/AndroidRuntime( 7099): 
D/AndroidRuntime( 7099): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/BSUtils ( 2845): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
D/AndroidRuntime( 7099): CheckJNI is OFF
I/BSUtils ( 2845): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2845): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1552): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/AndroidRuntime( 7099): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/art     ( 2845): Explicit concurrent mark sweep GC freed 32016(1783KB) AllocSpace objects, 5(126KB) LOS objects, 39% free, 11MB/18MB, paused 1.195ms total 74.368ms
D/BSUtils ( 2845): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (170 us)
I/art     ( 1471): Explicit concurrent mark sweep GC freed 4778(220KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 873us total 29.509ms
W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/BSUtils ( 2845): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/AndroidRuntime( 7099): Shutting down VM
I/BSUtils ( 2845): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 2845): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2845): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2845): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2845): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2845): publish the event [tag = DEV_ATTRIBS event name = SW]
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7129 uid=10456 gids={50456, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/Checkin ( 2845): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
I/global frequency( 2845): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
D/Checkin ( 2845): publish the event [tag = MOT_CHECKIN event name = LOG]
W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 7129): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 7129): Time to load native libraries: 7 ms (timestamps 4206-4213)
I/LibraryLoader( 7129): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7129): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
I/LibraryLoader( 7129): Expected native library version number "",actual native library version number ""
I/chromium( 7129): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7129): Initializing chromium process, singleProcess=true
W/art     ( 7129): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7129): ApplicationContext is null in ApplicationStatus
W/chromium( 7129): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7129): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7129): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7129): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7129): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7129): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7129): Local Branch: 
I/Adreno-EGL( 7129): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7129): Local Patches: NONE
I/Adreno-EGL( 7129): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2686197d:true
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
W/art     ( 7129): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7129): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7129): CordovaWebView is running on device made by: motorola
W/art     ( 7129): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7129): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 7129): Render dirty regions requested: true
D/Atlas   ( 7129): Validating map...
W/chromium( 7129): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/art     (  880): Explicit concurrent mark sweep GC freed 26311(1241KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.496ms total 127.442ms
I/OpenGLRenderer( 7129): Initialized EGL, version 1.4
D/OpenGLRenderer( 7129): Enabling debug mode 0
I/Keyboard.Facilitator( 1413): onFinishInput()
I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,1196
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +1s196ms
E/Adreno-ES20( 7129): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7129): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 7129): Cannot call determinedVisibility() - never saw a connection for the pid: 7129
D/JsMessageQueue( 7129): Set native->JS mode to OnlineEventsBridgeMode
,E/Adreno-ES20( 7129): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7129): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 7129): JniHelper::setJavaVM(0xb8e9c310), pthread_self() = -1188908848
D/JX-Cordova( 7129): jxcore cordova android initializing
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (38:306 vsyncs) (40:1169)
I/SFPerfTracer(  278):      triggers: (rate: 12:379) (compose: 0:1) (post: 0:1) (render: 0:2) (26:1053 frames) (27:1169)
,D/SFPerfTracer(  278):        layers: (3:11) (FocusedStackFrame (0xb78f2548): 0:14)* (DimLayer (0xb7963650): 0:6)* (StatusBar (0xb797e398): 0:174) (NavigationBar (0xb7981e88): 0:23) (com.android.systemui.ImageWallpaper (0xb7998990): 0:36)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb799d478): 0:55)- (Starting com.test.thalitest (0xb79a10f8): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb797ca30): 27:36) 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,D/TaskPersister(  880): removeObsoleteFile: deleting file=5_task_thumbnail.png
,W/jxcore-log( 7129): Initializing JXcore engine
W/jxcore-log( 7129): JXcore engine is ready
,W/jxcore-log( 7129): Starting JXcore engine
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/.test.thalitest( 7129): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10456 path="socket:[9633]" dev="sockfs" ino=9633 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 7129): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10456 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 7129): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10456 path="socket:[7968]" dev="sockfs" ino=7968 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 7129): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10456 path="socket:[28171]" dev="sockfs" ino=28171 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 7129): Platform android
W/jxcore-log( 7129): 
W/jxcore-log( 7129): Process ARCH arm
W/jxcore-log( 7129): 
,I/jxcore-log( 7129): JXcore Cordova bridge is ready!
I/jxcore-log( 7129): 
,W/jxcore-log( 7129): JXcore engine is started
I/chromium( 7129): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 7129): Skipped 182 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 7129): Toggling radios to true
I/jxcore-log( 7129): 
,D/BluetoothAdapter( 7129): enable(): BT is already enabled..!
,D/WifiService(  880): New client listening to asynchronous messages
,D/WifiService(  880): setWifiEnabled: true pid=7129, uid=10456
E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 7129): Radios toggled
I/jxcore-log( 7129): 
,I/jxcore-log( 7129): My device name is: motorola-XT1072
I/jxcore-log( 7129): 
,I/wpa_supplicant( 1396): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  291):  STA Disconnected !!
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): get_property_value, Enter
I/MDMCTBK (  291): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  291): get_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  473): NL - Read 1004 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 68 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 68 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  291): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  291): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
E/MDMCTBK (  291): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/wpa_supplicant( 1396): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
E/WifiStateMachine(  880): WifiStateMachine: Leaving Connected state
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  291): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  880): InitialState.processMessage what=4
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
D/Tethering(  880):  0
,I/wpa_supplicant( 1396): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  291): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  880): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/WifiP2pService(  880): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1396): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  288): Clearing all IP addresses on wlan0
,D/TCMD    (  473): NL - Read 60 bytes from update socket.
D/TCMD    (  473): NL - ignore NL message, type = 21
D/TCMD    (  473): Listening for incoming client connection request
,V/NativeCrypto( 1704): Read error: ssl=0xb919eaa8: I/O error during system call, Connection timed out
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/NativeCrypto( 1704): SSL shutdown failed: ssl=0xb919eaa8: I/O error during system call, Broken pipe
D/ConnectivityService(  880): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/WifiMetrics(  880): connected time updated 129217
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): ValidatedState{ when=-4ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-4ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=7231 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  880): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  880): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  880): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Disconnected - quitting
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 1958): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1532): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/ConnectivityService(  880): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1532): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityService(  880): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/ModemStatsDSDetect( 1532): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1532): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 1396): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  880): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1396): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  880): ConnectModeState: Network connection lost 
E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/ModemStatsDSDetect( 1532): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1532): onReceive() - done, currentInetCondition=0
,E/wpa_supplicant( 1396): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  288): Clearing all IP addresses on wlan0
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  880): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
W/ResourcesManager( 7231): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/PerfProfileCollectorService( 1958): User is not opt-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 1958): removeStateFiles() called
,D/PerfProfileCollectorService( 1958): User is not opt-in to Usage & Diagnostics.
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7260 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/AlarmManager(  880): send {d26d833, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,I/ActivityManager(  880): Killing 6810:android.process.acore/u0a7 (adj 15): empty #7
,D/TCMD    (  473): NL - Read 56 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 12 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 13 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  291): Event received = WPS-AP-AVAILABLE 
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_6810/cgroup.procs: No such file or directory
,E/WifiStateMachine(  880): [1,453,034,399,342 ms] noteScanEnd no scan source
I/wpa_supplicant( 1396): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  291): Event received = Trying to associate with
D/WifiMonitor(  880): didn't find BSSID Trying to associate with SSID 'NG700'
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1396): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiStateMachine(  880): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@23f04f26 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 7260): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  473): NL - Read 312 bytes from update socket.
,D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 192 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 68 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 1004 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1396): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  291): Event received = Associated with c0:ff:d4
D/TCMD    (  473): NL - Read 80 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 80 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/TCMD    (  473): NL - Read 68 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1396): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  291): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1396): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  291): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  291):  STA Connected !!
,D/TCMD    (  473): NL - Read 1004 bytes from update socket.
D/TCMD    (  473): NL - message type is RTM_NEWLINK
D/TCMD    (  473): Listening for incoming client connection request
,D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  880): ApnList is empty for checkDunConfigured()
E/MDMCTBK (  291): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/Tethering(  880):  upstream interface types: 
D/MDMCTBK (  291): get_freq !!, resp=2412
I/MDMCTBK (  291): get_freq !!, Strip data
D/Tethering(  880):  0
D/Tethering(  880):  1
I/MDMCTBK (  291): get_freq !!, band = 2, freq = 2412
D/Tethering(  880):  5
D/Tethering(  880):  7
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): get_property_value, Enter
I/MDMCTBK (  291): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  291): get_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  291): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  291): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  291): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): get_property_value, Enter
I/MDMCTBK (  291): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  291): get_property_value, Exit
,I/MDMCTBK (  291): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1205826112
I/MDMCTBK (  291): return from set_get_from_wpa_supplicant
I/MDMCTBK (  291): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  291): set_property_value, Enter
D/MDMCTBK (  291): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
E/MDMCTBK (  291): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  291): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  291): , reply_len: 3, ret: 0
E/MDMCTBK (  291): MdmCutbackHndler, resp=OK
E/MDMCTBK (  291): 
D/MDMCTBK (  291): wifi_set_tx_pwr: Exit
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  880): Network connection established
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  880): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  880): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  880): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  880): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  288): Setting iface cfg
,E/WifiStateMachine(  880): Start Dhcp Watchdog 2
,E/WifiStateMachine(  880): calculateWifiScore() report new score 60
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  880): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/Babel_SMS( 7260): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7260): MmsConfig.loadMmsSettings
I/Babel_SMS( 7260): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7260): MmsConfig.loadFromDatabase
E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend false
,E/wpa_supplicant( 1396): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1396): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  880): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@b56dcda target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@b56dcda target=com.android.internal.util.StateMachine$SmHandler }
,E/Babel_SMS( 7260): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7260): MmsConfig.loadFromResources
E/Babel_SMS( 7260): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7260): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7260): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7260): startup - clean
,I/Babel   ( 7260): deleted: false for 0
,V/AlarmManager(  880): done {d26d833, *alarm*:com.android.server.WifiManager.action.START_SCAN} [573ms]
,W/VideoCapabilities( 7260): Unrecognized profile 2130706433 for video/avc
E/DHCPCD  ( 7291): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
I/DHCPCD  ( 7291): version 5.5.6 starting
E/DHCPCD  ( 7291): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 7291): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 7291): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
W/AudioCapabilities( 7260): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7260): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7260): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7260): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7260): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7260): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7260): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Killing 6993:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/DHCPCD  ( 7291): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 7291): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 7291): wlan0: sending REQUEST (xid 0xe5a4fbe0), next in 3.75 seconds
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6993/cgroup.procs: No such file or directory
V/AlarmManager(  880): send {3200ef95, *alarm*:android.intent.action.TIME_TICK}
,I/vclib   ( 7260): onServiceConnected
,W/Babel   ( 7260): Attempted to change video mute state without an active call.
,V/AlarmManager(  880): done {3200ef95, *alarm*:android.intent.action.TIME_TICK} [165ms]
,I/DHCPCD  ( 7291): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 7291): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 7291): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 7291): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 7291): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 7291): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  473): NL - Read 60 bytes from update socket.
D/TCMD    (  473): NL - ignore NL message, type = 20
D/TCMD    (  473): Listening for incoming client connection request
,D/DHCPCD  ( 7291): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  880): WifiStateMachine DHCP successful
E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  880): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  880): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  880): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  880): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  880): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  880): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  880): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-8ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880):    accepting network in place of null
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  880): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  880): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/ModemStatsDSDetect( 1532): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1532): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1532): onReceive() - done, currentInetCondition=0
,E/WifiStateMachine(  880): ConnectedState Enter  mScreenOn=true scanperiod=20000
,E/WifiStateMachine(  880): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=99.00 rxSuccessRate=98.00 targetRoamBSSID=any RSSI=-50
E/WifiStateMachine(  880): WifiStateMachine CMD_START_SCAN with age=32064 interval=20000 maxinterval=300000
E/WifiStateMachine(  880): WifiStateMachine CMD_START_SCAN try full band scan age=32064 interval=20000 maxinterval=300000
E/WifiStateMachine(  880): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
,E/WifiStateMachine(  880): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=99.00 rx=98.00
D/ConnectivityManager.CallbackHandler( 1958): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 12:40:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453034401804], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453034401785]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Validated
D/ConnectivityService(  880): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1958): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1532): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1532): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1532): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1532): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  880): send {d26d833, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  880): done {d26d833, *alarm*:com.android.server.WifiManager.action.START_SCAN} [1ms]
E/WifiStateMachine(  880): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=99.00 rxSuccessRate=98.00 targetRoamBSSID=any RSSI=-50
,E/WifiStateMachine(  880): WifiStateMachine CMD_START_SCAN with age=32264 interval=20000 maxinterval=300000
E/WifiStateMachine(  880): WifiStateMachine CMD_START_SCAN try full band scan age=32264 interval=20000 maxinterval=300000
E/WifiStateMachine(  880): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  880): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=99.00 rx=98.00
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/PollingManager( 2845): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1471): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2845): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2845): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7347 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2845): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/PollingManager( 2845): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2845): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2845): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2845): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2845): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2845): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2845): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1471): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1471): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2845): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2845): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2845): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2845): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2845): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2845): [debug] > CusSM.onRadioDown
,I/MusicStore( 7347): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7347): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7347): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7347): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7347): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7347): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7347): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7347): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7347): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7347): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7347): GMSCore installation verified
,I/ConfigStore( 7347): Config Database version: 1
,I/MediaRouter( 7347): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7347): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7347): type=WIFI subType= reason=null isConnected=true
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020132=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully Activity=0x00000000=( none ) Accessibility="Wifi signal full."
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/NetworkMonitor( 7347): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7379 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  880): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/GHttpClientFactory( 7347): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7347): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 6719:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_6719/cgroup.procs: No such file or directory
,V/Mms     ( 7379): mnc/mcc: 
V/Mms     ( 7379): tag: int value: recipientLimit - 20
,V/Mms     ( 7379): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7379): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7379): tag: int value: maxSubjectLength - 80
V/Mms     ( 7379): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7379): tag: bool value: enableGroupMms - false
V/Mms     ( 7379):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7379): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7405 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6888:com.android.vending/u0a32 (adj 15): empty #7
D/PhoneMonitor( 7405): Register our PhoneStateListener
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_6888/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7405): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7405): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 7260:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7260/cgroup.procs: No such file or directory
,I/CheckinService( 1958): Checkin interval check for package: unspecified last checkin: 1453034314625 min interval config: 0 actual interval: 88753
,I/jxcore-log( 7129): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7129): 
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7434 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 1958): Checking schedule, now: 1453034403434 next: 1453034344585
I/CheckinService( 1958): active receiver: enabled
,I/CheckinService( 1958): Preparing to send checkin request
I/EventLogService( 1958): Accumulating logs since 1453034310462
,I/CheckinRequestBuilder( 1958): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1958): Failed to find provider info for com.google.android.wearable.settings
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/art     (  880): Explicit concurrent mark sweep GC freed 50007(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/31MB, paused 1.671ms total 131.415ms
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7460 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7477 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 21.290ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.602ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.589ms
W/ResourcesManager( 7460): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7477): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7477): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7477): VM with version 2.1.0 has multidex support
I/MultiDex( 7477): install
I/MultiDex( 7477): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7477): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7477): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7477): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7477): Installed default security provider GmsCore_OpenSSL
,I/jxcore-log( 7129): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7129): 
,I/jxcore-log( 7129): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7129): 
,I/Babel_SMS( 7460): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7460): MmsConfig.loadMmsSettings
I/Babel_SMS( 7460): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7460): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7460): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7460): MmsConfig.loadFromResources
I/art     ( 7477): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7477): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/Babel_SMS( 7460): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7460): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/jxcore-log( 7129): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7129): 
,I/jxcore-log( 7129): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7129): 
,W/Settings( 7460): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/jxcore-log( 7129): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7129): 
,I/Babel_Crash( 7460): startup - clean
,I/jxcore-log( 7129): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7129): 
I/Babel   ( 7460): deleted: false for 0
,D/NativeLibraryUtils( 7477): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7508 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WVCdm   (  294): Instantiating CDM.
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f64000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f64000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xbeaca4e0
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8fc5188, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8ff2a68, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb90c1a20, idLength=0xb1355730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=1661857541
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8fc7350
D/DrmWidevineDash(  294): message_length=1591, signature=0xb8fceec8, signature_length=2973062932
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/VideoCapabilities( 7460): Unrecognized profile 2130706433 for video/avc
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Central_PollingManager( 1471): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2845): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2845): now: 205117 ,futureTime: 9223372036854775807
D/PollingManager( 2845): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2845): now: 205117 ,futureTime: 9223372036854775807
D/PollingManager( 2845): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2845): now: 205118 ,futureTime: 9223372036854775807
D/OtaApp  ( 2845): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1471): now: 205119 ,futureTime: 86473102
D/Central_PollingManager( 1471): Polling alarm set to expire at: 86473102 Current Time: 205119
D/Tethering(  880): MasterInitialState.processMessage what=3
D/OtaApp  ( 2845): [debug] > PollingManagerService, now: 205123 ,futureTime: 19468611
D/OtaApp  ( 2845): [debug] > Polling alarm set to expire at: 19468611 Current Time: 205123
,I/NetworkMonitor( 7347): type=WIFI subType= reason=null isConnected=true
,W/AudioCapabilities( 7460): Unsupported mime audio/amr-wb-plus
,D/MMApiProvisionService( 2845): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2845): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2845): createDeviceIdOrLogin update_device
,W/VideoCapabilities( 7460): Unsupported mime video/mpeg2
D/Checkin ( 2845): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2845): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2845): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2845): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2845): createDeviceIdOrLogin update_device
,D/Checkin ( 2845): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2845): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2845): set mOutstandingReq to true.
,I/ Nonce  ( 2845):  Nonce getNonce 
I/ Nonce  ( 2845):  Nonce Request 
I/ Nonce  ( 2845):  Nonce execute Request 
,D/MMApiWebService( 2845): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2845): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2845): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2845): createDeviceIdOrLogin update_device
D/Checkin ( 2845): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2845): Not proxy app, so login/provision not allowed
D/OtaApp  ( 2845): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2845): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2845): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2845): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2845): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2845): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2845): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2845): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2845): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
D/OtaApp  ( 2845): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,D/MMApiWebService( 2845): generating token using payload instead of using session token
,I/VideoCapabilities( 7460): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7460): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7460): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7460): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7460): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7460): onServiceConnected
,W/Babel   ( 7460): Attempted to change video mute state without an active call.
,D/ Nonce  ( 2845):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1958): CM callback handler got msg 524295
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,I/MMApiWSBase( 2845): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2845): publish the event [tag = MOT_CCE event name = LOG]
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f64000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f64000
,I/Babel   ( 7460): connection state changed from UNKNOWN to CONNECTED
,I/jxcore-log( 7129): Test app app.js loaded
I/jxcore-log( 7129): 
I/ActivityManager(  880): Killing 7231:com.motorola.context/u0a8 (adj 15): empty #7
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb1355960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8fc5078, dataLength=8
,D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8ff7148, wrapped_rsa_key_length=1280
I/Choreographer( 7129): Skipped 393 frames!  The application may be doing too much work on its main thread.
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb90c1a60, idLength=0xbeaca2b0
,I/chromium( 7129): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=3136705840
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8fc7350
D/DrmWidevineDash(  294): message_length=1626, signature=0xb8fec078, signature_length=3198984852
,I/GAv4    ( 7508): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7508):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7508):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7508): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7508): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7508): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7508): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_7231/cgroup.procs: No such file or directory
,W/GAv4    ( 7508): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7508): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7508): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WebViewFactory( 7508): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/LibraryLoader( 7508): Time to load native libraries: 2 ms (timestamps 6004-6006)
I/LibraryLoader( 7508): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7508): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
I/LibraryLoader( 7508): Expected native library version number "",actual native library version number ""
,I/chromium( 7508): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7508): Initializing chromium process, singleProcess=true
,W/art     ( 7508): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7508): ApplicationContext is null in ApplicationStatus
,W/chromium( 7508): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7508): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7508): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7508): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7508): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7508): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7508): Local Branch: 
I/Adreno-EGL( 7508): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7508): Local Patches: NONE
I/Adreno-EGL( 7508): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/AudioManagerAndroid( 7508): Requires BLUETOOTH permission
,I/NSApplication( 7508): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7577 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7347:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7347/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7597 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7379:com.android.mms/u0a23 (adj 15): empty #7
,I/WVCdm   (  294): CdmEngine::CloseSession
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7379/cgroup.procs: No such file or directory
,W/ResourcesManager( 7597): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,I/ Nonce  ( 2845):  Nonce Reponse 
D/        ( 2845): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"7e806fda-e4c3-4f17-97f4-f17d0662a0bd"}
D/MMApiWSBase( 2845): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2845):  Nonce Handle Reponse 
D/MMApiProvisionService( 2845): mOutstandingReq set to false
,I/dex2oat ( 7619): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7619): dex2oat took 79.451ms (threads: 4)
,D/MMApiProvisionService( 2845):  pTime 1453032756427 sExp 172742 cTime 1453034406248 tTime 1453205498427
D/MMApiProvisionService( 2845):  No login Required 
,I/Adreno-EGL( 7477): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7477): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7477): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7477): Local Branch: 
I/Adreno-EGL( 7477): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7477): Local Patches: NONE
I/Adreno-EGL( 7477): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7636 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/Adreno-EGL( 7477): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7477): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7477): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7477): Local Branch: 
I/Adreno-EGL( 7477): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7477): Local Patches: NONE
I/Adreno-EGL( 7477): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7660 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7434:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/Adreno-EGL( 7477): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7477): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7477): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7477): Local Branch: 
I/Adreno-EGL( 7477): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7477): Local Patches: NONE
I/Adreno-EGL( 7477): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7477): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7477): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7477): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7477): Local Branch: 
I/Adreno-EGL( 7477): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7477): Local Patches: NONE
I/Adreno-EGL( 7477): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ContactLocale( 7636): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/DataUsage( 2845): invalid counter update blocked: 'err' by 0
D/Checkin ( 2845): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  880): Killing 7405:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/art     (  880): Explicit concurrent mark sweep GC freed 15540(730KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.534ms total 131.822ms
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7434/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7405/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 1958): Classify the device as Phone.
,I/MusicStore( 7660): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7660): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7660): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7660): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinTask( 1958): Sending checkin request (9521 bytes)
,W/ResourcesManager( 7660): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7660): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7660): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7660): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7660): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7660): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7660): GMSCore installation verified
,I/ConfigStore( 7660): Config Database version: 1
,I/MediaRouter( 7660): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7660): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7660): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7660): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7696 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7660): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7660): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 7460:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7460/cgroup.procs: No such file or directory
,V/Mms     ( 7696): mnc/mcc: 
,V/Mms     ( 7696): tag: int value: recipientLimit - 20
V/Mms     ( 7696): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7696): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7696): tag: int value: maxSubjectLength - 80
,V/Mms     ( 7696): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7696): tag: bool value: enableGroupMms - false
,V/Mms     ( 7696):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/art     ( 7696): No such thread id for suspend: 14
,W/art     ( 7696): No such thread id for suspend: 14
,I/CheckinRequestBuilder( 1958): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1958): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 7696): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7722 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7508:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 7722): Register our PhoneStateListener
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7508/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7722): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7722): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 1958): Checkin interval check for package: unspecified last checkin: 1453034314625 min interval config: 0 actual interval: 92947
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7740 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  880): send {3fec9949, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/ActivityManager(  880): Killing 7577:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7577/cgroup.procs: No such file or directory
,I/art     ( 7032): Explicit concurrent mark sweep GC freed 1570(70KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 387us total 27.924ms
,I/CheckinRequestBuilder( 1958): Classify the device as Phone.
,I/CheckinTask( 1958): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1958): Checking schedule, now: 1453034407777 next: 1453635544767
I/CheckinService( 1958): active receiver: disabled
,I/CheckinService( 1958): Checking schedule, now: 1453034407800 next: 1453635544767
I/CheckinService( 1958): active receiver: disabled
,D/CheckinService( 1958): Recording last checkin time for package unspecified as 1453034407803
,I/ActivityManager(  880): Killing 7636:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  880): Killing 7597:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7636/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7597/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7761 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7660:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7660/cgroup.procs: No such file or directory
,W/ResourcesManager( 7761): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7761): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7761): MmsConfig.loadMmsSettings
I/Babel_SMS( 7761): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7761): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7761): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7761): MmsConfig.loadFromResources
,E/Babel_SMS( 7761): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7761): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7761): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7761): startup - clean
,I/Babel   ( 7761): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7799 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/VideoCapabilities( 7761): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7761): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7761): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7761): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7761): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7761): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7761): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7761): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7761): onServiceConnected
,W/Babel   ( 7761): Attempted to change video mute state without an active call.
,I/Babel   ( 7761): connection state changed from UNKNOWN to CONNECTED
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7799): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager(  880): Killing 7696:com.android.mms/u0a23 (adj 13): empty #7
,I/GAv4    ( 7799): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7799):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7799):   adb logcat -s GAv4
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7799): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7799): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7799): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7696/cgroup.procs: No such file or directory
,W/GAv4    ( 7799): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7799): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7799): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7799): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7799): Time to load native libraries: 3 ms (timestamps 9477-9480)
I/LibraryLoader( 7799): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7799): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
I/LibraryLoader( 7799): Expected native library version number "",actual native library version number ""
I/chromium( 7799): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7799): Initializing chromium process, singleProcess=true
W/art     ( 7799): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7799): ApplicationContext is null in ApplicationStatus
,W/chromium( 7799): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7799): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7799): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7799): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7799): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7799): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7799): Local Branch: 
I/Adreno-EGL( 7799): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7799): Local Patches: NONE
I/Adreno-EGL( 7799): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7799): Requires BLUETOOTH permission
,I/NSApplication( 7799): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7867 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7722:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.573ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 19.652ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.501ms
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7722/cgroup.procs: No such file or directory
,I/art     (  880): Explicit concurrent mark sweep GC freed 11529(582KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.636ms total 120.081ms
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7886 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7740:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7740/cgroup.procs: No such file or directory
,W/ResourcesManager( 7886): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7906 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7799:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7906): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 7761:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2845): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7799/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7761/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2845): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2845): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2845): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2845): onServiceConnected()
,D/GetNotificationsWS( 2845): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2845): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7930 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2845): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1704): callingUid 10016, callindPid: 1704
,D/LocationInitializer( 1958): Restart initialization of location
,D/AuthorizationBluetoothService( 1704): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1704): [151] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7955 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1704): No location to return for getLastLocation()
W/FusedLocationProvider( 1704): location=null
,I/MusicStore( 7955): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7955): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7955): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7955): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7955): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7955): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7955): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7955): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7955): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7955): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7955): GMSCore installation verified
,I/ConfigStore( 7955): Config Database version: 1
,I/MediaRouter( 7955): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7955): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7955): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7955): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7985 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7955): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7955): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7985): mnc/mcc: 
,V/Mms     ( 7985): tag: int value: recipientLimit - 20
V/Mms     ( 7985): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7985): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7985): tag: int value: maxSubjectLength - 80
V/Mms     ( 7985): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7985): tag: bool value: enableGroupMms - false
,V/Mms     ( 7985):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7985): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8015 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7867:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7867/cgroup.procs: No such file or directory
,D/PhoneMonitor( 8015): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 8015): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8015): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 7886:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7886/cgroup.procs: No such file or directory
,I/CheckinService( 1958): Checkin interval check for package: unspecified last checkin: 1453034407803 min interval config: 0 actual interval: 3516
,I/CheckinService( 1958): Checkin interval check for package: unspecified last checkin: 1453034407803 min interval config: 0 actual interval: 3520
,I/CheckinService( 1958): Checking schedule, now: 1453034411327 next: 1453034437767
I/CheckinService( 1958): active receiver: disabled
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8036 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 1958): Checking schedule, now: 1453034411386 next: 1453034437767
I/CheckinService( 1958): active receiver: disabled
,W/ResourcesManager( 8036): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8036): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8036): MmsConfig.loadMmsSettings
I/Babel_SMS( 8036): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 8036): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8036): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 8036): MmsConfig.loadFromResources
E/Babel_SMS( 8036): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8036): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Settings( 8036): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 8036): startup - clean
,I/Babel   ( 8036): deleted: false for 0
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8063 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7906:android.process.acore/u0a7 (adj 15): empty #7
,W/VideoCapabilities( 8036): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8036): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 8036): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8036): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8036): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8036): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8036): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8036): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7906/cgroup.procs: No such file or directory
,I/vclib   ( 8036): onServiceConnected
,W/Babel   ( 8036): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8063): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8063): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 8063): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8063):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8063):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8063): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8063): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 8036): connection state changed from UNKNOWN to CONNECTED
,W/GAv4    ( 8063): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  880): Killing 7955:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/GAv4    ( 8063): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8063): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7955/cgroup.procs: No such file or directory
,I/WebViewFactory( 8063): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8063): Time to load native libraries: 2 ms (timestamps 2775-2777)
,I/LibraryLoader( 8063): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8063): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
I/LibraryLoader( 8063): Expected native library version number "",actual native library version number ""
I/chromium( 8063): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8063): Initializing chromium process, singleProcess=true
,W/art     ( 8063): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8063): ApplicationContext is null in ApplicationStatus
,W/chromium( 8063): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8063): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8063): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 8063): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8063): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8063): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8063): Local Branch: 
I/Adreno-EGL( 8063): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8063): Local Patches: NONE
I/Adreno-EGL( 8063): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 8063): Starting up...
,W/AudioManagerAndroid( 8063): Requires BLUETOOTH permission
,I/art     (  880): Explicit concurrent mark sweep GC freed 12777(614KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.653ms total 123.174ms
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8126 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7985:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7985/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8145 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 8015:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_8015/cgroup.procs: No such file or directory
,W/ResourcesManager( 8145): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/PowerManagerService(  880): Nap time (uid 1000)...
I/PowerManagerService(  880): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  880): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  880): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  880): Build Date: 10/28/14 Tue
I/Adreno-EGL(  880): Local Branch: 
I/Adreno-EGL(  880): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  880): Local Patches: NONE
I/Adreno-EGL(  880): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=8165 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7930:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     (  307): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 26.112ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 23.477ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 26.634ms
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7930/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 8036:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 8165): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_8036/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2845): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2845): bindWebServices(): registering our AIDL callback...
I/SundryService( 2845): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2845): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 2845): onServiceConnected()
D/GetNotificationsWS( 2845): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2845): unbindWebServices(): un-registering our AIDL callback...
I/PushService( 2845): started with background data enabled, making sure notification mechanism is enabled
D/OtaApp  ( 2845): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
D/OtaApp  ( 2845): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2845): [debug] > In cancelAnyPendingIntentSetPreviously
I/ActivityManager(  880): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,V/AlarmManager(  880): done {3fec9949, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [5729ms]
,D/OtaApp  ( 2845): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2845): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2845): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8205 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2845): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2845): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2845): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2845): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2845): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2845): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2845): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2845): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2845): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1413): onFinishInput()
,D/PhoneMonitor( 8205): Register our PhoneStateListener
,W/InputMethodManagerService(  880): Starting input on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@cf3c2f3 (uid=10456 pid=7129)
W/IInputConnectionWrapper( 7129): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  880): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,186
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,V/SetupWizard( 8205): Connected to Gservices successfully
,I/ActivityManager(  880): Killing 8063:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/        (  880): activate, handle: 1598182242, enabled: 0, index 2
,D/        (  880): BstSensorExt: id=1598182242, en=0
D/        (  880): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 261
,D/        (  880): activate, handle: 2, enabled: 0, index 5
,D/SurfaceFlinger(  278): Set power mode=0, type=0 flinger=0xb786f550
,D/qdhwcomposer(  278): hwc_blank: Blanking display: 0
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_8063/cgroup.procs: No such file or directory
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  278): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  278): hwc_blank: Done blanking display: 0
D/SurfaceControl(  880): Excessive delay in setPowerMode(): 323ms
,I/DisplayManagerService(  880): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/PowerManagerService(  880): Sleeping (uid 1000)...
,I/WindowManager(  880): AOD feature not enabled!
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/ActivityManager(  880): Display changed displayId=0
,D/WifiStateMachine(  880): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  880): handleScreenStateChanged Exit: true
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  880): do suspend false
,D/audio_hw_primary(  294): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  294): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  294): platform_set_parameters: exit with code(0)
,E/msm8974_platform(  294): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  294): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  294): adev_set_parameters: ERROR: set param called even when stream out is null
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1e571e01
,I/Launcher( 1570): Deferring update until onResume
,I/GCoreNlp( 1704): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=8233 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/rmt_storage(  287): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb85ee820
,I/rmt_storage(  287): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  287): wakelock acquired: 1, error no: 42
I/rmt_storage(  287): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1201739640)
,D/GCM     ( 1704): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/rmt_storage(  287): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  287): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  287): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1201739640) wakelock released: 1, error no: 0
I/rmt_storage(  287): 
,I/rmt_storage(  287): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb85ee820
,D/        (  880): activate, handle: 1598182229, enabled: 0, index 0
E/        (  880): <BST> disable accel, orig state: 1
I/        (  880): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,D/audio_hw_primary(  294): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  294): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  294): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  294): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  294): adev_set_parameters: ERROR: set param called even when stream out is null
,D/WifiStateMachine(  880): backgroundScan enabled=true startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  880): handleScreenStateChanged Exit: false
E/WifiStateMachine(  880): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
,E/native  (  880): do suspend true
,I/Keyboard.Facilitator( 1413): onFinishInput()
,I/PhenotypeConfigurator( 1704): Scheduling Phenotype for one-off execution 107 seconds from now (1453034414456)
,D/GetConfigurationSnapshotOperation( 1704): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/GCM     ( 1704): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8264 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7477:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/PhenotypeFlagCommitter( 1704): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1704): Using platform SSLCertificateSocketFactory
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_7477/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8292 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8308 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  880): Killing 8126:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  880): Killing 8145:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_8126/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_8145/cgroup.procs: No such file or directory
,W/ResourcesManager( 8308): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8308): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8308): MmsConfig.loadMmsSettings
I/Babel_SMS( 8308): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8308): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8308): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8308): MmsConfig.loadFromResources
E/Babel_SMS( 8308): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8308): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8308): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8308): startup - clean
,I/Babel   ( 8308): deleted: false for 0
,W/VideoCapabilities( 8308): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8342 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 8233:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/AudioCapabilities( 8308): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8308): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8308): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8308): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8308): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8308): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8308): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_8233/cgroup.procs: No such file or directory
,W/art     ( 8308): Suspending all threads took: 5.449ms
,I/vclib   ( 8308): onServiceConnected
,W/Babel   ( 8308): Attempted to change video mute state without an active call.
,W/ResourcesManager( 8308): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8308): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  880): Explicit concurrent mark sweep GC freed 25358(1275KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.715ms total 126.249ms
,W/asset   ( 8342): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8342): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8342): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8342): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,V/JNIHelp ( 8308): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PackageBroadcastService( 1958): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1958): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/UpdateIcingCorporaServi( 8264): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 1958): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8372 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/System  ( 8308): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8308): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 8372): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:34000 mC
,I/UpdateIcingCorporaServi( 8264): UpdateCorporaTask done [took 193 ms] updated apps [took 193 ms] 
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1958): Explicit concurrent mark sweep GC freed 51745(3MB) AllocSpace objects, 17(272KB) LOS objects, 25% free, 14MB/19MB, paused 1.213ms total 115.352ms
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8399 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 8205:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_8205/cgroup.procs: No such file or directory
,D/Finsky  ( 8399): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8399): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8399): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8399): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8399): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8399): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 8399): Skipping gmscore version check
,D/Finsky  ( 8399): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8399): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  880): Killing 8292:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_8292/cgroup.procs: No such file or directory
,W/ContextImpl( 1471): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/Icing   ( 1958): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1958): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 8342:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_8342/cgroup.procs: No such file or directory
,D/TaskPersister(  880): removeObsoleteFile: deleting file=5_task.xml
,V/AlarmManager(  880): send {ac70a43, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  880): done {ac70a43, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [7ms]
,I/ActivityManager(  880): Killing 8264:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_8264/cgroup.procs: No such file or directory
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=307, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311307, SEQNUM=4581, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2119, POWER_SUPPLY_CHARGE_COUNTER=-146, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2732): Disconnected process message: 10, size: 0
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:34000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=292, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311079, SEQNUM=4583, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=5954, POWER_SUPPLY_CHARGE_COUNTER=-110, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2732): Disconnected process message: 10, size: 0
,V/AlarmManager(  880): send {2eb1f8c0, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  880): done {2eb1f8c0, *walarm*:com.google.android.intent.action.SEND_IDLE} [77ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/ClearcutLoggerApiImpl( 1704): disconnect managed GoogleApiClient
,V/AlarmManager(  880): send {1f45334e, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  880): send {1199f9, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  880): done {1f45334e, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [18ms]
V/AlarmManager(  880): done {1199f9, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [19ms]
,I/CheckinService( 1958): Checkin interval check for package: unspecified last checkin: 1453034407803 min interval config: 0 actual interval: 44369
,I/CheckinService( 1958): Checking schedule, now: 1453034452187 next: 1453034437767
I/CheckinService( 1958): active receiver: enabled
,I/CheckinService( 1958): Preparing to send checkin request
I/EventLogService( 1958): Accumulating logs since 1453034403522
,I/CheckinRequestBuilder( 1958): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1958): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8472 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8472): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8472): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8472): VM with version 2.1.0 has multidex support
I/MultiDex( 8472): install
I/MultiDex( 8472): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8472): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8472): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8472): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8472): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1704): callingUid 10016, callindPid: 1704
,E/MDM     ( 1704): [195] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1704): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1958): Restart initialization of location
V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 8472): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8472): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 1704): Explicit concurrent mark sweep GC freed 106672(5MB) AllocSpace objects, 24(384KB) LOS objects, 40% free, 15MB/25MB, paused 1.226ms total 128.625ms
,W/GCoreFlp( 1704): No location to return for getLastLocation()
,W/FusedLocationProvider( 1704): location=null
,D/NativeLibraryUtils( 8472): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  294): Instantiating CDM.
I/WVCdm   (  294): CdmEngine::OpenSession
,I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
,D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f64000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f64000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb1355960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8fc5268, dataLength=8
,D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8fc7350, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb90c1a40, idLength=0xbeaca2b0
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=4252581826
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8fc7350
D/DrmWidevineDash(  294): message_length=1591, signature=0xb8f91150, signature_length=3198984852
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  294): CdmEngine::CloseSession
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
,D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f64000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f64000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb543f960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8f91228, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8ff7148, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb90c1a60, idLength=0xbeaca2b0
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=112088195
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8fc7350
D/DrmWidevineDash(  294): message_length=1625, signature=0xb8ffaec0, signature_length=3198984852
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8523): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8523): dex2oat took 74.728ms (threads: 4)
,I/Adreno-EGL( 8472): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8472): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8472): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8472): Local Branch: 
I/Adreno-EGL( 8472): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8472): Local Patches: NONE
I/Adreno-EGL( 8472): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8472): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8472): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8472): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8472): Local Branch: 
I/Adreno-EGL( 8472): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8472): Local Patches: NONE
I/Adreno-EGL( 8472): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8472): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8472): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8472): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8472): Local Branch: 
I/Adreno-EGL( 8472): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8472): Local Patches: NONE
I/Adreno-EGL( 8472): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8472): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8472): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8472): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8472): Local Branch: 
I/Adreno-EGL( 8472): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8472): Local Patches: NONE
I/Adreno-EGL( 8472): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 1958): Classify the device as Phone.
,I/CheckinTask( 1958): Sending checkin request (9514 bytes)
,I/CheckinRequestBuilder( 1958): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1958): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1958): Classify the device as Phone.
,I/CheckinTask( 1958): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1958): Checking schedule, now: 1453034455359 next: 1453635592349
I/CheckinService( 1958): active receiver: disabled
,D/CheckinService( 1958): Recording last checkin time for package unspecified as 1453034455373
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8543 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8543): Register our PhoneStateListener
,V/SetupWizard( 8543): Connected to Gservices successfully
,D/GCM     ( 1704): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     (  880): Explicit concurrent mark sweep GC freed 18881(978KB) AllocSpace objects, 6(219KB) LOS objects, 33% free, 21MB/32MB, paused 1.602ms total 131.401ms
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  880): Killing 8372:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  880): Killing 8165:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_8372/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_8165/cgroup.procs: No such file or directory
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8565 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 23.746ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.421ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.932ms
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@36669f41
,I/GCoreNlp( 1704): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1570): Deferring update until onResume
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8603 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8625 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 8399:com.android.vending/u0a32 (adj 15): empty #7
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311711, SEQNUM=4599, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=5449, POWER_SUPPLY_CHARGE_COUNTER=-75, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2732): Disconnected process message: 10, size: 0
W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_8399/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2732): Disconnected process message: 10, size: 0
,W/ResourcesManager( 8308): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8308): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8625): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8648 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 8543:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_8543/cgroup.procs: No such file or directory
,W/asset   ( 8648): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 8648): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8648): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8648): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 1958): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1958): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
I/UpdateIcingCorporaServi( 8565): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 1958): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8675 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8675): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8565): UpdateCorporaTask done [took 142 ms] updated apps [took 142 ms] 
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8704 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 8472:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_8472/cgroup.procs: No such file or directory
,D/Finsky  ( 8704): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8704): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8704): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8704): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8704): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8704): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8704): Skipping gmscore version check
,D/Finsky  ( 8704): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8704): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Killing 8603:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_8603/cgroup.procs: No such file or directory
,I/Icing   ( 1958): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1958): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 8648:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_8648/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  880): Killing 8308:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_8308/cgroup.procs: No such file or directory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1413): run()
,I/Keyboard.Facilitator( 1413): flushDynamicLanguageModels()
,I/ConfigService( 1704): onCreate
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ConfigService( 1704): onDestroy
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=279, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310880, SEQNUM=4605, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=4338, POWER_SUPPLY_CHARGE_COUNTER=8, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2732): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310556, SEQNUM=4609, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=4338, POWER_SUPPLY_CHARGE_COUNTER=23, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2732): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 7129): --= Surplus to requirements =--
I/jxcore-log( 7129): 
I/jxcore-log( 7129): ****TEST TOOK:  ms ****
I/jxcore-log( 7129): 
I/jxcore-log( 7129): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7129): 
,D/AndroidRuntime( 8772): 
D/AndroidRuntime( 8772): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8772): CheckJNI is OFF
,D/AndroidRuntime( 8772): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  880): Force stopping com.test.thalitest appid=10456 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 7129:com.test.thalitest/u0a456 (adj 9): stop com.test.thalitest
,W/PackageSettings(  880): Skipping PackageSetting{f36067b com.example.hello/10440} due to missing metadata
,I/WindowState(  880): WIN DEATH: Window{35b55bed u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  880): Client connection lost with reason: 4
,I/ActivityManager(  880):   Force finishing activity ActivityRecord{cc6dad1 u0 com.test.thalitest/.MainActivity t6}
,W/ActivityManager(  880): Spurious death for ProcessRecord{252673b8 7129:com.test.thalitest/u0a456}, curProc for 7129: null
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10456 user=0: pkg removed
,I/ActivityManager(  880):   Force finishing activity ActivityRecord{cc6dad1 u0 com.test.thalitest/.MainActivity t6 f}
W/ActivityManager(  880): Duplicate finish request for ActivityRecord{cc6dad1 u0 com.test.thalitest/.MainActivity t6 f}
,I/art     ( 3278): Explicit concurrent mark sweep GC freed 9150(2044KB) AllocSpace objects, 11(178KB) LOS objects, 40% free, 7MB/12MB, paused 805us total 41.362ms
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1704): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1413): resetDictionaries() : en_US
,I/art     ( 1570): Explicit concurrent mark sweep GC freed 5275(319KB) AllocSpace objects, 7(333KB) LOS objects, 24% free, 13MB/17MB, paused 515us total 113.572ms
,I/Keyboard.Facilitator.DecoderInitializer( 1413): run()
,I/Decoder ( 1413): createOrResetDecoder
,D/VoicemailCleanupService( 8625): Cleaning up data for package: com.test.thalitest
,I/art     ( 1958): Explicit concurrent mark sweep GC freed 17447(1029KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 14MB/19MB, paused 1.039ms total 149.352ms
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8802 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  880): Explicit concurrent mark sweep GC freed 24058(1561KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/32MB, paused 7.581ms total 151.004ms
,I/ConfigService( 1704): onCreate
,I/art     (  880): WaitForGcToComplete blocked for 56.575ms for cause Explicit
,W/asset   ( 8802): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8802): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8802): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8802): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1413): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1413): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1413): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1413): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1413): run()
I/StatsUtilsManager( 1413): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1413): shouldRecordStats() = Too Soon
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8827 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  880): removeObsoleteFile: deleting file=6_task.xml
,D/TaskPersister(  880): removeObsoleteFile: deleting file=6_task_thumbnail.png
,I/ActivityManager(  880): Killing 8565:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/Launcher( 1570): Deferring update until onResume
,I/art     (  880): Explicit concurrent mark sweep GC freed 7648(413KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/32MB, paused 1.778ms total 212.007ms
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_8565/cgroup.procs: No such file or directory
,W/ContextImpl( 8827): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 1958): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1958): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1958): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1958): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1958): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1958): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1958): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1704): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1704): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1958): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1958): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1958): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1958): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1958): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1958): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/AndroidRuntime( 8772): Shutting down VM
,D/gH_CompatibleDatabase( 1958): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1958): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1958): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1958): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1958): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1958): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1958): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8850 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/Icing   ( 1958): doRemovePackageData com.test.thalitest
,W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/ActivityManager(  880): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8876 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8903 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 8850): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  880): Killing 8675:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_8675/cgroup.procs: No such file or directory
,E/SQLiteLog( 8850): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/AppDataSearchHelper( 8850): Exception thrown from onTableChanged
E/AppDataSearchHelper( 8850): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 8850): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
E/AppDataSearchHelper( 8850): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
E/AppDataSearchHelper( 8850): 	at com.google.android.search.core.icingsync.d.j(InternalIcingCorporaProvider.java:709)
E/AppDataSearchHelper( 8850): 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
E/AppDataSearchHelper( 8850): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
E/AppDataSearchHelper( 8850): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AppDataSearchHelper( 8850): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AppDataSearchHelper( 8850): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AppDataSearchHelper( 8850): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AppDataSearchHelper( 8850): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AppDataSearchHelper( 8850): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AppDataSearchHelper( 8850): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AppDataSearchHelper( 8850): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AppDataSearchHelper( 8850): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchHelper( 8850): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchHelper( 8850): 	at android.os.Looper.loop(Looper.java:135)
E/AppDataSearchHelper( 8850): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchHelper( 8850): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 8850): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AppDataSearchHelper( 8850): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AppDataSearchHelper( 8850): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AppDataSearchHelper( 8850): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AppDataSearchHelper( 8850): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AppDataSearchHelper( 8850): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AppDataSearchHelper( 8850): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
E/AppDataSearchHelper( 8850): 	at com.google.android.gms.appdatasearch.a.a$1.JA(AppDataSearchDbOpenHelperBase.java:246)
E/AppDataSearchHelper( 8850): 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:227)
E/AppDataSearchHelper( 8850): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
E/AppDataSearchHelper( 8850): 	... 16 more
W/AppDataSearchHelper( 8850): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi( 8850): UpdateCorporaTask done [took 285 ms] updated apps [took 285 ms] 
,I/ActivityManager(  880): Killing 7032:com.google.process.gapps/u0a16 (adj 15): empty #7
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
