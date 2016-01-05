#### Test 54968200254eab2_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/AndroidRuntime( 6684): 
D/AndroidRuntime( 6684): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6684): CheckJNI is OFF
D/AndroidRuntime( 6684): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  882): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  882): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6703 uid=10408 gids={50408, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6684): Shutting down VM
V/ActivityManager(  882): Display changed displayId=0
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6703): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6703): Time to load native libraries: 4 ms (timestamps 7783-7787)
I/LibraryLoader( 6703): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6703): Binding Chromium to main looper Looper (main, tid 1) {1811f4bd}
I/LibraryLoader( 6703): Expected native library version number "",actual native library version number ""
I/chromium( 6703): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6703): Initializing chromium process, singleProcess=true
W/art     ( 6703): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6703): ApplicationContext is null in ApplicationStatus
W/chromium( 6703): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6703): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6703): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6703): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6703): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6703): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6703): Local Branch: 
I/Adreno-EGL( 6703): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6703): Local Patches: NONE
I/Adreno-EGL( 6703): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
W/ActivityManager(  882): Activity pause timeout for ActivityRecord{2361ceeb u0 com.test.thalitest/.MainActivity t3}
D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@200911de:true
W/art     ( 6703): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6703): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6703): CordovaWebView is running on device made by: motorola
W/art     ( 6703): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6703): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6703): Render dirty regions requested: true
D/Atlas   ( 6703): Validating map...
W/chromium( 6703): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6703): Initialized EGL, version 1.4
D/OpenGLRenderer( 6703): Enabling debug mode 0
I/Keyboard.Facilitator( 1417): onFinishInput()
I/LaunchCheckinHandler(  882): Displayed com.test.thalitest/.MainActivity,cp,ca,1041
I/ActivityManager(  882): Displayed com.test.thalitest/.MainActivity: +957ms (total +1s42ms)
W/IInputConnectionWrapper( 6703): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 6703): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6703): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6703): Cannot call determinedVisibility() - never saw a connection for the pid: 6703
D/JsMessageQueue( 6703): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6703): JniHelper::setJavaVM(0xb8ded310), pthread_self() = -1189618840
D/JX-Cordova( 6703): jxcore cordova android initializing
,W/jxcore-log( 6703): Initializing JXcore engine
W/jxcore-log( 6703): JXcore engine is ready
,W/jxcore-log( 6703): Starting JXcore engine
,W/.test.thalitest( 6703): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10408 path="socket:[6585]" dev="sockfs" ino=6585 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6703): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10408 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6703): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10408 path="socket:[9458]" dev="sockfs" ino=9458 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6703): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10408 path="socket:[29100]" dev="sockfs" ino=29100 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6703): Platform android
W/jxcore-log( 6703): 
,W/jxcore-log( 6703): Process ARCH arm
W/jxcore-log( 6703): 
,I/jxcore-log( 6703): JXcore Cordova bridge is ready!
I/jxcore-log( 6703): 
W/jxcore-log( 6703): JXcore engine is started
,I/Choreographer( 6703): Skipped 171 frames!  The application may be doing too much work on its main thread.
I/chromium( 6703): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6703): Toggling radios to true
I/jxcore-log( 6703): 
,D/BluetoothAdapter( 6703): enable(): BT is already enabled..!
,D/WifiService(  882): New client listening to asynchronous messages
,D/WifiService(  882): setWifiEnabled: true pid=6703, uid=10408
E/WifiService(  882): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6703): Radios toggled
I/jxcore-log( 6703): 
D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6703): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): Perf Test app loaded loaded
I/jxcore-log( 6703): 
I/jxcore-log( 6703): check test folder
I/jxcore-log( 6703): 
I/jxcore-log( 6703): found test : ./testFindPeers.js
I/jxcore-log( 6703): 
,I/wpa_supplicant( 1400): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292):  STA Disconnected !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,D/TCMD    (  488): NL - Read 1004 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 68 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 68 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering(  882): InitialState.processMessage what=4
I/wpa_supplicant( 1400): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  882): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  882): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/wpa_supplicant( 1400): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882):  0
,D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1400): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  289): Clearing all IP addresses on wlan0
D/TCMD    (  488): NL - Read 60 bytes from update socket.
D/TCMD    (  488): NL - ignore NL message, type = 21
D/TCMD    (  488): Listening for incoming client connection request
,I/jxcore-log( 6703): found test : ./testSendData.js
I/jxcore-log( 6703): 
,V/NativeCrypto( 1754): Read error: ssl=0xb9081178: I/O error during system call, Connection timed out
,V/NativeCrypto( 1754): SSL shutdown failed: ssl=0xb9081178: I/O error during system call, Broken pipe
,D/ConnectivityService(  882): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=-1ms what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info<unknown ssid>
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6771 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  882): connected time updated 124585
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/wpa_supplicant( 1400): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  882): Start Disconnecting Watchdog 1
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/wpa_supplicant( 1400): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  882): ConnectModeState: Network connection lost 
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1400): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  289): Clearing all IP addresses on wlan0
D/ConnectivityService(  882): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524292
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  882): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1959): CM callback handler got msg 524292
I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
I/chromium( 6703): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/ConnectivityService(  882): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6771): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  882): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/PhenotypeConfigurator( 1754): Scheduling Phenotype for one-off execution 12193 seconds from now (1451954459301)
,D/GetConfigurationSnapshotOperation( 1754): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/Babel_SMS( 6771): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6771): MmsConfig.loadMmsSettings
I/Babel_SMS( 6771): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6771): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6771): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6771): MmsConfig.loadFromResources
,E/Babel_SMS( 6771): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6771): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/PhenotypeFlagCommitter( 1754): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1754): Using platform SSLCertificateSocketFactory
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  292): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
E/WifiStateMachine(  882): [1,451,954,459,439 ms] noteScanEnd no scan source
I/wpa_supplicant( 1400): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  882): didn't find BSSID Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 1400): DSDS: eapol_sm_notify_config config->sim_num = 1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  292): Event received = Trying to associate with
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2a765b21 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/Settings( 6771): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6771): startup - clean
,I/Babel   ( 6771): deleted: false for 0
,D/TCMD    (  488): NL - Read 312 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 192 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 68 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 1004 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/TCMD    (  488): NL - Read 80 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 80 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 68 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
I/wpa_supplicant( 1400): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  292): Event received = Associated with c0:ff:d4
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6817 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1400): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1400): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/TCMD    (  488): NL - Read 1004 bytes from update socket.
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/MDMCTBK (  292): Event received = WPA: Key negotiation com
D/TCMD    (  488): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292):  STA Connected !!
,E/MDMCTBK (  292): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  292): get_freq !!, resp=2412
I/MDMCTBK (  292): get_freq !!, Strip data
I/MDMCTBK (  292): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
,I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  292): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  292): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1191522864
I/MDMCTBK (  292): return from set_get_from_wpa_supplicant
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
D/MDMCTBK (  292): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  292): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  292): , reply_len: 3, ret: 0
E/MDMCTBK (  292): MdmCutbackHndler, resp=OK
E/MDMCTBK (  292): 
D/MDMCTBK (  292): wifi_set_tx_pwr: Exit
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  882): Network connection established
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
D/Uploader( 1754): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  882): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  882): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  882): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  882): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  289): Setting iface cfg
,E/WifiStateMachine(  882): Start Dhcp Watchdog 2
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend false
,V/GLSActivity( 1754): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1754): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/wpa_supplicant( 1400): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1400): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2276edc9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2276edc9 target=com.android.internal.util.StateMachine$SmHandler }
,W/ResourcesManager( 6817): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/VideoCapabilities( 6771): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6771): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6771): Unsupported mime video/mpeg2
,D/Uploader( 1754): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/VideoCapabilities( 6771): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6771): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6771): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Killing 6341:android.process.acore/u0a7 (adj 15): empty #7
,W/VideoCapabilities( 6771): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6771): Unrecognized profile 2130706433 for video/avc
,E/DHCPCD  ( 6840): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
I/DHCPCD  ( 6840): version 5.5.6 starting
E/DHCPCD  ( 6840): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6840): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6840): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_6341/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 6546:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/DHCPCD  ( 6840): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6840): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6840): wlan0: sending REQUEST (xid 0x9a09e71f), next in 4.19 seconds
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_6546/cgroup.procs: No such file or directory
,I/vclib   ( 6771): onServiceConnected
,W/Babel   ( 6771): Attempted to change video mute state without an active call.
,V/AlarmManager(  882): send {3daefe87, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {385b14aa, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  882): done {385b14aa, *walarm*:com.google.android.intent.action.SEND_IDLE} [3ms]
,V/AlarmManager(  882): done {3daefe87, *alarm*:android.intent.action.TIME_TICK} [28ms]
,D/Uploader( 1754): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1754): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1754): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1754): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1754): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1754): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1754): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1754): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/DHCPCD  ( 6840): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6840): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 6840): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6840): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6840): wlan0: adding default route via 192.168.1.1
,D/DHCPCD  ( 6840): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  488): NL - Read 60 bytes from update socket.
D/TCMD    (  488): NL - ignore NL message, type = 20
D/TCMD    (  488): Listening for incoming client connection request
D/DHCPCD  ( 6840): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): WifiStateMachine DHCP successful
E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  882): Calling ARP set with IP = 192.168.1.123
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  882): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  882): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  882): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  882): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  882): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,E/WifiStateMachine(  882): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine(  882): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityService(  882): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882):    accepting network in place of null
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  882): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1959): CM callback handler got msg 524290
,E/global frequency( 2588): no tags to log
,D/Checkin ( 2588): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 00:41:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451954461721], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451954461691]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Validated
,D/ConnectivityService(  882): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  882): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1959): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1531): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1531): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/art     (  882): Explicit concurrent mark sweep GC freed 75534(3MB) AllocSpace objects, 4(248KB) LOS objects, 33% free, 20MB/30MB, paused 1.477ms total 137.077ms
,D/BSUtils ( 2588): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 56458(3MB) AllocSpace objects, 36(1243KB) LOS objects, 40% free, 7MB/12MB, paused 840us total 58.538ms
,D/BSUtils ( 2588): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2588): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2588): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,V/AlarmManager(  882): send {239c6cd0, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  882): done {239c6cd0, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [6ms]
,I/art     ( 2588): Explicit concurrent mark sweep GC freed 25973(1527KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.033ms total 102.425ms
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/Tethering(  882): MasterInitialState.processMessage what=3
D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/BSUtils ( 2588): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2588): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6917 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1465): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/BSUtils ( 2588): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/MusicStore( 6917): Database version: 120
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 4319(189KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 503us total 29.460ms
,D/BSUtils ( 2588): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6917): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/BSUtils ( 2588): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/BSUtils ( 2588): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/global frequency( 2588): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2588): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2588): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2588): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2588): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/OtaApp  ( 2588): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2588): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2588): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2588): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2588): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Checkin ( 2588): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,D/OtaApp  ( 2588): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/CCE     ( 2588): Registering with Alarm Manager to restart CCE
D/CCE     ( 2588): Registering with Alarm Manager to restart CCE
D/CCE     ( 2588): Registering with Alarm Manager to restart CCE
D/OtaApp  ( 2588): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2588): [debug] > CusSM.onRadioDown
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6917): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6917): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6917): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6917): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6917): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/global frequency( 2588): BcsDSCheckin.events found events 55
,D/Checkin ( 2588): publish the event [tag = MOT_CHECKIN event name = LOG]
,W/ActivityThread( 6917): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6917): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@950e6e9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6917): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6917): GMSCore installation verified
,I/BSUtils ( 2588): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/ConfigStore( 6917): Config Database version: 1
,D/ConnectivityService(  882): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/MMApiWebService( 2588): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     (  882): Explicit concurrent mark sweep GC freed 11304(578KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.517ms total 113.600ms
,I/MMApiWSBase( 2588): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2588): publish the event [tag = MOT_CCE event name = LOG]
,I/MediaRouter( 6917): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6917): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6917): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6917): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6962 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6917): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6917): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 6480:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_6480/cgroup.procs: No such file or directory
,V/Mms     ( 6962): mnc/mcc: 
,V/Mms     ( 6962): tag: int value: recipientLimit - 20
,V/Mms     ( 6962): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6962): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6962): tag: int value: maxSubjectLength - 80
V/Mms     ( 6962): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 6962): tag: bool value: enableGroupMms - false
V/Mms     ( 6962):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6962): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6988 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6578:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_6578/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6988): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6988): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6988): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 6771:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_6771/cgroup.procs: No such file or directory
,I/CheckinService( 1959): Checkin interval check for package: unspecified last checkin: 1451954378520 min interval config: 0 actual interval: 84843
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7007 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 1959): Checking schedule, now: 1451954463426 next: 1451954408493
I/CheckinService( 1959): active receiver: enabled
,I/CheckinService( 1959): Preparing to send checkin request
I/EventLogService( 1959): Accumulating logs since 1451954375363
,I/CheckinRequestBuilder( 1959): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1959): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7025 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7025): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7025): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7025): VM with version 2.1.0 has multidex support
I/MultiDex( 7025): install
I/MultiDex( 7025): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7043 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 20.680ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 19.587ms
,V/JNIHelp ( 7025): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 7043): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 20.345ms
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 6703): BLE supported!!
I/jxcore-log( 6703): 
,W/ActivityThread( 7025): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7025): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17b8c236: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7025): Installed default security provider GmsCore_OpenSSL
,I/art     ( 7025): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7025): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1959): CM callback handler got msg 524295
,D/MMApiWSBase( 2588): doRequest(): v1/cs/checkin resp length: 4
D/CCE     ( 2588): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
D/CCE     ( 2588): AppWSProxy - sendAIDLWSResponse() sending reponse
I/global frequency( 2588): BcsCore.status() called with error code=ERROR_OK
D/Checkin ( 2588): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/CheckinProvider(  882): 55 events delete 0 left
,D/NativeLibraryUtils( 7025): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  295): Instantiating CDM.
,I/Babel_SMS( 7043): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7043): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7043): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7043): MmsConfig.loadFromDatabase
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
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
,I/global frequency( 2588): BcsDSCheckin.events found events 0
D/QSEECOMAPI: (  295): Loaded image: APP id = 3
D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
,E/Babel_SMS( 7043): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7043): MmsConfig.loadFromResources
D/Checkin ( 2588): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,E/Babel_SMS( 7043): canonicalizeMccMnc: invalid mccmnc nullnull
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb5558960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb83c1fa8, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb83c1490, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb83cd8f0, idLength=0xb0e45730
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
D/WVCdm   (  295): PrepareKeyRequest: nonce=4096014212
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb827ffb8
D/DrmWidevineDash(  295): message_length=1591, signature=0xb8294c80, signature_length=2967754516
,I/Babel_SMS( 7043): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/BSUtils ( 2588): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/BSUtils ( 2588): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/Settings( 7043): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7043): startup - clean
,I/Babel   ( 7043): deleted: false for 0
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7079 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/DataUsage( 2588): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2588): publish the event [tag = MOT_CCE event name = LOG]
,W/VideoCapabilities( 7043): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7043): Unsupported mime audio/amr-wb-plus
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2588): now: 199548 ,futureTime: 9223372036854775807
,D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2588): now: 199553 ,futureTime: 9223372036854775807
,D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2588): now: 199553 ,futureTime: 9223372036854775807
D/OtaApp  ( 2588): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/OtaApp  ( 2588): [debug] > PollingManagerService, now: 199555 ,futureTime: 55999045
D/OtaApp  ( 2588): [debug] > Polling alarm set to expire at: 55999045 Current Time: 199556
,D/Central_PollingManager( 1465): now: 199560 ,futureTime: 86476495
D/Central_PollingManager( 1465): Polling alarm set to expire at: 86476495 Current Time: 199560
D/OtaApp  ( 2588): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2588): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2588): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/NetworkMonitor( 6917): type=WIFI subType= reason=null isConnected=true
,I/dex2oat ( 7096): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/OtaApp  ( 2588): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2588): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2588): publish the event [tag = MOT_OTA event name = LOG]
W/VideoCapabilities( 7043): Unsupported mime video/mpeg2
,D/MMApiProvisionService( 2588): isDeviceProvisioned: deviceId = 2072049230914535424
,D/OtaApp  ( 2588): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2588): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2588): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2588): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/CCE     ( 2588): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2588): createDeviceIdOrLogin update_device
D/Checkin ( 2588): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2588): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2588): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2588): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2588): createDeviceIdOrLogin update_device
,D/Checkin ( 2588): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2588): isDeviceProvisioned: deviceId = 2072049230914535424
,I/VideoCapabilities( 7043): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7043): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7043): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7043): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7043): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7043): onServiceConnected
,W/Babel   ( 7043): Attempted to change video mute state without an active call.
,I/art     (  882): Explicit concurrent mark sweep GC freed 12751(568KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.816ms total 126.204ms
,I/Babel   ( 7043): connection state changed from UNKNOWN to CONNECTED
,D/MMApiProvisionService( 2588): set mOutstandingReq to true.
I/ Nonce  ( 2588):  Nonce getNonce 
I/ Nonce  ( 2588):  Nonce Request 
I/ Nonce  ( 2588):  Nonce execute Request 
,D/MMApiWebService( 2588): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/ActivityManager(  882): Killing 6817:com.motorola.context/u0a8 (adj 15): empty #7
,D/MMApiProvisionService( 2588): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2588): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2588): createDeviceIdOrLogin update_device
,D/Checkin ( 2588): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2588): Not proxy app, so login/provision not allowed
,W/libprocessgroup(  882): failed to open /acct/uid_10008/pid_6817/cgroup.procs: No such file or directory
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 3836(157KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 585us total 32.068ms
,I/dex2oat ( 7096): dex2oat took 308.259ms (threads: 4)
D/MMApiWebService( 2588): generating token using payload instead of using session token
,D/ Nonce  ( 2588):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2588): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2588): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7079): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7079): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7079): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7079): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7079): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7079):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7079):   adb logcat -s GAv4
,I/Adreno-EGL( 7025): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7025): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7025): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7025): Local Branch: 
I/Adreno-EGL( 7025): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7025): Local Patches: NONE
I/Adreno-EGL( 7025): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/GAv4    ( 7079): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7079): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7079): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 7025): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7025): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7025): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7025): Local Branch: 
I/Adreno-EGL( 7025): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7025): Local Patches: NONE
I/Adreno-EGL( 7025): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 7079): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7079): Time to load native libraries: 1 ms (timestamps 290-291)
I/LibraryLoader( 7079): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7079): Binding Chromium to main looper Looper (main, tid 1) {81424e6}
,I/LibraryLoader( 7079): Expected native library version number "",actual native library version number ""
I/chromium( 7079): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7079): Initializing chromium process, singleProcess=true
,W/art     ( 7079): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7079): ApplicationContext is null in ApplicationStatus
,W/chromium( 7079): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7079): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7079): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7079): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7079): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7079): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7079): Local Branch: 
I/Adreno-EGL( 7079): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7079): Local Patches: NONE
I/Adreno-EGL( 7079): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7079): Requires BLUETOOTH permission
,I/NSApplication( 7079): Starting up...
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7153 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6917:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb0e45960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb82e6a58, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb83c1490, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb83cd930, idLength=0xbe9142b0
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
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
D/WVCdm   (  295): PrepareKeyRequest: nonce=418480995
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb827ffb8
,D/DrmWidevineDash(  295): message_length=1626, signature=0xb83c2008, signature_length=3197190804
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_6917/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 7025): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7025): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7025): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7025): Local Branch: 
I/Adreno-EGL( 7025): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7025): Local Patches: NONE
I/Adreno-EGL( 7025): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7180 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 6962:com.android.mms/u0a23 (adj 15): empty #7
,I/Adreno-EGL( 7025): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7025): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7025): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7025): Local Branch: 
I/Adreno-EGL( 7025): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7025): Local Patches: NONE
I/Adreno-EGL( 7025): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_6962/cgroup.procs: No such file or directory
,W/ResourcesManager( 7180): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ Nonce  ( 2588):  Nonce Reponse 
D/        ( 2588): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"020c2892-d75a-461f-b1ec-037e9c7ebaa2"}
D/MMApiWSBase( 2588): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2588):  Nonce Handle Reponse 
D/MMApiProvisionService( 2588): mOutstandingReq set to false
,D/MMApiProvisionService( 2588):  pTime 1451923699777 sExp 172742 cTime 1451954466100 tTime 1452096441777
D/MMApiProvisionService( 2588):  No login Required 
,I/CheckinRequestBuilder( 1959): Classify the device as Phone.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7205 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7228 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7007:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/CheckinTask( 1959): Sending checkin request (9554 bytes)
,I/ContactLocale( 7205): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 6988:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7007/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_6988/cgroup.procs: No such file or directory
,W/DataUsage( 2588): invalid counter update blocked: 'err' by 0
D/Checkin ( 2588): publish the event [tag = MOT_CCE event name = LOG]
,I/MusicStore( 7228): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7228): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7228): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7228): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7228): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7228): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7228): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7228): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7228): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@950e6e9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7228): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7228): GMSCore installation verified
,I/ConfigStore( 7228): Config Database version: 1
,I/MediaRouter( 7228): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7228): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7228): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7228): type=WIFI subType= reason=null isConnected=true
,I/CheckinRequestBuilder( 1959): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7262 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 1959): Failed to find provider info for com.google.android.wearable.settings
,I/GHttpClientFactory( 7228): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7228): Using platform SSLCertificateSocketFactory
,I/art     (  882): Explicit concurrent mark sweep GC freed 8632(430KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.636ms total 122.818ms
,I/ActivityManager(  882): Killing 7043:com.google.android.talk/u0a70 (adj 15): empty #7
,V/Mms     ( 7262): mnc/mcc: 
,V/Mms     ( 7262): tag: int value: recipientLimit - 20
,V/Mms     ( 7262): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7262): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7262): tag: int value: maxSubjectLength - 80
V/Mms     ( 7262): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7262): tag: bool value: enableGroupMms - false
,V/Mms     ( 7262):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7043/cgroup.procs: No such file or directory
,W/ResourcesManager( 7262): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7293 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310258, SEQNUM=4449, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-20733, POWER_SUPPLY_CHARGE_COUNTER=-652, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,W/GCM-DMM ( 1754): Force release of GOOGLE_C2DM lock
,I/ActivityManager(  882): Killing 7079:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 7293): Register our PhoneStateListener
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_7079/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2470): Disconnected process message: 10, size: 0
,D/MobileConnectivityChangeReceiver( 7293): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7293): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 7153:com.android.chrome/u0a52 (adj 15): empty #7
,I/CheckinRequestBuilder( 1959): Classify the device as Phone.
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_7153/cgroup.procs: No such file or directory
,I/CheckinService( 1959): Checkin interval check for package: unspecified last checkin: 1451954378520 min interval config: 0 actual interval: 89081
,I/CheckinTask( 1959): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1959): Checking schedule, now: 1451954467612 next: 1452555604608
I/CheckinService( 1959): active receiver: disabled
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7314 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/CheckinService( 1959): Checking schedule, now: 1451954467670 next: 1452555604608
,I/CheckinService( 1959): active receiver: disabled
,D/CheckinService( 1959): Recording last checkin time for package unspecified as 1451954467680
,I/ActivityManager(  882): Killing 7205:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  882): Killing 7180:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_7205/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7180/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7334 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7228:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_7228/cgroup.procs: No such file or directory
,W/ResourcesManager( 7334): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7334): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7334): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7334): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7334): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7334): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7334): MmsConfig.loadFromResources
E/Babel_SMS( 7334): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7334): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7334): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7334): startup - clean
,I/Babel   ( 7334): deleted: false for 0
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7365 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7334): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7334): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7334): Unsupported mime video/mpeg2
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7365): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/VideoCapabilities( 7334): Unsupported profile 4 for video/mp4v-es
,I/GAv4    ( 7365): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7365):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7365):   adb logcat -s GAv4
,W/VideoCapabilities( 7334): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7334): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7334): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/VideoCapabilities( 7334): Unrecognized profile 2130706433 for video/avc
W/ContextImpl( 7365): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7365): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/vclib   ( 7334): onServiceConnected
,W/Babel   ( 7334): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7365): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7365): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7365): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7365): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7334): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 7262:com.android.mms/u0a23 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_7262/cgroup.procs: No such file or directory
,I/WebViewFactory( 7365): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7365): Time to load native libraries: 1 ms (timestamps 4147-4148)
I/LibraryLoader( 7365): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7365): Binding Chromium to main looper Looper (main, tid 1) {81424e6}
I/LibraryLoader( 7365): Expected native library version number "",actual native library version number ""
,I/chromium( 7365): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7365): Initializing chromium process, singleProcess=true
,W/art     ( 7365): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7365): ApplicationContext is null in ApplicationStatus
,W/chromium( 7365): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7365): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7365): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7365): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7365): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7365): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7365): Local Branch: 
I/Adreno-EGL( 7365): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7365): Local Patches: NONE
I/Adreno-EGL( 7365): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ProcessCpuTracker(  882): Skipping unknown process pid 7388
,W/ProcessCpuTracker(  882): Skipping unknown process pid 7389
,W/ProcessCpuTracker(  882): Skipping unknown process pid 7394
W/ProcessCpuTracker(  882): Skipping unknown process pid 7413
,W/AudioManagerAndroid( 7365): Requires BLUETOOTH permission
,I/NSApplication( 7365): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7437 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 7293:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.185ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 28.212ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.593ms
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7293/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7461 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7314:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7314/cgroup.procs: No such file or directory
,W/ResourcesManager( 7461): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7484 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7365:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7484): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 7334:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_7365/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2588): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7334/cgroup.procs: No such file or directory
,I/art     ( 2588): Explicit concurrent mark sweep GC freed 32644(2006KB) AllocSpace objects, 5(103KB) LOS objects, 40% free, 11MB/19MB, paused 914us total 62.938ms
,D/GetNotificationsWS( 2588): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2588): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2588): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2588): onServiceConnected()
,D/GetNotificationsWS( 2588): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2588): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2588): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7517 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7517): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7517): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7517): MmsConfig.loadMmsSettings
I/Babel_SMS( 7517): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7517): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7517): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7517): MmsConfig.loadFromResources
,E/Babel_SMS( 7517): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7517): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7517): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7517): startup - clean
,I/Babel   ( 7517): deleted: false for 0
,I/GCM     ( 1959): Message from null null
E/GCM     ( 1959): Dropping message from null
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7549 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7517): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7517): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7517): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7517): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7517): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7517): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7517): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7517): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Killing 7437:com.android.chrome/u0a52 (adj 13): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_7437/cgroup.procs: No such file or directory
,I/vclib   ( 7517): onServiceConnected
W/Babel   ( 7517): Attempted to change video mute state without an active call.
,D/WearableService( 1754): callingUid 10016, callindPid: 1754
,E/MDM     ( 1754): [212] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1754): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1959): Restart initialization of location
,V/GLSActivity( 1754): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7574 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1754): No location to return for getLastLocation()
W/FusedLocationProvider( 1754): location=null
,I/art     (  882): Explicit concurrent mark sweep GC freed 13745(696KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.526ms total 118.797ms
,I/MusicStore( 7574): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7574): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7574): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7574): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7574): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7574): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7574): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7574): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7574): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@950e6e9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7574): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7574): GMSCore installation verified
,I/ConfigStore( 7574): Config Database version: 1
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/MediaRouter( 7574): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7574): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7574): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7574): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7607 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7574): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7574): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 7461:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,V/Mms     ( 7607): mnc/mcc: 
,V/Mms     ( 7607): tag: int value: recipientLimit - 20
,V/Mms     ( 7607): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7607): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7607): tag: int value: maxSubjectLength - 80
V/Mms     ( 7607): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7607): tag: bool value: enableGroupMms - false
V/Mms     ( 7607):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7461/cgroup.procs: No such file or directory
,W/ResourcesManager( 7607): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7638 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7484:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_7484/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7638): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7638): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7638): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  882): Killing 7517:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7517/cgroup.procs: No such file or directory
,I/CheckinService( 1959): Checkin interval check for package: unspecified last checkin: 1451954467680 min interval config: 0 actual interval: 4774
,I/CheckinService( 1959): Checkin interval check for package: unspecified last checkin: 1451954467680 min interval config: 0 actual interval: 4777
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7667 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 1959): Checking schedule, now: 1451954472530 next: 1451954497608
I/CheckinService( 1959): active receiver: disabled
,I/CheckinService( 1959): Checking schedule, now: 1451954472553 next: 1451954497608
I/CheckinService( 1959): active receiver: disabled
,W/ResourcesManager( 7667): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7667): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7667): MmsConfig.loadMmsSettings
I/Babel_SMS( 7667): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7667): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7667): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7667): MmsConfig.loadFromResources
,E/Babel_SMS( 7667): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7667): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7667): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7667): startup - clean
,I/Babel   ( 7667): deleted: false for 0
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7700 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7667): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7667): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7667): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7667): Unsupported profile 4 for video/mp4v-es
,I/GAv4    ( 7700): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7700):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7700):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7700): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/VideoCapabilities( 7667): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7667): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7667): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7667): Unrecognized profile 2130706433 for video/avc
,W/GAv4    ( 7700): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,I/vclib   ( 7667): onServiceConnected
W/Babel   ( 7667): Attempted to change video mute state without an active call.
,W/ContextImpl( 7700): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7700): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7700): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7700): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7700): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7667): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  882): Killing 7025:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_7025/cgroup.procs: No such file or directory
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  882): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  882): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  882): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1efb3aa7
,I/GCoreNlp( 1754): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1573): Deferring update until onResume
,I/WebViewFactory( 7700): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7700): Time to load native libraries: 2 ms (timestamps 8605-8607)
I/LibraryLoader( 7700): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7700): Binding Chromium to main looper Looper (main, tid 1) {81424e6}
,I/LibraryLoader( 7700): Expected native library version number "",actual native library version number ""
I/chromium( 7700): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7700): Initializing chromium process, singleProcess=true
,W/art     ( 7700): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7700): ApplicationContext is null in ApplicationStatus
,W/chromium( 7700): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7700): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7700): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7700): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7700): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7700): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7700): Local Branch: 
I/Adreno-EGL( 7700): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7700): Local Patches: NONE
I/Adreno-EGL( 7700): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7700): Requires BLUETOOTH permission
,I/NSApplication( 7700): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7767 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7574:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_7574/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7789 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7607:com.android.mms/u0a23 (adj 15): empty #7
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 24.066ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.735ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.714ms
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_7607/cgroup.procs: No such file or directory
,W/ResourcesManager( 7789): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7812 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  882): Explicit concurrent mark sweep GC freed 18139(913KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.566ms total 130.312ms
,I/ActivityManager(  882): Killing 7549:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7812): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 7638:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7549/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2588): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7638/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2588): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2588): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2588): onServiceConnected()
,D/GetNotificationsWS( 2588): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 2588): ServiceHandler.handleMessage: mWaitCount=0
,I/PushService( 2588): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2588): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2588): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2588): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  882): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2588): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2588): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2588): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2588): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7842 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2588): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2588): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2588): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2588): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2588): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2588): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2588): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2588): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2588): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1417): onFinishInput()
,W/IInputConnectionWrapper( 6703): showStatusIcon on inactive InputConnection
,D/PhoneMonitor( 7842): Register our PhoneStateListener
,V/SetupWizard( 7842): Connected to Gservices successfully
,I/ActivityManager(  882): Killing 7667:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7667/cgroup.procs: No such file or directory
,I/LaunchCheckinHandler(  882): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,206
,D/GCM     ( 1754): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7862 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/GCM     ( 1754): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7886 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 7700:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_7700/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7908 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7925 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  882): Killing 7767:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  882): Killing 7789:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_7767/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7789/cgroup.procs: No such file or directory
,W/ResourcesManager( 7925): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7925): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7925): MmsConfig.loadMmsSettings
I/Babel_SMS( 7925): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7925): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7925): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7925): MmsConfig.loadFromResources
,E/Babel_SMS( 7925): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7925): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7925): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7925): startup - clean
,I/Babel   ( 7925): deleted: false for 0
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7963 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7925): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7925): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7925): Unsupported mime video/mpeg2
,W/asset   ( 7963): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7963): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7963): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7925): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7925): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7925): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7925): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7925): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 1959): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1959): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 7886): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/Launcher( 1573): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1f2e635f new=com.google.android.velvet.VelvetApplication@1f2e635f
,I/Icing   ( 1959): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7994 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7925): onServiceConnected
W/Babel   ( 7925): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7994): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7925): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7925): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7886): UpdateCorporaTask done [took 165 ms] updated apps [took 165 ms] 
,I/ActivityManager(  882): Killing 7862:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,V/JNIHelp ( 7925): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7925): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7925): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_7862/cgroup.procs: No such file or directory
,I/art     ( 1959): Explicit concurrent mark sweep GC freed 50471(3MB) AllocSpace objects, 17(272KB) LOS objects, 24% free, 15MB/20MB, paused 1.092ms total 99.375ms
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8020 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1754): Explicit concurrent mark sweep GC freed 90026(4MB) AllocSpace objects, 19(304KB) LOS objects, 39% free, 15MB/26MB, paused 1.264ms total 107.181ms
,E/DataBuffer( 1754): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@34af6f70)
,E/DataBuffer( 1754): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@346c2e9)
E/DataBuffer( 1754): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1dba2b6e)
,E/DataBuffer( 1754): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2694320f)
E/DataBuffer( 1754): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1af4129c)
,I/ActivityManager(  882): Killing 7842:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_7842/cgroup.procs: No such file or directory
,D/Finsky  ( 8020): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8020): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8020): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8020): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/art     ( 5721): Explicit concurrent mark sweep GC freed 2964(128KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 365us total 31.778ms
,D/Finsky  ( 8020): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8020): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8020): Skipping gmscore version check
,D/Finsky  ( 8020): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8020): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  882): Killing 7908:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_7908/cgroup.procs: No such file or directory
,D/TaskPersister(  882): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 1959): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1959): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  882): Killing 7963:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_7963/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 7886:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_7886/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=254, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310467, SEQNUM=4480, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-778, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2470): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2470): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1754): disconnect managed GoogleApiClient
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  882): send {17be09a3, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  882): send {d274474, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  882): done {17be09a3, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [18ms]
,I/CheckinService( 1959): Checkin interval check for package: unspecified last checkin: 1451954467680 min interval config: 0 actual interval: 44522
,I/CheckinService( 1959): Checking schedule, now: 1451954512217 next: 1451954497608
I/CheckinService( 1959): active receiver: enabled
,V/AlarmManager(  882): done {d274474, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [87ms]
,I/CheckinService( 1959): Preparing to send checkin request
I/EventLogService( 1959): Accumulating logs since 1451954463449
,I/CheckinRequestBuilder( 1959): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1959): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  882): Explicit concurrent mark sweep GC freed 14690(761KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.383ms total 113.595ms
,V/GLSActivity( 1754): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1754): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8111 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8111): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8111): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8111): VM with version 2.1.0 has multidex support
I/MultiDex( 8111): install
I/MultiDex( 8111): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8111): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8111): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8111): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17b8c236: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8111): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1754): callingUid 10016, callindPid: 1754
,D/LocationInitializer( 1959): Restart initialization of location
,D/AuthorizationBluetoothService( 1754): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1754): [179] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1754): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1754): No location to return for getLastLocation()
,W/FusedLocationProvider( 1754): location=null
,I/art     ( 8111): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8111): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8111): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
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
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb5458960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb82e6fd0, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb83c1490, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb83cd910, idLength=0xb0e45730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
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
D/WVCdm   (  295): PrepareKeyRequest: nonce=3575553964
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb827ffb8
D/DrmWidevineDash(  295): message_length=1591, signature=0xb83c1eb8, signature_length=2967754516
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8148): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8148): dex2oat took 68.712ms (threads: 4)
,I/Adreno-EGL( 8111): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8111): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8111): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8111): Local Branch: 
I/Adreno-EGL( 8111): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8111): Local Patches: NONE
I/Adreno-EGL( 8111): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8111): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8111): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8111): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8111): Local Branch: 
I/Adreno-EGL( 8111): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8111): Local Patches: NONE
I/Adreno-EGL( 8111): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
,E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb5458960
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb82e71c0, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb83c1490, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb83cd930, idLength=0xbe9142b0
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
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
D/WVCdm   (  295): PrepareKeyRequest: nonce=2456260174
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb827ffb8
D/DrmWidevineDash(  295): message_length=1626, signature=0xb83c1eb8, signature_length=3197190804
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 8111): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8111): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8111): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8111): Local Branch: 
I/Adreno-EGL( 8111): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8111): Local Patches: NONE
I/Adreno-EGL( 8111): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8111): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8111): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8111): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8111): Local Branch: 
I/Adreno-EGL( 8111): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8111): Local Patches: NONE
I/Adreno-EGL( 8111): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 1959): Classify the device as Phone.
,I/CheckinTask( 1959): Sending checkin request (9558 bytes)
,I/CheckinRequestBuilder( 1959): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1959): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1959): Classify the device as Phone.
,I/CheckinTask( 1959): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1959): Checking schedule, now: 1451954516191 next: 1452555653186
I/CheckinService( 1959): active receiver: disabled
,D/CheckinService( 1959): Recording last checkin time for package unspecified as 1451954516207
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8182 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 24.232ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.584ms
,D/PhoneMonitor( 8182): Register our PhoneStateListener
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 20.510ms
,V/SetupWizard( 8182): Connected to Gservices successfully
,D/GCM     ( 1754): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  882): Killing 7812:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  882): Killing 7925:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_7812/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_7925/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8204 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  882): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  882): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@4b1b38a
,I/GCoreNlp( 1754): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1573): Deferring update until onResume
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8241 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8259 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  882): Killing 7994:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  882): Killing 8020:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_7994/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_8020/cgroup.procs: No such file or directory
,W/ResourcesManager( 8259): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8259): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8259): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8259): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8259): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8259): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 8259): MmsConfig.loadFromResources
E/Babel_SMS( 8259): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8259): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8259): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8259): startup - clean
,I/Babel   ( 8259): deleted: false for 0
,I/ActivityManager(  882): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8305 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/VideoCapabilities( 8259): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8259): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8259): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8259): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8259): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8259): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8259): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8259): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8330 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8182:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 8305): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_8182/cgroup.procs: No such file or directory
,I/vclib   ( 8259): onServiceConnected
,W/Babel   ( 8259): Attempted to change video mute state without an active call.
,W/asset   ( 8330): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8330): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 8330): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8330): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 8259): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8259): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 1959): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 1959): Null package name or gms related package.  Ignoreing.
,V/JNIHelp ( 8259): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/UpdateIcingCorporaServi( 8204): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/System  ( 8259): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8259): Installed default security provider GmsCore_OpenSSL
,I/UpdateIcingCorporaServi( 8204): UpdateCorporaTask done [took 108 ms] updated apps [took 108 ms] 
,I/art     (  882): Explicit concurrent mark sweep GC freed 18854(1036KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.627ms total 117.266ms
,I/Icing   ( 1959): updateResources: need to parse f{com.google.android.gms}
W/Launcher( 1573): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1f2e635f new=com.google.android.velvet.VelvetApplication@1f2e635f
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8362 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8362): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8389 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8111:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_8111/cgroup.procs: No such file or directory
,D/Finsky  ( 8389): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8389): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8389): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8389): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 8389): Skipping gmscore version check
,D/Finsky  ( 8389): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8389): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 8389): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8389): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  882): Killing 8241:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_8241/cgroup.procs: No such file or directory
,I/Icing   ( 1959): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1959): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  882): Killing 8330:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_8330/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Killing 8259:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_8259/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1417): run()
,I/Keyboard.Facilitator( 1417): flushDynamicLanguageModels()
,I/ConfigService( 1754): onCreate
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ConfigService( 1754): onDestroy
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=246, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310372, SEQNUM=4510, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-946, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2470): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6703): Connected to the server!
I/jxcore-log( 6703): 
,I/chromium( 6703): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  882): send {3daefe87, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): done {3daefe87, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=239, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310850, SEQNUM=4514, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-1280, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2470): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 6703): --- start :testFindPeers.js---
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): testFindPeers created [object Object]
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): serverPort is 8876
I/jxcore-log( 6703): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6703): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT4505
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6703): bind: Binding a new listener
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6703): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6703): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4505","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6703): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6703): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6703): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6703): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6703): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6703): start: OK
I/io.jxcore.node.ConnectionHelper( 6703): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT4505
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6703): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4505","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6703): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): start: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4505","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6703): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4505","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  882): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8033055c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8033055c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service
,D/WifiP2pService(  882): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): start: Starting P2P device discovery...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6703): start: OK
,I/jxcore-log( 6703): StartBroadcasting started ok
I/jxcore-log( 6703): 
I/chromium( 6703): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 6703): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6703): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6703): onDiscoveryManagerStateChanged: RUNNING
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 0 c0
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=5 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=5 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 6703): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service request added successfully
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service discovery started successfully
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-50
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] is available
,I/jxcore-log( 6703): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT818","peerAvailable":true}]
I/jxcore-log( 6703): 
I/jxcore-log( 6703): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 6703): 
I/jxcore-log( 6703): weAreDoneNow
I/jxcore-log( 6703): 
I/jxcore-log( 6703): done, now sending data to server
I/jxcore-log( 6703): 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 92
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 0 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:26000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1400): P2P-FIND-STOPPED 
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
,D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
,D/WifiP2pService(  882): InactiveState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-8ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
,D/WifiP2pService(  882): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-12ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-2ms what=139283 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
,V/AlarmManager(  882): send {3daefe87, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {b9b4bc6, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  882): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8455 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  882): done {3daefe87, *alarm*:android.intent.action.TIME_TICK} [84ms]
,I/GAv4    ( 8455): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8455):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8455):   adb logcat -s GAv4
,W/GAv4    ( 8455): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8455): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8455): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  882): done {b9b4bc6, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [346ms]
,I/ActivityManager(  882): Killing 8204:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_8204/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): Start timer timeout, starting now...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
I/wpa_supplicant( 1400): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=16 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139301 arg2=16 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6703): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service request added successfully
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 92
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139310 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service discovery started successfully
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
,D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] is available
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 1 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
,D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] is available
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-49
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] is available
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 92
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-53
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -53 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -53 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 2 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9383","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9383","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9383","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383] is available
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 3 c0
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172] is available
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 3 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 92
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 4 c0
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139307 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState clear service request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=24 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=24 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6703): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/io.jxcore.node.ConnectionHelper( 6703): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] removed
D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] not available
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service discovery started successfully
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=242, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311814, SEQNUM=4520, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11318, POWER_SUPPLY_CHARGE_COUNTER=-1490, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2470): Disconnected process message: 10, size: 0
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP ee:1f:
D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177] is available
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] is available
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] already in the list, will not add again
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172] already in the list, will not add again
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] is available
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9197","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9197","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9197","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197] is available
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 4 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 92
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 5 c0
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 0a
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 0a
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=-2ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139307 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=29 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=29 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6703): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service request added successfully
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service discovery started successfully
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] already in the list, will not add again
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706] is available
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9197","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9197","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9197","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], Bluetooth address: 90:E7:C4:F6:69:77, device name: , device address: 92:e7:c4:e6:4c:f8
,D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357] is available
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 6 c0
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] is available
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-3ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=-3ms what=139283 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=36 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=36 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6703): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service request added successfully
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service discovery started successfully
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3-1
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9197","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9197","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9197","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] already in the list, will not add again
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 92
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1400): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
,D/WifiP2pService(  882): InactiveState{ when=-10ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-10ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): discovery change broadcast false
,D/WifiP2pService(  882): InactiveState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-8ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  882): InactiveState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-13ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-14ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-14ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-14ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-14ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
,I/jxcore-log( 6703): teardown
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): testFindPeers stopped
I/jxcore-log( 6703): 
,I/io.jxcore.node.ConnectionHelper( 6703): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6703): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6703): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6703): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6703): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6703): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6703): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): stop: Stopping services
,D/WifiP2pService(  882): InactiveState{ when=0 what=139298 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139298 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): stop: Stopping P2P device discovery...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: NOT_INITIALIZED
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
D/WifiP2pService(  882): remove channel information from framework
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6703): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6703): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6703): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): setState: NOT_STARTED
,I/jxcore-log( 6703): StopBroadcasting went ok
I/jxcore-log( 6703): 
,I/chromium( 6703): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6703): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6703): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6703): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 6703): --- start :testSendData.js---
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 0
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): daya100000
I/jxcore-log( 6703): 
I/jxcore-log( 6703): check server
I/jxcore-log( 6703): 
I/jxcore-log( 6703): serverPort is 60561
I/jxcore-log( 6703): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6703): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT4505
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6703): bind: Binding a new listener
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6703): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6703): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4505","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6703): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6703): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6703): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6703): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6703): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6703): start: OK
I/io.jxcore.node.ConnectionHelper( 6703): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT4505
,D/BluetoothManagerService(  882): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6703): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4505","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6703): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): start: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4505","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6703): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4505","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  882): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8033055c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8033055c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service
,D/WifiP2pService(  882): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): start: Starting P2P device discovery...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6703): start: OK
,I/jxcore-log( 6703): StartBroadcasting started ok
I/jxcore-log( 6703): 
I/jxcore-log( 6703): null
I/jxcore-log( 6703): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Waiting for incoming connections...
,I/jxcore-log( 6703): 2016-01-05T00:47:23.644Z SendDataTCPServer.js: TCP/IP server is bound to port: 60561
I/jxcore-log( 6703): 
I/chromium( 6703): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6703): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6703): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1400): P2P-FIND-STOPPED 
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
,D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  882): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6703): onDiscoveryManagerStateChanged: RUNNING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 c0
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 7 c0
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=7 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=7 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pManager( 6703): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service request added successfully
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service discovery started successfully
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
,D/TCMD    (  488): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): Start timer timeout, starting now...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-40
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-49
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-54
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-58
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: Note4-1
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-2ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -58 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 7e
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 7e
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 0a
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 0a
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 92
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 7 
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2470): info:x10
,D/        ( 2470): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2470): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 c0
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 8 c0
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/BluetoothBondStateMachine( 2470): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,E/bt-btif ( 2470): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2470): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2470): Entering PendingCommandState State
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@90d65aa:true
,I/ActivityManager(  882): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetoothdeterminer.BTReceiver: pid=8517 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 2470): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2470): Failed to remove device: 08:EC:A9:50:75:41
,W/ResourcesManager( 8517): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/BluetoothBondStateMachine( 2470): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,D/BluetoothAdapterService( 2470): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1811f4bd
,D/BluetoothMetrics( 2470): btclass5a020c
,D/Checkin ( 2470): publish the event [tag = MOT_BT event name = PAIRING]
,I/BluetoothBondStateMachine( 2470): StableState(): Entering Off State
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3170d38:true
,W/bt-btif ( 2470): new conn_srvc id:26, app_id:255
W/bt-btif ( 2470): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2470): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Incoming connection initialized (thread ID: 811)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6703): Entering thread (ID: 811)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): onBytesRead: Read 82 bytes successfully (thread ID: 811)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): onBytesWritten: 81 bytes successfully written (thread ID: 811)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): removeThreadFromList: Removing thread with ID 811
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Handshake thread disposed (thread ID: 811)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6703): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6703): Exiting thread (ID: 811)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6703): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
I/io.jxcore.node.ConnectionHelper( 6703): onConnected: Incoming connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/io.jxcore.node.ConnectionHelper( 6703): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6703): onConnected: Incoming socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], created successfully
D/io.jxcore.node.ConnectionHelper( 6703): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 6703): Entering thread (ID: 812)
,I/io.jxcore.node.IncomingSocketThread( 6703): Local host address: localhost/127.0.0.1, port: 60561
,D/io.jxcore.node.IncomingSocketThread( 6703): Setting local streams and starting stream copying threads...
,I/jxcore-log( 6703): 2016-01-05T00:47:34.811Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6703): 
,I/io.jxcore.node.StreamCopyingThread( 6703): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6703): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6703): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6703): Exiting thread (ID: 812)
D/io.jxcore.node.StreamCopyingThread( 6703): Entering thread (ID: 814, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6703): Entering thread (ID: 813, name: Sender)
,I/ActivityManager(  882): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=8558 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8305:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_8305/cgroup.procs: No such file or directory
,W/ResourcesManager( 8558): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  882): Message: 20
,D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@385da077:true
,I/ActivityManager(  882): Killing 8362:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_8362/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.571Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.574Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.578Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.581Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.585Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.622Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.627Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6703): 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/jxcore-log( 6703): 2016-01-05T00:47:35.666Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.672Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.677Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.681Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.689Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.717Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.722Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.757Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.804Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.812Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.847Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.854Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.888Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.895Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.931Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.967Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:35.975Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6703): 
,W/bt-btif ( 2470): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 6703): Either failed to read from the output stream or write to the input stream (thread ID: 814, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6703): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6703): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 6703): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 812
,D/io.jxcore.node.IncomingSocketThread( 6703): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6703): doStop: Thread ID: 814
D/io.jxcore.node.IncomingSocketThread( 6703): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6703): doStop: Thread ID: 813
D/io.jxcore.node.IncomingSocketThread( 6703): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6703): closeLocalSocketAndStreams: Closing the local input stream...
,W/bt-rfcomm( 2470): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
,W/bt-rfcomm( 2470): RFCOMM_DisconnectInd LCID:0x41
,W/io.jxcore.node.StreamCopyingThread( 6703): Either failed to read from the output stream or write to the input stream (thread ID: 813, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6703): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6703): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6703): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 6703): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 6703): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6703): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6703): Exiting thread (ID: 814, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6703): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6703): Exiting thread (ID: 813, name: Sender)
,I/jxcore-log( 6703): 2016-01-05T00:47:36.058Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6703): 
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=17 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=19 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=19 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6703): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service request added successfully
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1400): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service discovery started successfully
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-36
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-2ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=-12ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-12ms what=147477 obj=Device: G3s-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] already in the list, will not add again
,E/bt-btm  ( 2470): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2470): onReceive
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=8590 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 44.361ms
,D/btif_config_util( 2470): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 26.319ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 19.805ms
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c01cd13:true
,I/BTConnectionReceiver( 8590): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 92:b6:
D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706] already in the list, will not add again
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8631 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/BluetoothClassifier( 8590): Bluetooth Device Name: A3-1
,I/ActivityManager(  882): Killing 8389:com.android.vending/u0a32 (adj 15): empty #7
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
W/libprocessgroup(  882): failed to open /acct/uid_10032/pid_8389/cgroup.procs: No such file or directory
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP a2:39:
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 7e:f9:
I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172] already in the list, will not add again
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 8 
,W/bt-btif ( 2470): info:x10
,D/        ( 2470): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2470): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2470): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
,E/bt-btif ( 2470): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2470): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2470): Entering PendingCommandState State
,I/ActivityManager(  882): Killing 1959:com.google.android.gms/u0a16 (adj 15): empty #7
,D/ConnectivityService(  882): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@26228d5a)
,D/ConnectivityService(  882): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiService(  882): Client connection lost with reason: 4
,E/ConnectivityService(  882): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_1959/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2470): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
D/BluetoothAdapterProperties( 2470): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 2470): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2470): StableState(): Entering Off State
,D/BluetoothMetrics( 2470): btclass5a020c
,D/Checkin ( 2470): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2470): new conn_srvc id:26, app_id:255
W/bt-btif ( 2470): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2470): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Incoming connection initialized (thread ID: 815)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6703): Entering thread (ID: 815)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): onBytesRead: Read 83 bytes successfully (thread ID: 815)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): onBytesWritten: 81 bytes successfully written (thread ID: 815)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): removeThreadFromList: Removing thread with ID 815
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Handshake thread disposed (thread ID: 815)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6703): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6703): Exiting thread (ID: 815)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6703): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
I/io.jxcore.node.ConnectionHelper( 6703): onConnected: Incoming connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/io.jxcore.node.ConnectionHelper( 6703): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6703): onConnected: Incoming socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], created successfully
D/io.jxcore.node.ConnectionHelper( 6703): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 6703): Entering thread (ID: 816)
,I/io.jxcore.node.IncomingSocketThread( 6703): Local host address: localhost/127.0.0.1, port: 60561
,D/io.jxcore.node.IncomingSocketThread( 6703): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6703): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6703): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6703): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6703): Exiting thread (ID: 816)
,I/jxcore-log( 6703): 2016-01-05T00:47:45.300Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6703): 
D/io.jxcore.node.StreamCopyingThread( 6703): Entering thread (ID: 817, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6703): Entering thread (ID: 818, name: Receiver)
,I/jxcore-log( 6703): 2016-01-05T00:47:46.045Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.058Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.091Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.098Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.104Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.111Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.118Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.158Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.215Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.221Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.227Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.268Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.350Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.388Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.434Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.440Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.446Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.477Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.506Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.512Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.518Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.558Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.606Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.615Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.659Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.699Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.707Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.772Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.811Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.848Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.854Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:47:46.887Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6703): 
,W/bt-btif ( 2470): invalid rfc slot id: 6
,W/io.jxcore.node.StreamCopyingThread( 6703): Either failed to read from the output stream or write to the input stream (thread ID: 818, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6703): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6703): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6703): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 816
D/io.jxcore.node.IncomingSocketThread( 6703): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6703): doStop: Thread ID: 818
D/io.jxcore.node.IncomingSocketThread( 6703): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6703): doStop: Thread ID: 817
D/io.jxcore.node.IncomingSocketThread( 6703): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread( 6703): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6703): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6703): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6703): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 6703): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6703): Exiting thread (ID: 818, name: Receiver)
,W/bt-rfcomm( 2470): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 2470): RFCOMM_DisconnectInd LCID:0x43
,W/io.jxcore.node.StreamCopyingThread( 6703): Either failed to read from the output stream or write to the input stream (thread ID: 817, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6703): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6703): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6703): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6703): Exiting thread (ID: 817, name: Sender)
,I/jxcore-log( 6703): 2016-01-05T00:47:47.019Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6703): 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 92
,E/bt-btm  ( 2470): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2470): onReceive
,I/BTConnectionReceiver( 8590): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8590): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/btif_config_util( 2470): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ActivityManager(  882): Waited long enough for: ServiceRecord{28043468 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1400): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,I/wpa_supplicant( 1400): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  292): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/WifiP2pService(  882): InactiveState{ when=-12ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-12ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
,D/WifiP2pService(  882): InactiveState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-7ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  882): InactiveState{ when=-12ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-12ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-14ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-15ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal,.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): Start timer timeout, starting now...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139265 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 9 c0
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 9 c0
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=139307 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139307 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=35 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=35 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6703): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service request added successfully
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 92
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service discovery started successfully
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177] already in the list, will not add again
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
,D/TCMD    (  488): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] already in the list, will not add again
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:e7:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP 92:e7:
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], Bluetooth address: 90:E7:C4:F6:69:77, device name: , device address: 92:e7:c4:e6:4c:f8
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357] already in the list, will not add again
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 9 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 9 
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 10 c
,D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 10 c
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 92
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 92
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
,D/TCMD    (  488): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172] already in the list, will not add again
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2437 02
,D/MDMCTBK (  292): Event received = P2P-SERV-DISC-REQ 2437 02
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 1400): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1400): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  292): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Android_608e
D/WifiP2pService(  882):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): restart: Restarting...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
,D/TCMD    (  488): Listening for incoming client connection request
--------- beginning of crash
F/libc    ( 1400): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 1400 (wpa_supplicant)
I/libc    ( 1400): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6703): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service request added successfully
,E/QC-QMI  (  436): qmuxd: RX on fd=27 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  436): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  436): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
E/QC-QMI  (  436): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
E/QC-QMI  (  436): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Failed to start the service discovery, got error code: 3
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,W/bt-btif ( 2470): info:x10
,D/        ( 2470): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2470): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2470): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,E/bt-btif ( 2470): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2470): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2470): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2470): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2470): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2470): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2470): StableState(): Entering Off State
,D/BluetoothMetrics( 2470): btclass5a020c
,D/Checkin ( 2470): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2470): new conn_srvc id:26, app_id:255
W/bt-btif ( 2470): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2470): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Incoming connection initialized (thread ID: 819)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6703): Entering thread (ID: 819)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): onBytesRead: Read 77 bytes successfully (thread ID: 819)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): onBytesWritten: 81 bytes successfully written (thread ID: 819)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): removeThreadFromList: Removing thread with ID 819
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Handshake thread disposed (thread ID: 819)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6703): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6703): Exiting thread (ID: 819)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6703): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,I/io.jxcore.node.ConnectionHelper( 6703): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/io.jxcore.node.ConnectionHelper( 6703): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6703): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], created successfully
D/io.jxcore.node.ConnectionHelper( 6703): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 6703): Entering thread (ID: 820)
,I/io.jxcore.node.IncomingSocketThread( 6703): Local host address: localhost/127.0.0.1, port: 60561
,D/io.jxcore.node.IncomingSocketThread( 6703): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6703): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6703): setBufferSize: Setting buffer size to 8192 bytes
I/jxcore-log( 6703): 2016-01-05T00:48:33.607Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6703): 
,I/io.jxcore.node.IncomingSocketThread( 6703): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6703): Exiting thread (ID: 820)
,D/io.jxcore.node.StreamCopyingThread( 6703): Entering thread (ID: 821, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6703): Entering thread (ID: 822, name: Receiver)
,I/jxcore-log( 6703): 2016-01-05T00:48:34.505Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.510Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.516Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.521Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.525Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.530Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.533Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.567Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.631Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.668Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.675Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.707Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.775Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.808Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.815Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.847Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.854Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.922Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.958Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:34.998Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:35.006Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:35.038Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:35.077Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): 2016-01-05T00:48:35.117Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6703): 
,W/bt-btif ( 2470): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread( 6703): Either failed to read from the output stream or write to the input stream (thread ID: 822, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6703): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6703): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6703): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 820
D/io.jxcore.node.IncomingSocketThread( 6703): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6703): doStop: Thread ID: 822
,D/io.jxcore.node.IncomingSocketThread( 6703): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6703): doStop: Thread ID: 821
,D/io.jxcore.node.IncomingSocketThread( 6703): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread( 6703): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.IncomingSocketThread( 6703): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 6703): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6703): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 6703): Either failed to read from the output stream or write to the input stream (thread ID: 821, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6703): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6703): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper( 6703): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6703): Exiting thread (ID: 822, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6703): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6703): Exiting thread (ID: 821, name: Sender)
,I/jxcore-log( 6703): 2016-01-05T00:48:35.167Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6703): 
,W/bt-rfcomm( 2470): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 2470): RFCOMM_DisconnectInd LCID:0x45
,E/bt-btm  ( 2470): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2470): onReceive
,I/BTConnectionReceiver( 8590): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8590): Bluetooth Device Name: G3-1
,D/btif_config_util( 2470): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,I/ActivityManager(  882): Waited long enough for: ServiceRecord{3eec2526 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] expired
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): checkListForExpiredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerLost: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/io.jxcore.node.ConnectionHelper( 6703): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] removed
D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] not available
,I/jxcore-log( 6703): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT3690","peerAvailable":false}]
I/jxcore-log( 6703): 
I/jxcore-log( 6703): Found peer : samsung-SM-A500FU_PT3690, Available: false
I/jxcore-log( 6703): 
I/jxcore-log( 6703): startWithNextDevice
I/jxcore-log( 6703): 
I/io.jxcore.node.ConnectionHelper( 6703): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/io.jxcore.node.ConnectionHelper( 6703): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] removed
,D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] not available
I/jxcore-log( 6703): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT1779","peerAvailable":false}]
I/jxcore-log( 6703): 
I/jxcore-log( 6703): Found peer : LGE-LG-D722_PT1779, Available: false
I/jxcore-log( 6703): 
I/jxcore-log( 6703): startWithNextDevice
I/jxcore-log( 6703): 
I/io.jxcore.node.ConnectionHelper( 6703): onPeerLost: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
D/io.jxcore.node.ConnectionHelper( 6703): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706] removed
D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706] not available
I/jxcore-log( 6703): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT706","peerAvailable":false}]
I/jxcore-log( 6703): 
I/jxcore-log( 6703): Found peer : samsung-SM-N910C_PT706, Available: false
I/jxcore-log( 6703): 
I/jxcore-log( 6703): startWithNextDevice
I/jxcore-log( 6703): 
I/io.jxcore.node.ConnectionHelper( 6703): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,D/io.jxcore.node.ConnectionHelper( 6703): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] removed
,D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] not available
,I/jxcore-log( 6703): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT818","peerAvailable":false}]
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): Found peer : samsung-SM-A300FU_PT818, Available: false
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): startWithNextDevice
I/jxcore-log( 6703): 
I/io.jxcore.node.ConnectionHelper( 6703): onPeerLost: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/io.jxcore.node.ConnectionHelper( 6703): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] removed
D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] not available
I/jxcore-log( 6703): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT6753","peerAvailable":false}]
I/jxcore-log( 6703): 
I/jxcore-log( 6703): Found peer : samsung-SM-A300FU_PT6753, Available: false
I/jxcore-log( 6703): 
I/jxcore-log( 6703): startWithNextDevice
I/jxcore-log( 6703): 
,E/WifiStateMachine(  882): Connection lost, restart supplicant
,E/WifiStateMachine(  882): setWifiState: disabled
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,E/WifiStateMachine(  882): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  882): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiConfigStore(  882): failed to set BSSID: any
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  289): Clearing all IP addresses on wlan0
,D/TCMD    (  488): NL - Read 60 bytes from update socket.
,D/TCMD    (  488): NL - ignore NL message, type = 21
,D/TCMD    (  488): Listening for incoming client connection request
,V/NativeCrypto( 1754): Read error: ssl=0xb9132a40: I/O error during system call, Connection timed out
,V/NativeCrypto( 1754): SSL shutdown failed: ssl=0xb9132a40: I/O error during system call, Broken pipe
,D/ConnectivityService(  882): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): ValidatedState{ when=-6ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-6ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info<unknown ssid>
,D/WifiMetrics(  882): connected time updated 601005
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,W/Settings( 1754): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: RESTARTING
,D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
,D/WifiScanningService(  882): SCAN_AVAILABLE : 1
D/RttService(  882): SCAN_AVAILABLE : 1
D/RttService(  882): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  882): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  882): [1,451,954,937,987 ms] noteScanEnd no scan source
D/WifiP2pService(  882): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): Failed to shutdown P2P device discovery, got error code: 0
,D/WifiP2pService(  882): discovery change broadcast false
,D/WifiP2pService(  882): P2pDisablingState
,D/WifiP2pService(  882): P2pDisablingState{ when=-2ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): p2p socket connection lost
,D/WifiP2pService(  882): P2pDisabledState
,D/WifiP2pService(  882): P2pDisabledState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 0 device(s) discovered
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): stop: Stopping services
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  882): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  882): NetworkAgent: NetworkAgent channel lost
D/Nat464Xlat(  882): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  882): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiP2pService(  882): P2pDisabledState{ when=-1ms what=139298 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139298 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Disconnected - quitting
E/WifiStateMachine(  882): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524292
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8759 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6703): Failed to clear local services, got error code: 2
I/io.jxcore.node.ConnectionHelper( 6703): onDiscoveryManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  882): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  882): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiP2pService(  882): P2pDisabledState{ when=0 what=139268 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=0 what=139268 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pDisabledState{ when=0 what=139307 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139307 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): Failed to shutdown P2P device discovery, got error code: 2
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Failed to clear service requests, got error code: 2
I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 8759): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8759): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8759): MmsConfig.loadMmsSettings
I/Babel_SMS( 8759): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 8759): MmsConfig.loadFromDatabase
,D/TCMD    (  488): NL - Read 1004 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/Tethering(  882): InitialState.processMessage what=4
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
,E/Babel_SMS( 8759): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8759): MmsConfig.loadFromResources
E/Babel_SMS( 8759): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8759): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/TCMD    (  488): NL - Read 68 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/art     (  882): Explicit concurrent mark sweep GC freed 53281(3MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.419ms total 134.713ms
,W/Settings( 8759): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8759): startup - clean
,I/Babel   ( 8759): deleted: false for 0
,D/TCMD    (  488): NL - Read 1004 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/TCMD    (  488): NL - Read 444 bytes from update socket.
D/TCMD    (  488): NL - ignore NL message, type = 17
D/TCMD    (  488): Listening for incoming client connection request
,W/VideoCapabilities( 8759): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8759): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8759): Unsupported mime video/mpeg2
,D/TCMD    (  488): NL - Read 1004 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/VideoCapabilities( 8759): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8759): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8759): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8759): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8759): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 8759): onServiceConnected
,W/Babel   ( 8759): Attempted to change video mute state without an active call.
,D/TCMD    (  488): NL - Read 444 bytes from update socket.
D/TCMD    (  488): NL - ignore NL message, type = 17
D/TCMD    (  488): Listening for incoming client connection request
,I/MDMCTBK (  292): NetlinkHandler, wifiStateChanged 0
,I/MDMCTBK (  292): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/OtaApp  ( 2588): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8797 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1465): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/CCE     ( 2588): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2588): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2588): Registering with Alarm Manager to restart CCE
,D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2588): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2588): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2588): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2588): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2588): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2588): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2588): [debug] > CusSM.onRadioDown
,I/MusicStore( 8797): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8797): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8797): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8797): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8797): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8797): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8797): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8797): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8797): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@950e6e9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8797): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8797): GMSCore installation verified
,I/ConfigStore( 8797): Config Database version: 1
,I/MediaRouter( 8797): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8797): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8845 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8797): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8797): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=8863 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,V/Mms     ( 8845): mnc/mcc: 
,V/Mms     ( 8845): tag: int value: recipientLimit - 20
V/Mms     ( 8845): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 8845): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8845): tag: int value: maxSubjectLength - 80
V/Mms     ( 8845): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8845): tag: bool value: enableGroupMms - false
V/Mms     ( 8845):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  882): Killing 8455:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/ResourcesManager( 8863): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8863): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8863): VM with version 2.1.0 has multidex support
,I/MultiDex( 8863): install
I/MultiDex( 8863): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  882): failed to open /acct/uid_10055/pid_8455/cgroup.procs: No such file or directory
,W/ResourcesManager( 8845): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8893 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8631:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,D/PhoneMonitor( 8893): Register our PhoneStateListener
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_8631/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 8893): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8893): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 8558:com.android.settings/1000 (adj 15): empty #7
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:27000 mC
,W/libprocessgroup(  882): failed to open /acct/uid_1000/pid_8558/cgroup.procs: No such file or directory
,V/JNIHelp ( 8863): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8863): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8863): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c56aa6c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8863): Installed default security provider GmsCore_OpenSSL
,D/NativeLibraryUtils( 8863): Install completed successfully. count=14 extracted=0
,I/iu.SyncManager( 8863): SYNC; picasa accounts
,D/NetworkLogImpl( 8863): Loaded NetworkSpeedPredictor
,I/ActivityManager(  882): Killing 8590:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_8590/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=8925 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8946 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 8759): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  882): Killing 8797:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_8797/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8946): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 8946): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8946):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8946):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8946): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8946): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8946): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8946): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 8946): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8946): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/WifiP2pService(  882): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/WebViewFactory( 8946): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8946): Time to load native libraries: 2 ms (timestamps 8006-8008)
I/LibraryLoader( 8946): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8946): Binding Chromium to main looper Looper (main, tid 1) {17c6be28}
I/LibraryLoader( 8946): Expected native library version number "",actual native library version number ""
,I/chromium( 8946): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8946): Initializing chromium process, singleProcess=true
,W/art     ( 8946): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 8946): ApplicationContext is null in ApplicationStatus
,W/chromium( 8946): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8946): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8946): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 8946): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8946): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8946): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8946): Local Branch: 
I/Adreno-EGL( 8946): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8946): Local Patches: NONE
I/Adreno-EGL( 8946): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 8946): Requires BLUETOOTH permission
,I/NSApplication( 8946): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9018 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 8845:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_8845/cgroup.procs: No such file or directory
,D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  882): ApnList is empty for checkDunConfigured()
,D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
,D/TCMD    (  488): NL - Read 1008 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering(  882): InitialState.processMessage what=4
D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
,D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  488): NL - Read 1008 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/QsoftapCmd(  289): Got softap fwreload command we are passing on
,D/SoftapController(  289): Softap fwReload - Ok
,D/CommandListener(  289): Setting iface cfg
,D/CommandListener(  289): Trying to bring down wlan0
D/CommandListener(  289): Clearing all IP addresses on wlan0
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9043 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 8893:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/wpa_supplicant( 9042): Successfully initialized wpa_supplicant
I/wpa_supplicant( 9042): Long line in configuration file truncated
,I/wpa_supplicant( 9042): rfkill: Cannot open RFKILL control device
D/TCMD    (  488): NL - Read 1004 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/TCMD    (  488): NL - Read 1004 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/libmdmdetect( 9042): ESOC framework not supported
E/Diag_Lib( 9042):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,E/wpa_supplicant( 9042): baseband property is set to [msm]
,I/libmdmdetect( 9042): ESOC framework not supported
,E/WifiStateMachine(  882): setWifiState: enabling
,E/WifiStateMachine(  882): Supplicant start successful
D/WifiMonitor(  882): startMonitoring(wlan0) with mConnected = false
W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_8893/cgroup.procs: No such file or directory
,E/wpa_supplicant( 9042):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 9042): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9042): card_info[i].card_state: 0x0
E/wpa_supplicant( 9042): card_info[i].error_code: 0x0
E/wpa_supplicant( 9042): SIM/USIM not ready
E/wpa_supplicant( 9042): Error while reading SIM card status
,E/wpa_supplicant( 9042): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9042): card_info[i].card_state: 0x0
,E/wpa_supplicant( 9042): card_info[i].error_code: 0x0
E/wpa_supplicant( 9042): SIM/USIM not ready
I/wpa_supplicant( 9042): eap_proxy: Card not ready
W/ResourcesManager( 9043): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 6703): timeout now
I/jxcore-log( 6703): 
I/jxcore-log( 6703): weAreDoneNow, resultArray.length: 0
I/jxcore-log( 6703): 
I/jxcore-log( 6703): sendReportNow
I/jxcore-log( 6703): 
I/jxcore-log( 6703): done, now sending data to server
I/jxcore-log( 6703): 
I/jxcore-log( 6703): 2016-01-05T00:49:03.643Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6703): 
,I/wpa_supplicant( 9042): Long line in configuration file truncated
I/wpa_supplicant( 9042): rfkill: Cannot open RFKILL control device
,D/TCMD    (  488): NL - Read 1004 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,E/wpa_supplicant( 9042): baseband property is set to [msm]
I/libmdmdetect( 9042): ESOC framework not supported
,E/wpa_supplicant( 9042):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9042): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 9042): card_info[i].card_state: 0x0
E/wpa_supplicant( 9042): card_info[i].error_code: 0x0
,E/wpa_supplicant( 9042): SIM/USIM not ready
E/wpa_supplicant( 9042): Error while reading SIM card status
,E/wpa_supplicant( 9042): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 9042): card_info[i].card_state: 0x0
E/wpa_supplicant( 9042): card_info[i].error_code: 0x0
E/wpa_supplicant( 9042): SIM/USIM not ready
I/wpa_supplicant( 9042): eap_proxy: Card not ready
I/wpa_supplicant( 9042): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,E/WifiStateMachine(  882): Supplicant connection established
E/WifiStateMachine(  882): setWifiState: enabled
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9068 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/WifiConfigStore(  882): Loading config and enabling all networks 
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiConfigStore(  882):  got CRC SSID "NG700" -> 1501448721
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.655ms
,E/WifiConfigStore(  882):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  882): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
W/Settings( 8759): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  882): Setting external_sim to 1
D/WifiStateMachine(  882): Setting OUI to DA-A1-19
I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa2e0a89c
D/wifi    (  882): halHandle = 0x0, mVM = 0xb8ded310, mCls = 0x1011c2
I/WifiNative-HAL(  882): Could not start hal
,E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/wpa_supplicant( 9042): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/native  (  882): do suspend true
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 19.541ms
,D/WifiP2pService(  882): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  289): Setting iface cfg
,D/CommandListener(  289): Trying to bring up p2p0
D/WifiMonitor(  882): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  882): P2pEnablingState
D/WifiP2pService(  882): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2p socket connection successful
D/WifiP2pService(  882): P2pEnabledState
D/WifiP2pService(  882): sending p2p connection changed broadcast
,D/WifiScanningService(  882): SCAN_AVAILABLE : 3
D/RttService(  882): SCAN_AVAILABLE : 3
D/WifiScanningService(  882): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  882): startHal
E/wifi    (  882): getStaticLongField sWifiHalHandle 0xa19329cc
D/wifi    (  882): halHandle = 0x0, mVM = 0xb8ded310, mCls = 0x20116e
I/WifiNative-HAL(  882): Could not start hal
E/WifiScanningService(  882): could not start HAL
D/RttService(  882): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-HAL(  882): p2pGetDeviceAddress
,D/WifiNative-HAL(  882): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT4505
,D/WifiP2pService(  882): DeviceAddress: 44:80:eb:7b:5a:07
,D/WifiP2pService(  882): MCC mode enabled 0
E/WifiStateMachine(  882): set country code US
,D/WifiP2pService(  882): mP2pAutoConnectSupport = 0
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 19.963ms
D/WifiP2pService(  882): sending p2p persistent groups changed broadcast
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): start: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4505","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6703): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4505","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
E/WifiStateMachine(  882): set frequency band 2
D/WifiP2pService(  882): InactiveState
D/WifiP2pService(  882): InactiveState{ when=-4ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-4ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 9042): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): InactiveState{ when=-8ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-8ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139292 arg2=48 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8033055c target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139292 arg2=48 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8033055c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service
,D/WifiP2pService(  882): add a new client
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6703): Local service added successfully
D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: RESTARTING
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info0x
D/WifiP2pService(  882): discovery change broadcast true
,I/io.jxcore.node.ConnectionHelper( 6703): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: STARTED
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 9042): P2P-FIND-STOPPED 
D/WifiP2pService(  882): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: RESTARTING
D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=51 target=com.android.internal.util.StateMachine$SmHandler }
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  882): Killing 8759:com.google.android.talk/u0a70 (adj 15): empty #7
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/MDMCTBK (  292): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  292): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): wifi_connect_to_supplicant, current pid is = 292
,D/MDMCTBK (  292): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  292): wifi_close_sockets: Exit
,E/MDMCTBK (  292): Attach monitor thread
D/MDMCTBK (  292): wifi_ctrl_recv: Exiting
D/MDMCTBK (  292): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  292): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  292): wifi_close_sockets: Exit
,I/ContactLocale( 9068): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 8925:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2588): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_8925/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_8759/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2588): bindWebServices(): registering our AIDL callback...
I/SundryService( 2588): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2588): ServiceHandler.handleMessage: mWaitCount=0
,I/art     (  882): Explicit concurrent mark sweep GC freed 27797(1482KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.574ms total 122.184ms
,D/GetNotificationsWS( 2588): onServiceConnected()
,D/GetNotificationsWS( 2588): onServiceConnected(): Registered for remote service callbacks...
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=9103 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GetNotificationsWS( 2588): unbindWebServices(): un-registering our AIDL callback...
,D/TCMD    (  488): NL - Read 1004 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/MusicStore( 9103): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9103): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9103): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9103): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 9103): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9103): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9103): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9103): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 9103): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@950e6e9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9103): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 9103): GMSCore installation verified
,I/ConfigStore( 9103): Config Database version: 1
,I/MediaRouter( 9103): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 9103): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledStateupdate channel list
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9135 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 9103): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 9103): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 8946:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_8946/cgroup.procs: No such file or directory
,V/Mms     ( 9135): mnc/mcc: 
,V/Mms     ( 9135): tag: int value: recipientLimit - 20
V/Mms     ( 9135): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 9135): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9135): tag: int value: maxSubjectLength - 80
V/Mms     ( 9135): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 9135): tag: bool value: enableGroupMms - false
V/Mms     ( 9135):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 9135): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9170 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9018:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_9018/cgroup.procs: No such file or directory
,D/PhoneMonitor( 9170): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 9170): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 9170): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 9043:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_9043/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9189 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9212 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9068:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_9068/cgroup.procs: No such file or directory
,W/ResourcesManager( 9212): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 9042): CTRL_IFACE: Detach monitor /data/misc/cutback/wpa_ctrl_292-4\x00 that cannot receive messages
,I/wpa_supplicant( 9042): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  882): [1,451,954,945,735 ms] noteScanEnd no scan source
,E/WifiStateMachine(  882): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2a765b21 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  882): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  882):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,E/WifiConfigStore(  882): will read network variables netId=0
,E/WifiStateMachine(  882): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  882): will read network variables netId=0
,E/WifiConfigStore(  882): setLastSelectedConfiguration -1
,I/Babel_SMS( 9212): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 9212): MmsConfig.loadMmsSettings
I/Babel_SMS( 9212): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9212): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9212): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 9212): MmsConfig.loadFromResources
,E/Babel_SMS( 9212): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 9212): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9212): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9212): startup - clean
,I/Babel   ( 9212): deleted: false for 0
,I/wpa_supplicant( 9042): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,I/wpa_supplicant( 9042): wlan0: Trying to associate with SSID 'NG700'
,D/WifiMonitor(  882): didn't find BSSID Trying to associate with SSID 'NG700'
D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 9042): DSDS: eapol_sm_notify_config config->sim_num = 1
D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9250 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=53 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState add service request
,D/WifiP2pManager( 6703): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service request added successfully
,D/TCMD    (  488): NL - Read 312 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 192 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 68 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 1004 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/Tethering(  882): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  882): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  882): ApnList is empty for checkDunConfigured()
D/Tethering(  882):  upstream interface types: 
D/Tethering(  882):  0
D/Tethering(  882):  1
D/Tethering(  882):  5
D/Tethering(  882):  7
D/Tethering(  882): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 9042): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  488): NL - Read 80 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 80 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/TCMD    (  488): NL - Read 68 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  882): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 9042): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 9042): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  488): NL - Read 1004 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  882): Network connection established
E/WifiStateMachine(  882): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  882): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  882): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  882): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  882): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 2
E/WifiStateMachine(  882): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  882): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  882): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  289): Setting iface cfg
E/WifiStateMachine(  882): Start Dhcp Watchdog 3
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend false
,E/wpa_supplicant( 9042): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  882): Unexpected BatchedScanResults :null
E/wpa_supplicant( 9042): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2276edc9 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2276edc9 target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 9212): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9212): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9212): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9212): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9212): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9212): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9212): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9212): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9250): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9250): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
I/GAv4    ( 9250): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9250):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9250):   adb logcat -s GAv4
W/ContextImpl( 9250): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
I/vclib   ( 9212): onServiceConnected
W/Babel   ( 9212): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9250): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 9212): connection state changed from UNKNOWN to DISCONNECTED
,W/GAv4    ( 9250): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  882): Killing 9103:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/GAv4    ( 9250): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9250): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/DHCPCD  ( 9286): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 9286): version 5.5.6 starting
,E/DHCPCD  ( 9286): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 9286): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 9286): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_9103/cgroup.procs: No such file or directory
,D/DHCPCD  ( 9286): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 9286): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 9286): wlan0: sending REQUEST (xid 0x2a837bff), next in 4.27 seconds
,I/WebViewFactory( 9250): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9250): Time to load native libraries: 1 ms (timestamps 1606-1607)
,I/LibraryLoader( 9250): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9250): Binding Chromium to main looper Looper (main, tid 1) {17c6be28}
,I/LibraryLoader( 9250): Expected native library version number "",actual native library version number ""
I/chromium( 9250): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9250): Initializing chromium process, singleProcess=true
,W/art     ( 9250): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 9250): ApplicationContext is null in ApplicationStatus
,W/chromium( 9250): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9250): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 9250): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 9250): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9250): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9250): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9250): Local Branch: 
I/Adreno-EGL( 9250): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9250): Local Patches: NONE
I/Adreno-EGL( 9250): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 9250): Requires BLUETOOTH permission
,I/NSApplication( 9250): Starting up...
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9331 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9135:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_9135/cgroup.procs: No such file or directory
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9350 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 9170:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_9170/cgroup.procs: No such file or directory
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
W/ResourcesManager( 9350): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Failed to start the service discovery, got error code: 2
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9373 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9212:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 9373): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 9189:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10070/pid_9212/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_9189/cgroup.procs: No such file or directory
,D/WearableService( 1754): callingUid 10016, callindPid: 1754
,E/MDM     ( 1754): [212] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 8863): Restart initialization of location
,D/AuthorizationBluetoothService( 1754): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1754): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 8863): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8863): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=9405 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  882): send {3daefe87, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  882): send {239c6cd0, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/DHCPCD  ( 9286): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 9286): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 9286): wlan0: adding IP address 192.168.1.123/24
D/TCMD    (  488): NL - Read 60 bytes from update socket.
D/TCMD    (  488): NL - ignore NL message, type = 20
D/TCMD    (  488): Listening for incoming client connection request
D/DHCPCD  ( 9286): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 9286): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 9286): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 9286): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/art     (  882): Explicit concurrent mark sweep GC freed 26058(1282KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.830ms total 123.553ms
,V/AlarmManager(  882): done {3daefe87, *alarm*:android.intent.action.TIME_TICK} [207ms]
,W/IcingInternalCorpora( 8863): getNumBytesRead when not calculated.
,W/GCoreFlp( 1754): No location to return for getLastLocation()
,W/FusedLocationProvider( 1754): location=null
,E/WifiStateMachine(  882): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  882): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  882): do suspend true
,D/WifiP2pService(  882): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  882): WifiStateMachine DHCP successful
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  882): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  882): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  882): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  882): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  882): Adding iface wlan0 to network 102
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  882): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  882): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  882): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  882): Adding Route [fe80::/64 -> :: wlan0] to network 102
E/WifiStateMachine(  882): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  882): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,D/ConnectivityService(  882): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,D/ConnectivityService(  882): Setting Dns servers for network 102 to [/192.168.1.1]
I/SBar.MotoNetworkCtrlr( 1291): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Connected
D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
D/CSLegacyTypeTracker(  882): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1531): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1291): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  882): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,V/AlarmManager(  882): done {239c6cd0, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [532ms]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 00:49:08 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451954948203], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451954948180]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Validated
D/ConnectivityService(  882): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1531): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1291): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1531): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/ModemStatsDSDetect( 1531): Inetcondition changed, white->blue
I/SBar.MotoNetworkCtrlr( 1291): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/ModemStatsDSDetect( 1531): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1291): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1291): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/GCM     ( 1754): Ack for not saved message 35
,I/ActivityManager(  882): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9477 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 25.365ms
,W/ResourcesManager( 9477): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.968ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.807ms
,I/Babel_SMS( 9477): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 9477): MmsConfig.loadMmsSettings
,I/Babel_SMS( 9477): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 9477): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9477): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 9477): MmsConfig.loadFromResources
,E/Babel_SMS( 9477): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 9477): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9477): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9477): startup - clean
,I/Babel   ( 9477): deleted: false for 0
,W/art     ( 9477): Suspending all threads took: 12.538ms
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): Start timer timeout, starting now...
D/WifiP2pService(  882): InactiveState{ when=0 what=139265 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139265 arg2=55 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 9042): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  882): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/VideoCapabilities( 9477): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9477): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9477): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9477): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9477): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9477): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9477): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9477): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  882): Killing 9250:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/ConnectivityService(  882): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/wpa_supplicant( 9042): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 4488
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_9250/cgroup.procs: No such file or directory
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
I/vclib   ( 9477): onServiceConnected
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,W/Babel   ( 9477): Attempted to change video mute state without an active call.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,I/wpa_supplicant( 9042): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,E/WifiStateMachine(  882): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  882): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/Nat464Xlat(  882): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  882): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524295
,E/WifiStateMachine(  882): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,I/wpa_supplicant( 9042): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/ConnectivityService(  882): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  882): MasterInitialState.processMessage what=3
,D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2588): now: 686032 ,futureTime: 9223372036854775807
D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2588): now: 686032 ,futureTime: 9223372036854775807
,D/PollingManager( 2588): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2588): now: 686032 ,futureTime: 9223372036854775807
D/OtaApp  ( 2588): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1465): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  882): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=9514 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2588): [debug] > PollingManagerService, now: 686095 ,futureTime: 55999045
D/OtaApp  ( 2588): [debug] > Polling alarm set to expire at: 55999045 Current Time: 686096
,D/Central_PollingManager( 1465): now: 686098 ,futureTime: 86476495
D/Central_PollingManager( 1465): Polling alarm set to expire at: 86476495 Current Time: 686098
,D/OtaApp  ( 2588): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2588): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2588): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2588): isDeviceProvisioned: deviceId = 2072049230914535424
,D/OtaApp  ( 2588): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2588): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2588): publish the event [tag = MOT_OTA event name = LOG]
,D/CCE     ( 2588): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2588): createDeviceIdOrLogin update_device
,D/Checkin ( 2588): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2588): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2588): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2588): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2588): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2588): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiProvisionService( 2588): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2588): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2588): createDeviceIdOrLogin update_device
,D/Checkin ( 2588): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2588): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2588): set mOutstandingReq to true.
,I/ Nonce  ( 2588):  Nonce getNonce 
I/ Nonce  ( 2588):  Nonce Request 
I/ Nonce  ( 2588):  Nonce execute Request 
D/MMApiWebService( 2588): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2588): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2588): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2588): createDeviceIdOrLogin update_device
D/Checkin ( 2588): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2588): Not proxy app, so login/provision not allowed
,D/MMApiWebService( 2588): generating token using payload instead of using session token
,D/ Nonce  ( 2588):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MusicStore( 9514): Database version: 120
,I/MMApiWSBase( 2588): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2588): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9514): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9514): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9514): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 9514): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9514): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9514): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9514): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9514): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@950e6e9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9514): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 9514): GMSCore installation verified
,I/ConfigStore( 9514): Config Database version: 1
,I/MediaRouter( 9514): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 9514): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 9514): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 9514): type=WIFI subType= reason=null isConnected=true
,I/wpa_supplicant( 9042): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  882): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9566 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/Mms     ( 9566): mnc/mcc: 
V/Mms     ( 9566): tag: int value: recipientLimit - 20
,V/Mms     ( 9566): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 9566): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9566): tag: int value: maxSubjectLength - 80
V/Mms     ( 9566): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 9566): tag: bool value: enableGroupMms - false
,V/Mms     ( 9566):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/art     (  882): Explicit concurrent mark sweep GC freed 18423(906KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.786ms total 155.041ms
,W/ResourcesManager( 9566): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 5721): Explicit concurrent mark sweep GC freed 1771(64KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 359us total 23.782ms
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9600 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/GHttpClientFactory( 9514): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 9514): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  882): Killing 9350:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 9600): Register our PhoneStateListener
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ActivityManager(  882): Killing 9331:com.android.chrome/u0a52 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_9350/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_9331/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 9600): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 9600): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  882): Killing 9373:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_9373/cgroup.procs: No such file or directory
,I/CheckinService( 8863): Checkin interval check for package: unspecified last checkin: 1451954516207 min interval config: 0 actual interval: 435972
,I/CheckinService( 8863): Disabling old GoogleServicesFramework version
,I/iu.Environment( 8863): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 8863): num queued entries: 0
,I/iu.UploadsManager( 8863): num updated entries: 0
I/iu.SyncManager( 8863): NEXT; no task
,D/ConnectivityService(  882): reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 00:49:12 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451954952266], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451954952249]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  882): Validated
D/ConnectivityService(  882): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  882): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1291): CM callback handler got msg 524290
,I/jxcore-log( 6703): Connected to the server!
I/jxcore-log( 6703): 
,I/chromium( 6703): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  882): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9629 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 8863): Checking schedule, now: 1451954952300 next: 1451954546186
I/CheckinService( 8863): active receiver: enabled
,I/ Nonce  ( 2588):  Nonce Reponse 
D/        ( 2588): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"469005c7-48b8-4d9c-99d3-c340e508631d"}
D/MMApiWSBase( 2588): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ Nonce  ( 2588):  Nonce Handle Reponse 
D/MMApiProvisionService( 2588): mOutstandingReq set to false
,I/CheckinService( 8863): Preparing to send checkin request
,I/EventLogService( 8863): Accumulating logs since 1451954512286
,I/Babel   ( 9477): connection state changed from UNKNOWN to CONNECTED
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 5898(295KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 7MB/12MB, paused 503us total 47.497ms
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9629): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9629): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 9629): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9629):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9629):   adb logcat -s GAv4
,D/MMApiProvisionService( 2588):  pTime 1451923699777 sExp 172742 cTime 1451954952459 tTime 1452096441777
D/MMApiProvisionService( 2588):  No login Required 
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9629): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 9629): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9629): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 9629): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9629): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/CheckinRequestBuilder( 8863): Checkin reason type: 8 attempt count: 1
,D/WifiService(  882): New client listening to asynchronous messages
,E/ActivityThread( 8863): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1754): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1754): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 9042): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  882): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=9681 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/wpa_supplicant( 9042): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-26
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -26 target=com.android.internal.util.StateMachine$SmHandler }
,I/WebViewFactory( 9629): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
I/LibraryLoader( 9629): Time to load native libraries: 2 ms (timestamps 7735-7737)
I/LibraryLoader( 9629): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 9629): Binding Chromium to main looper Looper (main, tid 1) {81424e6}
I/LibraryLoader( 9629): Expected native library version number "",actual native library version number ""
,I/chromium( 9629): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/ResourcesManager( 9681): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9681): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/BrowserStartupController( 9629): Initializing chromium process, singleProcess=true
W/art     ( 9629): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 9629): ApplicationContext is null in ApplicationStatus
W/DataUsage( 2588): invalid counter update blocked: 'err' by 0
D/Checkin ( 2588): publish the event [tag = MOT_CCE event name = LOG]
,I/MultiDex( 9681): VM with version 2.1.0 has multidex support
I/MultiDex( 9681): install
I/MultiDex( 9681): VM has multidex support, MultiDex support library is disabled.
W/chromium( 9629): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9629): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 9629): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 9629): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9629): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9629): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9629): Local Branch: 
I/Adreno-EGL( 9629): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9629): Local Patches: NONE
I/Adreno-EGL( 9629): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,V/JNIHelp ( 9681): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/AudioManagerAndroid( 9629): Requires BLUETOOTH permission
,I/NSApplication( 9629): Starting up...
,W/ActivityThread( 9681): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9681): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@17b8c236: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9681): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  882): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9718 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 9681): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 9681): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  882): Killing 9514:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/NativeLibraryUtils( 9681): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  882): failed to open /acct/uid_10080/pid_9514/cgroup.procs: No such file or directory
,D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
,I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9739 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Killing 9566:com.android.mms/u0a23 (adj 15): empty #7
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
,E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb5458960
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb82e7810, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8381f58, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb83cd8f0, idLength=0xb5558730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  295): PrepareKeyRequest: nonce=3170916887
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb827ffb8
D/DrmWidevineDash(  295): message_length=1591, signature=0xb8307020, signature_length=3042281236
,W/libprocessgroup(  882): failed to open /acct/uid_10023/pid_9566/cgroup.procs: No such file or directory
,W/ResourcesManager( 9739): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/wpa_supplicant( 9042): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 9759): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 9759): dex2oat took 64.925ms (threads: 4)
,I/ActivityManager(  882): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9766 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Adreno-EGL( 9681): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9681): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9681): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9681): Local Branch: 
I/Adreno-EGL( 9681): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9681): Local Patches: NONE
I/Adreno-EGL( 9681): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  882): Killing 9405:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/Adreno-EGL( 9681): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9681): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9681): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9681): Local Branch: 
I/Adreno-EGL( 9681): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9681): Local Patches: NONE
I/Adreno-EGL( 9681): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ContactLocale( 9766): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  882): Killing 9600:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,E/MDMCTBK (  292): Unable to attach monitor connection to supplicant on @android:wpa_wlan0
,D/MDMCTBK (  292): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  292): wifi_close_sockets: Exit
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/EmailService.MarketingOptInSetter( 2588): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_9405/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_9600/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2588): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2588): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2588): ServiceHandler.handleMessage: mWaitCount=0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
D/GetNotificationsWS( 2588): onServiceConnected()
D/GetNotificationsWS( 2588): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2588): unbindWebServices(): un-registering our AIDL callback...
D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
E/QSEECOMAPI: (  295): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  295): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  295): App is not loaded in QSEE
,D/OtaApp  ( 2588): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2588): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2588): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2588): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  882): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/wpa_supplicant( 9042): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f7d000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  295): hlos api version =  9
,D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb5458960
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb8307150, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb83c1490, wrapped_rsa_key_length=1280
,I/ActivityManager(  882): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=9797 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb83cd930, idLength=0xb0e45730
,D/OtaApp  ( 2588): [debug] > DownloadActivity, FormattedText
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
I/OtaApp  ( 2588): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
,D/Checkin ( 2588): publish the event [tag = MOT_OTA event name = LOG]
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=1715712598
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb827ffb8
D/DrmWidevineDash(  295): message_length=1626, signature=0xb82628a0, signature_length=2967754516
D/OtaApp  ( 2588): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2588): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2588): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2588): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2588): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2588): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2588): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2588): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2588): publish the event [tag = MOT_OTA event name = LOG]
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 9681): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9681): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9681): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9681): Local Branch: 
I/Adreno-EGL( 9681): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9681): Local Patches: NONE
I/Adreno-EGL( 9681): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/WearableService( 1754): callingUid 10016, callindPid: 1754
,I/Adreno-EGL( 9681): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9681): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9681): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9681): Local Branch: 
I/Adreno-EGL( 9681): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9681): Local Patches: NONE
I/Adreno-EGL( 9681): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/art     (  882): Explicit concurrent mark sweep GC freed 12905(630KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.640ms total 115.122ms
,I/ActivityManager(  882): Killing 9629:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,E/MDM     ( 1754): [151] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/libprocessgroup(  882): failed to open /acct/uid_10081/pid_9629/cgroup.procs: No such file or directory
D/LocationInitializer( 8863): Restart initialization of location
,D/AuthorizationBluetoothService( 1754): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1754): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1754): No location to return for getLastLocation()
W/FusedLocationProvider( 1754): location=null
,I/CheckinRequestBuilder( 8863): Classify the device as Phone.
,I/wpa_supplicant( 9042): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
,D/TCMD    (  488): Listening for incoming client connection request
,I/CheckinTask( 8863): Sending checkin request (9561 bytes)
,I/wpa_supplicant( 9042): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,I/CheckinRequestBuilder( 8863): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 8863): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 8863): Classify the device as Phone.
,I/CheckinTask( 8863): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 8863): Checking schedule, now: 1451954956663 next: 1452556093647
,I/CheckinService( 8863): active receiver: disabled
,D/CheckinService( 8863): Recording last checkin time for package unspecified as 1451954956676
,I/wpa_supplicant( 9042): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  882): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=9848 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 9848): Register our PhoneStateListener
,V/SetupWizard( 9848): Connected to Gservices successfully
,I/ActivityManager(  882): Killing 9718:com.android.chrome/u0a52 (adj 15): empty #7
,I/wpa_supplicant( 9042): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,I/wpa_supplicant( 9042): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,W/libprocessgroup(  882): failed to open /acct/uid_10052/pid_9718/cgroup.procs: No such file or directory
,D/WifiP2pService(  882): InactiveState{ when=-13ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-13ms what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=-1ms what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): restart: Restarting...
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-1ms what=139307 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=139307 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,D/WifiP2pService(  882): InactiveState{ when=0 what=139301 arg2=61 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139301 arg2=61 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState add service request
D/WifiP2pManager( 6703): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service request added successfully
D/GCM     ( 1754): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/AlarmManager(  882): send {239c6cd0, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  882): done {239c6cd0, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [4ms]
,I/GCM     ( 1754): Ack for not saved message 35
,I/wpa_supplicant( 9042): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
,D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=139310 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139310 arg2=62 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState discover services
,I/wpa_supplicant( 9042): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service discovery started successfully
,I/wpa_supplicant( 9042): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-33
,D/WifiP2pService(  882): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: 10-0050F204-5
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 392
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 37
D/WifiP2pService(  882):  status: 3
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: -33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): InactiveState{ when=0 what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): DefaultState{ when=0 what=139283 arg2=63 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,D/TCMD    (  488): NL - Read 56 bytes from update socket.
D/TCMD    (  488): NL - message type is RTM_NEWLINK
D/TCMD    (  488): Listening for incoming client connection request
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6172","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6172] already in the list, will not add again
,D/WifiP2pService(  882): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] is available
,I/jxcore-log( 6703): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT6753","peerAvailable":true}]
I/jxcore-log( 6703): 
I/jxcore-log( 6703): Found peer : samsung-SM-A300FU_PT6753, Available: true
I/jxcore-log( 6703): 
I/jxcore-log( 6703): startWithNextDevice
I/jxcore-log( 6703): 
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818]
,I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 6703): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT818] is available
,I/jxcore-log( 6703): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT818","peerAvailable":true}]
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): Found peer : samsung-SM-A300FU_PT818, Available: true
I/jxcore-log( 6703): 
I/jxcore-log( 6703): startWithNextDevice
I/jxcore-log( 6703): 
,I/MDMCTBK (  292): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  292): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  292): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/WifiP2pService(  882): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:e7:c4:e6:4c:f8 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
I/io.jxcore.node.ConnectionHelper( 6703): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], Bluetooth address: 90:E7:C4:F6:69:77, device name: , device address: 92:e7:c4:e6:4c:f8
,W/io.jxcore.node.ConnectionHelper( 6703): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357] already in the list, will not add again
,I/ActivityManager(  882): Killing 9766:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  882): Killing 9739:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  882): failed to open /acct/uid_10007/pid_9766/cgroup.procs: No such file or directory
,W/libprocessgroup(  882): failed to open /acct/uid_10090/pid_9739/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=9891 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 28.981ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 19.525ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 20.508ms
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  882): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  882): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  882): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2c7ab161
,I/GCoreNlp( 1754): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1573): Deferring update until onResume
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=9929 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=9951 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9797:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10088/pid_9797/cgroup.procs: No such file or directory
,W/ResourcesManager( 9477): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9477): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9477): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 9477): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9477): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=9973 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9848:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 9951): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  882): failed to open /acct/uid_10035/pid_9848/cgroup.procs: No such file or directory
,W/asset   ( 9973): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 9973): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 9973): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 9973): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 8863): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/Launcher( 1573): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1f2e635f new=com.google.android.velvet.VelvetApplication@1f2e635f
,I/UpdateIcingCorporaServi( 9891): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  882): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=9998 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 8863): Null package name or gms related package.  Ignoreing.
,W/ResourcesManager( 9998): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 9891): UpdateCorporaTask done [took 138 ms] updated apps [took 138 ms] 
,I/Icing   ( 8863): Storage manager: low false usage 1.70MB avail 3.11GB capacity 4.85GB
,I/ActivityManager(  882): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=10036 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 8863): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  882): Killing 9681:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10016/pid_9681/cgroup.procs: No such file or directory
,I/Icing   ( 8863): Internal init done: storage state 0
,I/Icing   ( 8863): Post-init done
,I/Icing   ( 8863): updateResources: need to parse f{com.google.android.gms}
,W/SQLiteConnectionPool( 8863): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/art     (  882): Explicit concurrent mark sweep GC freed 18915(1036KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.934ms total 121.009ms
,D/Finsky  (10036): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  (10036): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(10036): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(10036): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  (10036): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  (10036): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     (10036): Skipping gmscore version check
,D/Finsky  (10036): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  (10036): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  882): Killing 9929:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10019/pid_9929/cgroup.procs: No such file or directory
,I/jxcore-log( 6703): teardown
I/jxcore-log( 6703): 
,I/jxcore-log( 6703): testSendData stopped
I/jxcore-log( 6703): 
,I/io.jxcore.node.ConnectionHelper( 6703): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6703): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6703): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6703): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6703): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6703): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6703): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6703): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6703): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): stop: Stopping P2P device discovery...
,D/WifiP2pService(  882): InactiveState{ when=0 what=139298 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=0 what=139298 arg2=64 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): setState: NOT_INITIALIZED
D/WifiP2pService(  882): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6703): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6703): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6703): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6703): setState: NOT_STARTED
I/jxcore-log( 6703): StopBroadcasting went ok
I/jxcore-log( 6703): 
D/WifiP2pService(  882): InactiveState{ when=0 what=139268 arg2=65 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 9042): P2P-FIND-STOPPED 
I/wpa_supplicant( 9042): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 9042): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 9042): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 9042): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/jxcore-log( 6703): 2016-01-05T00:49:24.276Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 6703): 
I/io.jxcore.node.ConnectionHelper( 6703): onConnectionManagerStateChanged: NOT_STARTED
I/chromium( 6703): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 6703): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6703): Local services cleared successfully
D/WifiP2pService(  882): InactiveState{ when=-5ms what=139307 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-5ms what=139307 arg2=66 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState clear service request
D/WifiP2pService(  882): remove channel information from framework
D/WifiP2pService(  882): InactiveState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6703): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6703): Service requests cleared successfully
D/WifiP2pService(  882): InactiveState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): P2pEnabledState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  882): InactiveState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  882): P2pEnabledState{ when=-3ms what=147478 obj=Device: 
D/WifiP2pService(  882):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  882):  primary type: null
D/WifiP2pService(  882):  secondary type: null
D/WifiP2pService(  882):  wps: 0
D/WifiP2pService(  882):  grpcapab: 0
D/WifiP2pService(  882):  devcapab: 0
D/WifiP2pService(  882):  status: 4
D/WifiP2pService(  882):  wfdInfo: null
D/WifiP2pService(  882):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 6703): ****TEST TOOK:  ms ****
I/jxcore-log( 6703): 
I/jxcore-log( 6703): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6703): 
,D/AndroidRuntime(10082): 
D/AndroidRuntime(10082): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(10082): CheckJNI is OFF
,I/Icing   ( 8863): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 8863): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 8863): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  882): Killing 9973:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10027/pid_9973/cgroup.procs: No such file or directory
,D/AndroidRuntime(10082): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  882): Force stopping com.test.thalitest appid=10408 user=-1: uninstall pkg
I/ActivityManager(  882): Killing 6703:com.test.thalitest/u0a408 (adj 9): stop com.test.thalitest
,D/WifiService(  882): Client connection lost with reason: 4
,I/WindowState(  882): WIN DEATH: Window{1d0bae8e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  882): Skipping PackageSetting{1a56a02a com.example.hello/10406} due to missing metadata
,I/ActivityManager(  882):   Force finishing activity ActivityRecord{2361ceeb u0 com.test.thalitest/.MainActivity t3}
,W/ActivityManager(  882): Spurious death for ProcessRecord{22bd386e 6703:com.test.thalitest/u0a408}, curProc for 6703: null
,I/ActivityManager(  882): Force stopping com.test.thalitest appid=10408 user=0: pkg removed
,I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1754): Ignoring removeGeofence because network location is disabled.
,I/art     ( 3034): Explicit concurrent mark sweep GC freed 12504(2MB) AllocSpace objects, 17(272KB) LOS objects, 39% free, 7MB/12MB, paused 1.371ms total 50.633ms
,I/Keyboard.Facilitator( 1417): resetDictionaries() : en_US
,D/VoicemailCleanupService( 9951): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.DecoderInitializer( 1417): run()
,I/Decoder ( 1417): createOrResetDecoder
,I/art     ( 1573): Explicit concurrent mark sweep GC freed 9131(622KB) AllocSpace objects, 8(409KB) LOS objects, 24% free, 13MB/17MB, paused 474us total 81.905ms
,I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=10114 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ConfigService( 1754): onCreate
,D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  882): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  882): removeObsoleteFile: deleting file=3_task.xml
,W/asset   (10114): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager(10114): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager(10114): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10114): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): run()
,I/Launcher( 1573): Deferring update until onResume
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = user
I/art     (  882): Explicit concurrent mark sweep GC freed 14791(992KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.496ms total 228.648ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1417): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1417): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1417): run()
I/StatsUtilsManager( 1417): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1417): shouldRecordStats() = Too Soon
,I/ActivityManager(  882): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=10138 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  882): Killing 9891:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/AndroidRuntime(10082): Shutting down VM
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_9891/cgroup.procs: No such file or directory
,W/ContextImpl(10138): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 8863): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 8863): Reading stored module config
D/AccountUtils( 8863): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 8863): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 8863): Loading module APK com.google.android.play.games
,I/LocationSettingsChecker( 8863): Removing dialog suppression flag for package com.test.thalitest
,I/GMPM-SVC( 8863): App measurement is starting up, version: 8489
,I/GMPM-SVC( 8863): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1754): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1754): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 8863): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 8863): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 8863): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 8863): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 8863): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 8863): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 8863): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 8863): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 8863): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 8863): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 8863): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 8863): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 8863): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=10171 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/Icing   ( 8863): doRemovePackageData com.test.thalitest
,D/ChimeraCfgMgr( 8863): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 8863): Module APK com.google.android.play.games already loaded
,W/BaseAppContext( 8863): Using Auth Proxy for data requests.
,E/BaseAppContext( 8863): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 8863): Using Auth Proxy for data requests.
,W/Launcher( 1573): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1f2e635f new=com.google.android.velvet.VelvetApplication@1f2e635f
,I/ActivityManager(  882): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=10205 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/BaseAppContext( 8863): Using Auth Proxy for data requests.
W/BaseAppContext( 8863): Using Auth Proxy for data requests.
,D/ConnectivityService(  882): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  882): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  882): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 8863): CM callback handler got msg 524290
,W/BaseAppContext( 8863): Using Auth Proxy for data requests.
,W/BaseAppContext( 8863): Using Auth Proxy for data requests.
,W/BaseAppContext( 8863): Using Auth Proxy for data requests.
,W/BaseAppContext( 8863): Using Auth Proxy for data requests.
,W/BaseAppContext( 8863): Using Auth Proxy for data requests.
,I/art     ( 5721): Explicit concurrent mark sweep GC freed 2982(110KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 386us total 24.097ms
,W/DriveInitializer( 8863): Awaiting to be initialized
W/DriveInitializer( 8863): Background init thread started
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.gms/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8863): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.gms/files
,E/SQLiteLog( 8863): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/DriveInitializer( 8863): Background init thread ended
,E/SQLiteLog( 8863): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 8863): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process ( 8863): Sending signal. PID: 8863 SIG: 9
,I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=10233 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/ConnectivityService(  882): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2dbac8b5)
,D/ConnectivityService(  882): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiService(  882): Client connection lost with reason: 4
E/ConnectivityService(  882): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager(  882): Process com.google.android.gms (pid 8863) has died
,W/ActivityManager(  882): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  882): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1508ms
W/ActivityManager(  882): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11508ms
W/ActivityManager(  882): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 21508ms
W/ActivityManager(  882): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21508ms
,E/native  ( 1417): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1417): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/native  ( 1417): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/native  ( 1417): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=10253 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,E/SharedPreferencesImpl(10171): Couldn't rename file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml to backup file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml.bak
,E/AndroidRuntime(10171): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime(10171): Process: com.google.android.googlequicksearchbox:search, PID: 10171
E/AndroidRuntime(10171): java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime(10171): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:108)
E/AndroidRuntime(10171): 	at com.google.android.apps.gsa.shared.e.j.c(ExtraDexRegistry.java:214)
E/AndroidRuntime(10171): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.bb(UpdateIcingCorporaService.java:232)
E/AndroidRuntime(10171): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:205)
E/AndroidRuntime(10171): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(10171): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10171): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime(10171): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime(10171): Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime(10171): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
E/AndroidRuntime(10171): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
E/AndroidRuntime(10171): 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
E/AndroidRuntime(10171): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:94)
E/AndroidRuntime(10171): 	... 7 more
E/AndroidRuntime(10171): Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime(10171): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
E/AndroidRuntime(10171): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
E/AndroidRuntime(10171): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/AndroidRuntime(10171): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/AndroidRuntime(10171): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/AndroidRuntime(10171): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime(10171): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime(10171): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime(10171): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime(10171): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/AndroidRuntime(10171): Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10171): 	at java.io.File.createNewFile(File.java:941)
E/AndroidRuntime(10171): 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
E/AndroidRuntime(10171): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
E/AndroidRuntime(10171): 	... 9 more
E/AndroidRuntime(10171): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10171): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime(10171): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime(10171): 	at java.io.File.createNewFile(File.java:934)
E/AndroidRuntime(10171): 	... 11 more
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.454ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 325us total 20.504ms
I/Process (10171): Sending signal. PID: 10171 SIG: 9
,E/DropBoxManagerService(  882): Can't write: system_app_crash
E/DropBoxManagerService(  882): java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  882): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  882): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  882): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  882): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  882): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  882): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  882): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  882): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  882): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  882): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  882): 	... 5 more
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 28.679ms

```
