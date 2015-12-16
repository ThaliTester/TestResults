#### Test 506502783fcf234_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,V/AlarmManager(  885): send {1f0c5b3e, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  885): send {2b1ac0d7, *walarm*:com.google.android.intent.action.SEND_IDLE}
V/AlarmManager(  885): done {2b1ac0d7, *walarm*:com.google.android.intent.action.SEND_IDLE} [23ms]
V/AlarmManager(  885): done {1f0c5b3e, *alarm*:android.intent.action.TIME_TICK} [47ms]
--------- beginning of main
I/PhenotypeConfigurator( 1726): Scheduling Phenotype for one-off execution 8716 seconds from now (1450238340722)
D/GetConfigurationSnapshotOperation( 1726): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
I/PhenotypeFlagCommitter( 1726): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
I/GoogleURLConnFactory( 1726): Using platform SSLCertificateSocketFactory
D/AndroidRuntime( 7028): 
D/AndroidRuntime( 7028): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7028): CheckJNI is OFF
D/AndroidRuntime( 7028): Calling main entry com.android.commands.am.Am
I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  885): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7063 uid=10381 gids={50381, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 7028): Shutting down VM
V/ActivityManager(  885): Display changed displayId=0
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 7063): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7063): Time to load native libraries: 14 ms (timestamps 6220-6234)
I/LibraryLoader( 7063): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7063): Binding Chromium to main looper Looper (main, tid 1) {38795ee5}
,I/LibraryLoader( 7063): Expected native library version number "",actual native library version number ""
,I/chromium( 7063): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7063): Initializing chromium process, singleProcess=true
,W/art     ( 7063): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7063): ApplicationContext is null in ApplicationStatus
,W/chromium( 7063): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7063): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7063): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7063): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7063): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7063): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7063): Local Branch: 
I/Adreno-EGL( 7063): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7063): Local Patches: NONE
I/Adreno-EGL( 7063): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  885): Message: 20
,D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17948992:true
,W/ActivityManager(  885): Activity pause timeout for ActivityRecord{3c26f3cf u0 com.test.thalitest/.MainActivity t3}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,W/art     ( 7063): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7063): onDetachedFromWindow called when already detached. Ignoring
,I/art     (  885): Explicit concurrent mark sweep GC freed 36653(1772KB) AllocSpace objects, 2(225KB) LOS objects, 33% free, 20MB/30MB, paused 1.616ms total 154.185ms
,D/SystemWebViewEngine( 7063): CordovaWebView is running on device made by: motorola
,W/art     ( 7063): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7063): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 7063): Render dirty regions requested: true
,D/Atlas   ( 7063): Validating map...
,W/chromium( 7063): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 7063): Initialized EGL, version 1.4
,D/OpenGLRenderer( 7063): Enabling debug mode 0
,I/Keyboard.Facilitator( 1418): onFinishInput()
,I/LaunchCheckinHandler(  885): Displayed com.test.thalitest/.MainActivity,cp,ca,946
I/ActivityManager(  885): Displayed com.test.thalitest/.MainActivity: +875ms (total +946ms)
,W/IInputConnectionWrapper( 7063): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 7063): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 7063): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 7063): Cannot call determinedVisibility() - never saw a connection for the pid: 7063
,D/JsMessageQueue( 7063): Set native->JS mode to OnlineEventsBridgeMode
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/jxcore_app_log( 7063): JniHelper::setJavaVM(0xb8e60310), pthread_self() = -1189149632
D/JX-Cordova( 7063): jxcore cordova android initializing
,W/jxcore-log( 7063): Initializing JXcore engine
W/jxcore-log( 7063): JXcore engine is ready
,W/jxcore-log( 7063): Starting JXcore engine
,W/.test.thalitest( 7063): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10381 path="socket:[5878]" dev="sockfs" ino=5878 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 7063): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10381 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 7063): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10381 path="socket:[9541]" dev="sockfs" ino=9541 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 7063): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10381 path="socket:[30901]" dev="sockfs" ino=30901 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 7063): Platform android
W/jxcore-log( 7063): 
,W/jxcore-log( 7063): Process ARCH arm
W/jxcore-log( 7063): 
,I/jxcore-log( 7063): JXcore Cordova bridge is ready!
I/jxcore-log( 7063): 
,W/jxcore-log( 7063): JXcore engine is started
,I/chromium( 7063): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7063): Toggling radios to true
I/jxcore-log( 7063): 
,D/BluetoothAdapter( 7063): enable(): BT is already enabled..!
,D/WifiService(  885): New client listening to asynchronous messages
,D/WifiService(  885): setWifiEnabled: true pid=7063, uid=10381
E/WifiService(  885): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 7063): Radios toggled
I/jxcore-log( 7063): 
,D/BluetoothManagerService(  885): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 7063): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 7063): 
I/jxcore-log( 7063): Perf Test app loaded loaded
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): check test folder
I/jxcore-log( 7063): 
,I/jxcore-log( 7063): found test : ./testFindPeers.js
I/jxcore-log( 7063): 
,D/TCMD    (  499): NL - Read 1004 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
,D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
,I/wpa_supplicant( 1411): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294):  STA Disconnected !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  294): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering(  885): InitialState.processMessage what=4
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1411): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
E/WifiStateMachine(  885): WifiStateMachine: Leaving Connected state
,W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
,I/wpa_supplicant( 1411): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/Tethering(  885): ApnList is empty for checkDunConfigured()
D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  1
D/Tethering(  885):  5
D/Tethering(  885):  7
D/Tethering(  885):  0
I/jxcore-log( 7063): found test : ./testSendData.js
I/jxcore-log( 7063): 
,E/WifiStateMachine(  885): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering(  885): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  885): do suspend true
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  292): Clearing all IP addresses on wlan0
,D/TCMD    (  499): NL - Read 60 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 21
,D/TCMD    (  499): Listening for incoming client connection request
,V/NativeCrypto( 1726): Read error: ssl=0xb90f1bb0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1726): SSL shutdown failed: ssl=0xb90f1bb0: I/O error during system call, Broken pipe
,E/WifiStateMachine(  885): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
,I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/WifiMetrics(  885): connected time updated 160626
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/ActivityManager(  885): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=7157 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  885): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  885): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Disconnected - quitting
,D/CSLegacyTypeTracker(  885): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  885): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524292
I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/chromium( 7063): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
E/WifiStateMachine(  885): Start Disconnecting Watchdog 1
,I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1411): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
E/WifiStateMachine(  885): ConnectModeState: Network connection lost 
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  885): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  885): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  885): do suspend true
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  292): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  885): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/ResourcesManager( 7157): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7183 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6831:com.google.android.videos/u0a98 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10098/pid_6831/cgroup.procs: No such file or directory
,W/ResourcesManager( 7183): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 8
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  294): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1411): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  294): Event received = Trying to associate with
D/WifiMonitor(  885): didn't find BSSID Trying to associate with SSID 'NG700'
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
E/wpa_supplicant( 1411): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/TCMD    (  499): NL - Read 56 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
,E/WifiStateMachine(  885): [1,450,238,348,024 ms] noteScanEnd no scan source
,E/WifiStateMachine(  885): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@16fc2ec9 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  885): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel_SMS( 7183): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7183): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7183): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7183): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7183): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7183): MmsConfig.loadFromResources
,E/Babel_SMS( 7183): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7183): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7183): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7183): startup - clean
,D/TCMD    (  499): NL - Read 312 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 192 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
,D/TCMD    (  499): NL - Read 1004 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1411): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  294): Event received = Associated with c0:ff:d4
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,D/TCMD    (  499): NL - Read 80 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 80 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/TCMD    (  499): NL - Read 68 bytes from update socket.
D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/Tethering(  885): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  885): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  885): ApnList is empty for checkDunConfigured()
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1411): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1411): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/Tethering(  885):  upstream interface types: 
D/Tethering(  885):  0
,D/Tethering(  885):  1
D/TCMD    (  499): NL - Read 1004 bytes from update socket.
,D/TCMD    (  499): NL - message type is RTM_NEWLINK
D/TCMD    (  499): Listening for incoming client connection request
D/Tethering(  885):  5
D/Tethering(  885):  7
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  294): Event received = WPA: Key negotiation com
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  294):  STA Connected !!
E/MDMCTBK (  294): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  294): get_freq !!, resp=2412
I/MDMCTBK (  294): get_freq !!, Strip data
I/MDMCTBK (  294): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  294): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  294): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  294): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1192329816
I/MDMCTBK (  294): return from set_get_from_wpa_supplicant
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
D/MDMCTBK (  294): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
E/MDMCTBK (  294): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  294): , reply_len: 3, ret: 0
E/MDMCTBK (  294): MdmCutbackHndler, resp=OK
E/MDMCTBK (  294): 
D/MDMCTBK (  294): wifi_set_tx_pwr: Exit
I/Babel   ( 7183): deleted: false for 0
,D/Tethering(  885): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  885): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  885): Network connection established
E/WifiStateMachine(  885): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  885): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  885): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  885): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  885): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  885): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  292): Setting iface cfg
,E/WifiStateMachine(  885): Start Dhcp Watchdog 2
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  885): do suspend false
,E/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  885): Unexpected BatchedScanResults :null
,E/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23abc592 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@23abc592 target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 7183): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7183): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7183): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7183): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7183): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7183): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7183): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7183): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  885): Killing 6925:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,E/DHCPCD  ( 7232): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 7232): version 5.5.6 starting
,E/DHCPCD  ( 7232): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 7232): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 7232): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_6925/cgroup.procs: No such file or directory
,I/vclib   ( 7183): onServiceConnected
W/Babel   ( 7183): Attempted to change video mute state without an active call.
,D/DHCPCD  ( 7232): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 7232): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 7232): wlan0: sending REQUEST (xid 0xdb553541), next in 3.02 seconds
,I/DHCPCD  ( 7232): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 7232): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 7232): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 7232): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 7232): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 7232): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  499): NL - Read 60 bytes from update socket.
D/TCMD    (  499): NL - ignore NL message, type = 20
D/TCMD    (  499): Listening for incoming client connection request
,D/DHCPCD  ( 7232): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  885): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  885): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  885): do suspend true
,D/WifiP2pService(  885): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  885): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  885): WifiStateMachine DHCP successful
E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  885): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  885): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  885): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  885): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  885): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  885): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  885): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  885): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  885): Setting Dns servers for network 101 to [/192.168.1.1]
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
,D/CSLegacyTypeTracker(  885): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  885): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine(  885): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/Checkin (  885): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  885): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1535): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 03:59:10 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450238350255], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450238350235]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Validated
,D/ConnectivityService(  885): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524290
D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1535): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1294): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1535): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1535): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1535): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/PollingManager( 2719): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  885): MasterInitialState.processMessage what=3
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2719): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1477): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2719): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6895): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 6895): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6895): type=WIFI subType= reason=null isConnected=true
,D/OtaApp  ( 2719): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2719): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2719): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2719): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2719): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2719): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2719): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2719): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2719): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2719): Registering with Alarm Manager to restart CCE
D/CCE     ( 2719): Registering with Alarm Manager to restart CCE
D/CCE     ( 2719): Registering with Alarm Manager to restart CCE
D/OtaApp  ( 2719): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2719): [debug] > CusSM.onRadioDown
I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7323 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 22.043ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 22.505ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 21.231ms
,V/Mms     ( 7323): mnc/mcc: 
,V/Mms     ( 7323): tag: int value: recipientLimit - 20
V/Mms     ( 7323): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7323): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7323): tag: int value: maxSubjectLength - 80
V/Mms     ( 7323): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7323): tag: bool value: enableGroupMms - false
V/Mms     ( 7323):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7323): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7349 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6692:com.google.android.gms/u0a16 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_6692/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7349): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7349): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7349): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  885): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  885): Start proc com.google.android.gms for broadcast com.google.android.gms/.mdm.receivers.ConnectivityReceiver: pid=7370 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6546:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_6546/cgroup.procs: No such file or directory
,W/ResourcesManager( 7370): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7370): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/global frequency( 2719): no tags to log
,D/Checkin ( 2719): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MultiDex( 7370): VM with version 2.1.0 has multidex support
I/MultiDex( 7370): install
I/MultiDex( 7370): VM has multidex support, MultiDex support library is disabled.
D/BSUtils ( 2719): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 58897(3MB) AllocSpace objects, 34(1219KB) LOS objects, 39% free, 7MB/12MB, paused 841us total 46.557ms
,V/JNIHelp ( 7370): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7370): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7370): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@247abd34: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7370): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  885): Killing 7183:com.google.android.talk/u0a70 (adj 15): empty #7
,I/art     (  885): Explicit concurrent mark sweep GC freed 49018(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.733ms total 134.565ms
,D/BSUtils ( 2719): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2719): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7183/cgroup.procs: No such file or directory
,D/NativeLibraryUtils( 7370): Install completed successfully. count=14 extracted=0
,D/BSUtils ( 2719): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/CheckinService( 7370): Checkin interval check for package: unspecified last checkin: 1450238262038 min interval config: 0 actual interval: 89655
,I/CheckinService( 7370): Disabling old GoogleServicesFramework version
,I/CheckinService( 7370): Checking schedule, now: 1450238351736 next: 1450238291959
I/CheckinService( 7370): active receiver: enabled
,I/CheckinService( 7370): Preparing to send checkin request
,D/BSUtils ( 2719): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/EventLogService( 7370): Accumulating logs since 1450238259096
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/iu.SyncManager( 7370): SYNC; picasa accounts
,I/BSUtils ( 2719): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/NetworkLogImpl( 7370): Loaded NetworkSpeedPredictor
,I/iu.Environment( 7370): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/BSUtils ( 2719): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/iu.UploadsManager( 7370): num queued entries: 0
I/iu.UploadsManager( 7370): num updated entries: 0
,I/iu.SyncManager( 7370): NEXT; no task
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7406 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 4432(184KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 579us total 30.706ms
,I/art     ( 7370): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7370): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 2719): Explicit concurrent mark sweep GC freed 25502(1495KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.123ms total 91.168ms
,D/BSUtils ( 2719): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2719): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2719): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2719): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2719): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2719): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2719): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2719): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2719): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/CheckinRequestBuilder( 7370): Checkin reason type: 8 attempt count: 1
,D/WifiService(  885): New client listening to asynchronous messages
,E/ActivityThread( 7370): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7433 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7433): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 7063): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7063): 
,I/ActivityManager(  885): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7456 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7456): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7456): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel_SMS( 7433): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7433): MmsConfig.loadMmsSettings
I/Babel_SMS( 7433): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7433): MmsConfig.loadFromDatabase
,I/MultiDex( 7456): VM with version 2.1.0 has multidex support
I/MultiDex( 7456): install
,I/MultiDex( 7456): VM has multidex support, MultiDex support library is disabled.
,E/Babel_SMS( 7433): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7433): MmsConfig.loadFromResources
,V/JNIHelp ( 7456): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Babel_SMS( 7433): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7433): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ActivityThread( 7456): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7456): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d0a1abe: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7456): Installed default security provider GmsCore_OpenSSL
,W/Settings( 7433): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7433): startup - clean
,I/Babel   ( 7433): deleted: false for 0
,I/art     ( 7456): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7456): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7490 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 7456): Install completed successfully. count=14 extracted=0
,W/VideoCapabilities( 7433): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7433): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7433): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7433): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7433): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7433): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7433): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7433): Unrecognized profile 2130706433 for video/avc
,I/art     (  885): Explicit concurrent mark sweep GC freed 9678(454KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.453ms total 112.246ms
,I/vclib   ( 7433): onServiceConnected
W/Babel   ( 7433): Attempted to change video mute state without an active call.
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
,I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,I/Babel   ( 7433): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  885): Killing 7157:com.motorola.context/u0a8 (adj 15): empty #7
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e8b000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e8b000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xbe8eb4e0
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb76709c8, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb76aa5c8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb77a7a80, idLength=0xb55c6730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=51004925
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb76dd828
D/DrmWidevineDash(  296): message_length=1590, signature=0xb7688f10, signature_length=3042731796
,D/ConnectivityService(  885): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_7157/cgroup.procs: No such file or directory
,D/Tethering(  885): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2719): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2719): now: 207953 ,futureTime: 9223372036854775807
D/PollingManager( 2719): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2719): now: 207953 ,futureTime: 9223372036854775807
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/PollingManager( 2719): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2719): now: 207954 ,futureTime: 9223372036854775807
,D/OtaApp  ( 2719): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2719): [debug] > PollingManagerService, now: 207958 ,futureTime: 35381012
D/OtaApp  ( 2719): [debug] > Polling alarm set to expire at: 35381012 Current Time: 207959
,I/NetworkMonitor( 6895): type=WIFI subType= reason=null isConnected=true
,D/Central_PollingManager( 1477): now: 207965 ,futureTime: 86486013
D/Central_PollingManager( 1477): Polling alarm set to expire at: 86486013 Current Time: 207968
,D/MMApiProvisionService( 2719): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2719): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2719): createDeviceIdOrLogin update_device
,D/Checkin ( 2719): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2719): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2719): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2719): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2719): createDeviceIdOrLogin update_device
,D/Checkin ( 2719): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2719): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2719): set mOutstandingReq to true.
,I/ Nonce  ( 2719):  Nonce getNonce 
I/ Nonce  ( 2719):  Nonce Request 
I/ Nonce  ( 2719):  Nonce execute Request 
,D/MMApiWebService( 2719): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2719): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2719): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2719): createDeviceIdOrLogin update_device
,D/Checkin ( 2719): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2719): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2719): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2719): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2719): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2719): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2719): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2719): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2719): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2719): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2719): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2719): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 3477(144KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 698us total 34.287ms
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,D/MMApiWebService( 2719): generating token using payload instead of using session token
,D/ Nonce  ( 2719):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2719): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2719): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 7490): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7490):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7490):   adb logcat -s GAv4
,W/ContextImpl( 7490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7490): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7490): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7490): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7490): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 7523): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7523): dex2oat took 149.794ms (threads: 4)
,I/Adreno-EGL( 7456): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7456): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7456): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7456): Local Branch: 
I/Adreno-EGL( 7456): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7456): Local Patches: NONE
I/Adreno-EGL( 7456): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 7490): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/Adreno-EGL( 7456): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7456): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7456): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7456): Local Branch: 
I/Adreno-EGL( 7456): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7456): Local Patches: NONE
I/Adreno-EGL( 7456): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/LibraryLoader( 7490): Time to load native libraries: 3 ms (timestamps 8588-8591)
I/LibraryLoader( 7490): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7490): Binding Chromium to main looper Looper (main, tid 1) {2650af6e}
,I/LibraryLoader( 7490): Expected native library version number "",actual native library version number ""
,I/chromium( 7490): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7490): Initializing chromium process, singleProcess=true
W/art     ( 7490): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7490): ApplicationContext is null in ApplicationStatus
,W/chromium( 7490): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7490): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7490): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7490): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7490): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7490): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7490): Local Branch: 
I/Adreno-EGL( 7490): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7490): Local Patches: NONE
I/Adreno-EGL( 7490): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7490): Requires BLUETOOTH permission
E/WifiStateMachine(  885): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  885): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  885): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  885): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  885): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524295
,I/NSApplication( 7490): Starting up...
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7566 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 6895:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_6895/cgroup.procs: No such file or directory
,I/Adreno-EGL( 7456): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7456): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7456): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7456): Local Branch: 
I/Adreno-EGL( 7456): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7456): Local Patches: NONE
I/Adreno-EGL( 7456): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7456): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7456): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7456): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7456): Local Branch: 
I/Adreno-EGL( 7456): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7456): Local Patches: NONE
I/Adreno-EGL( 7456): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ Nonce  ( 2719):  Nonce Reponse 
D/        ( 2719): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"fa8a5be6-7d1f-43ea-b2b7-0f9e7f230850"}
D/MMApiWSBase( 2719): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2719):  Nonce Handle Reponse 
D/MMApiProvisionService( 2719): mOutstandingReq set to false
,D/MMApiProvisionService( 2719):  pTime 1450100652194 sExp 172742 cTime 1450238354378 tTime 1450273394194
D/MMApiProvisionService( 2719):  No login Required 
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7586 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7323:com.android.mms/u0a23 (adj 15): empty #7
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_7323/cgroup.procs: No such file or directory
,W/ResourcesManager( 7586): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e8b000
E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e8b000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  296): hlos api version =  9
,D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb54c6960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb7674f60, dataLength=8
,D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb76aa5c8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb77a7ac0, idLength=0xb55c6730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=2370495955
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7689990
D/DrmWidevineDash(  296): message_length=1626, signature=0xb77a21c0, signature_length=3042731796
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7608 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,W/DataUsage( 2719): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2719): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7630 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7406:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/CheckinRequestBuilder( 7370): Classify the device as Phone.
,I/ContactLocale( 7608): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Killing 7349:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7406/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7349/cgroup.procs: No such file or directory
,I/MusicStore( 7630): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7630): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7630): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7630): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/CheckinTask( 7370): Sending checkin request (9511 bytes)
,W/ResourcesManager( 7630): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7630): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7630): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7630): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7630): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13d22d91: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7630): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7630): GMSCore installation verified
,I/ConfigStore( 7630): Config Database version: 1
,V/AlarmManager(  885): send {23ff29a5, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/art     (  885): Explicit concurrent mark sweep GC freed 11394(542KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.702ms total 126.926ms
,I/MediaRouter( 7630): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7630): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7630): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7630): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7676 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 24.851ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 424us total 20.044ms
,I/GHttpClientFactory( 7630): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7630): Using platform SSLCertificateSocketFactory
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 26.521ms
,I/CheckinRequestBuilder( 7370): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 7370): Failed to find provider info for com.google.android.wearable.settings
,V/Mms     ( 7676): mnc/mcc: 
,V/Mms     ( 7676): tag: int value: recipientLimit - 20
V/Mms     ( 7676): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7676): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7676): tag: int value: maxSubjectLength - 80
V/Mms     ( 7676): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7676): tag: bool value: enableGroupMms - false
V/Mms     ( 7676):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     ( 6664): Explicit concurrent mark sweep GC freed 1841(68KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 502us total 27.080ms
,I/ActivityManager(  885): Killing 7433:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7433/cgroup.procs: No such file or directory
,W/ResourcesManager( 7676): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7712 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7490:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/CheckinRequestBuilder( 7370): Classify the device as Phone.
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_7490/cgroup.procs: No such file or directory
,I/CheckinTask( 7370): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 7370): Checking schedule, now: 1450238356087 next: 1450839493081
I/CheckinService( 7370): active receiver: disabled
,D/CheckinService( 7370): Recording last checkin time for package unspecified as 1450238356109
,I/ActivityManager(  885): Killing 7586:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,D/PhoneMonitor( 7712): Register our PhoneStateListener
,I/ActivityManager(  885): Killing 7566:com.android.chrome/u0a52 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7586/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7566/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7712): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7712): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 7608:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_7608/cgroup.procs: No such file or directory
,I/CheckinService( 7370): Checkin interval check for package: unspecified last checkin: 1450238356109 min interval config: 0 actual interval: 266
,I/CheckinService( 7370): Checking schedule, now: 1450238356382 next: 1450238386081
,I/CheckinService( 7370): active receiver: disabled
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7734 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7757 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7630:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_7630/cgroup.procs: No such file or directory
,W/ResourcesManager( 7757): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7757): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7757): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7757): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7757): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7757): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7757): MmsConfig.loadFromResources
,E/Babel_SMS( 7757): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7757): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7757): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7757): startup - clean
,I/Babel   ( 7757): deleted: false for 0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7788 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7757): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7757): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7757): Unsupported mime video/mpeg2
,I/GAv4    ( 7788): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7788):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7788):   adb logcat -s GAv4
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7788): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/VideoCapabilities( 7757): Unsupported profile 4 for video/mp4v-es
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7788): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7788): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/VideoCapabilities( 7757): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7757): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7757): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/VideoCapabilities( 7757): Unrecognized profile 2130706433 for video/avc
W/ContextImpl( 7788): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7788): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7788): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/vclib   ( 7757): onServiceConnected
,W/Babel   ( 7757): Attempted to change video mute state without an active call.
,W/GAv4    ( 7788): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7757): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  885): Killing 7676:com.android.mms/u0a23 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_7676/cgroup.procs: No such file or directory
,I/WebViewFactory( 7788): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7788): Time to load native libraries: 1 ms (timestamps 2467-2468)
,I/LibraryLoader( 7788): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7788): Binding Chromium to main looper Looper (main, tid 1) {2650af6e}
I/LibraryLoader( 7788): Expected native library version number "",actual native library version number ""
,I/chromium( 7788): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7788): Initializing chromium process, singleProcess=true
,W/art     ( 7788): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7788): ApplicationContext is null in ApplicationStatus
,W/chromium( 7788): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7788): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7788): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7788): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7788): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7788): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7788): Local Branch: 
I/Adreno-EGL( 7788): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7788): Local Patches: NONE
I/Adreno-EGL( 7788): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7788): Requires BLUETOOTH permission
,I/NSApplication( 7788): Starting up...
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7860 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7712:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_7712/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7879 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7734:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7734/cgroup.procs: No such file or directory
,W/ResourcesManager( 7879): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7899 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7788:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7899): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Killing 7757:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2719): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_7788/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_7757/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2719): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2719): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2719): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2719): onServiceConnected()
,D/GetNotificationsWS( 2719): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2719): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2719): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1726): callingUid 10016, callindPid: 1726
,I/art     (  885): Explicit concurrent mark sweep GC freed 11306(558KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.542ms total 123.449ms
,E/MDM     ( 1726): [176] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 7370): Restart initialization of location
,D/AuthorizationBluetoothService( 1726): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7935 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1726): Explicit concurrent mark sweep GC freed 95519(5MB) AllocSpace objects, 29(487KB) LOS objects, 40% free, 14MB/24MB, paused 1.387ms total 158.104ms
,W/GCoreFlp( 1726): No location to return for getLastLocation()
W/FusedLocationProvider( 1726): location=null
,W/IcingInternalCorpora( 7370): getNumBytesRead when not calculated.
,E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@90fb31f)
,E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d3ce66c)
,E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@14ab3435)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@ccb90ca)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3f06623b)
,E/MDM     ( 1726): [189] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 7370): Restart initialization of location
,D/AuthorizationBluetoothService( 1726): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7965 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1726): No location to return for getLastLocation()
,W/FusedLocationProvider( 1726): location=null
,I/MusicStore( 7965): Database version: 120
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7965): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7965): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7965): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7965): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7965): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7965): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7965): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7965): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13d22d91: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7965): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7965): GMSCore installation verified
,I/ConfigStore( 7965): Config Database version: 1
,I/MediaRouter( 7965): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7965): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7965): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7965): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  885): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8002 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7965): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7965): Using platform SSLCertificateSocketFactory
,V/Mms     ( 8002): mnc/mcc: 
,V/Mms     ( 8002): tag: int value: recipientLimit - 20
V/Mms     ( 8002): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 8002): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8002): tag: int value: maxSubjectLength - 80
V/Mms     ( 8002): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8002): tag: bool value: enableGroupMms - false
,V/Mms     ( 8002):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 8002): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8032 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7860:com.android.chrome/u0a52 (adj 15): empty #7
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 23.166ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 19.234ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.666ms
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_7860/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 7879:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 8032): Register our PhoneStateListener
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_7879/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 8032): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 8032): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  885): Killing 7899:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_7899/cgroup.procs: No such file or directory
,I/CheckinService( 7370): Checkin interval check for package: unspecified last checkin: 1450238356109 min interval config: 0 actual interval: 4024
,I/CheckinService( 7370): Checkin interval check for package: unspecified last checkin: 1450238356109 min interval config: 0 actual interval: 4028
,I/CheckinService( 7370): Checking schedule, now: 1450238360150 next: 1450238386081
,I/CheckinService( 7370): active receiver: disabled
,I/CheckinService( 7370): Checking schedule, now: 1450238360177 next: 1450238386081
I/CheckinService( 7370): active receiver: disabled
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8053 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 8053): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8053): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8053): MmsConfig.loadMmsSettings
I/Babel_SMS( 8053): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8053): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8053): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8053): MmsConfig.loadFromResources
,E/Babel_SMS( 8053): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8053): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8053): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8053): startup - clean
,I/Babel   ( 8053): deleted: false for 0
,I/ActivityManager(  885): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8087 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 8053): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8053): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 8053): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8053): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8053): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8053): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8053): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8053): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 8053): onServiceConnected
W/Babel   ( 8053): Attempted to change video mute state without an active call.
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8087): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8087): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 8053): connection state changed from UNKNOWN to CONNECTED
I/GAv4    ( 8087): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8087):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8087):   adb logcat -s GAv4
,I/ActivityManager(  885): Killing 7965:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8087): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  279): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  279): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8087): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  885): failed to open /acct/uid_10080/pid_7965/cgroup.procs: No such file or directory
,W/GAv4    ( 8087): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8087): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8087): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/WebViewFactory( 8087): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 8087): Time to load native libraries: 2 ms (timestamps 6069-6071)
,I/LibraryLoader( 8087): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8087): Binding Chromium to main looper Looper (main, tid 1) {2650af6e}
I/LibraryLoader( 8087): Expected native library version number "",actual native library version number ""
,I/chromium( 8087): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8087): Initializing chromium process, singleProcess=true
,W/art     ( 8087): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 8087): ApplicationContext is null in ApplicationStatus
,W/chromium( 8087): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 8087): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 8087): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 8087): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8087): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8087): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8087): Local Branch: 
I/Adreno-EGL( 8087): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8087): Local Patches: NONE
I/Adreno-EGL( 8087): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 8087): Requires BLUETOOTH permission
,I/art     (  885): Explicit concurrent mark sweep GC freed 11081(531KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.502ms total 114.584ms
,I/NSApplication( 8087): Starting up...
,I/ActivityManager(  885): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8159 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8002:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10023/pid_8002/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=8178 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 7456:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:33000 mC
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_7456/cgroup.procs: No such file or directory
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 8178): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  885): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  885): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  885): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  885): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1a553c4
,I/GCoreNlp( 1726): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1572): Deferring update until onResume
,I/ActivityManager(  885): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=8209 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 7935:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 8209): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Killing 8032:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_7935/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2719): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_8032/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2719): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2719): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2719): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2719): onServiceConnected()
D/GetNotificationsWS( 2719): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2719): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2719): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2719): started with background data enabled, making sure notification mechanism is enabled
D/OtaApp  ( 2719): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2719): [debug] > In cancelAnyPendingIntentSetPreviously
I/ActivityManager(  885): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,V/AlarmManager(  885): done {23ff29a5, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [6849ms]
,D/OtaApp  ( 2719): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2719): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2719): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8239 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2719): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2719): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2719): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2719): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2719): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2719): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2719): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2719): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2719): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 7063): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1418): onFinishInput()
,D/PhoneMonitor( 8239): Register our PhoneStateListener
,I/LaunchCheckinHandler(  885): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,169
,V/SetupWizard( 8239): Connected to Gservices successfully
,I/ActivityManager(  885): Killing 8053:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_8053/cgroup.procs: No such file or directory
,D/GCM     ( 1726): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1726): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  885): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=8262 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/GCM     ( 1726): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8286 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8087:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10081/pid_8087/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8309 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8326 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8159:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  885): Killing 8178:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10052/pid_8159/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_8178/cgroup.procs: No such file or directory
,W/ResourcesManager( 8326): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8326): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8326): MmsConfig.loadMmsSettings
I/Babel_SMS( 8326): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8326): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8326): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8326): MmsConfig.loadFromResources
,E/Babel_SMS( 8326): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8326): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8326): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8326): startup - clean
,I/Babel   ( 8326): deleted: false for 0
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8355 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 320us total 21.594ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 24.541ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 20.332ms
,W/asset   ( 8355): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8355): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8355): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8355): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/VideoCapabilities( 8326): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8326): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8326): Unsupported mime video/mpeg2
,D/PackageBroadcastService( 7370): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3b383c47 new=com.google.android.velvet.VelvetApplication@3b383c47
,I/UpdateIcingCorporaServi( 8286): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 7370): Null package name or gms related package.  Ignoreing.
I/VideoCapabilities( 8326): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8326): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8326): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8326): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8326): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8388 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8388): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8286): UpdateCorporaTask done [took 173 ms] updated apps [took 173 ms] 
,I/ActivityManager(  885): Killing 8262:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/Icing   ( 7370): Storage manager: low false usage 1.76MB avail 3.13GB capacity 4.85GB
,I/art     (  885): Explicit concurrent mark sweep GC freed 17536(910KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.812ms total 124.054ms
,W/libprocessgroup(  885): failed to open /acct/uid_10088/pid_8262/cgroup.procs: No such file or directory
,I/vclib   ( 8326): onServiceConnected
,W/Babel   ( 8326): Attempted to change video mute state without an active call.
,W/ResourcesManager( 8326): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8326): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8326): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 8326): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8326): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  885): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8428 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8239:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/Icing   ( 7370): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_8239/cgroup.procs: No such file or directory
,D/Finsky  ( 8428): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 7370): Internal init done: storage state 0
,I/Icing   ( 7370): Post-init done
,I/Icing   ( 7370): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 8428): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8428): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8428): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 8428): Skipping gmscore version check
D/Finsky  ( 8428): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8428): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 8428): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8428): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  885): Killing 8309:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_8309/cgroup.procs: No such file or directory
,D/TaskPersister(  885): removeObsoleteFile: deleting file=2_task.xml
,I/Icing   ( 7370): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 7370): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 7370): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  885): Killing 8355:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_8355/cgroup.procs: No such file or directory
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=296, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311469, SEQNUM=4493, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-492, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2524): Disconnected process message: 10, size: 0
,I/ActivityManager(  885): Killing 8286:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_8286/cgroup.procs: No such file or directory
,I/CheckinService( 7370): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:33000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312136, SEQNUM=4497, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-517, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2524): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2524): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ClearcutLoggerApiImpl( 1726): disconnect managed GoogleApiClient
,V/AlarmManager(  885): send {389b5fd, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  885): send {313cc095, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  885): done {389b5fd, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [18ms]
,V/AlarmManager(  885): done {313cc095, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [23ms]
,I/CheckinService( 7370): Checkin interval check for package: unspecified last checkin: 1450238356109 min interval config: 0 actual interval: 38539
,I/CheckinService( 7370): Checking schedule, now: 1450238394660 next: 1450238386081
I/CheckinService( 7370): active receiver: enabled
,I/CheckinService( 7370): Preparing to send checkin request
I/EventLogService( 7370): Accumulating logs since 1450238352115
,I/CheckinRequestBuilder( 7370): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 7370): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  885): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8519 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8519): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8519): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8519): VM with version 2.1.0 has multidex support
I/MultiDex( 8519): install
I/MultiDex( 8519): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8519): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8519): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8519): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d0a1abe: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8519): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1726): callingUid 10016, callindPid: 1726
,E/MDM     ( 1726): [176] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1726): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 7370): Restart initialization of location
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 8519): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8519): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/GCoreFlp( 1726): No location to return for getLastLocation()
W/FusedLocationProvider( 1726): location=null
,D/NativeLibraryUtils( 8519): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  296): Instantiating CDM.
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e89000
,E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e89000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb5020960
,D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb779e690, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb76aa5c8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb77a7aa0, idLength=0xb55c6730
D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=3629591441
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb76dd828
D/DrmWidevineDash(  296): message_length=1591, signature=0xb77a22f0, signature_length=3042731796
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8560): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8560): dex2oat took 66.586ms (threads: 4)
,I/Adreno-EGL( 8519): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8519): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8519): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8519): Local Branch: 
I/Adreno-EGL( 8519): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8519): Local Patches: NONE
I/Adreno-EGL( 8519): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8519): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8519): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8519): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8519): Local Branch: 
I/Adreno-EGL( 8519): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8519): Local Patches: NONE
I/Adreno-EGL( 8519): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8519): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8519): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8519): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8519): Local Branch: 
I/Adreno-EGL( 8519): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8519): Local Patches: NONE
I/Adreno-EGL( 8519): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8519): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8519): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8519): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8519): Local Branch: 
I/Adreno-EGL( 8519): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8519): Local Patches: NONE
I/Adreno-EGL( 8519): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  296): CdmEngine::OpenSession
I/WVCdm   (  296): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  296): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  296): Service_Initialize: starts!
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
E/QSEECOMAPI: (  296): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  296): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  296): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  296): App is not loaded in QSEE
,D/QSEECOMAPI: (  296): Loaded image: APP id = 3
,D/DrmWidevineDash(  296): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e89000
,E/DrmWidevineDash(  296): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4e89000
,D/DrmWidevineDash(  296): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  296): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  296): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: starts! SID=0xb5020960
D/DrmWidevineDash(  296): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  296): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: starts! randomData=0xb77a24c8, dataLength=8
D/DrmWidevineDash(  296): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb76aa5c8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  296): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  296): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  296): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  296): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  296): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: starts! deviceID=0xb77a7ac0, idLength=0xb54c6730
,D/DrmWidevineDash(  296): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  296): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  296): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  296): hlos api version =  9
D/DrmWidevineDash(  296): tz api version =  8
D/DrmWidevineDash(  296): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  296): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  296): PrepareKeyRequest: nonce=1154941297
D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7689990
D/DrmWidevineDash(  296): message_length=1626, signature=0xb768bfd0, signature_length=3041683220
,D/DrmWidevineDash(  296): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  296): CdmEngine::CloseSession
D/DrmWidevineDash(  296): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  296): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  296): L3 Terminate.
D/DrmWidevineDash(  296): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  296): Service_Uninitialize: starts!
D/QSEECOMAPI: (  296): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  296): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  296): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  296): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 7370): Classify the device as Phone.
,I/CheckinTask( 7370): Sending checkin request (9510 bytes)
,I/CheckinRequestBuilder( 7370): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 7370): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 7370): Classify the device as Phone.
,I/CheckinTask( 7370): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 7370): Checking schedule, now: 1450238397503 next: 1450839534494
I/CheckinService( 7370): active receiver: disabled
,D/CheckinService( 7370): Recording last checkin time for package unspecified as 1450238397520
,I/ActivityManager(  885): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8590 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8590): Register our PhoneStateListener
,V/SetupWizard( 8590): Connected to Gservices successfully
,D/GCM     ( 1726): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  885): Killing 8388:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  885): Killing 8209:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_8388/cgroup.procs: No such file or directory
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_8209/cgroup.procs: No such file or directory
,V/AlarmManager(  885): send {1f0c5b3e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {349a2d75, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  885): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8612 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  885): done {1f0c5b3e, *alarm*:android.intent.action.TIME_TICK} [118ms]
,I/GAv4    ( 8612): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8612):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8612):   adb logcat -s GAv4
,W/GAv4    ( 8612): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8612): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8612): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  885): done {349a2d75, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [273ms]
,I/ActivityManager(  885): Killing 8428:com.android.vending/u0a32 (adj 13): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_8428/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8659 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  885): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  885): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  885): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  885): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2ad86921
,I/GCoreNlp( 1726): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1572): Deferring update until onResume
,I/art     (  885): Explicit concurrent mark sweep GC freed 22255(1148KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.378ms total 117.127ms
,I/ActivityManager(  885): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8688 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  885): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8710 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  885): Killing 8590:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10035/pid_8590/cgroup.procs: No such file or directory
,W/ResourcesManager( 8326): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8326): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8710): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8734 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  885): Killing 8519:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_8519/cgroup.procs: No such file or directory
,W/asset   ( 8734): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8734): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8734): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8734): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 7370): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 7370): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3b383c47 new=com.google.android.velvet.VelvetApplication@3b383c47
,I/UpdateIcingCorporaServi( 8659): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 7370): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  885): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8760 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8760): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8659): UpdateCorporaTask done [took 158 ms] updated apps [took 158 ms] 
,I/ActivityManager(  885): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8791 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 22.680ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 20.485ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.884ms
,W/ProcessCpuTracker(  885): Skipping unknown process pid 8779
,W/ProcessCpuTracker(  885): Skipping unknown process pid 8782
,I/ActivityManager(  885): Killing 8612:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10055/pid_8612/cgroup.procs: No such file or directory
,D/Finsky  ( 8791): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8791): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8791): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8791): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8791): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8791): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8791): Skipping gmscore version check
,I/ActivityManager(  885): Killing 8688:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10019/pid_8688/cgroup.procs: No such file or directory
,D/Finsky  ( 8791): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8791): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 7370): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 7370): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  885): Killing 8734:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10027/pid_8734/cgroup.procs: No such file or directory
,I/ActivityManager(  885): Killing 8326:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10070/pid_8326/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1418): run()
I/Keyboard.Facilitator( 1418): flushDynamicLanguageModels()
,I/ConfigService( 1726): onCreate
,I/ConfigService( 1726): onDestroy
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311448, SEQNUM=4525, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-580, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2524): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 7063): Connected to the server!
I/jxcore-log( 7063): 
,I/chromium( 7063): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  294): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311029, SEQNUM=4531, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=-843, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2524): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2524): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  885): send {1f0c5b3e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {e748dd7, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  885): done {e748dd7, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [25ms]
,V/AlarmManager(  885): done {1f0c5b3e, *alarm*:android.intent.action.TIME_TICK} [54ms]
,V/AlarmManager(  885): send {199ee3a6, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  885): done {199ee3a6, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [3ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  885): send {1f0c5b3e, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  885): send {362216c4, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  885): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8885 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  885): done {1f0c5b3e, *alarm*:android.intent.action.TIME_TICK} [86ms]
,I/GAv4    ( 8885): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8885):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8885):   adb logcat -s GAv4
,W/GAv4    ( 8885): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8885): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8885): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  885): done {362216c4, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [233ms]
,I/ActivityManager(  885): Killing 8659:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_8659/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310896, SEQNUM=4539, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=3229, POWER_SUPPLY_CHARGE_COUNTER=3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2524): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310592, SEQNUM=4547, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2119, POWER_SUPPLY_CHARGE_COUNTER=9, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2524): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  885): User[0] Flushing usage stats to disk
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310866, SEQNUM=4549, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2524): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2524): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311177, SEQNUM=4551, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=5449, POWER_SUPPLY_CHARGE_COUNTER=7, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2524): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=257, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311160, SEQNUM=4552, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=6, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2524): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=256, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312033, SEQNUM=4553, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9214, POWER_SUPPLY_CHARGE_COUNTER=26, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=256, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310866, SEQNUM=4555, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-22, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  885): send {1f0c5b3e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {2d9e6b6b, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,V/AlarmManager(  885): send {199ee3a6, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  885): send {399154e2, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  885): send {138a3073, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,V/AlarmManager(  885): send {188bdb30, *walarm*:com.motorola.ccc.cce.alarmintent}
,V/AlarmManager(  885): send {77523a9, *walarm*:com.motorola.ccc.cce.alarmintent}
,V/AlarmManager(  885): send {1b73dd2e, *walarm*:com.motorola.ccc.cce.alarmintent}
,I/ProcessStatsService(  885): Prepared write state in 75ms
,V/AlarmManager(  885): done {2d9e6b6b, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [112ms]
,V/AlarmManager(  885): done {199ee3a6, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [131ms]
,I/ProcessStatsService(  885): Prepared write state in 8ms
,I/ProcessStatsService(  885): Prepared write state in 17ms
,I/ProcessStatsService(  885): Prepared write state in 7ms
,V/AlarmManager(  885): done {1f0c5b3e, *alarm*:android.intent.action.TIME_TICK} [179ms]
,V/AlarmManager(  885): done {399154e2, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [188ms]
,V/AlarmManager(  885): done {138a3073, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [211ms]
,I/EventLogService( 7370): Aggregate from 1450238394682 (log), 1450237531422 (data)
,V/AlarmManager(  885): done {188bdb30, *walarm*:com.motorola.ccc.cce.alarmintent} [233ms]
,V/AlarmManager(  885): done {77523a9, *walarm*:com.motorola.ccc.cce.alarmintent} [247ms]
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  885): done {1b73dd2e, *walarm*:com.motorola.ccc.cce.alarmintent} [266ms]
,I/ProcessStatsService(  885): Pruning old procstats: /data/system/procstats/state-2015-01-07-01-19-15.bin
,TIME-OUT KILL (timeout was 1800000ms),I/GoogleURLConnFactory( 1726): Using platform SSLCertificateSocketFactory
I/PhenotypeConfigurator( 1726): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
D/AndroidRuntime( 8968): 
D/AndroidRuntime( 8968): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8968): CheckJNI is OFF
D/AndroidRuntime( 8968): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10381 user=-1: uninstall pkg
I/ActivityManager(  885): Killing 7063:com.test.thalitest/u0a381 (adj 9): stop com.test.thalitest
W/PackageSettings(  885): Skipping PackageSetting{1cc14832 com.example.hello/10377} due to missing metadata
D/WifiService(  885): Client connection lost with reason: 4
I/WindowState(  885): WIN DEATH: Window{13ce7b42 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  885):   Force finishing activity ActivityRecord{3c26f3cf u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10381 user=0: pkg removed
I/art     ( 3539): Explicit concurrent mark sweep GC freed 7258(1574KB) AllocSpace objects, 28(448KB) LOS objects, 40% free, 7MB/12MB, paused 780us total 39.951ms
W/ActivityManager(  885): Spurious death for ProcessRecord{37a4ec42 7063:com.test.thalitest/u0a381}, curProc for 7063: null
W/GeofencerStateMachine( 1726): Ignoring removeGeofence because network location is disabled.
I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1418): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1418): run()
I/Decoder ( 1418): createOrResetDecoder
D/VoicemailCleanupService( 8710): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=9010 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 1572): Explicit concurrent mark sweep GC freed 6680(448KB) AllocSpace objects, 6(297KB) LOS objects, 25% free, 13MB/17MB, paused 673us total 143.205ms
I/ConfigService( 1726): onCreate
I/art     (  885): Explicit concurrent mark sweep GC freed 30472(2010KB) AllocSpace objects, 11(268KB) LOS objects, 33% free, 20MB/30MB, paused 2.115ms total 189.999ms
I/art     (  885): WaitForGcToComplete blocked for 94.182ms for cause Explicit
W/asset   ( 9010): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 9010): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 9010): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9010): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1418): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1418): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1418): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1418): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1418): run()
I/StatsUtilsManager( 1418): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1418): shouldRecordStats() = Too Soon
I/ActivityManager(  885): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=9038 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  885): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  885): removeObsoleteFile: deleting file=3_task.xml
I/Launcher( 1572): Deferring update until onResume
I/art     (  885): Explicit concurrent mark sweep GC freed 7005(387KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.627ms total 192.280ms
W/ContextImpl( 9038): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 7370): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 7370): Reading stored module config
D/AccountUtils( 7370): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 7370): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7370): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 7370): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 7370): App measurement is starting up, version: 8489
I/GMPM-SVC( 7370): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
D/AndroidRuntime( 8968): Shutting down VM
I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
E/NetworkScheduler.SchedulerReceiver( 1726): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1726): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 7370): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 7370): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 7370): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 7370): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 7370): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 7370): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 7370): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 7370): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 7370): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 7370): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 7370): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 7370): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 7370): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=9067 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 7370): doRemovePackageData com.test.thalitest
D/ChimeraCfgMgr( 7370): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 7370): Module APK com.google.android.play.games already loaded
W/BaseAppContext( 7370): Using Auth Proxy for data requests.
I/ActivityManager(  885): Killing 8760:com.google.android.apps.plus/u0a90 (adj 15): empty #7
W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_8760/cgroup.procs: No such file or directory
E/BaseAppContext( 7370): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3b383c47 new=com.google.android.velvet.VelvetApplication@3b383c47
I/ActivityManager(  885): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=9103 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
W/BaseAppContext( 7370): Using Auth Proxy for data requests.
W/BaseAppContext( 7370): Using Auth Proxy for data requests.
W/BaseAppContext( 7370): Using Auth Proxy for data requests.
D/ConnectivityService(  885): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  885): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  885): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 7370): CM callback handler got msg 524290
W/BaseAppContext( 7370): Using Auth Proxy for data requests.
W/BaseAppContext( 7370): Using Auth Proxy for data requests.
W/BaseAppContext( 7370): Using Auth Proxy for data requests.
W/BaseAppContext( 7370): Using Auth Proxy for data requests.
W/BaseAppContext( 7370): Using Auth Proxy for data requests.
E/SQLiteLog( 7370): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 7370): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 7370): Process: com.google.android.gms, PID: 7370
E/AndroidRuntime( 7370): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 7370): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 7370): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 7370): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 7370): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 7370): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 7370): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 7370): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 7370): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 7370): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 7370): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 7370): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7370): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7370): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 7370): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 7370): Sending signal. PID: 7370 SIG: 9
E/DropBoxManagerService(  885): Can't write: system_app_crash
E/DropBoxManagerService(  885): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  885): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  885): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  885): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  885): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  885): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  885): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  885): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  885): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  885): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  885): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  885): 	... 5 more
D/ConnectivityService(  885): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@35383155)
D/WifiService(  885): Client connection lost with reason: 4
D/ConnectivityService(  885): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  885): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/System.err( 1726): FileClientSessionCache: Error writing session data for example.com to /data/data/com.google.android.gms/app_sslcache/example.com.443.
W/System.err( 1726): java.io.FileNotFoundException: /data/data/com.google.android.gms/app_sslcache/example.com.443: open failed: EROFS (Read-only file system)
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
