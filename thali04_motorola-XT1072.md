#### Test 56151093914d164_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
D/AndroidRuntime( 6627): 
D/AndroidRuntime( 6627): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6627): CheckJNI is OFF
D/AndroidRuntime( 6627): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  277): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (178 us)
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 6627): Shutting down VM
I/ActivityManager(  883): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6646 uid=10457 gids={50457, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6646): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6646): Time to load native libraries: 2 ms (timestamps 7603-7605)
,I/LibraryLoader( 6646): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6646): Binding Chromium to main looper Looper (main, tid 1) {f6951de}
,I/LibraryLoader( 6646): Expected native library version number "",actual native library version number ""
,I/chromium( 6646): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/SFPerfTracer(  277):      triggers: (rate: 11:569) (compose: 0:1) (post: 0:1) (render: 0:2) (18:865 frames) (19:968)
D/SFPerfTracer(  277):        layers: (4:12) (FocusedStackFrame (0xb827efa8): 1:11)* (DimLayer (0xb826b450): 1:6) (com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (0xb82016f8): 0:38)- (StatusBar (0xb8295760): 0:160) (NavigationBar (0xb82969f0): 0:25) (com.android.systemui.ImageWallpaper (0xb8299610): 0:32)* (Starting com.motorola.ccc.ota (0xb82a0f18): 0:28)- (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb82a2c30): 18:49) (Starting com.test.thalitest (0xb82016f8): 1:3)* 
,I/BrowserStartupController( 6646): Initializing chromium process, singleProcess=true
,W/art     ( 6646): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6646): ApplicationContext is null in ApplicationStatus
,W/chromium( 6646): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6646): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6646): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6646): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6646): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6646): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6646): Local Branch: 
I/Adreno-EGL( 6646): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6646): Local Patches: NONE
I/Adreno-EGL( 6646): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b08225:true
,W/art     ( 6646): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6646): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6646): CordovaWebView is running on device made by: motorola
,W/art     ( 6646): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6646): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6646): Render dirty regions requested: true
,D/Atlas   ( 6646): Validating map...
,W/chromium( 6646): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6646): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6646): Enabling debug mode 0
,I/Keyboard.Facilitator( 1416): onFinishInput()
,I/LaunchCheckinHandler(  883): Displayed com.test.thalitest/.MainActivity,cp,ca,1065
I/ActivityManager(  883): Displayed com.test.thalitest/.MainActivity: +1s65ms
,E/Adreno-ES20( 6646): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6646): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6646): Cannot call determinedVisibility() - never saw a connection for the pid: 6646
,D/JsMessageQueue( 6646): Set native->JS mode to OnlineEventsBridgeMode
,E/Adreno-ES20( 6646): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6646): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
D/jxcore_app_log( 6646): JniHelper::setJavaVM(0xb7980310), pthread_self() = -1211133840
D/JX-Cordova( 6646): jxcore cordova android initializing
I/SFPerfTracer(  277):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (19:278 vsyncs) (21:1039)
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/TaskPersister(  883): removeObsoleteFile: deleting file=5_task_thumbnail.png
,W/jxcore-log( 6646): Initializing JXcore engine
W/jxcore-log( 6646): JXcore engine is ready
,W/jxcore-log( 6646): Starting JXcore engine
,W/.test.thalitest( 6646): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10457 path="socket:[9785]" dev="sockfs" ino=9785 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6646): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10457 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6646): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10457 path="socket:[6602]" dev="sockfs" ino=6602 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6646): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10457 path="socket:[29429]" dev="sockfs" ino=29429 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6646): Platform android
W/jxcore-log( 6646): 
,W/jxcore-log( 6646): Process ARCH arm
W/jxcore-log( 6646): 
,I/jxcore-log( 6646): JXcore Cordova bridge is ready!
I/jxcore-log( 6646): 
W/jxcore-log( 6646): JXcore engine is started
,I/chromium( 6646): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 6646): Skipped 184 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 6646): Toggling radios to true
I/jxcore-log( 6646): 
,D/BluetoothAdapter( 6646): enable(): BT is already enabled..!
,D/WifiService(  883): New client listening to asynchronous messages
,D/WifiService(  883): setWifiEnabled: true pid=6646, uid=10457
,E/WifiService(  883): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6646): Radios toggled
I/jxcore-log( 6646): 
I/jxcore-log( 6646): My device name is: motorola-XT1072
I/jxcore-log( 6646): 
,I/wpa_supplicant( 1437): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  290): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  290):  STA Disconnected !!
,D/TCMD    (  479): NL - Read 1004 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 68 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 68 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): get_property_value, Enter
I/MDMCTBK (  290): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  290): get_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  290): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  290): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
E/MDMCTBK (  290): MdmCutbackHndler,Airplane Mode Enabled !! =1
I/wpa_supplicant( 1437): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
I/wpa_supplicant( 1437): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  290): Event received = CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  290): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  883): WifiStateMachine: Leaving Connected state
D/Tethering(  883): InitialState.processMessage what=4
W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
D/Tethering(  883):  0
,D/Tethering(  883): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  883): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1437): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  288): Clearing all IP addresses on wlan0
,D/TCMD    (  479): NL - Read 60 bytes from update socket.
D/TCMD    (  479): NL - ignore NL message, type = 21
D/TCMD    (  479): Listening for incoming client connection request
,V/NativeCrypto( 1715): Read error: ssl=0xb7c7ae50: I/O error during system call, Connection timed out
,V/NativeCrypto( 1715): SSL shutdown failed: ssl=0xb7c7ae50: I/O error during system call, Broken pipe
,D/ConnectivityService(  883): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): ValidatedState{ when=-2ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-2ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info<unknown ssid>
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  883): connected time updated 132360
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  883): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6735 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/ConnectivityService(  883): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  883): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  883): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1292): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1521): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1292): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/wpa_supplicant( 1437): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  883): Start Disconnecting Watchdog 1
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1521): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1292): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/wpa_supplicant( 1437): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  883): ConnectModeState: Network connection lost 
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/ConnectivityService(  883): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1437): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  288): Clearing all IP addresses on wlan0
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  883): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
,D/ChimeraCfgMgr( 6366): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6366): Module APK com.google.android.play.games already loaded
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6735): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/GamesSyncServiceMain( 6366): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 6366): Failed to execute periodic sync, missing client context - aborting
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6762 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/AlarmManager(  883): send {1ae14a44, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,I/ActivityManager(  883): Killing 6487:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  290): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  290): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1437): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  290): Event received = Trying to associate with
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
,E/wpa_supplicant( 1437): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/TCMD    (  479): NL - Read 56 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
E/WifiStateMachine(  883): [1,453,043,053,270 ms] noteScanEnd no scan source
D/WifiMonitor(  883): didn't find BSSID Trying to associate with SSID 'NG700'
,E/WifiStateMachine(  883): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1c2a49b2 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info0x
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_6487/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6762): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  479): NL - Read 312 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 192 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 68 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/TCMD    (  479): NL - Read 1004 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  0
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
I/wpa_supplicant( 1437): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  290): Event received = Associated with c0:ff:d4
D/TCMD    (  479): NL - Read 80 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 80 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/TCMD    (  479): NL - Read 68 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
,D/Tethering(  883): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1437): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1437): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  479): NL - Read 1004 bytes from update socket.
D/TCMD    (  479): NL - message type is RTM_NEWLINK
D/TCMD    (  479): Listening for incoming client connection request
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  290): Event received = WPA: Key negotiation com
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  290): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  290):  STA Connected !!
E/MDMCTBK (  290): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  290): get_freq !!, resp=2412
I/MDMCTBK (  290): get_freq !!, Strip data
I/MDMCTBK (  290): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
,I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): get_property_value, Enter
I/MDMCTBK (  290): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  290): get_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  290): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  290): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
I/MDMCTBK (  290): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  290): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  290): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): get_property_value, Enter
I/MDMCTBK (  290): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  290): get_property_value, Exit
I/MDMCTBK (  290): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1215877720
I/MDMCTBK (  290): return from set_get_from_wpa_supplicant
I/MDMCTBK (  290): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  290): set_property_value, Enter
I/MDMCTBK (  290): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  290): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  290): set_property_value, Exit
E/MDMCTBK (  290): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  290): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  290): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  290): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  290): , reply_len: 3, ret: 0
E/MDMCTBK (  290): MdmCutbackHndler, resp=OK
E/MDMCTBK (  290): 
D/MDMCTBK (  290): wifi_set_tx_pwr: Exit
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  883): Network connection established
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  883): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  883): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine(  883): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  288): Setting iface cfg
E/WifiStateMachine(  883): Start Dhcp Watchdog 2
,E/WifiStateMachine(  883): calculateWifiScore() report new score 60
,D/ConnectivityService(  883): updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend false
,E/wpa_supplicant( 1437): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  883): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1437): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@19b8a518 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@19b8a518 target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel_SMS( 6762): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6762): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6762): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6762): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6762): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6762): MmsConfig.loadFromResources
,E/Babel_SMS( 6762): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6762): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6762): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6762): startup - clean
,I/Babel   ( 6762): deleted: false for 0
,E/DHCPCD  ( 6799): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
I/DHCPCD  ( 6799): version 5.5.6 starting
E/DHCPCD  ( 6799): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6799): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6799): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 6799): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6799): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6799): wlan0: sending REQUEST (xid 0xdbafc221), next in 3.02 seconds
,V/AlarmManager(  883): done {1ae14a44, *alarm*:com.android.server.WifiManager.action.START_SCAN} [713ms]
,W/VideoCapabilities( 6762): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6762): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6762): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6762): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6762): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6762): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6762): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6762): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Killing 6064:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_6064/cgroup.procs: No such file or directory
,I/vclib   ( 6762): onServiceConnected
W/Babel   ( 6762): Attempted to change video mute state without an active call.
,I/DHCPCD  ( 6799): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6799): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6799): wlan0: adding IP address 192.168.1.123/24
D/TCMD    (  479): NL - Read 60 bytes from update socket.
D/TCMD    (  479): NL - ignore NL message, type = 20
D/TCMD    (  479): Listening for incoming client connection request
D/DHCPCD  ( 6799): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6799): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6799): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/DHCPCD  ( 6799): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  883): WifiStateMachine DHCP successful
E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  883): Calling ARP set with IP = 192.168.1.123
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  883): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  883): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/ConnectivityService(  883): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  883): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  883): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/ConnectivityService(  883): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883):    accepting network in place of null
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  883): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,E/WifiStateMachine(  883): ConnectedState Enter  mScreenOn=true scanperiod=20000
E/WifiStateMachine(  883): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=138.00 rxSuccessRate=136.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  883): WifiStateMachine CMD_START_SCAN with age=35017 interval=20000 maxinterval=300000
E/WifiStateMachine(  883): WifiStateMachine CMD_START_SCAN try full band scan age=35017 interval=20000 maxinterval=300000
E/WifiStateMachine(  883): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  883): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=138.00 rx=136.00
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1521): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1292): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,D/ConnectivityService(  883): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1292): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 15:04:15 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453043055535], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453043055516]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Validated
,D/ConnectivityService(  883): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1292): CM callback handler got msg 524290
I/ModemStatsDSDetect( 1521): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1292): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1521): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1521): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1521): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1292): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1292): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,V/AlarmManager(  883): send {1ae14a44, *alarm*:com.android.server.WifiManager.action.START_SCAN}
,V/AlarmManager(  883): done {1ae14a44, *alarm*:com.android.server.WifiManager.action.START_SCAN} [1ms]
E/WifiStateMachine(  883): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=138.00 rxSuccessRate=136.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  883): WifiStateMachine CMD_START_SCAN with age=35218 interval=20000 maxinterval=300000
E/WifiStateMachine(  883): WifiStateMachine CMD_START_SCAN try full band scan age=35218 interval=20000 maxinterval=300000
E/WifiStateMachine(  883): WifiStateMachine CMD_START_SCAN prevent full band scan due to pkt rate
E/WifiStateMachine(  883): WifiStateMachine CMD_START_SCAN source -2 ...and ignore scans tx=138.00 rx=136.00
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1475): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6863 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1475): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1475): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2602): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2602): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2602): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2602): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2602): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2602): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2602): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2602): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2602): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2602): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2602): [debug] > CusSM.onRadioDown
,I/MusicStore( 6863): Database version: 120
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1292): CM callback handler got msg 524295
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6863): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/ConnectivityService(  883): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6863): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  276): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6863): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1292): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020132=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully Activity=0x00000000=( none ) Accessibility="Wifi signal full."
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 6863): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6863): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6863): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6863): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6863): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2cae3c5a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6863): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6863): GMSCore installation verified
,I/ConfigStore( 6863): Config Database version: 1
,I/MediaRouter( 6863): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6863): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6863): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6863): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6897 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6863): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6863): Using platform SSLCertificateSocketFactory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  883): Killing 6416:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_6416/cgroup.procs: No such file or directory
,V/Mms     ( 6897): mnc/mcc: 
V/Mms     ( 6897): tag: int value: recipientLimit - 20
,V/Mms     ( 6897): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6897): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6897): tag: int value: maxSubjectLength - 80
V/Mms     ( 6897): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6897): tag: bool value: enableGroupMms - false
V/Mms     ( 6897):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6897): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6924 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/jxcore-log( 6646): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6646): 
,I/ActivityManager(  883): Killing 6516:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6924): Register our PhoneStateListener
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_6516/cgroup.procs: No such file or directory
,I/art     (  883): Explicit concurrent mark sweep GC freed 51866(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/31MB, paused 1.657ms total 134.182ms
,D/MobileConnectivityChangeReceiver( 6924): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6924): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 6762:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_6762/cgroup.procs: No such file or directory
,I/CheckinService( 6366): Checkin interval check for package: unspecified last checkin: 1453042928523 min interval config: 0 actual interval: 129204
,I/CheckinService( 6366): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6366): SYNC; picasa accounts
,D/NetworkLogImpl( 6366): Loaded NetworkSpeedPredictor
,I/CheckinService( 6366): Checking schedule, now: 1453043057771 next: 1453042958279
I/CheckinService( 6366): active receiver: enabled
,I/iu.Environment( 6366): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6366): num queued entries: 0
,I/iu.UploadsManager( 6366): num updated entries: 0
,I/iu.SyncManager( 6366): NEXT; no task
,I/CheckinService( 6366): Preparing to send checkin request
,I/EventLogService( 6366): Accumulating logs since 1453042921345
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6951 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 6646): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6646): 
I/jxcore-log( 6646): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6646): 
,I/CheckinRequestBuilder( 6366): Checkin reason type: 8 attempt count: 1
,D/WifiService(  883): New client listening to asynchronous messages
,E/ActivityThread( 6366): Failed to find provider info for com.google.android.wearable.settings
,I/jxcore-log( 6646): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6646): 
,I/jxcore-log( 6646): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6646): 
,I/jxcore-log( 6646): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6646): 
,I/jxcore-log( 6646): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6646): 
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6977 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2602): now: 208203 ,futureTime: 9223372036854775807
D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2602): now: 208203 ,futureTime: 9223372036854775807
D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2602): now: 208204 ,futureTime: 9223372036854775807
D/OtaApp  ( 2602): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1475): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/OtaApp  ( 2602): [debug] > PollingManagerService, now: 208208 ,futureTime: 10818010
D/OtaApp  ( 2602): [debug] > Polling alarm set to expire at: 10818010 Current Time: 208209
,D/Central_PollingManager( 1475): now: 208208 ,futureTime: 86473509
D/Central_PollingManager( 1475): Polling alarm set to expire at: 86473509 Current Time: 208210
,I/NetworkMonitor( 6863): type=WIFI subType= reason=null isConnected=true
,D/MMApiProvisionService( 2602): isDeviceProvisioned: deviceId = 2072049230914535424
,W/ResourcesManager( 6977): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 1475): Explicit concurrent mark sweep GC freed 6169(298KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 665us total 31.240ms
,D/CCE     ( 2602): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2602): createDeviceIdOrLogin update_device
,I/ActivityManager(  883): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6995 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 22.557ms
,D/Checkin ( 2602): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2602): Not proxy app, so login/provision not allowed
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.803ms
,D/MMApiProvisionService( 2602): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2602): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2602): createDeviceIdOrLogin update_device
D/Checkin ( 2602): publish the event [tag = MOT_CCE event name = LOG]
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 21.489ms
D/MMApiProvisionService( 2602): isDeviceProvisioned: deviceId = 2072049230914535424
,W/ResourcesManager( 6995): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/MMApiProvisionService( 2602): set mOutstandingReq to true.
I/ Nonce  ( 2602):  Nonce getNonce 
I/ Nonce  ( 2602):  Nonce Request 
I/ Nonce  ( 2602):  Nonce execute Request 
W/ResourcesManager( 6995): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/MMApiWebService( 2602): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
D/MMApiProvisionService( 2602): isDeviceProvisioned: deviceId = 2072049230914535424
,I/MultiDex( 6995): VM with version 2.1.0 has multidex support
I/MultiDex( 6995): install
I/MultiDex( 6995): VM has multidex support, MultiDex support library is disabled.
,D/CCE     ( 2602): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2602): createDeviceIdOrLogin update_device
,D/Checkin ( 2602): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2602): Not proxy app, so login/provision not allowed
,V/JNIHelp ( 6995): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/OtaApp  ( 2602): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2602): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2602): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2602): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2602): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2602): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2602): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2602): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2602): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/ActivityThread( 6995): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6995): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a545c33: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6995): Installed default security provider GmsCore_OpenSSL
,I/Babel_SMS( 6977): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6977): MmsConfig.loadMmsSettings
I/Babel_SMS( 6977): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6977): MmsConfig.loadFromDatabase
,I/art     ( 6995): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6995): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/Babel_SMS( 6977): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6977): MmsConfig.loadFromResources
,E/Babel_SMS( 6977): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6977): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/NativeLibraryUtils( 6995): Install completed successfully. count=14 extracted=0
,I/art     ( 2602): Explicit concurrent mark sweep GC freed 13848(796KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 11MB/19MB, paused 55.360ms total 358.686ms
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/Settings( 6977): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/jxcore-log( 6646): Test app app.js loaded
I/jxcore-log( 6646): 
W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
I/Choreographer( 6646): Skipped 387 frames!  The application may be doing too much work on its main thread.
,I/Babel_Crash( 6977): startup - clean
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,I/chromium( 6646): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Babel   ( 6977): deleted: false for 0
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe8000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe8000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xbe8224e0
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8d46c20, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8e326c8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8e8b848, idLength=0xb54c3730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1,
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=1977056271
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8db5230
,D/DrmWidevineDash(  295): message_length=1591, signature=0xb8db5870, signature_length=3041670932
,D/MMApiWebService( 2602): generating token using payload instead of using session token
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7026 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ Nonce  ( 2602):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2602): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2602): publish the event [tag = MOT_CCE event name = LOG]
,W/VideoCapabilities( 6977): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6977): Unsupported mime audio/amr-wb-plus
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
W/VideoCapabilities( 6977): Unsupported mime video/mpeg2
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/VideoCapabilities( 6977): Unsupported profile 4 for video/mp4v-es
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/VideoCapabilities( 6977): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6977): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6977): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6977): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6977): onServiceConnected
W/Babel   ( 6977): Attempted to change video mute state without an active call.
,I/Babel   ( 6977): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  883): Killing 6735:com.motorola.context/u0a8 (adj 15): empty #7
,I/dex2oat ( 7048): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  883): failed to open /acct/uid_10008/pid_6735/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/dex2oat ( 7048): dex2oat took 134.711ms (threads: 4)
,I/Adreno-EGL( 6995): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6995): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6995): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6995): Local Branch: 
I/Adreno-EGL( 6995): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6995): Local Patches: NONE
I/Adreno-EGL( 6995): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7026): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7026): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7026): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7026): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7026): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7026):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7026):   adb logcat -s GAv4
,W/GAv4    ( 7026): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7026): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 6995): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6995): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6995): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6995): Local Branch: 
I/Adreno-EGL( 6995): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6995): Local Patches: NONE
I/Adreno-EGL( 6995): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
W/GAv4    ( 7026): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 6995): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6995): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6995): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6995): Local Branch: 
I/Adreno-EGL( 6995): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6995): Local Patches: NONE
I/Adreno-EGL( 6995): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6995): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6995): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6995): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6995): Local Branch: 
I/Adreno-EGL( 6995): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6995): Local Patches: NONE
I/Adreno-EGL( 6995): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 7026): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7026): Time to load native libraries: 2 ms (timestamps 9876-9878)
I/LibraryLoader( 7026): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7026): Binding Chromium to main looper Looper (main, tid 1) {2f6cb823}
,I/LibraryLoader( 7026): Expected native library version number "",actual native library version number ""
,I/chromium( 7026): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7026): Initializing chromium process, singleProcess=true
,W/art     ( 7026): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7026): ApplicationContext is null in ApplicationStatus
,W/chromium( 7026): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7026): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7026): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7026): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7026): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7026): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7026): Local Branch: 
I/Adreno-EGL( 7026): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7026): Local Patches: NONE
I/Adreno-EGL( 7026): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ Nonce  ( 2602):  Nonce Reponse 
D/        ( 2602): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"8c5c0d52-d9b1-4234-8cfb-9c19deb2d333"}
D/MMApiWSBase( 2602): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2602):  Nonce Handle Reponse 
D/MMApiProvisionService( 2602): mOutstandingReq set to false
,W/AudioManagerAndroid( 7026): Requires BLUETOOTH permission
,I/art     (  883): Explicit concurrent mark sweep GC freed 13784(685KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/31MB, paused 1.522ms total 114.242ms
,I/NSApplication( 7026): Starting up...
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/MMApiProvisionService( 2602):  pTime 1453032756427 sExp 172742 cTime 1453043060382 tTime 1453205498427
D/MMApiProvisionService( 2602):  No login Required 
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7102 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6863:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe8000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe8000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xbe8224e0
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8d58d70, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8d8e9e8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8e8b868, idLength=0xb13d8730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=3633159406
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8db3920
D/DrmWidevineDash(  295): message_length=1626, signature=0xb8db3f80, signature_length=2973599508
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_6863/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7121 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6897:com.android.mms/u0a23 (adj 15): empty #7
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,W/DataUsage( 2602): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2602): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_6897/cgroup.procs: No such file or directory
,W/ResourcesManager( 7121): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 6366): Classify the device as Phone.
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7146 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7169 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6951:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ContactLocale( 7146): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 6924:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_6951/cgroup.procs: No such file or directory
,I/CheckinTask( 6366): Sending checkin request (9508 bytes)
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_6924/cgroup.procs: No such file or directory
,I/MusicStore( 7169): Database version: 120
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7169): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7169): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7169): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7169): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7169): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7169): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7169): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7169): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2cae3c5a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7169): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7169): GMSCore installation verified
,I/ConfigStore( 7169): Config Database version: 1
,I/art     ( 6184): Explicit concurrent mark sweep GC freed 1512(53KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 421us total 29.900ms
,I/MediaRouter( 7169): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7169): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7169): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7169): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7202 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7169): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7169): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  883): Killing 6977:com.google.android.talk/u0a70 (adj 15): empty #7
,I/CheckinRequestBuilder( 6366): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_6977/cgroup.procs: No such file or directory
,E/ActivityThread( 6366): Failed to find provider info for com.google.android.wearable.settings
,V/Mms     ( 7202): mnc/mcc: 
,V/Mms     ( 7202): tag: int value: recipientLimit - 20
V/Mms     ( 7202): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7202): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7202): tag: int value: maxSubjectLength - 80
V/Mms     ( 7202): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7202): tag: bool value: enableGroupMms - false
V/Mms     ( 7202):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7202): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7237 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7026:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_7026/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 6366): Classify the device as Phone.
,D/PhoneMonitor( 7237): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7237): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7237): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 7102:com.android.chrome/u0a52 (adj 15): empty #7
,I/CheckinTask( 6366): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6366): Checking schedule, now: 1453043062159 next: 1453644199127
W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_7102/cgroup.procs: No such file or directory
I/CheckinService( 6366): active receiver: disabled
,D/CheckinService( 6366): Recording last checkin time for package unspecified as 1453043062174
,I/CheckinService( 6366): Checkin interval check for package: unspecified last checkin: 1453043062174 min interval config: 0 actual interval: 5
,I/CheckinService( 6366): Checking schedule, now: 1453043062186 next: 1453043092127
I/CheckinService( 6366): active receiver: disabled
,I/ActivityManager(  883): Killing 7121:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  883): Killing 7146:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7121/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_7146/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7259 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1292): onReceive: WifiManager.RSSI_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7282 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7169:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_7169/cgroup.procs: No such file or directory
,V/AlarmManager(  883): send {388d2f52, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,W/ResourcesManager( 7282): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  883): Explicit concurrent mark sweep GC freed 9607(481KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.513ms total 110.394ms
,I/Babel_SMS( 7282): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7282): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7282): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7282): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7282): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7282): MmsConfig.loadFromResources
E/Babel_SMS( 7282): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7282): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7282): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7282): startup - clean
,I/Babel   ( 7282): deleted: false for 0
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7313 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7282): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7282): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7282): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7282): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7282): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7282): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7282): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7282): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7282): onServiceConnected
,W/Babel   ( 7282): Attempted to change video mute state without an active call.
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
I/Babel   ( 7282): connection state changed from UNKNOWN to CONNECTED
,W/ContextImpl( 7313): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager(  883): Killing 7202:com.android.mms/u0a23 (adj 13): empty #7
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7313): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7313): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7313): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7313): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7313):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7313):   adb logcat -s GAv4
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_7202/cgroup.procs: No such file or directory
,W/GAv4    ( 7313): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7313): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7313): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7313): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7313): Time to load native libraries: 1 ms (timestamps 3484-3485)
I/LibraryLoader( 7313): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7313): Binding Chromium to main looper Looper (main, tid 1) {2f6cb823}
,I/LibraryLoader( 7313): Expected native library version number "",actual native library version number ""
I/chromium( 7313): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7313): Initializing chromium process, singleProcess=true
,W/art     ( 7313): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7313): ApplicationContext is null in ApplicationStatus
,I/PowerManagerService(  883): Nap time (uid 1000)...
I/PowerManagerService(  883): Going to sleep due to screen timeout (uid 1000)...
,W/chromium( 7313): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7313): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7313): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7313): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7313): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7313): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7313): Local Branch: 
I/Adreno-EGL( 7313): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7313): Local Patches: NONE
I/Adreno-EGL( 7313): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL(  883): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  883): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  883): Build Date: 10/28/14 Tue
I/Adreno-EGL(  883): Local Branch: 
I/Adreno-EGL(  883): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  883): Local Patches: NONE
I/Adreno-EGL(  883): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7313): Requires BLUETOOTH permission
,I/NSApplication( 7313): Starting up...
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
,I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7384 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 7237:com.google.android.setupwizard/u0a35 (adj 15): empty #7
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 21.730ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 22.430ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 22.051ms
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7237/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7403 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7259:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7259/cgroup.procs: No such file or directory
,W/ResourcesManager( 7403): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/        (  883): activate, handle: 1598182242, enabled: 0, index 2
,D/        (  883): BstSensorExt: id=1598182242, en=0
D/        (  883): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 235
,D/        (  883): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  883): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  883): Display changed displayId=0
,D/SurfaceFlinger(  277): Set power mode=0, type=0 flinger=0xb8166550
,D/qdhwcomposer(  277): hwc_blank: Blanking display: 0
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7423 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  883): Killing 7313:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/rmt_storage(  287): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7e13820
I/rmt_storage(  287): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  287): wakelock acquired: 1, error no: 42
I/rmt_storage(  287): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1209976696)
,I/ContactLocale( 7423): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/qdhwcomposer(  277): handle_blank_event: dpy:0 panel power state: 0
I/qdhwcomposer(  277): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  277): hwc_blank: Done blanking display: 0
D/SurfaceControl(  883): Excessive delay in setPowerMode(): 322ms
I/SFPerfTracer(  277):      triggers: (rate: 11:570) (compose: 0:1) (post: 0:1) (render: 0:2) (22:948 frames) (23:1080)
D/SFPerfTracer(  277):        layers: (4:12) (FocusedStackFrame (0xb827efa8): 0:14)* (DimLayer (0xb826b450): 0:8)* (StatusBar (0xb8295760): 0:165) (NavigationBar (0xb82969f0): 0:25) (com.android.systemui.ImageWallpaper (0xb8299610): 0:32)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb82a2c30): 0:59)- (Starting com.test.thalitest (0xb82016f8): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb82a18f8): 0:41) (ColorFade (0xb82016f8): 23:25) 
,I/rmt_storage(  287): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  287): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  287): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1209976696) wakelock released: 1, error no: 0
I/rmt_storage(  287): 
,I/rmt_storage(  287): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb7e13820
,I/WindowManager(  883): AOD feature not enabled!
,I/ActivityManager(  883): Killing 7282:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2602): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
I/PowerManagerService(  883): Sleeping (uid 1000)...
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7282/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_7313/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1292): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiStateMachine(  883): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: true
,D/GetNotificationsWS( 2602): bindWebServices(): registering our AIDL callback...
,D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=on
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  883): do suspend false
,I/SundryService( 2602): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2602): ServiceHandler.handleMessage: mWaitCount=0
E/msm8974_platform(  295): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
,D/GetNotificationsWS( 2602): onServiceConnected()
D/GetNotificationsWS( 2602): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2602): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2602): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7454 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/        (  883): activate, handle: 1598182229, enabled: 0, index 0
E/        (  883): <BST> disable accel, orig state: 1
I/        (  883): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/Keyboard.Facilitator( 1416): onFinishInput()
D/WifiStateMachine(  883): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  883): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
D/audio_hw_primary(  295): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  295): platform_set_parameters: exit with code(0)
D/audio_hw_extn(  295): audio_extn_set_anc_parameters: anc_enabled:0
E/audio_a2dp_hw(  295): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$14300 - processMessage - processMsg
E/native  (  883): do suspend true
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7476 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6995:com.google.android.gms.unstable/u0a16 (adj 13): empty #7
,I/MusicStore( 7476): Database version: 120
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_6995/cgroup.procs: No such file or directory
W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7476): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7476): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7476): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7476): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7476): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7476): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7476): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7476): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2cae3c5a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7476): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7476): GMSCore installation verified
,I/ConfigStore( 7476): Config Database version: 1
,I/MediaRouter( 7476): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7476): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7476): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7476): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7510 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7476): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7476): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  883): Killing 7384:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_7384/cgroup.procs: No such file or directory
,V/Mms     ( 7510): mnc/mcc: 
,V/Mms     ( 7510): tag: int value: recipientLimit - 20
V/Mms     ( 7510): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7510): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7510): tag: int value: maxSubjectLength - 80
,V/Mms     ( 7510): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7510): tag: bool value: enableGroupMms - false
V/Mms     ( 7510):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7510): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7536 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7403:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 7536): Register our PhoneStateListener
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7403/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7536): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7536): onReceive CONNECTIVITY_CHANGE networkType=1
,I/art     (  883): Explicit concurrent mark sweep GC freed 17323(872KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.920ms total 123.288ms
,I/CheckinService( 6366): Checkin interval check for package: unspecified last checkin: 1453043062174 min interval config: 0 actual interval: 3952
,I/CheckinService( 6366): Checkin interval check for package: unspecified last checkin: 1453043062174 min interval config: 0 actual interval: 3955
,I/CheckinService( 6366): Checking schedule, now: 1453043066139 next: 1453043092127
I/CheckinService( 6366): active receiver: disabled
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7556 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 6366): Checking schedule, now: 1453043066197 next: 1453043092127
I/CheckinService( 6366): active receiver: disabled
,I/ActivityManager(  883): Killing 7423:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_7423/cgroup.procs: No such file or directory
,W/ResourcesManager( 7556): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7556): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7556): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7556): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7556): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7556): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7556): MmsConfig.loadFromResources
,E/Babel_SMS( 7556): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7556): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7556): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7556): startup - clean
,I/Babel   ( 7556): deleted: false for 0
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7587 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7556): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7556): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7556): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7556): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7556): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7556): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7556): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7556): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7556): onServiceConnected
W/Babel   ( 7556): Attempted to change video mute state without an active call.
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7587): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7587): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7587): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7587):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7587):   adb logcat -s GAv4
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  276): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 7587): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/ContextImpl( 7587): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/Babel   ( 7556): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  883): Killing 7476:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7587): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7587): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7587): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_7476/cgroup.procs: No such file or directory
,I/WebViewFactory( 7587): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7587): Time to load native libraries: 1 ms (timestamps 7078-7079)
,I/LibraryLoader( 7587): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7587): Binding Chromium to main looper Looper (main, tid 1) {2f6cb823}
,I/LibraryLoader( 7587): Expected native library version number "",actual native library version number ""
I/chromium( 7587): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7587): Initializing chromium process, singleProcess=true
,W/art     ( 7587): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7587): ApplicationContext is null in ApplicationStatus
,W/chromium( 7587): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7587): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7587): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7587): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7587): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7587): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7587): Local Branch: 
I/Adreno-EGL( 7587): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7587): Local Patches: NONE
I/Adreno-EGL( 7587): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7587): Requires BLUETOOTH permission
,I/NSApplication( 7587): Starting up...
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7657 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 7510:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_7510/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7676 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7536:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7536/cgroup.procs: No such file or directory
,W/ResourcesManager( 7676): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7699 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,I/art     (  307): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 31.195ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 19.208ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 26.445ms
,I/ActivityManager(  883): Killing 7556:com.google.android.talk/u0a70 (adj 15): empty #7
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ContactLocale( 7699): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 7454:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7556/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2602): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7454/cgroup.procs: No such file or directory
,I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/GetNotificationsWS( 2602): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2602): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2602): onServiceConnected()
D/GetNotificationsWS( 2602): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 2602): ServiceHandler.handleMessage: mWaitCount=0
,I/PushService( 2602): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2602): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@33d370e4
,D/OtaApp  ( 2602): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2602): [debug] > In cancelAnyPendingIntentSetPreviously
,I/GCoreNlp( 1715): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  883): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,V/ActivityManager(  883): Display changed displayId=0
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2602): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2602): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2602): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2602): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2602): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2602): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2602): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,I/Launcher( 1572): Deferring update until onResume
D/OtaApp  ( 2602): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2602): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1416): onFinishInput()
,W/IInputConnectionWrapper( 6646): showStatusIcon on inactive InputConnection
,D/WearableService( 1715): callingUid 10016, callindPid: 1715
,D/LocationInitializer( 6366): Restart initialization of location
,E/MDM     ( 1715): [197] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1715): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/LaunchCheckinHandler(  883): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,147
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1715): No location to return for getLastLocation()
W/FusedLocationProvider( 1715): location=null
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7749 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7749): Register our PhoneStateListener
,V/SetupWizard( 7749): Connected to Gservices successfully
,D/GCM     ( 1715): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1715): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7770 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  883): done {388d2f52, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [6374ms]
,D/GCM     ( 1715): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7800 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7587:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_7587/cgroup.procs: No such file or directory
,V/AlarmManager(  883): send {cf623ae, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7834 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7840 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7657:com.android.chrome/u0a52 (adj 15): empty #7
,I/art     (  883): Explicit concurrent mark sweep GC freed 21936(1109KB) AllocSpace objects, 2(153KB) LOS objects, 33% free, 20MB/31MB, paused 1.483ms total 132.032ms
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_7657/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 7676:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/ResourcesManager( 7840): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7676/cgroup.procs: No such file or directory
,I/Babel_SMS( 7840): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7840): MmsConfig.loadMmsSettings
I/Babel_SMS( 7840): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7840): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7840): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7840): MmsConfig.loadFromResources
E/Babel_SMS( 7840): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7840): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7840): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7840): startup - clean
,I/Babel   ( 7840): deleted: false for 0
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7888 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7840): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7840): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7840): Unsupported mime video/mpeg2
,W/asset   ( 7888): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7888): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7888): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7888): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7840): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7840): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7840): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7840): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7840): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 6366): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6366): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 7800): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1f2a2f78 new=com.google.android.velvet.VelvetApplication@1f2a2f78
,I/Icing   ( 6366): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7921 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7840): onServiceConnected
,W/Babel   ( 7840): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7921): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7840): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7840): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7800): UpdateCorporaTask done [took 188 ms] updated apps [took 188 ms] 
,I/ActivityManager(  883): Killing 7770:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,V/JNIHelp ( 7840): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7770/cgroup.procs: No such file or directory
,W/System  ( 7840): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7840): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7949 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7749:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7749/cgroup.procs: No such file or directory
,D/Finsky  ( 7949): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/TaskPersister(  883): removeObsoleteFile: deleting file=5_task.xml
,D/Finsky  ( 7949): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7949): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7949): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7949): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7949): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7949): Skipping gmscore version check
,I/ActivityManager(  883): Killing 7834:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_7834/cgroup.procs: No such file or directory
,V/AlarmManager(  883): done {cf623ae, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [1857ms]
,D/Finsky  ( 7949): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7949): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 6366): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6366): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=302, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311879, SEQNUM=4492, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-168, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2477): Disconnected process message: 10, size: 0
,I/ActivityManager(  883): Killing 7888:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_7888/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2477): Disconnected process message: 10, size: 0
,I/ActivityManager(  883): Killing 7800:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_7800/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,I/CheckinService( 6366): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=288, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311608, SEQNUM=4500, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=3229, POWER_SUPPLY_CHARGE_COUNTER=-172, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2477): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2477): Disconnected process message: 10, size: 0
,V/AlarmManager(  883): send {47ec140, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  883): done {47ec140, *walarm*:com.google.android.intent.action.SEND_IDLE} [74ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/ClearcutLoggerApiImpl( 1715): disconnect managed GoogleApiClient
,V/AlarmManager(  883): send {33b0b0e9, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {59f879, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  883): send {3699d9be, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  883): done {59f879, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [18ms]
,V/AlarmManager(  883): done {3699d9be, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [31ms]
,I/CheckinService( 6366): Checkin interval check for package: unspecified last checkin: 1453043062174 min interval config: 0 actual interval: 42041
,V/AlarmManager(  883): done {33b0b0e9, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/CheckinService( 6366): Checking schedule, now: 1453043104239 next: 1453043092127
I/CheckinService( 6366): active receiver: enabled
,I/CheckinService( 6366): Preparing to send checkin request
I/EventLogService( 6366): Accumulating logs since 1453043058043
,I/CheckinRequestBuilder( 6366): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6366): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8037 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8037): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8037): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8037): VM with version 2.1.0 has multidex support
I/MultiDex( 8037): install
,I/MultiDex( 8037): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8037): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8037): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8037): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a545c33: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8037): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1715): callingUid 10016, callindPid: 1715
,D/LocationInitializer( 6366): Restart initialization of location
,D/AuthorizationBluetoothService( 1715): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1715): [178] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1715): No location to return for getLastLocation()
W/FusedLocationProvider( 1715): location=null
,I/art     ( 8037): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 8037): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8037): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
,I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe8000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe8000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  295): hlos api version =  9
,D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb54c3960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8d58be8, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8d8e9e8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8e8b828, idLength=0xbe8222b0
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=3662208155
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8db3920
D/DrmWidevineDash(  295): message_length=1591, signature=0xb8db5888, signature_length=3196199572
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8069): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8069): dex2oat took 65.349ms (threads: 4)
,I/Adreno-EGL( 8037): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8037): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8037): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8037): Local Branch: 
I/Adreno-EGL( 8037): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8037): Local Patches: NONE
I/Adreno-EGL( 8037): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8037): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8037): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8037): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8037): Local Branch: 
I/Adreno-EGL( 8037): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8037): Local Patches: NONE
I/Adreno-EGL( 8037): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8037): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8037): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8037): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8037): Local Branch: 
I/Adreno-EGL( 8037): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8037): Local Patches: NONE
I/Adreno-EGL( 8037): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8037): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8037): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8037): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8037): Local Branch: 
I/Adreno-EGL( 8037): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8037): Local Patches: NONE
I/Adreno-EGL( 8037): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe8000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe8000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb54c3960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8db5508, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8d8e9e8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb8e8b868, idLength=0xb13d8730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  295): PrepareKeyRequest: nonce=2807634261
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8db3a30
,D/DrmWidevineDash(  295): message_length=1626, signature=0xb8dc5c20, signature_length=2973599508
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/CheckinRequestBuilder( 6366): Classify the device as Phone.
,I/CheckinTask( 6366): Sending checkin request (9513 bytes)
,I/CheckinRequestBuilder( 6366): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6366): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  883): Explicit concurrent mark sweep GC freed 15451(770KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/31MB, paused 1.443ms total 118.654ms
,I/CheckinRequestBuilder( 6366): Classify the device as Phone.
,I/CheckinTask( 6366): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6366): Checking schedule, now: 1453043108611 next: 1453644245606
I/CheckinService( 6366): active receiver: disabled
,D/CheckinService( 6366): Recording last checkin time for package unspecified as 1453043108626
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8104 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8104): Register our PhoneStateListener
,V/SetupWizard( 8104): Connected to Gservices successfully
,D/GCM     ( 1715): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  883): Killing 7921:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  883): Killing 7699:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7921/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_7699/cgroup.procs: No such file or directory
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=282, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311820, SEQNUM=4512, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-184, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2477): Disconnected process message: 10, size: 0
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8126 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 41.652ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 18.965ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 19.934ms
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1d35b689
,I/GCoreNlp( 1715): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1572): Deferring update until onResume
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8163 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8182 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7949:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_7949/cgroup.procs: No such file or directory
,W/ResourcesManager( 7840): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7840): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8206 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 8104:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 8182): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_8104/cgroup.procs: No such file or directory
,W/asset   ( 8206): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 8206): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8206): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8206): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6366): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6366): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 8126): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1f2a2f78 new=com.google.android.velvet.VelvetApplication@1f2a2f78
,I/Icing   ( 6366): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8233 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8233): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8126): UpdateCorporaTask done [took 171 ms] updated apps [took 171 ms] 
,I/art     ( 1715): Explicit concurrent mark sweep GC freed 109768(6MB) AllocSpace objects, 30(503KB) LOS objects, 40% free, 15MB/26MB, paused 1.156ms total 113.806ms
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8257 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 8037:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_8037/cgroup.procs: No such file or directory
,D/Finsky  ( 8257): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8257): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8257): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8257): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8257): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8257): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8257): Skipping gmscore version check
,D/Finsky  ( 8257): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8257): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  883): Killing 8163:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_8163/cgroup.procs: No such file or directory
,I/Icing   ( 6366): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6366): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  883): Killing 8206:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_8206/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  883): Killing 7840:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7840/cgroup.procs: No such file or directory
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1416): run()
I/Keyboard.Facilitator( 1416): flushDynamicLanguageModels()
,I/ConfigService( 1715): onCreate
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312067, SEQNUM=4522, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-199, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2477): Disconnected process message: 10, size: 0
,I/ConfigService( 1715): onDestroy
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  290): NetlinkHandler, power_supply subsys
I/MDMCTBK (  290): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  290): checkDefaultInst, current pid is = 290
I/MDMCTBK (  290): checkDefaultInst, pid match
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  290): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  290): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6646): --= Surplus to requirements =--
I/jxcore-log( 6646): 
I/jxcore-log( 6646): ****TEST TOOK:  ms ****
I/jxcore-log( 6646): 
I/jxcore-log( 6646): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6646): 
,D/AndroidRuntime( 8324): 
D/AndroidRuntime( 8324): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8324): CheckJNI is OFF
,D/AndroidRuntime( 8324): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  883): Force stopping com.test.thalitest appid=10457 user=-1: uninstall pkg
,I/ActivityManager(  883): Killing 6646:com.test.thalitest/u0a457 (adj 9): stop com.test.thalitest
,I/WindowState(  883): WIN DEATH: Window{2abf3e95 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  883): Client connection lost with reason: 4
,W/PackageSettings(  883): Skipping PackageSetting{cd81957 com.example.hello/10440} due to missing metadata
,I/ActivityManager(  883):   Force finishing activity ActivityRecord{d0f2ef9 u0 com.test.thalitest/.MainActivity t6}
W/ActivityManager(  883): Spurious death for ProcessRecord{8dceb77 6646:com.test.thalitest/u0a457}, curProc for 6646: null
,I/ActivityManager(  883): Force stopping com.test.thalitest appid=10457 user=0: pkg removed
,I/ActivityManager(  883):   Force finishing activity ActivityRecord{d0f2ef9 u0 com.test.thalitest/.MainActivity t6 f}
W/ActivityManager(  883): Duplicate finish request for ActivityRecord{d0f2ef9 u0 com.test.thalitest/.MainActivity t6 f}
,I/art     ( 3052): Explicit concurrent mark sweep GC freed 8788(1966KB) AllocSpace objects, 10(162KB) LOS objects, 39% free, 7MB/12MB, paused 892us total 47.820ms
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1715): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1416): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1416): run()
,I/art     ( 1572): Explicit concurrent mark sweep GC freed 5116(314KB) AllocSpace objects, 6(276KB) LOS objects, 24% free, 13MB/17MB, paused 494us total 107.703ms
,I/art     ( 6366): Explicit concurrent mark sweep GC freed 17712(1054KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 13MB/17MB, paused 753us total 136.945ms
,D/VoicemailCleanupService( 8182): Cleaning up data for package: com.test.thalitest
,W/SQLiteConnectionPool( 6366): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Decoder ( 1416): createOrResetDecoder
,I/art     (  883): Explicit concurrent mark sweep GC freed 22381(1420KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 21MB/31MB, paused 3.548ms total 174.169ms
I/art     (  883): WaitForGcToComplete blocked for 70.631ms for cause Explicit
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8356 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ConfigService( 1715): onCreate
,W/asset   ( 8356): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8356): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8356): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8356): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = history
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1416): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1416): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1416): run()
I/StatsUtilsManager( 1416): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1416): shouldRecordStats() = Too Soon
,I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8380 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  883): removeObsoleteFile: deleting file=6_task.xml
,I/ActivityManager(  883): Killing 8126:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/art     (  883): Explicit concurrent mark sweep GC freed 6849(388KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 3.049ms total 218.500ms
,D/AndroidRuntime( 8324): Shutting down VM
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_8126/cgroup.procs: No such file or directory
,W/ContextImpl( 8380): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 6366): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 6366): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6366): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6366): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 6366): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6366): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1715): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1715): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8401 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/LocationSettingsChecker( 6366): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 6366): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6366): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,I/Launcher( 1572): Deferring update until onResume
,D/gH_MetricsDatabase( 6366): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6366): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 6366): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6366): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,W/BaseAppContext( 6366): Using Auth Proxy for data requests.
,D/gH_CompatibleDatabase( 6366): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
W/BaseAppContext( 6366): Using Auth Proxy for data requests.
,D/gH_CompatibleDatabase( 6366): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6366): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 6366): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6366): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 6366): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 6366): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1f2a2f78 new=com.google.android.velvet.VelvetApplication@1f2a2f78
,I/GMPM-SVC( 6366): App measurement is starting up, version: 8489
,I/GMPM-SVC( 6366): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/ActivityManager(  883): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8426 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/Icing   ( 6366): doRemovePackageData com.test.thalitest
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8456 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 8401): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  883): Killing 8233:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_8233/cgroup.procs: No such file or directory
,D/ConnectivityService(  883): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  883): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 6366): CM callback handler got msg 524290
,W/DriveInitializer( 6366): Awaiting to be initialized
W/DriveInitializer( 6366): Background init thread started
,I/GAv4    ( 8426): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8426):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8426):   adb logcat -s GAv4
,I/UpdateIcingCorporaServi( 8401): UpdateCorporaTask done [took 439 ms] updated apps [took 439 ms] 
,I/ActivityManager(  883): Killing 8257:com.android.vending/u0a32 (adj 15): empty #7
,W/GAv4    ( 8426): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  276): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.gms/files/
W/Vold    (  276): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6366): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.gms/files
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_8257/cgroup.procs: No such file or directory
,E/SQLiteLog( 6366): (3850) statement aborts at 151: [DELETE FROM FileContent163 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
,E/DocListDatabase( 6366): Failed to delete from FileContent163 table
E/DocListDatabase( 6366): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 6366): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 6366): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 6366): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 6366): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 6366): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 6366): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 6366): 	at com.google.android.gms.drive.database.f.a(SourceFile:987)
E/DocListDatabase( 6366): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/DocListDatabase( 6366): 	at com.google.android.gms.drive.j.ah.run(SourceFile:51)
E/DocListDatabase( 6366): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 6366): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 6366): 	at java.lang.Thread.run(Thread.java:818)
,--------- beginning of crash
E/AndroidRuntime( 6366): FATAL EXCEPTION: pool-10-thread-1
E/AndroidRuntime( 6366): Process: com.google.android.gms, PID: 6366
E/AndroidRuntime( 6366): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6366): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6366): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 6366): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6366): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6366): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 6366): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 6366): 	at com.google.android.gms.drive.database.f.a(SourceFile:987)
E/AndroidRuntime( 6366): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/AndroidRuntime( 6366): 	at com.google.android.gms.drive.j.ah.run(SourceFile:51)
E/AndroidRuntime( 6366): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 6366): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 6366): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 8426): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 8426): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 8426): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
I/Process ( 6366): Sending signal. PID: 6366 SIG: 9
E/DropBoxManagerService(  883): Can't write: system_app_crash
E/DropBoxManagerService(  883): java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  883): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  883): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  883): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  883): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  883): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  883): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  883): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  883): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  883): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  883): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  883): 	... 5 more
W/GAv4    ( 8426): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 8426): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 8426): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 8426): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 8426): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 8426): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8426): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 8426): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 8426): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 8426): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 8426): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 8426): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 8426): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 8426): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 8426): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 8426): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 8426): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 8426): 	at gir$c.run(Unknown Source)
,E/GAv4    ( 8426): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 8426): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 8426): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 8426): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 8426): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 8426): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8426): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8426): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 8426): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 8426): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 8426): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 8426): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 8426): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 8426): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 8426): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 8426): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 8426): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 8426): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 8426): 	at gir$c.run(Unknown Source)
E/GAv4    ( 8426): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 8426): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 8426): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/AnalyticsTrackerProxyImpl( 8426): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SharedPreferencesImpl( 8426): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 8426): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 8426): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
D/ConnectivityService(  883): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@8571a2a)
D/ConnectivityService(  883): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiService(  883): Client connection lost with reason: 4
E/ConnectivityService(  883): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  277): handle_blank_event: dpy:0 panel power state: 0

```
