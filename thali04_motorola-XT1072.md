#### Test 50650278bb431e6_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
D/AndroidRuntime( 6421): 
D/AndroidRuntime( 6421): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6421): CheckJNI is OFF
D/AndroidRuntime( 6421): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6440 uid=10396 gids={50396, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6421): Shutting down VM
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6440): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6440): Time to load native libraries: 5 ms (timestamps 7570-7575)
I/LibraryLoader( 6440): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6440): Binding Chromium to main looper Looper (main, tid 1) {3432fe1f}
,I/LibraryLoader( 6440): Expected native library version number "",actual native library version number ""
I/chromium( 6440): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6440): Initializing chromium process, singleProcess=true
,W/art     ( 6440): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6440): ApplicationContext is null in ApplicationStatus
,W/chromium( 6440): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6440): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6440): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6440): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6440): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6440): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6440): Local Branch: 
I/Adreno-EGL( 6440): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6440): Local Patches: NONE
I/Adreno-EGL( 6440): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bc9595d:true
,W/ActivityManager(  881): Activity pause timeout for ActivityRecord{38b4696e u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 6440): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6440): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6440): CordovaWebView is running on device made by: motorola
,W/art     ( 6440): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6440): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6440): Render dirty regions requested: true
,D/Atlas   ( 6440): Validating map...
,W/chromium( 6440): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  881): Explicit concurrent mark sweep GC freed 10489(590KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.483ms total 115.242ms
,I/OpenGLRenderer( 6440): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6440): Enabling debug mode 0
,I/Keyboard.Facilitator( 1414): onFinishInput()
,I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,1141
I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +1s69ms (total +1s141ms)
,W/IInputConnectionWrapper( 6440): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6440): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6440): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6440): Cannot call determinedVisibility() - never saw a connection for the pid: 6440
,D/JsMessageQueue( 6440): Set native->JS mode to OnlineEventsBridgeMode
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  297): Event received = CTRL-EVENT-BSS-REMOVED 8
,D/jxcore_app_log( 6440): JniHelper::setJavaVM(0xb89a7310), pthread_self() = -1194108952
D/JX-Cordova( 6440): jxcore cordova android initializing
,W/jxcore-log( 6440): Initializing JXcore engine
W/jxcore-log( 6440): JXcore engine is ready
,W/jxcore-log( 6440): Starting JXcore engine
,W/.test.thalitest( 6440): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10396 path="socket:[7502]" dev="sockfs" ino=7502 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6440): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10396 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6440): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10396 path="socket:[5598]" dev="sockfs" ino=5598 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6440): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10396 path="socket:[29163]" dev="sockfs" ino=29163 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6440): Platform android
W/jxcore-log( 6440): 
W/jxcore-log( 6440): Process ARCH arm
W/jxcore-log( 6440): 
,I/jxcore-log( 6440): JXcore Cordova bridge is ready!
I/jxcore-log( 6440): 
,W/jxcore-log( 6440): JXcore engine is started
,I/chromium( 6440): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6440): Toggling radios to true
I/jxcore-log( 6440): 
,D/BluetoothAdapter( 6440): enable(): BT is already enabled..!
,D/WifiService(  881): New client listening to asynchronous messages
,D/WifiService(  881): setWifiEnabled: true pid=6440, uid=10396
,E/WifiService(  881): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6440): Radios toggled
I/jxcore-log( 6440): 
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6440): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6440): 
,I/jxcore-log( 6440): Perf Test app loaded loaded
I/jxcore-log( 6440): 
,I/jxcore-log( 6440): check test folder
I/jxcore-log( 6440): 
I/jxcore-log( 6440): found test : ./testFindPeers.js
I/jxcore-log( 6440): 
,D/TCMD    (  481): NL - Read 1004 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
,D/Tethering(  881): InitialState.processMessage what=4
,I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
,D/MDMCTBK (  297): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  297):  STA Disconnected !!
,W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  1
D/Tethering(  881):  5
,D/Tethering(  881):  7
D/Tethering(  881):  0
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): get_property_value, Enter
I/MDMCTBK (  297): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  297): get_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  297): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  297): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  297): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
E/MDMCTBK (  297): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
E/WifiStateMachine(  881): WifiStateMachine: Leaving Connected state
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  297): Event received = CTRL-EVENT-REGDOM-CHANGE
,I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  297): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  881): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  881): do suspend true
D/Tethering(  881): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  295): Clearing all IP addresses on wlan0
,I/jxcore-log( 6440): found test : ./testSendData.js
I/jxcore-log( 6440): 
D/TCMD    (  481): NL - Read 60 bytes from update socket.
D/TCMD    (  481): NL - ignore NL message, type = 21
D/TCMD    (  481): Listening for incoming client connection request
,V/NativeCrypto( 1807): Read error: ssl=0xb8c047a0: I/O error during system call, Connection timed out
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,V/NativeCrypto( 1807): SSL shutdown failed: ssl=0xb8c047a0: I/O error during system call, Broken pipe
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
D/WifiMetrics(  881): connected time updated 301981
D/ConnectivityService(  881): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6502 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/jxcore-log( 6440): found test : ./testSendData2.js
I/jxcore-log( 6440): 
,E/jxcore  ( 6440): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 6440): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,I/chromium( 6440): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/ConnectivityService(  881): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  881): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Disconnected - quitting
D/CSLegacyTypeTracker(  881): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/ConnectivityService(  881): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  881): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
E/WifiStateMachine(  881): Start Disconnecting Watchdog 1
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-STARTED 
I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  881): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  881): do suspend true
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  295): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,W/ResourcesManager( 6502): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  881): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  881): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  881): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6530 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6135:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10057/pid_6135/cgroup.procs: No such file or directory
,W/ResourcesManager( 6530): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/wpa_supplicant( 1433): wlan0: Trying to associate with SSID 'NG700'
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  297): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  297): Event received = WPS-AP-AVAILABLE 
E/WifiStateMachine(  881): [1,450,653,283,195 ms] noteScanEnd no scan source
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  297): Event received = Trying to associate with
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiMonitor(  881): didn't find BSSID Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 1433): DSDS: eapol_sm_notify_config config->sim_num = 1
D/TCMD    (  481): NL - Read 56 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
E/WifiStateMachine(  881): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3a9e8563 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel_SMS( 6530): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6530): MmsConfig.loadMmsSettings
I/Babel_SMS( 6530): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6530): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6530): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6530): MmsConfig.loadFromResources
,E/Babel_SMS( 6530): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6530): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/TCMD    (  481): NL - Read 312 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 192 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 1004 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
I/wpa_supplicant( 1433): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  481): NL - Read 80 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 80 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
D/TCMD    (  481): NL - Read 68 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
,D/Tethering(  881): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  881): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  297): Event received = Associated with c0:ff:d4
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
E/Tethering(  881): ApnList is empty for checkDunConfigured()
D/Tethering(  881):  upstream interface types: 
D/Tethering(  881):  0
D/Tethering(  881):  1
D/Tethering(  881):  5
D/Tethering(  881):  7
D/Tethering(  881): sendTetherStateChangedBroadcast 1, 0, 0
E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1433): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1433): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/TCMD    (  481): NL - Read 1004 bytes from update socket.
D/TCMD    (  481): NL - message type is RTM_NEWLINK
D/TCMD    (  481): Listening for incoming client connection request
,D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  297): Event received = WPA: Key negotiation com
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  297): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  297):  STA Connected !!
E/MDMCTBK (  297): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  297): get_freq !!, resp=2412
I/MDMCTBK (  297): get_freq !!, Strip data
I/MDMCTBK (  297): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): get_property_value, Enter
I/MDMCTBK (  297): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  297): get_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  297): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  297): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
I/MDMCTBK (  297): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  297): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  297): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): get_property_value, Enter
I/MDMCTBK (  297): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  297): get_property_value, Exit
,I/MDMCTBK (  297): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1219793496
I/MDMCTBK (  297): return from set_get_from_wpa_supplicant
I/MDMCTBK (  297): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  297): set_property_value, Enter
I/MDMCTBK (  297): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  297): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  297): set_property_value, Exit
E/MDMCTBK (  297): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  297): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  297): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  297): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  297): , reply_len: 3, ret: 0
E/MDMCTBK (  297): MdmCutbackHndler, resp=OK
E/MDMCTBK (  297): 
D/MDMCTBK (  297): wifi_set_tx_pwr: Exit
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  881): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  881): Network connection established
E/WifiStateMachine(  881): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/Settings( 6530): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  881): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  881): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  881): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  881): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  881): ObtainingIpAddress "NG700" nid=0
,E/WifiConfigStore(  881): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Babel_Crash( 6530): startup - clean
,D/CommandListener(  295): Setting iface cfg
,E/WifiStateMachine(  881): Start Dhcp Watchdog 2
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  881): do suspend false
,E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  881): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1433): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  881): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@15ba269e target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@15ba269e target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel   ( 6530): deleted: false for 0
,W/VideoCapabilities( 6530): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6530): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6530): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6530): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6530): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6530): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6530): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6530): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  881): Killing 6189:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,E/DHCPCD  ( 6570): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6570): version 5.5.6 starting
E/DHCPCD  ( 6570): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 6570): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6570): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6189/cgroup.procs: No such file or directory
,I/vclib   ( 6530): onServiceConnected
,W/Babel   ( 6530): Attempted to change video mute state without an active call.
,D/DHCPCD  ( 6570): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6570): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6570): wlan0: sending REQUEST (xid 0xbe77ef62), next in 4.37 seconds
,I/DHCPCD  ( 6570): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6570): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6570): wlan0: adding IP address 192.168.1.123/24
,D/TCMD    (  481): NL - Read 60 bytes from update socket.
D/TCMD    (  481): NL - ignore NL message, type = 20
D/TCMD    (  481): Listening for incoming client connection request
D/DHCPCD  ( 6570): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6570): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6570): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/DHCPCD  ( 6570): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  881): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  881): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  881): do suspend true
,D/WifiP2pService(  881): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  881): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  881): WifiStateMachine DHCP successful
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  881): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  881): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  881): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  881): Adding iface wlan0 to network 101
,E/WifiStateMachine(  881): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  881): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  881): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  881): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,E/WifiStateMachine(  881): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  881): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  881): Setting Dns servers for network 101 to [/192.168.1.1]
D/Checkin (  881): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Nat464Xlat(  881): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  881): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881):    accepting network in place of null
D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  881): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1289): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  881): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 20 Dec 2015 23:14:44 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450653284463], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450653284433]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  881): Validated
D/ConnectivityService(  881): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  881): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524290
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1289): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1289): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/ModemStatsDSDetect( 1530): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1530): Inetcondition changed, white->blue
,I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1289): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1289): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  881): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  881): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/Nat464Xlat(  881): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  881): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1289): CM callback handler got msg 524295
,E/WifiStateMachine(  881): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  881): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1474): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2738): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2738): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6635 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/PollingManager( 2738): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1474): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1474): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2738): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2738): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2738): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2738): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2738): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2738): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2738): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2738): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2738): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2738): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2738): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2738): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2738): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2738): [debug] > CusSM.onRadioDown
,I/MusicStore( 6635): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6635): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6635): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6635): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6635): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6635): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6635): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6635): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6635): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@355c5aeb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6635): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6635): GMSCore installation verified
,I/ConfigStore( 6635): Config Database version: 1
,I/MediaRouter( 6635): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6635): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6635): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6635): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6685 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6635): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6635): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Killing 5973:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_5973/cgroup.procs: No such file or directory
,V/Mms     ( 6685): mnc/mcc: 
,V/Mms     ( 6685): tag: int value: recipientLimit - 20
V/Mms     ( 6685): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6685): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6685): tag: int value: maxSubjectLength - 80
V/Mms     ( 6685): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6685): tag: bool value: enableGroupMms - false
V/Mms     ( 6685):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6685): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6716 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6051:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_6051/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6716): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6716): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6716): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 6530:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6530/cgroup.procs: No such file or directory
,I/CheckinService( 6253): Checkin interval check for package: unspecified last checkin: 1450653056466 min interval config: 0 actual interval: 230375
,I/CheckinService( 6253): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6253): SYNC; picasa accounts
,I/CheckinService( 6253): Checking schedule, now: 1450653286871 next: 1450653086448
I/CheckinService( 6253): active receiver: enabled
,D/NetworkLogImpl( 6253): Loaded NetworkSpeedPredictor
,I/CheckinService( 6253): Preparing to send checkin request
,I/iu.Environment( 6253): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 6253): Accumulating logs since 1450653053315
,I/iu.UploadsManager( 6253): num queued entries: 0
I/iu.UploadsManager( 6253): num updated entries: 0
,I/iu.SyncManager( 6253): NEXT; no task
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6745 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6253): Checkin reason type: 8 attempt count: 1
,D/WifiService(  881): New client listening to asynchronous messages
,E/ActivityThread( 6253): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  881): Explicit concurrent mark sweep GC freed 44368(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.545ms total 123.180ms
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  881): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6767 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/Tethering(  881): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1474): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2738): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/PollingManager( 2738): now: 348427 ,futureTime: 9223372036854775807
D/PollingManager( 2738): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2738): now: 348427 ,futureTime: 9223372036854775807
D/PollingManager( 2738): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2738): now: 348427 ,futureTime: 9223372036854775807
D/OtaApp  ( 2738): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6635): type=WIFI subType= reason=null isConnected=true
,D/Central_PollingManager( 1474): now: 348430 ,futureTime: 86484960
D/Central_PollingManager( 1474): Polling alarm set to expire at: 86484960 Current Time: 348431
,D/OtaApp  ( 2738): [debug] > PollingManagerService, now: 348432 ,futureTime: 43309247
,D/OtaApp  ( 2738): [debug] > Polling alarm set to expire at: 43309247 Current Time: 348432
,D/MMApiProvisionService( 2738): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2738): isDeviceProvisioned: deviceId = 2072049230914535424
,W/ResourcesManager( 6767): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MMApiProvisionService( 2738): isDeviceProvisioned: deviceId = 2072049230914535424
,D/OtaApp  ( 2738): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2738): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2738): [debug] > CusSM.sendUpgradeStatus: no unlogged events.,
,D/OtaApp  ( 2738): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2738): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,I/ActivityManager(  881): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6789 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,D/Checkin ( 2738): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2738): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2738): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2738): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2738): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/ResourcesManager( 6789): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6789): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6789): VM with version 2.1.0 has multidex support
,I/MultiDex( 6789): install
I/MultiDex( 6789): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6789): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel_SMS( 6767): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6767): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6767): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6767): MmsConfig.loadFromDatabase
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6440): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6440): setDiscoveryMode: Mode set to WIFI
I/jxcore-log( 6440): BLE supported!!
I/jxcore-log( 6440): 
,E/Babel_SMS( 6767): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6767): MmsConfig.loadFromResources
,E/Babel_SMS( 6767): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6767): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
W/ActivityThread( 6789): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6789): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@350654d0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6789): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6789): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6789): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/Settings( 6767): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6767): startup - clean
,I/Babel   ( 6767): deleted: false for 0
,D/NativeLibraryUtils( 6789): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6821 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  322): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 21.310ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 19.116ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 19.882ms
,D/WVCdm   (  305): Instantiating CDM.
,I/WVCdm   (  305): CdmEngine::OpenSession
I/WVCdm   (  305): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  305): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/VideoCapabilities( 6767): Unrecognized profile 2130706433 for video/avc
,D/DrmWidevineDash(  305): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  305): Service_Initialize: starts!
,D/QSEECOMAPI: (  305): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  305): App is not loaded in QSEE
E/QSEECOMAPI: (  305): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  305): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  305): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  305): App is not loaded in QSEE
E/QSEECOMAPI: (  305): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  305): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  305): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  305): App is not loaded in QSEE
,W/AudioCapabilities( 6767): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6767): Unsupported mime video/mpeg2
,D/QSEECOMAPI: (  305): Loaded image: APP id = 3
,D/DrmWidevineDash(  305): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  305): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f97000
E/DrmWidevineDash(  305): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f97000
,D/DrmWidevineDash(  305): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  305): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  305): hlos api version =  9
D/DrmWidevineDash(  305): tz api version =  8
D/DrmWidevineDash(  305): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  305): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  305): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  305): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  305): OEMCrypto_OpenSession: starts! SID=0xb5567960
D/DrmWidevineDash(  305): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  305): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  305): OEMCrypto_GetRandom: starts! randomData=0xb76fad70, dataLength=8
D/DrmWidevineDash(  305): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  305): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb76e9450, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  305): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  305): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  305): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  305): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  305): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  305): OEMCrypto_GetDeviceID: starts! deviceID=0xb76ff838, idLength=0xb5467730
,D/DrmWidevineDash(  305): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: starts!
I/VideoCapabilities( 6767): Unsupported profile 4 for video/mp4v-es
D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  305): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  305): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  305): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  305): hlos api version =  9
D/DrmWidevineDash(  305): tz api version =  8
D/DrmWidevineDash(  305): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  305): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  305): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  305): PrepareKeyRequest: nonce=1961286629
D/DrmWidevineDash(  305): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb76eead0
D/DrmWidevineDash(  305): message_length=1591, signature=0xb7647920, signature_length=3041294100
,W/VideoCapabilities( 6767): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6767): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6767): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6767): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6767): onServiceConnected
,W/Babel   ( 6767): Attempted to change video mute state without an active call.
,I/Babel   ( 6767): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 6502:com.motorola.context/u0a8 (adj 15): empty #7
,D/DrmWidevineDash(  305): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  305): CdmEngine::CloseSession
,D/DrmWidevineDash(  305): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  305): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  305): L3 Terminate.
D/DrmWidevineDash(  305): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  305): Service_Uninitialize: starts!
D/QSEECOMAPI: (  305): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  305): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  305): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  305): OEMCrypto_Terminate: ends! returns 0
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_6502/cgroup.procs: No such file or directory
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6821): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6821): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6821): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6821): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6821): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6821):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6821):   adb logcat -s GAv4
,W/GAv4    ( 6821): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6821): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6821): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6821): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6821): Time to load native libraries: 1 ms (timestamps 9786-9787)
,I/LibraryLoader( 6821): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6821): Binding Chromium to main looper Looper (main, tid 1) {31009200}
,I/LibraryLoader( 6821): Expected native library version number "",actual native library version number ""
,I/chromium( 6821): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6821): Initializing chromium process, singleProcess=true
,W/art     ( 6821): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6821): ApplicationContext is null in ApplicationStatus
,W/chromium( 6821): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6821): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6821): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6821): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6821): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6821): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6821): Local Branch: 
I/Adreno-EGL( 6821): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6821): Local Patches: NONE
I/Adreno-EGL( 6821): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/dex2oat ( 6876): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/AudioManagerAndroid( 6821): Requires BLUETOOTH permission
,I/NSApplication( 6821): Starting up...
,I/dex2oat ( 6876): dex2oat took 87.404ms (threads: 4)
,I/Adreno-EGL( 6789): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6789): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6789): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6789): Local Branch: 
I/Adreno-EGL( 6789): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6789): Local Patches: NONE
I/Adreno-EGL( 6789): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6894 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6635:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6635/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6789): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6789): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6789): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6789): Local Branch: 
I/Adreno-EGL( 6789): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6789): Local Patches: NONE
I/Adreno-EGL( 6789): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6789): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6789): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6789): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6789): Local Branch: 
I/Adreno-EGL( 6789): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6789): Local Patches: NONE
I/Adreno-EGL( 6789): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6789): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6789): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6789): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6789): Local Branch: 
I/Adreno-EGL( 6789): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6789): Local Patches: NONE
I/Adreno-EGL( 6789): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6915 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6685:com.android.mms/u0a23 (adj 15): empty #7
,I/WVCdm   (  305): CdmEngine::OpenSession
I/WVCdm   (  305): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  305): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  305): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  305): Service_Initialize: starts!
D/QSEECOMAPI: (  305): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  305): App is not loaded in QSEE
E/QSEECOMAPI: (  305): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  305): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  305): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  305): App is not loaded in QSEE
E/QSEECOMAPI: (  305): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  305): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  305): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  305): App is not loaded in QSEE
,D/QSEECOMAPI: (  305): Loaded image: APP id = 3
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_6685/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  305): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  305): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f97000
E/DrmWidevineDash(  305): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f97000
,D/DrmWidevineDash(  305): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  305): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  305): hlos api version =  9
D/DrmWidevineDash(  305): tz api version =  8
D/DrmWidevineDash(  305): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  305): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  305): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  305): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  305): OEMCrypto_OpenSession: starts! SID=0xb5567960
,D/DrmWidevineDash(  305): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  305): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  305): OEMCrypto_GetRandom: starts! randomData=0xb76fb020, dataLength=8
D/DrmWidevineDash(  305): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  305): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb76e9450, wrapped_rsa_key_length=1280
,W/ResourcesManager( 6915): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/DrmWidevineDash(  305): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  305): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  305): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  305): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  305): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  305): OEMCrypto_GetDeviceID: starts! deviceID=0xb76ff878, idLength=0xb3f32730
,D/DrmWidevineDash(  305): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  305): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  305): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  305): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  305): hlos api version =  9
,D/DrmWidevineDash(  305): tz api version =  8
,D/DrmWidevineDash(  305): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  305): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  305): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  305): PrepareKeyRequest: nonce=2850954182
D/DrmWidevineDash(  305): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb76eead0
D/DrmWidevineDash(  305): message_length=1626, signature=0xb7647a78, signature_length=3019056916
,D/DrmWidevineDash(  305): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  305): CdmEngine::CloseSession
D/DrmWidevineDash(  305): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  305): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  305): L3 Terminate.
D/DrmWidevineDash(  305): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  305): Service_Uninitialize: starts!
D/QSEECOMAPI: (  305): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  305): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  305): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  305): OEMCrypto_Terminate: ends! returns 0
I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6937 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6253): Classify the device as Phone.
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6963 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6745:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ContactLocale( 6937): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/CheckinTask( 6253): Sending checkin request (9459 bytes)
,I/ActivityManager(  881): Killing 6716:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_6745/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_6716/cgroup.procs: No such file or directory
,I/MusicStore( 6963): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6963): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6963): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6963): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6963): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6963): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6963): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6963): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6963): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@355c5aeb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6963): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6963): GMSCore installation verified
,I/ConfigStore( 6963): Config Database version: 1
,I/art     ( 6217): Explicit concurrent mark sweep GC freed 1536(65KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 410us total 28.817ms
,I/MediaRouter( 6963): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6963): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6963): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6963): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7005 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6253): Checkin reason type: 8 attempt count: 1
,I/art     (  881): Explicit concurrent mark sweep GC freed 14303(683KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.642ms total 136.148ms
,E/ActivityThread( 6253): Failed to find provider info for com.google.android.wearable.settings
,I/GHttpClientFactory( 6963): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6963): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Killing 6767:com.google.android.talk/u0a70 (adj 15): empty #7
,V/Mms     ( 7005): mnc/mcc: 
,V/Mms     ( 7005): tag: int value: recipientLimit - 20
V/Mms     ( 7005): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7005): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7005): tag: int value: maxSubjectLength - 80
V/Mms     ( 7005): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7005): tag: bool value: enableGroupMms - false
,V/Mms     ( 7005):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_6767/cgroup.procs: No such file or directory
,W/ResourcesManager( 7005): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7036 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6821:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 7036): Register our PhoneStateListener
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_6821/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7036): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7036): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  881): Killing 6894:com.android.chrome/u0a52 (adj 15): empty #7
,I/CheckinRequestBuilder( 6253): Classify the device as Phone.
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_6894/cgroup.procs: No such file or directory
,I/CheckinService( 6253): Checkin interval check for package: unspecified last checkin: 1450653056466 min interval config: 0 actual interval: 234502
,I/CheckinTask( 6253): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6253): Checking schedule, now: 1450653290980 next: 1451254427973
I/CheckinService( 6253): active receiver: disabled
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7057 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/CheckinService( 6253): Checking schedule, now: 1450653291052 next: 1451254427973
I/CheckinService( 6253): active receiver: disabled
,D/CheckinService( 6253): Recording last checkin time for package unspecified as 1450653291056
,I/ActivityManager(  881): Killing 6915:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  881): Killing 6937:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6915/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_6937/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7077 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6963:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6963/cgroup.procs: No such file or directory
,W/ResourcesManager( 7077): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7077): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7077): MmsConfig.loadMmsSettings
I/Babel_SMS( 7077): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7077): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7077): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7077): MmsConfig.loadFromResources
,E/Babel_SMS( 7077): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7077): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7077): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7077): startup - clean
,I/Babel   ( 7077): deleted: false for 0
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7108 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7077): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7077): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7077): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7077): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7077): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7077): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7077): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7077): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7077): onServiceConnected
W/Babel   ( 7077): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7108): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 7108): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7108):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7108):   adb logcat -s GAv4
,W/ContextImpl( 7108): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,I/Babel   ( 7077): connection state changed from UNKNOWN to CONNECTED
,W/ContextImpl( 7108): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/ActivityManager(  881): Killing 7005:com.android.mms/u0a23 (adj 13): empty #7
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/GAv4    ( 7108): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/ContextImpl( 7108): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_7005/cgroup.procs: No such file or directory
,W/GAv4    ( 7108): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7108): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7108): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7108): Time to load native libraries: 2 ms (timestamps 3386-3388)
,I/LibraryLoader( 7108): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7108): Binding Chromium to main looper Looper (main, tid 1) {31009200}
,I/LibraryLoader( 7108): Expected native library version number "",actual native library version number ""
I/chromium( 7108): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7108): Initializing chromium process, singleProcess=true
,W/art     ( 7108): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7108): ApplicationContext is null in ApplicationStatus
,W/chromium( 7108): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7108): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7108): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7108): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7108): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7108): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7108): Local Branch: 
I/Adreno-EGL( 7108): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7108): Local Patches: NONE
I/Adreno-EGL( 7108): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7108): Requires BLUETOOTH permission
,I/NSApplication( 7108): Starting up...
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7180 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7036:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7036/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7199 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 7057:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/art     (  322): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 240us total 22.421ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 18.933ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.679ms
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7057/cgroup.procs: No such file or directory
,W/ResourcesManager( 7199): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7219 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7108:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/art     ( 7199): Suspending all threads took: 5.788ms
,I/ContactLocale( 7219): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  881): Killing 7077:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_7108/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2738): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7077/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2738): bindWebServices(): registering our AIDL callback...
I/SundryService( 2738): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2738): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2738): onServiceConnected()
,D/GetNotificationsWS( 2738): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2738): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7248 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2738): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  881): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7271 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 6789:com.google.android.gms.unstable/u0a16 (adj 13): empty #7
,I/MusicStore( 7271): Database version: 120
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_6789/cgroup.procs: No such file or directory
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
,I/art     (  881): Explicit concurrent mark sweep GC freed 10907(552KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.515ms total 112.225ms
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7271): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7271): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7271): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7271): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7271): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7271): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7271): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7271): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@355c5aeb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7271): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7271): GMSCore installation verified
,I/ConfigStore( 7271): Config Database version: 1
,I/MediaRouter( 7271): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7271): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7271): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7271): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  881): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7302 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7271): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7271): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  881): Killing 7180:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_7180/cgroup.procs: No such file or directory
,V/Mms     ( 7302): mnc/mcc: 
,V/Mms     ( 7302): tag: int value: recipientLimit - 20
V/Mms     ( 7302): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7302): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7302): tag: int value: maxSubjectLength - 80
V/Mms     ( 7302): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7302): tag: bool value: enableGroupMms - false
V/Mms     ( 7302):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7302): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7328 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7199:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 7328): Register our PhoneStateListener
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7199/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7328): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7328): onReceive CONNECTIVITY_CHANGE networkType=1
,I/CheckinService( 6253): Checkin interval check for package: unspecified last checkin: 1450653291056 min interval config: 0 actual interval: 3448
,I/CheckinService( 6253): Checkin interval check for package: unspecified last checkin: 1450653291056 min interval config: 0 actual interval: 3452
,I/CheckinService( 6253): Checking schedule, now: 1450653294514 next: 1450653320973
I/CheckinService( 6253): active receiver: disabled
,I/CheckinService( 6253): Checking schedule, now: 1450653294528 next: 1450653320973
I/CheckinService( 6253): active receiver: disabled
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7348 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7219:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_7219/cgroup.procs: No such file or directory
,W/ResourcesManager( 7348): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7348): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7348): MmsConfig.loadMmsSettings
I/Babel_SMS( 7348): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7348): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7348): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7348): MmsConfig.loadFromResources
,E/Babel_SMS( 7348): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7348): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7348): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7348): startup - clean
,I/Babel   ( 7348): deleted: false for 0
,I/ActivityManager(  881): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7379 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7348): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7348): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7348): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7348): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7348): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7348): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7348): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7348): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7348): onServiceConnected
W/Babel   ( 7348): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7379): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7379): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7379): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7379):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7379):   adb logcat -s GAv4
,W/GAv4    ( 7379): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7348): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  881): Killing 7271:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/GAv4    ( 7379): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7379): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7379): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7379): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_7271/cgroup.procs: No such file or directory
,I/WebViewFactory( 7379): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7379): Time to load native libraries: 2 ms (timestamps 6661-6663)
,I/LibraryLoader( 7379): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7379): Binding Chromium to main looper Looper (main, tid 1) {31009200}
,I/LibraryLoader( 7379): Expected native library version number "",actual native library version number ""
I/chromium( 7379): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7379): Initializing chromium process, singleProcess=true
,W/art     ( 7379): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7379): ApplicationContext is null in ApplicationStatus
,W/chromium( 7379): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7379): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7379): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7379): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7379): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7379): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7379): Local Branch: 
I/Adreno-EGL( 7379): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7379): Local Patches: NONE
I/Adreno-EGL( 7379): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,W/AudioManagerAndroid( 7379): Requires BLUETOOTH permission
,I/NSApplication( 7379): Starting up...
,I/ActivityManager(  881): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7452 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7302:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10023/pid_7302/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7471 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7328:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7328/cgroup.procs: No such file or directory
,W/ResourcesManager( 7471): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7491 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7348:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ActivityManager(  881): Killing 7248:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ContactLocale( 7491): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/EmailService.MarketingOptInSetter( 2738): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7348/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7248/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2738): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2738): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2738): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2738): onServiceConnected()
D/GetNotificationsWS( 2738): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2738): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2738): started with background data enabled, making sure notification mechanism is enabled
D/OtaApp  ( 2738): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2738): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2738): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  881): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2738): [debug] > DownloadActivity, FormattedText
,D/WearableService( 1807): callingUid 10016, callindPid: 1807
I/OtaApp  ( 2738): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2738): publish the event [tag = MOT_OTA event name = LOG]
,D/LocationInitializer( 6253): Restart initialization of location
,D/AuthorizationBluetoothService( 1807): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/OtaApp  ( 2738): [debug] > cancelling the previous pending intent set for download later
,E/MDM     ( 1807): [184] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/OtaApp  ( 2738): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2738): publish the event [tag = MOT_OTA event name = LOG]
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1807): No location to return for getLastLocation()
,W/FusedLocationProvider( 1807): location=null
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7531 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/art     (  322): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.096ms
,D/OtaApp  ( 2738): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2738): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2738): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2738): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2738): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2738): publish the event [tag = MOT_OTA event name = LOG]
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 20.234ms
,I/Keyboard.Facilitator( 1414): onFinishInput()
,W/IInputConnectionWrapper( 6440): showStatusIcon on inactive InputConnection
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 22.193ms
,I/LaunchCheckinHandler(  881): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,224
,D/PhoneMonitor( 7531): Register our PhoneStateListener
,I/art     (  881): Explicit concurrent mark sweep GC freed 13473(644KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.369ms total 110.966ms
,V/SetupWizard( 7531): Connected to Gservices successfully
,D/GCM     ( 1807): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  881): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7553 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  881): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  881): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@37761cd
,I/GCoreNlp( 1807): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1567): Deferring update until onResume
,D/GCM     ( 1807): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7580 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7379:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10081/pid_7379/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7613 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7631 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7452:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  881): Killing 7471:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10052/pid_7452/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7471/cgroup.procs: No such file or directory
,W/ResourcesManager( 7631): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7631): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7631): MmsConfig.loadMmsSettings
I/Babel_SMS( 7631): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7631): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7631): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7631): MmsConfig.loadFromResources
,E/Babel_SMS( 7631): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7631): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7631): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7631): startup - clean
,I/Babel   ( 7631): deleted: false for 0
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7660 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7631): Unrecognized profile 2130706433 for video/avc
,W/asset   ( 7660): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7660): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7660): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7660): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/AudioCapabilities( 7631): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7631): Unsupported mime video/mpeg2
,D/PackageBroadcastService( 6253): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6253): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 7580): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@bb8d1b1 new=com.google.android.velvet.VelvetApplication@bb8d1b1
,I/VideoCapabilities( 7631): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7631): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7631): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7688 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7631): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7631): Unrecognized profile 2130706433 for video/avc
,I/Icing   ( 6253): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7688): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7580): UpdateCorporaTask done [took 202 ms] updated apps [took 202 ms] 
,I/ActivityManager(  881): Killing 7553:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10088/pid_7553/cgroup.procs: No such file or directory
,I/vclib   ( 7631): onServiceConnected
,W/Babel   ( 7631): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7631): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7631): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7631): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7631): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7631): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7732 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7531:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7531/cgroup.procs: No such file or directory
,D/Finsky  ( 7732): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7732): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7732): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7732): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7732): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7732): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7732): Skipping gmscore version check
,D/Finsky  ( 7732): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7732): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  881): Killing 7613:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10019/pid_7613/cgroup.procs: No such file or directory
,D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 6253): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6253): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6253): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,V/AlarmManager(  881): send {3d241ab1, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {1433d654, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  881): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=7784 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  881): done {3d241ab1, *alarm*:android.intent.action.TIME_TICK} [90ms]
,I/GAv4    ( 7784): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7784):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7784):   adb logcat -s GAv4
,W/GAv4    ( 7784): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7784): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7784): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  881): done {1433d654, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [299ms]
,I/ActivityManager(  881): Killing 7660:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10027/pid_7660/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 7580:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_7580/cgroup.procs: No such file or directory
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=281, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311189, SEQNUM=4501, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=105, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,I/ActivityManager(  881): Killing 7491:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_7491/cgroup.procs: No such file or directory
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/CheckinService( 6253): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311281, SEQNUM=4503, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=64, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310918, SEQNUM=4505, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=23, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1414): run()
I/Keyboard.Facilitator( 1414): flushDynamicLanguageModels()
,I/ConfigService( 1807): onCreate
,I/art     (  881): Explicit concurrent mark sweep GC freed 19898(1032KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.351ms total 127.893ms
,I/ConfigService( 1807): onDestroy
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310892, SEQNUM=4511, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311351, SEQNUM=4513, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-515, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  881): send {3d241ab1, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {1f4751, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  881): send {3952d11, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  881): done {1f4751, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [21ms]
,V/AlarmManager(  881): done {3d241ab1, *alarm*:android.intent.action.TIME_TICK} [48ms]
,V/AlarmManager(  881): done {3952d11, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [55ms]
,I/CheckinService( 6253): Checkin interval check for package: unspecified last checkin: 1450653291056 min interval config: 0 actual interval: 466040
,I/CheckinService( 6253): Checking schedule, now: 1450653757108 next: 1450653320973
I/CheckinService( 6253): active receiver: enabled
,I/CheckinService( 6253): Preparing to send checkin request
I/EventLogService( 6253): Accumulating logs since 1450653287022
,I/CheckinRequestBuilder( 6253): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6253): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/DataBuffer( 1807): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e4739e8)
E/DataBuffer( 1807): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19688801)
I/art     ( 1807): Explicit concurrent mark sweep GC freed 97964(5MB) AllocSpace objects, 30(503KB) LOS objects, 39% free, 15MB/25MB, paused 1.363ms total 111.088ms
E/DataBuffer( 1807): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1cb866a6)
,E/DataBuffer( 1807): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@342e78e7)
E/DataBuffer( 1807): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@a4a0c94)
,E/DataBuffer( 1807): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3fd4a33d)
,E/DataBuffer( 1807): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@35744732)
E/DataBuffer( 1807): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@32dfbc83)
E/DataBuffer( 1807): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@25055e00)
,E/DataBuffer( 1807): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19ed3639)
,E/DataBuffer( 1807): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2ad79ddf)
E/DataBuffer( 1807): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@29625a2c)
E/DataBuffer( 1807): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@61fcf5)
E/DataBuffer( 1807): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1f498a8a)
E/DataBuffer( 1807): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2b4238fb)
,I/ActivityManager(  881): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7844 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7844): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7844): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7844): VM with version 2.1.0 has multidex support
I/MultiDex( 7844): install
I/MultiDex( 7844): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7844): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7844): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7844): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@350654d0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7844): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1807): callingUid 10016, callindPid: 1807
,E/MDM     ( 1807): [226] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1807): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6253): Restart initialization of location
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1807): No location to return for getLastLocation()
W/FusedLocationProvider( 1807): location=null
I/art     ( 7844): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7844): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7844): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  305): Instantiating CDM.
,I/WVCdm   (  305): CdmEngine::OpenSession
I/WVCdm   (  305): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  305): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  305): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  305): Service_Initialize: starts!
D/QSEECOMAPI: (  305): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  305): App is not loaded in QSEE
E/QSEECOMAPI: (  305): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  305): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  305): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  305): App is not loaded in QSEE
E/QSEECOMAPI: (  305): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  305): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  305): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  305): App is not loaded in QSEE
,D/QSEECOMAPI: (  305): Loaded image: APP id = 3
,D/DrmWidevineDash(  305): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  305): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f95000
,E/DrmWidevineDash(  305): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f95000
,D/DrmWidevineDash(  305): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  305): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  305): hlos api version =  9
D/DrmWidevineDash(  305): tz api version =  8
D/DrmWidevineDash(  305): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  305): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  305): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  305): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  305): OEMCrypto_OpenSession: starts! SID=0xbecab4e0
D/DrmWidevineDash(  305): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  305): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  305): OEMCrypto_GetRandom: starts! randomData=0xb76fb4c8, dataLength=8
D/DrmWidevineDash(  305): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  305): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb76e9450, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  305): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  305): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  305): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  305): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  305): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  305): OEMCrypto_GetDeviceID: starts! deviceID=0xb76ff858, idLength=0xb3f32730
,D/DrmWidevineDash(  305): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  305): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  305): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  305): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  305): hlos api version =  9
,D/DrmWidevineDash(  305): tz api version =  8
,D/DrmWidevineDash(  305): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  305): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  305): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  305): PrepareKeyRequest: nonce=1853993862
D/DrmWidevineDash(  305): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb76eead0
D/DrmWidevineDash(  305): message_length=1591, signature=0xb7647920, signature_length=3019056916
,D/DrmWidevineDash(  305): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  305): CdmEngine::CloseSession
D/DrmWidevineDash(  305): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  305): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  305): L3 Terminate.
D/DrmWidevineDash(  305): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  305): Service_Uninitialize: starts!
D/QSEECOMAPI: (  305): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  305): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  305): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  305): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7887): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7887): dex2oat took 72.988ms (threads: 4)
,I/Adreno-EGL( 7844): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7844): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7844): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7844): Local Branch: 
I/Adreno-EGL( 7844): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7844): Local Patches: NONE
I/Adreno-EGL( 7844): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7844): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7844): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7844): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7844): Local Branch: 
I/Adreno-EGL( 7844): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7844): Local Patches: NONE
I/Adreno-EGL( 7844): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7844): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7844): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7844): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7844): Local Branch: 
I/Adreno-EGL( 7844): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7844): Local Patches: NONE
I/Adreno-EGL( 7844): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7844): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7844): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7844): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7844): Local Branch: 
I/Adreno-EGL( 7844): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7844): Local Patches: NONE
I/Adreno-EGL( 7844): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  305): CdmEngine::OpenSession
I/WVCdm   (  305): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  305): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  305): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  305): Service_Initialize: starts!
D/QSEECOMAPI: (  305): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  305): App is not loaded in QSEE
,E/QSEECOMAPI: (  305): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  305): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  305): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  305): App is not loaded in QSEE
E/QSEECOMAPI: (  305): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  305): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  305): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  305): App is not loaded in QSEE
,D/QSEECOMAPI: (  305): Loaded image: APP id = 3
,D/DrmWidevineDash(  305): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  305): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f95000
E/DrmWidevineDash(  305): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f95000
,D/DrmWidevineDash(  305): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  305): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  305): hlos api version =  9
D/DrmWidevineDash(  305): tz api version =  8
D/DrmWidevineDash(  305): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  305): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  305): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  305): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  305): OEMCrypto_OpenSession: starts! SID=0xbecab4e0
D/DrmWidevineDash(  305): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  305): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  305): OEMCrypto_GetRandom: starts! randomData=0xb76fdb90, dataLength=8
,D/DrmWidevineDash(  305): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  305): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb76e9450, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  305): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  305): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  305): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  305): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  305): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  305): OEMCrypto_GetDeviceID: starts! deviceID=0xb76ff878, idLength=0xb5467730
,D/DrmWidevineDash(  305): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  305): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  305): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  305): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  305): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  305): hlos api version =  9
D/DrmWidevineDash(  305): tz api version =  8
D/DrmWidevineDash(  305): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  305): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  305): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  305): PrepareKeyRequest: nonce=3809176807
D/DrmWidevineDash(  305): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb76eead0
D/DrmWidevineDash(  305): message_length=1626, signature=0xb7647a78, signature_length=3041294100
,D/DrmWidevineDash(  305): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  305): CdmEngine::CloseSession
D/DrmWidevineDash(  305): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  305): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  305): L3 Terminate.
D/DrmWidevineDash(  305): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  305): Service_Uninitialize: starts!
D/QSEECOMAPI: (  305): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  305): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  305): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  305): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 6253): Classify the device as Phone.
,I/CheckinTask( 6253): Sending checkin request (9450 bytes)
,I/CheckinRequestBuilder( 6253): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6253): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6253): Classify the device as Phone.
,I/CheckinTask( 6253): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6253): Checking schedule, now: 1450653760098 next: 1451254897089
I/CheckinService( 6253): active receiver: disabled
,D/CheckinService( 6253): Recording last checkin time for package unspecified as 1450653760111
,I/ActivityManager(  881): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7911 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7911): Register our PhoneStateListener
,V/SetupWizard( 7911): Connected to Gservices successfully
,D/GCM     ( 1807): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310519, SEQNUM=4523, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-593, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,I/ActivityManager(  881): Killing 7732:com.android.vending/u0a32 (adj 13): empty #7
,I/ActivityManager(  881): Killing 7688:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_7732/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_7688/cgroup.procs: No such file or directory
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7934 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  322): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 37.267ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 19.943ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 342us total 26.029ms
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  881): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  881): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  881): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2096e70d
,I/GCoreNlp( 1807): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1567): Deferring update until onResume
,I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7971 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7990 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7784:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10055/pid_7784/cgroup.procs: No such file or directory
,W/ResourcesManager( 7631): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7631): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 7990): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8016 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  881): Killing 7911:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10035/pid_7911/cgroup.procs: No such file or directory
,W/asset   ( 8016): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8016): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8016): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8016): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/art     (  881): Explicit concurrent mark sweep GC freed 20277(1144KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.778ms total 118.135ms
,D/PackageBroadcastService( 6253): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6253): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@bb8d1b1 new=com.google.android.velvet.VelvetApplication@bb8d1b1
,I/UpdateIcingCorporaServi( 7934): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  881): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8043 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 6253): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 8043): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7934): UpdateCorporaTask done [took 153 ms] updated apps [took 153 ms] 
,I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8078 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Killing 7844:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_7844/cgroup.procs: No such file or directory
,D/Finsky  ( 8078): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8078): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8078): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8078): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8078): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8078): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8078): Skipping gmscore version check
,D/Finsky  ( 8078): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8078): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  881): Killing 7971:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10019/pid_7971/cgroup.procs: No such file or directory
,I/Icing   ( 6253): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6253): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  881): Killing 8016:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10027/pid_8016/cgroup.procs: No such file or directory
,I/ActivityManager(  881): Killing 7631:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10070/pid_7631/cgroup.procs: No such file or directory
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312254, SEQNUM=4535, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-617, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311351, SEQNUM=4536, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-628, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=255, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311031, SEQNUM=4538, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=3733, POWER_SUPPLY_CHARGE_COUNTER=7, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=254, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311580, SEQNUM=4539, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=37, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  881): User[0] Flushing usage stats to disk
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  881): send {3d241ab1, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {2dc24c15, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  881): done {3d241ab1, *alarm*:android.intent.action.TIME_TICK} [50ms]
,V/AlarmManager(  881): done {2dc24c15, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [84ms]
,I/GoogleURLConnFactory( 1807): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1807): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/PhenotypeConfigurator( 1807): Server returned 404
,V/AlarmManager(  881): send {3d241ab1, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {3598b7ce, *walarm*:com.motorola.motocare.trigger.AlarmTrigger.AppUsageAlarmTrigger}
,V/AlarmManager(  881): done {3598b7ce, *walarm*:com.motorola.motocare.trigger.AlarmTrigger.AppUsageAlarmTrigger} [11ms]
,V/AlarmManager(  881): done {3d241ab1, *alarm*:android.intent.action.TIME_TICK} [63ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=254, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310437, SEQNUM=4545, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  881): send {3d241ab1, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {115b36ef, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  881): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8151 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  881): done {3d241ab1, *alarm*:android.intent.action.TIME_TICK} [114ms]
,I/GAv4    ( 8151): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8151):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8151):   adb logcat -s GAv4
,W/GAv4    ( 8151): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8151): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8151): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  881): done {115b36ef, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [260ms]
I/ActivityManager(  881): Killing 7934:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_7934/cgroup.procs: No such file or directory
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=252, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311580, SEQNUM=4552, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-13, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  881): send {3d241ab1, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {1f4751, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  881): send {1a6d65fc, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  881): done {1f4751, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [25ms]
,V/AlarmManager(  881): done {3d241ab1, *alarm*:android.intent.action.TIME_TICK} [50ms]
,V/AlarmManager(  881): done {1a6d65fc, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [55ms]
,I/EventLogService( 6253): Aggregate from 1450653757152 (log), 1450652401594 (data)
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=252, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311580, SEQNUM=4557, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-18, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=252, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311550, SEQNUM=4558, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-91, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=252, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310975, SEQNUM=4559, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2119, POWER_SUPPLY_CHARGE_COUNTER=3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  881): send {3d241ab1, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {23fec635, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  881): send {3cbff2a6, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,I/ProcessStatsService(  881): Prepared write state in 9ms
,V/AlarmManager(  881): done {3d241ab1, *alarm*:android.intent.action.TIME_TICK} [64ms]
,I/ProcessStatsService(  881): Prepared write state in 6ms
,V/AlarmManager(  881): done {23fec635, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [84ms]
,V/AlarmManager(  881): done {3cbff2a6, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [96ms]
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  881): Pruning old procstats: /data/system/procstats/state-2015-12-20-03-05-00.bin
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=251, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311571, SEQNUM=4565, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=251, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311567, SEQNUM=4568, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1008, POWER_SUPPLY_CHARGE_COUNTER=6, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=251, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311256, SEQNUM=4569, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=5, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=251, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311260, SEQNUM=4570, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=251, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311554, SEQNUM=4572, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=251, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311554, SEQNUM=4573, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=4339, POWER_SUPPLY_CHARGE_COUNTER=17, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2577): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8241): 
D/AndroidRuntime( 8241): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8241): CheckJNI is OFF
D/AndroidRuntime( 8241): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10396 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 6440:com.test.thalitest/u0a396 (adj 9): stop com.test.thalitest
I/WindowState(  881): WIN DEATH: Window{13b853cd u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  881): Client connection lost with reason: 4
W/PackageSettings(  881): Skipping PackageSetting{262ee724 com.example.hello/10377} due to missing metadata
I/ActivityManager(  881):   Force finishing activity ActivityRecord{38b4696e u0 com.test.thalitest/.MainActivity t3}
W/ActivityManager(  881): Spurious death for ProcessRecord{1b972ec4 6440:com.test.thalitest/u0a396}, curProc for 6440: null
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10396 user=0: pkg removed
I/art     ( 3232): Explicit concurrent mark sweep GC freed 8362(1660KB) AllocSpace objects, 41(656KB) LOS objects, 39% free, 7MB/12MB, paused 578us total 40.215ms
I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1414): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1414): run()
W/GeofencerStateMachine( 1807): Ignoring removeGeofence because network location is disabled.
I/Decoder ( 1414): createOrResetDecoder
D/VoicemailCleanupService( 7990): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8268 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 1567): Explicit concurrent mark sweep GC freed 6782(450KB) AllocSpace objects, 6(297KB) LOS objects, 25% free, 13MB/17MB, paused 12.023ms total 82.533ms
I/art     (  881): Explicit concurrent mark sweep GC freed 29533(2007KB) AllocSpace objects, 11(264KB) LOS objects, 33% free, 20MB/30MB, paused 1.790ms total 160.005ms
I/art     (  881): WaitForGcToComplete blocked for 79.877ms for cause Explicit
I/ConfigService( 1807): onCreate
W/asset   ( 8268): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8268): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8268): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8268): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = user
I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8295 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1414): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1414): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1414): run()
I/StatsUtilsManager( 1414): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1414): shouldRecordStats() = Too Soon
I/ActivityManager(  881): Killing 8043:com.google.android.apps.plus/u0a90 (adj 15): empty #7
D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  881): Explicit concurrent mark sweep GC freed 7473(417KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.785ms total 196.333ms
W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_8043/cgroup.procs: No such file or directory
D/TaskPersister(  881): removeObsoleteFile: deleting file=3_task.xml
D/AndroidRuntime( 8241): Shutting down VM
I/Launcher( 1567): Deferring update until onResume
W/ContextImpl( 8295): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 6253): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 6253): Reading stored module config
D/AccountUtils( 6253): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 6253): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6253): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 6253): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 6253): App measurement is starting up, version: 8489
I/GMPM-SVC( 6253): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/NetworkScheduler.SchedulerReceiver( 1807): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1807): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 6253): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6253): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6253): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6253): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 6253): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6253): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 6253): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 6253): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6253): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6253): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6253): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6253): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6253): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8326 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
V/AlarmManager(  881): send {3d241ab1, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {3fa10650, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  881): send {195c4049, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  881): send {2953cd4e, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  881): done {3d241ab1, *alarm*:android.intent.action.TIME_TICK} [36ms]
I/Icing   ( 6253): doRemovePackageData com.test.thalitest
D/ChimeraCfgMgr( 6253): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6253): Module APK com.google.android.play.games already loaded
W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@bb8d1b1 new=com.google.android.velvet.VelvetApplication@bb8d1b1
I/ActivityManager(  881): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8352 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
W/BaseAppContext( 6253): Using Auth Proxy for data requests.
E/BaseAppContext( 6253): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 6253): Using Auth Proxy for data requests.
E/ConnectivityChangeReceiver( 6253): Ignoring connectivity change
W/BaseAppContext( 6253): Using Auth Proxy for data requests.
W/BaseAppContext( 6253): Using Auth Proxy for data requests.
D/ConnectivityService(  881): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  881): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  881): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 6253): CM callback handler got msg 524290
W/BaseAppContext( 6253): Using Auth Proxy for data requests.
W/BaseAppContext( 6253): Using Auth Proxy for data requests.
W/BaseAppContext( 6253): Using Auth Proxy for data requests.
W/BaseAppContext( 6253): Using Auth Proxy for data requests.
W/BaseAppContext( 6253): Using Auth Proxy for data requests.
I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8386 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 8326): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/art     (  322): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.971ms
W/DriveInitializer( 6253): Awaiting to be initialized
W/DriveInitializer( 6253): Background init thread started
I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 22.432ms
I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 22.125ms
I/ActivityManager(  881): Killing 8078:com.android.vending/u0a32 (adj 15): empty #7
W/art     ( 6253): Verification of void com.google.android.gms.games.provider.PlayGamesContentProvider.<clinit>() took 125.282ms
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6253): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.gms/files
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_8078/cgroup.procs: No such file or directory

```
