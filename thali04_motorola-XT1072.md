#### Test 539786633aa3ea0_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:32000 mC
D/AndroidRuntime( 6564): 
D/AndroidRuntime( 6564): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6564): CheckJNI is OFF
D/AndroidRuntime( 6564): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  883): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6583 uid=10390 gids={50390, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6564): Shutting down VM
V/ActivityManager(  883): Display changed displayId=0
W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6583): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6583): Time to load native libraries: 11 ms (timestamps 7567-7578)
I/LibraryLoader( 6583): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6583): Binding Chromium to main looper Looper (main, tid 1) {11cf6728}
,I/LibraryLoader( 6583): Expected native library version number "",actual native library version number ""
,I/chromium( 6583): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6583): Initializing chromium process, singleProcess=true
,W/art     ( 6583): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6583): ApplicationContext is null in ApplicationStatus
,W/chromium( 6583): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6583): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6583): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6583): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6583): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6583): Local Branch: 
I/Adreno-EGL( 6583): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6583): Local Patches: NONE
I/Adreno-EGL( 6583): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4bd9077:true
W/ActivityManager(  883): Activity pause timeout for ActivityRecord{331c107f u0 com.test.thalitest/.MainActivity t3}
I/art     (  883): Explicit concurrent mark sweep GC freed 32422(1616KB) AllocSpace objects, 2(217KB) LOS objects, 33% free, 20MB/31MB, paused 1.887ms total 123.455ms
W/art     ( 6583): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6583): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6583): CordovaWebView is running on device made by: motorola
W/art     ( 6583): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6583): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6583): Render dirty regions requested: true
D/Atlas   ( 6583): Validating map...
W/chromium( 6583): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6583): Initialized EGL, version 1.4
D/OpenGLRenderer( 6583): Enabling debug mode 0
I/Keyboard.Facilitator( 1424): onFinishInput()
I/LaunchCheckinHandler(  883): Displayed com.test.thalitest/.MainActivity,cp,ca,1191
I/ActivityManager(  883): Displayed com.test.thalitest/.MainActivity: +1s28ms (total +1s191ms)
W/IInputConnectionWrapper( 6583): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 6583): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6583): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6583): Cannot call determinedVisibility() - never saw a connection for the pid: 6583
,D/JsMessageQueue( 6583): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6583): JniHelper::setJavaVM(0xb8318310), pthread_self() = -1200980096
,D/JX-Cordova( 6583): jxcore cordova android initializing
,W/art     ( 6583): Suspending all threads took: 9.927ms
,I/art     ( 6583): Background partial concurrent mark sweep GC freed 8800(697KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 11MB/19MB, paused 13.013ms total 59.889ms
,W/jxcore-log( 6583): Initializing JXcore engine
W/jxcore-log( 6583): JXcore engine is ready
,W/jxcore-log( 6583): Starting JXcore engine
,W/.test.thalitest( 6583): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10390 path="socket:[7489]" dev="sockfs" ino=7489 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6583): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10390 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6583): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10390 path="socket:[6804]" dev="sockfs" ino=6804 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6583): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10390 path="socket:[27277]" dev="sockfs" ino=27277 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6583): Platform android
W/jxcore-log( 6583): 
W/jxcore-log( 6583): Process ARCH arm
W/jxcore-log( 6583): 
,I/jxcore-log( 6583): JXcore Cordova bridge is ready!
I/jxcore-log( 6583): 
W/jxcore-log( 6583): JXcore engine is started
I/Choreographer( 6583): Skipped 177 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6583): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6583): Toggling radios to true
I/jxcore-log( 6583): 
,D/BluetoothAdapter( 6583): enable(): BT is already enabled..!
,D/WifiService(  883): New client listening to asynchronous messages
,D/WifiService(  883): setWifiEnabled: true pid=6583, uid=10390
E/WifiService(  883): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6583): Radios toggled
I/jxcore-log( 6583): 
,D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/wpa_supplicant( 1403): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  311):  STA Disconnected !!
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
,I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): get_property_value, Enter
I/MDMCTBK (  311): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  311): get_property_value, Exit
I/MDMCTBK (  311): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  311): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  311): set_property_value, Enter
I/MDMCTBK (  311): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  311): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  311): set_property_value, Exit
I/MDMCTBK (  311): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  311): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  311): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  311): set_property_value, Enter
I/MDMCTBK (  311): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  311): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  311): set_property_value, Exit
E/MDMCTBK (  311): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  311): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1403): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  311): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  883): WifiStateMachine: Leaving Connected state
,D/Tethering(  883): InitialState.processMessage what=4
E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  883): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/wpa_supplicant( 1403): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  311): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  883): do suspend true
W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  883): ApnList is empty for checkDunConfigured()
,D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1403): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Tethering(  883):  0
,D/Tethering(  883): sendTetherStateChangedBroadcast 0, 0, 0
,D/CommandListener(  308): Clearing all IP addresses on wlan0
D/TCMD    (  465): NL - Read 60 bytes from update socket.
D/TCMD    (  465): NL - ignore NL message, type = 21
D/TCMD    (  465): Listening for incoming client connection request
,V/NativeCrypto( 1713): Read error: ssl=0xb86177e0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1713): SSL shutdown failed: ssl=0xb86177e0: I/O error during system call, Broken pipe
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info<unknown ssid>
D/ConnectivityService(  883): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/WifiMetrics(  883): connected time updated 122577
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  883): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6670 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/art     (  328): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 330us total 23.354ms
,D/ConnectivityService(  883): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  883): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Disconnected - quitting
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  883): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/art     (  328): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 19.691ms
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524292
E/wpa_supplicant( 1403): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  883): Start Disconnecting Watchdog 1
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  311): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1403): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,E/WifiStateMachine(  883): ConnectModeState: Network connection lost 
E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  883): do suspend true
I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/wpa_supplicant( 1403): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
D/CommandListener(  308): Clearing all IP addresses on wlan0
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 22.039ms
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,E/ConnectivityService(  883): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  883): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6670): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6696 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6345:com.google.android.videos/u0a98 (adj 15): empty #7
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  311): Event received = WPS-AP-AVAILABLE 
,I/wpa_supplicant( 1403): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  311): Event received = Trying to associate with
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  311): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  883): [1,450,445,372,979 ms] noteScanEnd no scan source
D/WifiMonitor(  883): didn't find BSSID Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 1403): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiStateMachine(  883): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@37d5ed5c sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info0x
,W/libprocessgroup(  883): failed to open /acct/uid_10098/pid_6345/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6696): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/PhenotypeConfigurator( 1713): Scheduling Phenotype for one-off execution 13967 seconds from now (1450445373071)
,D/GetConfigurationSnapshotOperation( 1713): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/TCMD    (  465): NL - Read 312 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 192 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
,D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 80 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 80 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
I/wpa_supplicant( 1403): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  311): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  311): Event received = Associated with c0:ff:d4
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  311): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  0
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  311): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1403): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1403): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  311): Event received = WPA: Key negotiation com
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  311): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  311):  STA Connected !!
E/MDMCTBK (  311): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  311): get_freq !!, resp=2412
I/MDMCTBK (  311): get_freq !!, Strip data
I/MDMCTBK (  311): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): get_property_value, Enter
I/MDMCTBK (  311): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  311): get_property_value, Exit
I/MDMCTBK (  311): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  311): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  311): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
,I/MDMCTBK (  311): set_property_value, Enter
I/MDMCTBK (  311): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  311): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  311): set_property_value, Exit
I/MDMCTBK (  311): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  311): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  311): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): get_property_value, Enter
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
I/MDMCTBK (  311): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  311): get_property_value, Exit
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
I/MDMCTBK (  311): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1216508608
I/MDMCTBK (  311): return from set_get_from_wpa_supplicant
I/MDMCTBK (  311): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
I/MDMCTBK (  311): set_property_value, Enter
I/MDMCTBK (  311): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  311): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  311): set_property_value, Exit
E/MDMCTBK (  311): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  311): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  311): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  311): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  311): , reply_len: 3, ret: 0
E/MDMCTBK (  311): MdmCutbackHndler, resp=OK
E/MDMCTBK (  311): 
D/MDMCTBK (  311): wifi_set_tx_pwr: Exit
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Tethering(  883): sendTetherStateChangedBroadcast 1, 0, 0
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  883): Network connection established
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  883): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  883): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  883): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  308): Setting iface cfg
,E/WifiStateMachine(  883): Start Dhcp Watchdog 2
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend false
,E/wpa_supplicant( 1403): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  883): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1403): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  883): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@358619bd target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@358619bd target=com.android.internal.util.StateMachine$SmHandler }
,I/PhenotypeFlagCommitter( 1713): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1713): Using platform SSLCertificateSocketFactory
,I/Babel_SMS( 6696): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6696): MmsConfig.loadMmsSettings
I/Babel_SMS( 6696): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6696): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6696): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6696): MmsConfig.loadFromResources
E/Babel_SMS( 6696): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6696): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/Uploader( 1713): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,E/DHCPCD  ( 6739): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6739): version 5.5.6 starting
,E/DHCPCD  ( 6739): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6739): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 6739): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,E/global frequency( 2522): no tags to log
D/Checkin ( 2522): publish the event [tag = MOT_CHECKIN event name = LOG]
W/Settings( 6696): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6696): startup - clean
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 55616(3MB) AllocSpace objects, 37(1250KB) LOS objects, 40% free, 7MB/12MB, paused 908us total 67.680ms
D/DHCPCD  ( 6739): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6739): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6739): wlan0: sending REQUEST (xid 0x5e850ced), next in 4.03 seconds
,D/BSUtils ( 2522): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1555): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/Babel   ( 6696): deleted: false for 0
,D/BSUtils ( 2522): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2522): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2522): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1555): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,W/VideoCapabilities( 6696): Unrecognized profile 2130706433 for video/avc
D/BSUtils ( 2522): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,W/AudioCapabilities( 6696): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6696): Unsupported mime video/mpeg2
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 4267(178KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 543us total 28.642ms
,I/BSUtils ( 2522): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/VideoCapabilities( 6696): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6696): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6696): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6696): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6696): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Killing 5884:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/art     (  883): Explicit concurrent mark sweep GC freed 37883(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.811ms total 137.349ms
,D/BSUtils ( 2522): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1555): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2522): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_5884/cgroup.procs: No such file or directory
I/vclib   ( 6696): onServiceConnected
,W/Babel   ( 6696): Attempted to change video mute state without an active call.
,I/BSUtils ( 2522): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2522): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2522): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2522): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2522): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2522): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2522): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2522): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2522): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Uploader( 1713): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1713): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Uploader( 1713): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1713): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1713): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1713): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1713): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1713): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/DHCPCD  ( 6739): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6739): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6739): wlan0: adding IP address 192.168.1.123/24
,D/DHCPCD  ( 6739): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6739): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6739): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  465): NL - Read 60 bytes from update socket.
D/TCMD    (  465): NL - ignore NL message, type = 20
D/TCMD    (  465): Listening for incoming client connection request
D/DHCPCD  ( 6739): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend true
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  883): WifiStateMachine DHCP successful
E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  883): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  883): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  883): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  883): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  883): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  883): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  883): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  883): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-4ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883):    accepting network in place of null
,I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
E/WifiStateMachine(  883): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/CSLegacyTypeTracker(  883): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  883): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Dec 2015 13:29:35 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450445375185], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450445375166]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Validated
,D/ConnectivityService(  883): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1538): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1482): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1482): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6461): type=WIFI subType= reason=null isConnected=true
,D/Central_PollingManager( 1482): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6461): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 6461): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/OtaApp  ( 2522): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6816 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2522): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2522): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2522): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2522): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2522): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2522): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2522): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2522): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2522): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2522): [debug] > CusSM.onRadioDown
,V/Mms     ( 6816): mnc/mcc: 
V/Mms     ( 6816): tag: int value: recipientLimit - 20
V/Mms     ( 6816): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6816): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6816): tag: int value: maxSubjectLength - 80
V/Mms     ( 6816): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6816): tag: bool value: enableGroupMms - false
V/Mms     ( 6816):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6816): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6840 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,V/AlarmManager(  883): send {15125e1f, *walarm*:com.google.android.intent.action.SEND_IDLE}
,I/ActivityManager(  883): Killing 6213:com.google.android.gms/u0a16 (adj 15): empty #7
,D/PhoneMonitor( 6840): Register our PhoneStateListener
,D/ConnectivityService(  883): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_6213/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6583): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): my name is : motorola-XT1072_PT3006
I/jxcore-log( 6583): 
,D/MobileConnectivityChangeReceiver( 6840): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6840): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Start proc com.google.android.gms for broadcast com.google.android.gms/.mdm.receivers.ConnectivityReceiver: pid=6861 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6391:com.android.vending/u0a32 (adj 15): empty #7
,I/jxcore-log( 6583): attempting to connect to test coordinator
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): check test folder
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): found test : ./testFindPeers.js
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): found test : ./testReConnect.js
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): found test : ./testSendData.js
I/jxcore-log( 6583): 
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_6391/cgroup.procs: No such file or directory
,I/jxcore-log( 6583): Test app app.js loaded
I/jxcore-log( 6583): 
,I/Choreographer( 6583): Skipped 243 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6583): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ResourcesManager( 6861): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6861): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6861): VM with version 2.1.0 has multidex support
I/MultiDex( 6861): install
,I/MultiDex( 6861): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6861): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6861): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6861): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f880683: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6861): Installed default security provider GmsCore_OpenSSL
,I/CheckinService( 6861): Checkin interval check for package: unspecified last checkin: 1450445294216 min interval config: 0 actual interval: 82414
,D/NativeLibraryUtils( 6861): Install completed successfully. count=14 extracted=0
,I/CheckinService( 6861): Disabling old GoogleServicesFramework version
,I/CheckinService( 6861): Checking schedule, now: 1450445376675 next: 1450445323600
I/CheckinService( 6861): active receiver: enabled
,I/CheckinService( 6861): Preparing to send checkin request
,I/EventLogService( 6861): Accumulating logs since 1450445290387
,I/iu.SyncManager( 6861): SYNC; picasa accounts
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,D/NetworkLogImpl( 6861): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6861): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6861): num queued entries: 0
,I/iu.UploadsManager( 6861): num updated entries: 0
,I/iu.SyncManager( 6861): NEXT; no task
,I/art     ( 6861): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6861): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6910 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:33000 mC
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524295
,I/CheckinRequestBuilder( 6861): Checkin reason type: 8 attempt count: 1
,D/WifiService(  883): New client listening to asynchronous messages
,E/ActivityThread( 6861): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  883): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6935 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6953 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6935): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6935): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel   ( 6696): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  883): Killing 6670:com.motorola.context/u0a8 (adj 15): empty #7
,I/MultiDex( 6935): VM with version 2.1.0 has multidex support
I/MultiDex( 6935): install
I/MultiDex( 6935): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  883): failed to open /acct/uid_10008/pid_6670/cgroup.procs: No such file or directory
,V/JNIHelp ( 6935): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     (  883): Explicit concurrent mark sweep GC freed 21384(1058KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.909ms total 130.025ms
,W/ActivityThread( 6935): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6935): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3697ca15: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6935): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6935): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6935): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6953): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6953): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,D/NativeLibraryUtils( 6935): Install completed successfully. count=14 extracted=0
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6953): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6953): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6953): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6953):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6953):   adb logcat -s GAv4
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
D/WVCdm   (  314): Instantiating CDM.
I/WVCdm   (  314): CdmEngine::OpenSession
,I/WVCdm   (  314): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  314): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/GAv4    ( 6953): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  314): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  314): Service_Initialize: starts!
D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
E/QSEECOMAPI: (  314): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  314): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
E/QSEECOMAPI: (  314): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  314): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
,W/GAv4    ( 6953): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6953): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/QSEECOMAPI: (  314): Loaded image: APP id = 3
,D/DrmWidevineDash(  314): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f48000
E/DrmWidevineDash(  314): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f48000
,D/DrmWidevineDash(  314): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  314): hlos api version =  9
D/DrmWidevineDash(  314): tz api version =  8
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  314): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  314): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  314): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  314): OEMCrypto_OpenSession: starts! SID=0xb5523960
,D/DrmWidevineDash(  314): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  314): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_GetRandom: starts! randomData=0xb8953d60, dataLength=8
D/DrmWidevineDash(  314): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  314): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a0b7e8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  314): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  314): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  314): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  314): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  314): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  314): OEMCrypto_GetDeviceID: starts! deviceID=0xb8a15958, idLength=0xb1339730
,D/DrmWidevineDash(  314): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  314): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  314): hlos api version =  9
D/DrmWidevineDash(  314): tz api version =  8
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  314): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  314): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  314): PrepareKeyRequest: nonce=1720521557
D/DrmWidevineDash(  314): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb89c9ec0
D/DrmWidevineDash(  314): message_length=1591, signature=0xb8942318, signature_length=2972948244
,D/DrmWidevineDash(  314): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  314): CdmEngine::CloseSession
D/DrmWidevineDash(  314): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  314): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  314): L3 Terminate.
D/DrmWidevineDash(  314): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  314): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  314): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  314): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  314): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_Terminate: ends! returns 0
,I/WebViewFactory( 6953): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  883): MasterInitialState.processMessage what=3
D/Central_PollingManager( 1482): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2522): now: 197796 ,futureTime: 9223372036854775807
D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2522): now: 197796 ,futureTime: 9223372036854775807
D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2522): now: 197796 ,futureTime: 9223372036854775807
D/Central_PollingManager( 1482): now: 197797 ,futureTime: 86473089
D/Central_PollingManager( 1482): Polling alarm set to expire at: 86473089 Current Time: 197797
D/OtaApp  ( 2522): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2522): [debug] > PollingManagerService, now: 197800 ,futureTime: 78264029
,D/OtaApp  ( 2522): [debug] > Polling alarm set to expire at: 78264029 Current Time: 197800
,I/NetworkMonitor( 6461): type=WIFI subType= reason=null isConnected=true
I/LibraryLoader( 6953): Time to load native libraries: 3 ms (timestamps 7811-7814)
I/LibraryLoader( 6953): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6953): Binding Chromium to main looper Looper (main, tid 1) {32c06285}
,I/LibraryLoader( 6953): Expected native library version number "",actual native library version number ""
,I/chromium( 6953): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/MMApiProvisionService( 2522): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2522): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2522): createDeviceIdOrLogin update_device
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2522): Not proxy app, so login/provision not allowed
,I/BrowserStartupController( 6953): Initializing chromium process, singleProcess=true
W/art     ( 6953): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6953): ApplicationContext is null in ApplicationStatus
,D/MMApiProvisionService( 2522): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2522): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2522): createDeviceIdOrLogin update_device
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2522): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2522): set mOutstandingReq to true.
,I/ Nonce  ( 2522):  Nonce getNonce 
I/ Nonce  ( 2522):  Nonce Request 
I/ Nonce  ( 2522):  Nonce execute Request 
,D/MMApiWebService( 2522): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,W/chromium( 6953): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6953): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6953): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6953): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6953): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6953): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6953): Local Branch: 
I/Adreno-EGL( 6953): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6953): Local Patches: NONE
I/Adreno-EGL( 6953): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/art     ( 2522): Explicit concurrent mark sweep GC freed 12444(682KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 11MB/18MB, paused 1.016ms total 85.132ms
,W/AudioManagerAndroid( 6953): Requires BLUETOOTH permission
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 3783(164KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 790us total 44.269ms
,I/NSApplication( 6953): Starting up...
,D/MMApiProvisionService( 2522): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2522): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2522): createDeviceIdOrLogin update_device
D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2522): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2522): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2522): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2522): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/MMApiWebService( 2522): generating token using payload instead of using session token
,D/OtaApp  ( 2522): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2522): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
,D/ Nonce  ( 2522):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/OtaApp  ( 2522): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2522): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2522): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,I/MMApiWSBase( 2522): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7022 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6461:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,D/OtaApp  ( 2522): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_6461/cgroup.procs: No such file or directory
,I/dex2oat ( 7045): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7045): dex2oat took 178.249ms (threads: 4)
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7055 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 6816:com.android.mms/u0a23 (adj 15): empty #7
,I/Adreno-EGL( 6935): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6935): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6935): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6935): Local Branch: 
I/Adreno-EGL( 6935): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6935): Local Patches: NONE
I/Adreno-EGL( 6935): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_6816/cgroup.procs: No such file or directory
,W/ResourcesManager( 7055): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Adreno-EGL( 6935): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6935): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6935): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6935): Local Branch: 
I/Adreno-EGL( 6935): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6935): Local Patches: NONE
I/Adreno-EGL( 6935): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,V/AlarmManager(  883): send {25733e97, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7076 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/Adreno-EGL( 6935): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6935): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6935): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6935): Local Branch: 
I/Adreno-EGL( 6935): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6935): Local Patches: NONE
I/Adreno-EGL( 6935): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6935): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6935): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6935): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6935): Local Branch: 
I/Adreno-EGL( 6935): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6935): Local Patches: NONE
I/Adreno-EGL( 6935): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7097 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ Nonce  ( 2522):  Nonce Reponse 
D/        ( 2522): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"3068638b-57fa-421f-a3b1-7e86b6756e8c"}
D/MMApiWSBase( 2522): doRequest(): /v1/gdi/nonce.json resp length: 61
I/ActivityManager(  883): Killing 6910:com.google.android.apps.photos/u0a88 (adj 15): empty #7
I/art     (  328): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 281us total 23.116ms
I/ Nonce  ( 2522):  Nonce Handle Reponse 
D/MMApiProvisionService( 2522): mOutstandingReq set to false
I/art     (  328): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.132ms
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.882ms
,I/ContactLocale( 7076): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/WVCdm   (  314): CdmEngine::OpenSession
I/WVCdm   (  314): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  314): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  314): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  314): Service_Initialize: starts!
D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
E/QSEECOMAPI: (  314): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  314): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
E/QSEECOMAPI: (  314): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  314): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
,D/MMApiProvisionService( 2522):  pTime 1450280700010 sExp 172742 cTime 1450445379395 tTime 1450453442010
D/MMApiProvisionService( 2522):  No login Required 
,D/QSEECOMAPI: (  314): Loaded image: APP id = 3
,I/ActivityManager(  883): Killing 6840:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,D/DrmWidevineDash(  314): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f48000
,E/DrmWidevineDash(  314): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f48000
,D/DrmWidevineDash(  314): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  314): hlos api version =  9
D/DrmWidevineDash(  314): tz api version =  8
,D/DrmWidevineDash(  314): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  314): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  314): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  314): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  314): OEMCrypto_OpenSession: starts! SID=0xbea894e0
D/DrmWidevineDash(  314): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  314): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_GetRandom: starts! randomData=0xb88ff1a8, dataLength=8
D/DrmWidevineDash(  314): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  314): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a0b7e8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  314): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  314): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  314): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  314): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  314): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  314): OEMCrypto_GetDeviceID: starts! deviceID=0xb8a15998, idLength=0xb5423730
,D/DrmWidevineDash(  314): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  314): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  314): hlos api version =  9,
D/DrmWidevineDash(  314): tz api version =  8
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  314): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  314): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  314): PrepareKeyRequest: nonce=503058945
,D/DrmWidevineDash(  314): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb89c9ec0
D/DrmWidevineDash(  314): message_length=1626, signature=0xb8902ed0, signature_length=3041015572
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_6910/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_6840/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  314): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  314): CdmEngine::CloseSession
D/DrmWidevineDash(  314): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  314): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  314): L3 Terminate.
D/DrmWidevineDash(  314): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  314): Service_Uninitialize: starts!
D/QSEECOMAPI: (  314): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  314): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  314): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  314): OEMCrypto_Terminate: ends! returns 0
,I/MusicStore( 7097): Database version: 120
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7097): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/DataUsage( 2522): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7097): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7097): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7097): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7097): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7097): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7097): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7097): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@398fa4c4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7097): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7097): GMSCore installation verified
,I/ConfigStore( 7097): Config Database version: 1
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/MediaRouter( 7097): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7097): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7097): type=WIFI subType= reason=null isConnected=true
,I/art     (  883): Explicit concurrent mark sweep GC freed 11640(579KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.416ms total 111.198ms
,I/NetworkMonitor( 7097): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7142 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7097): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7097): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  883): Killing 6696:com.google.android.talk/u0a70 (adj 15): empty #7
,V/Mms     ( 7142): mnc/mcc: 
,V/Mms     ( 7142): tag: int value: recipientLimit - 20
,V/Mms     ( 7142): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7142): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7142): tag: int value: maxSubjectLength - 80
V/Mms     ( 7142): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7142): tag: bool value: enableGroupMms - false
V/Mms     ( 7142):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_6696/cgroup.procs: No such file or directory
,W/ResourcesManager( 7142): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7173 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6953:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_6953/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7173): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7173): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7173): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 7022:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_7022/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 6861): Classify the device as Phone.
,I/CheckinService( 6861): Checkin interval check for package: unspecified last checkin: 1450445294216 min interval config: 0 actual interval: 86452
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7196 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinTask( 6861): Sending checkin request (9517 bytes)
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7215 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7055:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7055/cgroup.procs: No such file or directory
,W/ResourcesManager( 7215): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 6583): BLE supported!!
I/jxcore-log( 6583): 
,I/Babel_SMS( 7215): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7215): MmsConfig.loadMmsSettings
I/Babel_SMS( 7215): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7215): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7215): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7215): MmsConfig.loadFromResources
,E/Babel_SMS( 7215): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7215): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7215): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7215): startup - clean
,I/Babel   ( 7215): deleted: false for 0
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7246 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7215): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7215): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7215): Unsupported mime video/mpeg2
,I/CheckinRequestBuilder( 6861): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6861): Failed to find provider info for com.google.android.wearable.settings
,I/VideoCapabilities( 7215): Unsupported profile 4 for video/mp4v-es
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7246): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7246): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/VideoCapabilities( 7215): Unrecognized profile 2130706433 for video/avc
I/GAv4    ( 7246): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7246):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7246):   adb logcat -s GAv4
W/VideoCapabilities( 7215): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7215): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7215): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,I/vclib   ( 7215): onServiceConnected
W/Babel   ( 7215): Attempted to change video mute state without an active call.
,W/ContextImpl( 7246): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7246): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7246): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7246): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7215): connection state changed from UNKNOWN to CONNECTED
,W/GAv4    ( 7246): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  883): Killing 7076:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_7076/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 6861): Classify the device as Phone.
,I/CheckinTask( 6861): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6861): Checking schedule, now: 1450445381929 next: 1451046518921
I/CheckinService( 6861): active receiver: disabled
,I/CheckinService( 6861): Checking schedule, now: 1450445381947 next: 1451046518921
I/CheckinService( 6861): active receiver: disabled
,D/CheckinService( 6861): Recording last checkin time for package unspecified as 1450445381949
,I/ActivityManager(  883): Killing 7097:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_7097/cgroup.procs: No such file or directory
,I/WebViewFactory( 7246): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7246): Time to load native libraries: 1 ms (timestamps 1858-1859)
I/LibraryLoader( 7246): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7246): Binding Chromium to main looper Looper (main, tid 1) {32c06285}
I/LibraryLoader( 7246): Expected native library version number "",actual native library version number ""
,I/chromium( 7246): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7246): Initializing chromium process, singleProcess=true
,W/art     ( 7246): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7246): ApplicationContext is null in ApplicationStatus
,W/chromium( 7246): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7246): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7246): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7246): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7246): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7246): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7246): Local Branch: 
I/Adreno-EGL( 7246): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7246): Local Patches: NONE
I/Adreno-EGL( 7246): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7246): Starting up...
,W/AudioManagerAndroid( 7246): Requires BLUETOOTH permission
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7318 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7173:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ActivityManager(  883): Killing 7142:com.android.mms/u0a23 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7173/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_7142/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7337 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 7196:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7196/cgroup.procs: No such file or directory
,W/ResourcesManager( 7337): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7360 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7246:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/art     ( 7337): Suspending all threads took: 9.745ms
,I/ContactLocale( 7360): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 7215:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_7246/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2522): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7215/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2522): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2522): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2522): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 2522): onServiceConnected()
,D/GetNotificationsWS( 2522): onServiceConnected(): Registered for remote service callbacks...
,V/AlarmManager(  883): done {15125e1f, *walarm*:com.google.android.intent.action.SEND_IDLE} [7112ms]
,D/GetNotificationsWS( 2522): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2522): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1713): callingUid 10016, callindPid: 1713
,E/MDM     ( 1713): [173] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6861): Restart initialization of location
,D/AuthorizationBluetoothService( 1713): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  883): Explicit concurrent mark sweep GC freed 12381(601KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.479ms total 121.449ms
,W/GCoreFlp( 1713): No location to return for getLastLocation()
W/FusedLocationProvider( 1713): location=null
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7400 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/IcingInternalCorpora( 6861): getNumBytesRead when not calculated.
,E/MDM     ( 1713): [180] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1713): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 6861): Restart initialization of location
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7429 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1713): No location to return for getLastLocation()
W/FusedLocationProvider( 1713): location=null
,I/MusicStore( 7429): Database version: 120
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7429): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7429): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7429): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7429): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7429): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7429): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7429): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7429): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@398fa4c4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7429): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7429): GMSCore installation verified
,I/ConfigStore( 7429): Config Database version: 1
,I/MediaRouter( 7429): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7429): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7429): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7429): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7464 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  328): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 23.010ms
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 20.543ms
,I/GHttpClientFactory( 7429): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.326ms
,I/GoogleURLConnFactory( 7429): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7464): mnc/mcc: 
,V/Mms     ( 7464): tag: int value: recipientLimit - 20
V/Mms     ( 7464): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7464): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7464): tag: int value: maxSubjectLength - 80
V/Mms     ( 7464): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7464): tag: bool value: enableGroupMms - false
,V/Mms     ( 7464):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7464): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7499 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7318:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_7318/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7499): Register our PhoneStateListener
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=309, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311401, SEQNUM=4473, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-302, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/MobileConnectivityChangeReceiver( 7499): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7499): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  883): Killing 7337:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7337/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,I/CheckinService( 6861): Checkin interval check for package: unspecified last checkin: 1450445381949 min interval config: 0 actual interval: 2708
,I/CheckinService( 6861): Checkin interval check for package: unspecified last checkin: 1450445381949 min interval config: 0 actual interval: 2710
,I/CheckinService( 6861): Checking schedule, now: 1450445384664 next: 1450445411921
I/CheckinService( 6861): active receiver: disabled
,I/CheckinService( 6861): Checking schedule, now: 1450445384676 next: 1450445411921
I/CheckinService( 6861): active receiver: disabled
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7520 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7520): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7520): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7520): MmsConfig.loadMmsSettings
I/Babel_SMS( 7520): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7520): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7520): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7520): MmsConfig.loadFromResources
,E/Babel_SMS( 7520): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7520): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7520): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7520): startup - clean
,I/Babel   ( 7520): deleted: false for 0
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7550 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7520): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7520): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7520): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7520): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7520): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7520): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7520): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/VideoCapabilities( 7520): Unrecognized profile 2130706433 for video/avc
W/ContextImpl( 7550): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/vclib   ( 7520): onServiceConnected
I/GAv4    ( 7550): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7550):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7550):   adb logcat -s GAv4
W/Babel   ( 7520): Attempted to change video mute state without an active call.
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7550): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7550): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7550): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7550): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7550): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7550): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7520): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  883): Killing 7360:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_7360/cgroup.procs: No such file or directory
,I/WebViewFactory( 7550): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7550): Time to load native libraries: 2 ms (timestamps 5410-5412)
,I/LibraryLoader( 7550): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7550): Binding Chromium to main looper Looper (main, tid 1) {32c06285}
,I/LibraryLoader( 7550): Expected native library version number "",actual native library version number ""
I/chromium( 7550): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7550): Initializing chromium process, singleProcess=true
,W/art     ( 7550): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7550): ApplicationContext is null in ApplicationStatus
,W/chromium( 7550): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7550): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7550): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7550): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7550): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7550): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7550): Local Branch: 
I/Adreno-EGL( 7550): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7550): Local Patches: NONE
I/Adreno-EGL( 7550): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7550): Requires BLUETOOTH permission
,I/NSApplication( 7550): Starting up...
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7617 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7464:com.android.mms/u0a23 (adj 15): empty #7
,I/ActivityManager(  883): Killing 7429:com.google.android.music:main/u0a80 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_7464/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_7429/cgroup.procs: No such file or directory
,I/art     (  883): Explicit concurrent mark sweep GC freed 11396(569KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.923ms total 127.425ms
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7640 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7499:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7499/cgroup.procs: No such file or directory
,W/ResourcesManager( 7640): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7660 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7520:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ActivityManager(  883): Killing 7400:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ContactLocale( 7660): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7520/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 2522): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7400/cgroup.procs: No such file or directory
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,D/GetNotificationsWS( 2522): bindWebServices(): registering our AIDL callback...
I/SundryService( 2522): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2522): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2522): onServiceConnected()
D/GetNotificationsWS( 2522): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2522): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2522): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2522): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2522): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2522): [debug] > In cancelAnyPendingIntentSetPreviously
I/ActivityManager(  883): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:34000 mC
,W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7697 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/OtaApp  ( 2522): [debug] > DownloadActivity, FormattedText
,I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/OtaApp  ( 2522): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
V/AlarmManager(  883): done {25733e97, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [8090ms]
,D/OtaApp  ( 2522): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2522): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@291992ee
,D/OtaApp  ( 2522): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2522): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2522): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2522): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6583): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1424): onFinishInput()
I/GCoreNlp( 1713): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1574): Deferring update until onResume
,I/LaunchCheckinHandler(  883): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,204
,I/art     ( 1713): Explicit concurrent mark sweep GC freed 84444(4MB) AllocSpace objects, 17(272KB) LOS objects, 39% free, 14MB/24MB, paused 1.206ms total 123.296ms
,E/DataBuffer( 1713): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@49de1ca)
,E/DataBuffer( 1713): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3e40df3b)
E/DataBuffer( 1713): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@28453658)
,E/DataBuffer( 1713): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1c1723b1)
E/DataBuffer( 1713): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@ea05096)
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7723 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7550:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_7550/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7723): Register our PhoneStateListener
,V/SetupWizard( 7723): Connected to Gservices successfully,
,I/ActivityManager(  883): Killing 6935:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_6935/cgroup.procs: No such file or directory
,D/GCM     ( 1713): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1713): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7758 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     ( 6185): Explicit concurrent mark sweep GC freed 3029(118KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 348us total 22.815ms
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7780 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7797 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  883): Killing 7617:com.android.chrome/u0a52 (adj 15): empty #7
,I/art     (  328): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 22.261ms
,I/art     (  328): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.466ms
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.801ms
,I/ActivityManager(  883): Killing 7640:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_7617/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7640/cgroup.procs: No such file or directory
,W/ResourcesManager( 7797): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7797): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7797): MmsConfig.loadMmsSettings
I/Babel_SMS( 7797): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7797): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7797): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7797): MmsConfig.loadFromResources
,E/Babel_SMS( 7797): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7797): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7797): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7797): startup - clean
,I/Babel   ( 7797): deleted: false for 0
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7830 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7697:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/VideoCapabilities( 7797): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7797): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7797): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7797): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7797): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7797): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7797): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7797): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7697/cgroup.procs: No such file or directory
,W/asset   ( 7830): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7830): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 7830): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7830): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6861): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/Launcher( 1574): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2f490a72 new=com.google.android.velvet.VelvetApplication@2f490a72
I/UpdateIcingCorporaServi( 7758): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 6861): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7862 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7797): onServiceConnected
,W/Babel   ( 7797): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7797): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7797): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7862): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7758): UpdateCorporaTask done [took 183 ms] updated apps [took 182 ms] ,
,V/JNIHelp ( 7797): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Icing   ( 6861): Storage manager: low false usage 1.78MB avail 3.12GB capacity 4.85GB
,W/System  ( 7797): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7797): Installed default security provider GmsCore_OpenSSL
,I/art     (  883): Explicit concurrent mark sweep GC freed 16757(855KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.645ms total 115.471ms
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7903 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7723:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/Icing   ( 6861): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7723/cgroup.procs: No such file or directory
,D/Finsky  ( 7903): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 6861): Internal init done: storage state 0
,I/Icing   ( 6861): Post-init done
,I/Icing   ( 6861): updateResources: need to parse f{com.google.android.gms}
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,D/Finsky  ( 7903): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7903): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7903): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7903): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7903): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7903): Skipping gmscore version check
,D/Finsky  ( 7903): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7903): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/TaskPersister(  883): removeObsoleteFile: deleting file=2_task.xml
,I/ActivityManager(  883): Killing 7780:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_7780/cgroup.procs: No such file or directory
,I/Icing   ( 6861): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6861): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6861): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  883): Killing 7830:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_7830/cgroup.procs: No such file or directory
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ActivityManager(  883): Killing 7758:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_7758/cgroup.procs: No such file or directory
,I/CheckinService( 6861): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:34000 mC
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,V/AlarmManager(  883): send {1e8d2863, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  883): send {1302b26a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  883): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=7967 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  883): done {1e8d2863, *alarm*:android.intent.action.TIME_TICK} [135ms]
,I/GAv4    ( 7967): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7967):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7967):   adb logcat -s GAv4
,W/GAv4    ( 7967): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7967): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7967): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  883): Killing 7660:android.process.acore/u0a7 (adj 15): empty #7
,V/AlarmManager(  883): done {1302b26a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [317ms]
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_7660/cgroup.procs: No such file or directory
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=304, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311471, SEQNUM=4500, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2725, POWER_SUPPLY_CHARGE_COUNTER=-291, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:33000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:33000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ClearcutLoggerApiImpl( 1713): disconnect managed GoogleApiClient
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311922, SEQNUM=4502, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=5956, POWER_SUPPLY_CHARGE_COUNTER=-265, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,V/AlarmManager(  883): send {b632f44, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  883): send {127e735b, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  883): done {b632f44, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [17ms]
V/AlarmManager(  883): done {127e735b, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [18ms]
,I/CheckinService( 6861): Checkin interval check for package: unspecified last checkin: 1450445381949 min interval config: 0 actual interval: 44749
,I/CheckinService( 6861): Checking schedule, now: 1450445426713 next: 1450445411921
I/CheckinService( 6861): active receiver: enabled
,I/CheckinService( 6861): Preparing to send checkin request
I/EventLogService( 6861): Accumulating logs since 1450445376943
,I/CheckinRequestBuilder( 6861): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6861): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  883): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8024 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8024): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8024): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8024): VM with version 2.1.0 has multidex support
I/MultiDex( 8024): install
I/MultiDex( 8024): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8024): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8024): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8024): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3697ca15: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8024): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1713): callingUid 10016, callindPid: 1713
,E/MDM     ( 1713): [151] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1713): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6861): Restart initialization of location
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1713): No location to return for getLastLocation()
W/FusedLocationProvider( 1713): location=null
,I/art     ( 8024): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 8024): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8024): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  314): Instantiating CDM.
,I/WVCdm   (  314): CdmEngine::OpenSession
I/WVCdm   (  314): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  314): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  314): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  314): Service_Initialize: starts!
,D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
E/QSEECOMAPI: (  314): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  314): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
E/QSEECOMAPI: (  314): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  314): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  314): App is not loaded in QSEE
,D/QSEECOMAPI: (  314): Loaded image: APP id = 3
,D/DrmWidevineDash(  314): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f48000
E/DrmWidevineDash(  314): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f48000
,D/DrmWidevineDash(  314): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  314): hlos api version =  9
D/DrmWidevineDash(  314): tz api version =  8
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  314): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  314): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  314): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  314): OEMCrypto_OpenSession: starts! SID=0xbea894e0
D/DrmWidevineDash(  314): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  314): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_GetRandom: starts! randomData=0xb88dec70, dataLength=8
D/DrmWidevineDash(  314): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8a0b7e8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  314): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  314): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  314): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  314): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  314): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  314): OEMCrypto_GetDeviceID: starts! deviceID=0xb8a15978, idLength=0xb5523730
,D/DrmWidevineDash(  314): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  314): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  314): hlos api version =  9
D/DrmWidevineDash(  314): tz api version =  8
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  314): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  314): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  314): PrepareKeyRequest: nonce=4199970588
D/DrmWidevineDash(  314): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb89c9ec0
D/DrmWidevineDash(  314): message_length=1591, signature=0xb891c5e0, signature_length=3042064148
,D/DrmWidevineDash(  314): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  314): CdmEngine::CloseSession
D/DrmWidevineDash(  314): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  314): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  314): L3 Terminate.
D/DrmWidevineDash(  314): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  314): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  314): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  314): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  314): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8062): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8062): dex2oat took 62.762ms (threads: 4)
,I/Adreno-EGL( 8024): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8024): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8024): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8024): Local Branch: 
I/Adreno-EGL( 8024): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8024): Local Patches: NONE
I/Adreno-EGL( 8024): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/Adreno-EGL( 8024): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8024): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8024): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8024): Local Branch: 
I/Adreno-EGL( 8024): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8024): Local Patches: NONE
I/Adreno-EGL( 8024): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8024): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8024): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8024): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8024): Local Branch: 
I/Adreno-EGL( 8024): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8024): Local Patches: NONE
I/Adreno-EGL( 8024): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8024): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8024): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8024): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8024): Local Branch: 
I/Adreno-EGL( 8024): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8024): Local Patches: NONE
I/Adreno-EGL( 8024): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  314): CdmEngine::OpenSession
I/WVCdm   (  314): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  314): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  314): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  314): Service_Initialize: starts!
D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
E/QSEECOMAPI: (  314): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  314): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
E/QSEECOMAPI: (  314): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  314): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
,D/QSEECOMAPI: (  314): Loaded image: APP id = 3
,D/DrmWidevineDash(  314): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  314): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f48000
E/DrmWidevineDash(  314): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f48000
,D/DrmWidevineDash(  314): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  314): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  314): hlos api version =  9
D/DrmWidevineDash(  314): tz api version =  8
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  314): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  314): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  314): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  314): OEMCrypto_OpenSession: starts! SID=0xbea894e0
D/DrmWidevineDash(  314): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  314): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_GetRandom: starts! randomData=0xb89ca198, dataLength=8
D/DrmWidevineDash(  314): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  314): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8944990, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  314): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  314): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  314): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  314): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  314): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  314): OEMCrypto_GetDeviceID: starts! deviceID=0xb8a15998, idLength=0xb5523730
,D/DrmWidevineDash(  314): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  314): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  314): hlos api version =  9
D/DrmWidevineDash(  314): tz api version =  8
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  314): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  314): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  314): PrepareKeyRequest: nonce=432510406
D/DrmWidevineDash(  314): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8a0b7e8
D/DrmWidevineDash(  314): message_length=1626, signature=0xb88ff160, signature_length=3042064148
,D/DrmWidevineDash(  314): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  314): CdmEngine::CloseSession
D/DrmWidevineDash(  314): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  314): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  314): L3 Terminate.
D/DrmWidevineDash(  314): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  314): Service_Uninitialize: starts!
D/QSEECOMAPI: (  314): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  314): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  314): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 6861): Classify the device as Phone.
,I/CheckinTask( 6861): Sending checkin request (9517 bytes)
,I/CheckinRequestBuilder( 6861): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6861): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6861): Classify the device as Phone.
,I/CheckinTask( 6861): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6861): Checking schedule, now: 1450445429698 next: 1451046566692
I/CheckinService( 6861): active receiver: disabled
,D/CheckinService( 6861): Recording last checkin time for package unspecified as 1450445429709
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8085 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8085): Register our PhoneStateListener
,V/SetupWizard( 8085): Connected to Gservices successfully
,D/GCM     ( 1713): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  883): Killing 7903:com.android.vending/u0a32 (adj 13): empty #7
,I/ActivityManager(  883): Killing 7862:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_7903/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7862/cgroup.procs: No such file or directory
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8107 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:32000 mC
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2f199f65
,I/GCoreNlp( 1713): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1574): Deferring update until onResume
,I/art     (  883): Explicit concurrent mark sweep GC freed 23445(1225KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.593ms total 130.062ms
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8144 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8163 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7967:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10055/pid_7967/cgroup.procs: No such file or directory
,W/ResourcesManager( 7797): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7797): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8163): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8186 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 8085:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_8085/cgroup.procs: No such file or directory
,W/asset   ( 8186): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 8186): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 8186): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8186): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6861): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6861): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 8107): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1574): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2f490a72 new=com.google.android.velvet.VelvetApplication@2f490a72
,I/Icing   ( 6861): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8213 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  328): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.035ms
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.066ms
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 30.078ms
,W/ResourcesManager( 8213): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8107): UpdateCorporaTask done [took 178 ms] updated apps [took 178 ms] 
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8238 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 8024:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_8024/cgroup.procs: No such file or directory
,D/Finsky  ( 8238): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8238): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8238): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8238): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8238): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
D/Finsky  ( 8238): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  883): Killing 8144:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,D/Ads     ( 8238): Skipping gmscore version check
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_8144/cgroup.procs: No such file or directory
,D/Finsky  ( 8238): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8238): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 6861): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6861): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,I/ActivityManager(  883): Killing 8186:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_8186/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 7797:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7797/cgroup.procs: No such file or directory
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:32000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1424): run()
I/Keyboard.Facilitator( 1424): flushDynamicLanguageModels()
,I/ConfigService( 1713): onCreate
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ConfigService( 1713): onDestroy
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311212, SEQNUM=4520, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2119, POWER_SUPPLY_CHARGE_COUNTER=-199, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ClearcutLoggerApiImpl( 1713): disconnect managed GoogleApiClient
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,V/AlarmManager(  883): send {1e8d2863, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {5c9c96d, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  883): done {5c9c96d, *walarm*:android.content.syncmanager.SYNC_ALARM} [10ms]
,V/AlarmManager(  883): done {1e8d2863, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311413, SEQNUM=4524, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-158, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311689, SEQNUM=4525, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-158, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310235, SEQNUM=4527, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=2, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311091, SEQNUM=4528, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=6, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311629, SEQNUM=4530, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-14, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311031, SEQNUM=4531, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-26, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector connect called
I/jxcore-log( 6583): 
I/jxcore-log( 6583): Coordinator is now connected to the server!
I/jxcore-log( 6583): 
,I/chromium( 6583): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=271, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311595, SEQNUM=4534, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-79, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6583): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): DBG, CoordinatorConnector command called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":16,"addressList":[{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0}]}
I/jxcore-log( 6583): 
I/jxcore-log( 6583): Start now : testSendData.js
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 16
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): check server
I/jxcore-log( 6583): 
I/jxcore-log( 6583): serverPort is 54023
I/jxcore-log( 6583): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT3006
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6583): bind: Binding a new listener
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6583): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6583): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3006","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): start: OK
I/io.jxcore.node.ConnectionHelper( 6583): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT3006
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6583): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3006","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6583): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): start: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3006","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6583): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3006","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  883): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@835fbd26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@835fbd26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service
,D/WifiP2pService(  883): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): start: Starting P2P device discovery...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  883): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6583): start: OK
I/jxcore-log( 6583): StartBroadcasting started ok
I/jxcore-log( 6583): 
I/jxcore-log( 6583): do fake peer & start
I/jxcore-log( 6583): 
I/jxcore-log( 6583): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:39:32.529Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:39:32.530Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:39:32.530Z SendDataConnector.js: do connect now
I/jxcore-log( 6583): 
I/io.jxcore.node.ConnectionHelper( 6583): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 6583): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 6583): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/jxcore-log( 6583): 2015-12-18T13:39:32.538Z SendDataTCPServer.js: TCP/IP server is bound to port: 54023
I/jxcore-log( 6583): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 790)
,W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,I/chromium( 6583): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6583): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6583): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6583): onDiscoveryManagerStateChanged: RUNNING
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
,D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-ADDED 0 c0
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,E/bt-btif ( 2413): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2413): invalid rfc slot id: 5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 790)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Maximum number of allowed retries (0) reached, giving up... (thread ID: 790)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Exiting thread (thread ID: 790)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/jxcore-log( 6583): 2015-12-18T13:39:33.635Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:39:33.636Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:39:33.636Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6583): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): shutdown (thread ID: 790)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1403): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-31
,D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/WifiP2pService(  883): InactiveState{ when=-4ms what=147477 obj=Device: A3-1
D/WifiP2pService(  883):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-4ms what=147477 obj=Device: A3-1
D/WifiP2pService(  883):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pService(  883): InactiveState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139301 arg2=4 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service request
,D/WifiP2pManager( 6583): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service request added successfully
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  883): InactiveState{ when=0 what=139310 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=139310 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState discover services
,I/wpa_supplicant( 1403): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
,D/MDMCTBK (  311): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service discovery started successfully
,I/wpa_supplicant( 1403): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  883):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  883):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1844","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1844","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1844","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
,I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844] is available
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4486","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4486","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4486","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], Bluetooth address: 34:FC:EF:11:AE:67, device name: , device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486] is available
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
,D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278] is available
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6583): 2015-12-18T13:39:38.643Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:39:38.643Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-REMOVED 0 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9724","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9724","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9724","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724] is available
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 fa
D/MDMCTBK (  311): Event received = P2P-SERV-DISC-REQ 2462 fa
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1403): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
I/wpa_supplicant( 1403): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 4488
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147477 obj=Device: G4-1
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 4488
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  883):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  883):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=-1ms what=139283 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP fa:cf:
D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP fa:cf:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:fa:cf:c5:d9:e5:62 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7815","ra":"F8:CF:C5:D9:E5:61"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:fa:cf:c5:d9:e5:62 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7815","ra":"F8:CF:C5:D9:E5:61"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7815","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT7815]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT7815]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT7815]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT7815], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT7815]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT7815], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: fa:cf:c5:d9:e5:62
D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT7815] is available
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
,I/jxcore-log( 6583): 2015-12-18T13:39:43.651Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:39:43.652Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:39:43.652Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:39:43.652Z SendDataConnector.js: do connect now
I/jxcore-log( 6583): 
I/io.jxcore.node.ConnectionHelper( 6583): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 6583): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 6583): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 792)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6583): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-REMOVED 1 
,W/bt-sdp  ( 2413): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2413): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2413): invalid rfc slot id: 6
,W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnectionTimeout: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/jxcore-log( 6583): 2015-12-18T13:39:58.658Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] timed out
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:39:58.659Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] timed out
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:39:58.659Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6583): 
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-ADDED 2 c0
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
D/MDMCTBK (  311): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 ea
D/MDMCTBK (  311): Event received = P2P-SERV-DISC-REQ 2462 ea
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 ea
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-REQ 2462 ea
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT8124","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT8124","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT8124","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] is available
,I/jxcore-log( 6583): 2015-12-18T13:40:03.660Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:03.660Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,D/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
,E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 6583): 2015-12-18T13:40:08.664Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:08.664Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:08.664Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:08.664Z SendDataConnector.js: do connect now
I/jxcore-log( 6583): 
,I/io.jxcore.node.ConnectionHelper( 6583): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 6583): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 6583): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 794)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6583): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-REMOVED 2 
,W/bt-sdp  ( 2413): SDP - Rcvd conn cnf with error: 0x8  CID 0x42
,E/bt-btif ( 2413): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2413): invalid rfc slot id: 7
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 792)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Maximum number of allowed retries (0) reached, giving up... (thread ID: 792)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): shutdown (thread ID: 792)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Exiting thread (thread ID: 792)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/jxcore-log( 6583): 2015-12-18T13:40:11.780Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:11.781Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:11.781Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6583): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): setState: RESTARTING
,D/WifiP2pService(  883): InactiveState{ when=0 what=139268 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1403): P2P-FIND-STOPPED 
,D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
,D/MDMCTBK (  311): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1403): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/wpa_supplicant( 1403): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1403): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1403): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  311): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/MDMCTBK (  311): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  311): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  311): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/WifiP2pService(  883): InactiveState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): discovery change broadcast false
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-2ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-10ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): InactiveState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-9ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 0 device(s) discovered
,I/jxcore-log( 6583): 2015-12-18T13:40:16.781Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:16.782Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
,W/bt-sdp  ( 2413): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2413): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2413): invalid rfc slot id: 8
,W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): Start timer timeout, starting now...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139265 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139265 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  883): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/wpa_supplicant( 1403): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-ADDED 3 c0
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  883):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-4ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  883):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): restart: Restarting...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139307 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139307 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState clear service request
,D/WifiP2pService(  883): InactiveState{ when=0 what=139301 arg2=17 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139301 arg2=17 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service request
,D/WifiP2pManager( 6583): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service request added successfully
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
D/MDMCTBK (  311): Event received = P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-REQ 2462 7e
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,E/bt-btif ( 2413): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2413): invalid rfc slot id: 9
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 794)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Maximum number of allowed retries (0) reached, giving up... (thread ID: 794)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Exiting thread (thread ID: 794)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): shutdown (thread ID: 794)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/WifiP2pService(  883): InactiveState{ when=0 what=139310 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=139310 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState discover services
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service discovery started successfully
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-REMOVED 3 
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
,E/bt-btif ( 2413): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2413): Entering PendingCommandState State
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e11cc6:true
,I/ActivityManager(  883): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetoothdeterminer.BTReceiver: pid=8343 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
D/BluetoothAdapterProperties( 2413): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
D/BluetoothAdapterService( 2413): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11cf6728
,D/BluetoothMetrics( 2413): btclass5a020c
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 c0
D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-ADDED 4 c0
,D/Checkin ( 2413): publish the event [tag = MOT_BT event name = PAIRING]
,W/ResourcesManager( 8343): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/BluetoothBondStateMachine( 2413): StableState(): Entering Off State
,D/BluetoothManagerService(  883): Message: 20
,D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ecbffb4:true
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/ActivityManager(  883): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=8371 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 8107:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/bt-btif ( 2413): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2413): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2413): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection initialized (thread ID: 796)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Entering thread (ID: 796)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): onBytesRead: Read 81 bytes successfully (thread ID: 796)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Got valid identity from [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8525]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): onBytesWritten: 81 bytes successfully written (thread ID: 796)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): removeThreadFromList: Removing thread with ID 796
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Handshake thread disposed (thread ID: 796)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onIncomingConnectionConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8525]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Exiting thread (ID: 796)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8525]
I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Incoming connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8525]
,D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8525] is available
,I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Incoming socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8525], created successfully
,D/io.jxcore.node.ConnectionHelper( 6583): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 6583): Entering thread (ID: 797)
,I/io.jxcore.node.IncomingSocketThread( 6583): Local host address: localhost/127.0.0.1, port: 54023
,D/io.jxcore.node.IncomingSocketThread( 6583): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6583): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 6583): Exiting thread (ID: 797)
I/jxcore-log( 6583): 2015-12-18T13:40:19.903Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6583): 
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 798, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 799, name: Receiver)
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_8107/cgroup.procs: No such file or directory
,W/ResourcesManager( 8371): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  883): Message: 20
,D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27ec2223:true
,I/ActivityManager(  883): Killing 8163:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_8163/cgroup.procs: No such file or directory
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT674","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT674","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT674","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674] is available
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74c1c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6583): 2015-12-18T13:40:21.038Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:21.326Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:21.378Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:21.483Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:21.495Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6583): 
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
,E/bt-btif ( 2413): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2413): Entering PendingCommandState State
,I/jxcore-log( 6583): 2015-12-18T13:40:21.538Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:21.634Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:21.666Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6583): 
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2413): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2413): StableState(): Entering Off State
,D/BluetoothMetrics( 2413): btclass5a020c
,D/Checkin ( 2413): publish the event [tag = MOT_BT event name = PAIRING]
,I/jxcore-log( 6583): 2015-12-18T13:40:21.735Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6583): 
,W/bt-btif ( 2413): new conn_srvc id:26, app_id:255
W/bt-btif ( 2413): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2413): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection initialized (thread ID: 800)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Entering thread (ID: 800)
,D/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 6583): 2015-12-18T13:40:21.783Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:21.784Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:21.784Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:21.784Z SendDataConnector.js: do connect now
I/jxcore-log( 6583): 
I/io.jxcore.node.ConnectionHelper( 6583): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 6583): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 6583): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 801)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6583): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74c1c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,I/jxcore-log( 6583): 2015-12-18T13:40:22.117Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:22.127Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6583): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): onBytesRead: Read 83 bytes successfully (thread ID: 800)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
,E/bt-btif ( 2413): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2413): invalid rfc slot id: 12
,W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): onBytesWritten: 81 bytes successfully written (thread ID: 800)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): removeThreadFromList: Removing thread with ID 800
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Handshake thread disposed (thread ID: 800)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Exiting thread (ID: 800)
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
,I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Incoming connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
,D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Incoming socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124], created successfully
D/io.jxcore.node.ConnectionHelper( 6583): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 6583): Entering thread (ID: 802)
,I/io.jxcore.node.IncomingSocketThread( 6583): Local host address: localhost/127.0.0.1, port: 54023
D/io.jxcore.node.IncomingSocketThread( 6583): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6583): 2015-12-18T13:40:22.178Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6583): 
,I/io.jxcore.node.IncomingSocketThread( 6583): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6583): Exiting thread (ID: 802)
,I/jxcore-log( 6583): 2015-12-18T13:40:22.183Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6583): 
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 803, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 804, name: Receiver)
,I/jxcore-log( 6583): 2015-12-18T13:40:22.202Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 6583): 
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,E/bt-btif ( 2413): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2413): invalid rfc slot id: 13
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 801)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Maximum number of allowed retries (0) reached, giving up... (thread ID: 801)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Exiting thread (thread ID: 801)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/jxcore-log( 6583): 2015-12-18T13:40:22.219Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:22.221Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:22.221Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6583): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): shutdown (thread ID: 801)
,I/jxcore-log( 6583): 2015-12-18T13:40:22.235Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:22.285Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 6583): 
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/jxcore-log( 6583): 2015-12-18T13:40:22.365Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:22.374Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:22.387Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:22.550Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:22.556Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:22.575Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.008Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.043Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.058Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.067Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.096Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.105Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.117Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.130Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.150Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.154Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.174Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.180Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.208Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.216Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.241Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.247Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.270Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6583): 
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.332Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.366Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.380Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.401Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.408Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.431Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.466Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.482Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 6583): 
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/jxcore-log( 6583): 2015-12-18T13:40:23.521Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.521Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.564Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.568Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.592Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.596Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.610Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.626Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.631Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.666Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.772Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.808Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.813Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.846Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.860Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.871Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:23.988Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.026Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.074Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.106Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.146Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.151Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.186Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.236Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.251Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6583): 
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.313Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.383Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.405Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.421Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.476Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.532Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.556Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.571Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.586Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.632Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 6583): 
,I/wpa_supplicant( 1403): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-44
,D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  883):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  883):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -44 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
,I/jxcore-log( 6583): 2015-12-18T13:40:24.724Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.798Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.802Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.869Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.919Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.956Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:24.969Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 6583): 
,W/bt-btif ( 2413): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 799, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6583): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8525] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 797
D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 799
D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 798
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6583): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 798, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6583): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8525] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 799, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 798, name: Sender)
,I/jxcore-log( 6583): 2015-12-18T13:40:24.992Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:25.045Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:25.076Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:25.116Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:25.156Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:25.201Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:25.236Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 6583): 
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74a5c rs_disc_pending=0
W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6583): 2015-12-18T13:40:25.276Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:25.316Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6583): 
,W/bt-btif ( 2413): invalid rfc slot id: 10
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 804, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6583): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 802
D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 804
D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 803
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6583): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 803, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6583): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 803, name: Sender)
,W/bt-rfcomm( 2413): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 2413): RFCOMM_DisconnectInd LCID:0x48
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 804, name: Receiver)
,I/jxcore-log( 6583): 2015-12-18T13:40:25.398Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6583): 
,I/wpa_supplicant( 1403): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-51
,D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 4488
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -51 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 4488
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -51 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2509","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2509","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2509","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2509] is available
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 7e
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-REQ 2462 7e
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [7c:f9:0e:37:96:ab]: 0, 0, 0
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=8420 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/BluetoothManagerService(  883): Message: 20
,D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@57a3595:true
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8457 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 1403): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  883):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  883):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/BluetoothClassifier( 8420): Bluetooth Device Name: A5-1
,I/ActivityManager(  883): Killing 8238:com.android.vending/u0a32 (adj 15): empty #7
,I/ActivityManager(  883): Killing 8213:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_8238/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_8213/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,E/bt-btif ( 2413): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 12 NewState: 11
,I/BluetoothBondStateMachine( 2413): Entering PendingCommandState State
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): 2015-12-18T13:40:27.222Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:27.222Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
D/BluetoothAdapterProperties( 2413): Removing bonded device:7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,D/BluetoothMetrics( 2413): btclass5a020c
,D/Checkin ( 2413): publish the event [tag = MOT_BT event name = PAIRING]
I/BluetoothBondStateMachine( 2413): StableState(): Entering Off State
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74a5c rs_disc_pending=1
W/bt-btif ( 2413): bta_dm_check_av:0
W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2413): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,W/bt-rfcomm( 2413): RFCOMM_DisconnectInd LCID:0x46
,W/bt-btif ( 2413): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2413): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2413): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection initialized (thread ID: 806)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Entering thread (ID: 806)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): onBytesRead: Read 83 bytes successfully (thread ID: 806)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6384]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): onBytesWritten: 81 bytes successfully written (thread ID: 806)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): removeThreadFromList: Removing thread with ID 806
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Handshake thread disposed (thread ID: 806)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6384]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6384]
I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Incoming connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6384]
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6384] is available
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Exiting thread (ID: 806)
I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Incoming socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6384], created successfully
D/io.jxcore.node.ConnectionHelper( 6583): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 6583): Entering thread (ID: 807)
,I/io.jxcore.node.IncomingSocketThread( 6583): Local host address: localhost/127.0.0.1, port: 54023
,D/io.jxcore.node.IncomingSocketThread( 6583): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6583): startStreamCopyingThreads: OK
I/jxcore-log( 6583): 2015-12-18T13:40:27.517Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6583): 
D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 808, name: Sender)
D/io.jxcore.node.IncomingSocketThread( 6583): Exiting thread (ID: 807)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 809, name: Receiver)
,I/jxcore-log( 6583): 2015-12-18T13:40:28.348Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.405Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.411Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.420Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.499Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.509Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.515Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.546Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.639Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.650Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.659Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.696Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.740Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.747Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.753Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.760Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.796Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.864Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.870Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.906Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.943Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.951Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:28.987Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:29.092Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:29.103Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:29.112Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:29.146Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 6583): 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-REMOVED 4 
,I/jxcore-log( 6583): 2015-12-18T13:40:29.207Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:29.246Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:29.388Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:29.428Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 6583): 
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2413): onReceive
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 6583): 2015-12-18T13:40:30.399Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:30.436Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:30.869Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:30.873Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6583): 
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74a5c rs_disc_pending=1
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2413): onReceive
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: HTC One M8s
,I/art     (  883): Explicit concurrent mark sweep GC freed 22619(1419KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.496ms total 124.395ms
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7435c rs_disc_pending=0
W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2413): invalid rfc slot id: 11
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 809, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6583): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6384] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 807
D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 809
D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 808
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6583): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 809, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 808, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6583): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6384] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 808, name: Sender)
,I/jxcore-log( 6583): 2015-12-18T13:40:31.246Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6583): 
,W/ProcessCpuTracker(  883): Skipping unknown process pid 8520
W/ProcessCpuTracker(  883): Skipping unknown process pid 8521
W/ProcessCpuTracker(  883): Skipping unknown process pid 8523
W/ProcessCpuTracker(  883): Skipping unknown process pid 8524
,W/bt-rfcomm( 2413): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 2413): RFCOMM_DisconnectInd LCID:0x4c
,D/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
,E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 6583): 2015-12-18T13:40:32.224Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:32.224Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:32.224Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:32.224Z SendDataConnector.js: do connect now
I/jxcore-log( 6583): 
,I/io.jxcore.node.ConnectionHelper( 6583): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
,D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 6583): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 6583): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 810)
W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7435c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2413): onReceive
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: A5-1
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,E/bt-btif ( 2413): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2413): invalid rfc slot id: 15
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 810)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Maximum number of allowed retries (0) reached, giving up... (thread ID: 810)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Exiting thread (thread ID: 810)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/jxcore-log( 6583): 2015-12-18T13:40:39.106Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:39.107Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 6583): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): shutdown (thread ID: 810)
,I/jxcore-log( 6583): 2015-12-18T13:40:39.120Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6583): 
D/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 6583): 2015-12-18T13:40:39.122Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 6583): 
I/jxcore-log( 6583): ---- round done--------
I/jxcore-log( 6583): 
I/jxcore-log( 6583): ---- gotta redo : F4:F1:E1:5C:3B:E2, try count now: 1
I/jxcore-log( 6583): 
I/jxcore-log( 6583): do fake peer & start
I/jxcore-log( 6583): 
I/jxcore-log( 6583): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:39.123Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:39.123Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:40:39.124Z SendDataConnector.js: do connect now
I/jxcore-log( 6583): 
,I/io.jxcore.node.ConnectionHelper( 6583): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): connect: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 6583): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
I/chromium( 6583): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F4:F1:E1:5C:3B:E2 done with result: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 812)
W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74f9c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,E/bt-btif ( 2413): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2413): Entering PendingCommandState State
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7489c rs_disc_pending=0
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2413): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2413): StableState(): Entering Off State
,D/BluetoothMetrics( 2413): btclass5a020c
,D/Checkin ( 2413): publish the event [tag = MOT_BT event name = PAIRING]
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74f9c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 c0
,D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-ADDED 5 c0
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101] is available
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 92
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-REQ 2462 92
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2413): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2413): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2413): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onSocketConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 812)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): onBytesWritten: 81 bytes successfully written (thread ID: 813)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Outgoing connection initialized (*handshake* thread ID: 813)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Exiting thread (thread ID: 812)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Entering thread (ID: 813)
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): onBytesRead: Read 82 bytes successfully (thread ID: 813)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onHandshakeSucceeded: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Exiting thread (ID: 813)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Outgoing connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
,W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6583): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6583): Entering thread (ID: 814)
,D/io.jxcore.node.OutgoingSocketThread( 6583): Server socket local port: 45531
,I/io.jxcore.node.OutgoingSocketThread( 6583): Now accepting connections...
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/io.jxcore.node.ConnectionHelper( 6583): onListeningForIncomingConnections: Outgoing connection is using port 45531 (peer ID: 08:EC:A9:50:76:27)
,I/jxcore-log( 6583): 2015-12-18T13:40:45.624Z SendDataConnector.js: CLIENT connected to 45531, error: null
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:40:45.624Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6583): 
,I/io.jxcore.node.OutgoingSocketThread( 6583): Incoming data from address: /127.0.0.1, port: 45531
,D/io.jxcore.node.OutgoingSocketThread( 6583): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6583): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6583): Exiting thread (ID: 814)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 816, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 815, name: Sender)
,I/jxcore-log( 6583): 2015-12-18T13:40:45.652Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6583): 
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1403): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,I/wpa_supplicant( 1403): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  883):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  883):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: G3-1
D/WifiP2pService(  883):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 4488
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147477 obj=Device: G3-1
D/WifiP2pService(  883):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 4488
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): restart: Restarting...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139307 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=139307 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/WifiP2pService(  883): InactiveState{ when=0 what=139301 arg2=25 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139301 arg2=25 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service request
,D/WifiP2pManager( 6583): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service request added successfully
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 ee
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-REQ 2462 ee
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 a2
D/MDMCTBK (  311): Event received = P2P-SERV-DISC-REQ 2462 a2
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  883): InactiveState{ when=0 what=139310 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139310 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState discover services
,I/wpa_supplicant( 1403): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
,D/MDMCTBK (  311): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service discovery started successfully
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9453","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9453","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9453","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453] is available
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278] already in the list, will not add again
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-REMOVED 5 
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74f9c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7515c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6865","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6865","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6865","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865] is available
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101] already in the list, will not add again
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2509","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2509","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2509","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
,I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2509] already in the list, will not add again
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [08:ec:a9:50:75:41]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74f9c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74f9c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,D/        ( 2413): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6583): 2015-12-18T13:40:58.159Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6583): 
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,E/bt-btif ( 2413): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2413): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2413): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2413): StableState(): Entering Off State
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,D/BluetoothMetrics( 2413): btclass5a020c
,D/Checkin ( 2413): publish the event [tag = MOT_BT event name = PAIRING]
,I/jxcore-log( 6583): 2015-12-18T13:40:58.932Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6583): 
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74ddc rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2413): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2413): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2413): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection initialized (thread ID: 817)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Entering thread (ID: 817)
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74ddc rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): onBytesRead: Read 77 bytes successfully (thread ID: 817)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): onBytesWritten: 81 bytes successfully written (thread ID: 817)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): removeThreadFromList: Removing thread with ID 817
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Handshake thread disposed (thread ID: 817)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Exiting thread (ID: 817)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865], created successfully
D/io.jxcore.node.ConnectionHelper( 6583): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 6583): Entering thread (ID: 818)
,I/io.jxcore.node.IncomingSocketThread( 6583): Local host address: localhost/127.0.0.1, port: 54023
,D/io.jxcore.node.IncomingSocketThread( 6583): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6583): 2015-12-18T13:40:59.732Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6583): 
,I/io.jxcore.node.IncomingSocketThread( 6583): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6583): Exiting thread (ID: 818)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 819, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 820, name: Receiver)
,D/        ( 2413): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 6583): 2015-12-18T13:41:00.286Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6583): 
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,E/bt-btif ( 2413): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2413): Entering PendingCommandState State
,I/jxcore-log( 6583): 2015-12-18T13:41:00.738Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:00.750Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6583): 
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2413): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2413): StableState(): Entering Off State
,D/BluetoothMetrics( 2413): btclass5a020c
,D/Checkin ( 2413): publish the event [tag = MOT_BT event name = PAIRING]
,I/jxcore-log( 6583): 2015-12-18T13:41:00.814Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:00.859Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:00.869Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:00.880Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:00.892Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:00.926Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:00.990Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:00.997Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.004Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.036Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 6583): 
,W/bt-btif ( 2413): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2413): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2413): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection initialized (thread ID: 821)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Entering thread (ID: 821)
,I/jxcore-log( 6583): 2015-12-18T13:41:01.133Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.145Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.159Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.196Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.201Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 6583): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): onBytesRead: Read 83 bytes successfully (thread ID: 821)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): onBytesWritten: 81 bytes successfully written (thread ID: 821)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): removeThreadFromList: Removing thread with ID 821
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Handshake thread disposed (thread ID: 821)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Exiting thread (ID: 821)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Incoming connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
,D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Incoming socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], created successfully
D/io.jxcore.node.ConnectionHelper( 6583): onConnected: The total number of connections is now 3
,D/io.jxcore.node.IncomingSocketThread( 6583): Entering thread (ID: 822)
,I/io.jxcore.node.IncomingSocketThread( 6583): Local host address: localhost/127.0.0.1, port: 54023
,D/io.jxcore.node.IncomingSocketThread( 6583): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6583): 2015-12-18T13:41:01.234Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6583): 
,I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6583): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6583): Exiting thread (ID: 822)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 823, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 824, name: Receiver)
,I/jxcore-log( 6583): 2015-12-18T13:41:01.267Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.289Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.303Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.336Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.383Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.435Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 6583): 
,D/        ( 2413): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 6583): 2015-12-18T13:41:01.440Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.466Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.473Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.506Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.513Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.600Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.636Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.688Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.705Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.787Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.826Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.904Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.926Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:01.944Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.029Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.056Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.077Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.120Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.155Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.183Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.198Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.203Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.216Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.233Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.240Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.261Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6583): 
,W/bt-btif ( 2413): invalid rfc slot id: 14
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 820, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6583): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 818
D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 820
D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 819
,D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6583): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 820, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 819, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6583): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 819, name: Sender)
,I/jxcore-log( 6583): 2015-12-18T13:41:02.323Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.339Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.346Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.349Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.366Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.380Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.396Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.426Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.477Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.497Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.513Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.520Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6583): 
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7515c rs_disc_pending=0
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6583): 2015-12-18T13:41:02.650Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.687Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.732Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.881Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.894Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.988Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.999Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:02.999Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.008Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.008Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6583): 
D/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
,I/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.IncomingSocketThread( 6583): close
D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 816
D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 815
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 815, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6583): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6583): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 816, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6583): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 815, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 816, name: Receiver)
,W/bt-btif ( 2413): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/jxcore-log( 6583): 2015-12-18T13:41:03.032Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6583): 
I/jxcore-log( 6583): ---- round done--------
I/jxcore-log( 6583): 
I/jxcore-log( 6583): do fake peer & start
I/jxcore-log( 6583): 
I/jxcore-log( 6583): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:41:03.033Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:41:03.033Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:41:03.033Z SendDataConnector.js: do connect now
I/jxcore-log( 6583): 
I/io.jxcore.node.ConnectionHelper( 6583): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): connect: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnecting: Note4-1 E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 6583): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
I/chromium( 6583): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 825)
W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 6583): 2015-12-18T13:41:03.050Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.250Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.286Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.326Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.366Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.415Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.426Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.483Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 6583): 
,W/bt-rfcomm( 2413): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 2413): RFCOMM_DisconnectInd LCID:0x42
,I/jxcore-log( 6583): 2015-12-18T13:41:03.516Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.615Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 6583): 
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 6583): 2015-12-18T13:41:03.646Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.653Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.695Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.782Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.816Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.882Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.956Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:03.996Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:04.042Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 6583): 
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: Note4-1
,I/jxcore-log( 6583): 2015-12-18T13:41:04.097Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:04.102Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 6583): 
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7515c rs_disc_pending=0
W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6583): 2015-12-18T13:41:04.139Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:04.177Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6583): 
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7451c rs_disc_pending=0
,W/bt-btif ( 2413): bta_dm_check_av:0
W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2413): invalid rfc slot id: 17
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 824, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6583): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 822
D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 824
D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 823
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6583): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 823, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6583): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 823, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 824, name: Receiver)
W/bt-rfcomm( 2413): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 2413): RFCOMM_DisconnectInd LCID:0x44
I/jxcore-log( 6583): 2015-12-18T13:41:04.254Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6583): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): checkListForExpiredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT7815] expired
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT7815], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Removed [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT7815]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerLost: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT7815]
,D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT7815] removed
D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT7815] not available
I/io.jxcore.node.ConnectionHelper( 6583): onPeerLost: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] removed
D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] not available
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2413): onReceive
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2413): onReceive
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: A3-1
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1403): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 c0
D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-ADDED 6 c0
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2
,D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  883):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A3)
D/WifiP2pService(  883):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): restart: Restarting...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139307 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139307 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState clear service request
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=139301 arg2=29 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=139301 arg2=29 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service request
,D/WifiP2pManager( 6583): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service request added successfully
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,W/bt-rfcomm( 2413): PORT_StartCnf failed result:5
,W/bt-btm  ( 2413): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7451c rs_disc_pending=2
E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2413): bta_dm_check_av:0
W/bt-btif ( 2413): invalid rfc slot id: 19
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2413): onReceive
,D/WifiP2pService(  883): InactiveState{ when=0 what=139310 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=139310 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState discover services
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 825)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Maximum number of allowed retries (0) reached, giving up... (thread ID: 825)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Exiting thread (thread ID: 825)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
,I/jxcore-log( 6583): 2015-12-18T13:41:13.878Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278] failed
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:41:13.878Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278] failed
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:41:13.878Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6583): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): shutdown (thread ID: 825)
,I/BluetoothClassifier( 8420): Bluetooth Device Name: Note4-1
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service discovery started successfully
,I/wpa_supplicant( 1403): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  311): Event received = P2P: Reject scan trigger 
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT674","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT674","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT674","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674] already in the list, will not add again
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
,I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101] already in the list, will not add again
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6865","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6865","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6865","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
,I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865] already in the list, will not add again
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
,W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278] already in the list, will not add again
,I/jxcore-log( 6583): 2015-12-18T13:41:18.885Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:18.886Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6583): 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-REMOVED 6 
,I/ActivityManager(  883): Waited long enough for: ServiceRecord{2ad4ae05 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,D/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
,E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:14:E2:C0), either no such connection or failed to close the connection
I/jxcore-log( 6583): 2015-12-18T13:41:23.889Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:23.889Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:41:23.889Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:41:23.890Z SendDataConnector.js: do connect now
I/jxcore-log( 6583): 
I/io.jxcore.node.ConnectionHelper( 6583): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): connect: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnecting: Note4-1 E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 6583): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 827)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6583): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btm  ( 2413): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7515c rs_disc_pending=2
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2413): onReceive
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: G3-1
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2509","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2509","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2509","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2509] already in the list, will not add again
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7451c rs_disc_pending=0
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7531c rs_disc_pending=0
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 2413): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2413): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2413): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2413): StableState(): Entering Off State
,D/BluetoothMetrics( 2413): btclass5a020c
,D/Checkin ( 2413): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2413): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2413): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2413): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection initialized (thread ID: 828)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Entering thread (ID: 828)
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7531c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7451c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2413): invalid rfc slot id: 18
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Disconnected: bt socket closed, read return: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): removeThreadFromList: Removing thread with ID 828
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Handshake failed (thread ID: 828)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Exiting thread (ID: 828)
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7531c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4486","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4486","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4486","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
,I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
,W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486] already in the list, will not add again
,W/bt-rfcomm( 2413): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 2413): RFCOMM_DisconnectInd LCID:0x48
,I/wpa_supplicant( 1403): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/wpa_supplicant( 1403): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/wpa_supplicant( 1403): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  311): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:b6:86
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/MDMCTBK (  311): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=52:55:27
D/MDMCTBK (  311): Event received = P2P-DEVICE-LOST p2p_dev_addr=52:55:27
,D/WifiP2pService(  883): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=-4ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): restart: Restarting...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139307 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139307 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pService(  883): InactiveState{ when=0 what=139301 arg2=35 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139301 arg2=35 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service request
,D/WifiP2pManager( 6583): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service request added successfully
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,D/WifiP2pService(  883): InactiveState{ when=0 what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState discover services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service discovery started successfully
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1403): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  311): Event received = P2P: Reject scan trigger 
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,E/bt-btif ( 2413): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 12 NewState: 11
,I/BluetoothBondStateMachine( 2413): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2413): Removing bonded device:E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2413): StableState(): Entering Off State
,D/BluetoothMetrics( 2413): btclass5a020c
,D/Checkin ( 2413): publish the event [tag = MOT_BT event name = PAIRING]
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 c0
,D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-ADDED 7 c0
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
,D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
,I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101] already in the list, will not add again
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2413): onReceive
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: G4-1
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT674","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT674","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT674","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
,I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674] already in the list, will not add again
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7451c rs_disc_pending=0
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2413): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2413): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2413): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onSocketConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 827)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): onBytesWritten: 81 bytes successfully written (thread ID: 829)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Outgoing connection initialized (*handshake* thread ID: 829)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Exiting thread (thread ID: 827)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Entering thread (ID: 829)
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6865","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6865","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6865","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): onBytesRead: Read 82 bytes successfully (thread ID: 829)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onHandshakeSucceeded: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Exiting thread (ID: 829)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
,I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Outgoing connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
,D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Outgoing socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6583): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6583): Entering thread (ID: 830)
,D/io.jxcore.node.OutgoingSocketThread( 6583): Server socket local port: 41307
,I/io.jxcore.node.OutgoingSocketThread( 6583): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6583): onListeningForIncomingConnections: Outgoing connection is using port 41307 (peer ID: E0:DB:10:14:E2:C0)
,I/jxcore-log( 6583): 2015-12-18T13:41:34.053Z SendDataConnector.js: CLIENT connected to 41307, error: null
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:41:34.053Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6583): 
,I/io.jxcore.node.OutgoingSocketThread( 6583): Incoming data from address: /127.0.0.1, port: 41307
,D/io.jxcore.node.OutgoingSocketThread( 6583): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6583): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6583): Exiting thread (ID: 830)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 832, name: Receiver)
,I/jxcore-log( 6583): 2015-12-18T13:41:34.071Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6583): 
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 831, name: Sender)
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9453","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9453","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP ee:1f:
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9453","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453] already in the list, will not add again
,I/jxcore-log( 6583): 2015-12-18T13:41:35.414Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6583): 
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6583): 2015-12-18T13:41:35.621Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6583): 
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: G4-1
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
,D/TCMD    (  465): Listening for incoming client connection request
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7451c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7531c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6583): 2015-12-18T13:41:36.916Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:37.171Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6583): 
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/wpa_supplicant( 1403): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-32
,D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  883):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  883):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -32 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 6583): 2015-12-18T13:41:37.573Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6583): 
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=-1ms what=139283 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278] already in the list, will not add again
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 2413): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2413): Entering PendingCommandState State
,I/jxcore-log( 6583): 2015-12-18T13:41:38.326Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6583): 
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6583): 2015-12-18T13:41:38.635Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6583): 
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2413): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2413): StableState(): Entering Off State
,D/BluetoothMetrics( 2413): btclass5a020c
,D/Checkin ( 2413): publish the event [tag = MOT_BT event name = PAIRING]
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/jxcore-log( 6583): 2015-12-18T13:41:38.872Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:39.202Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6583): 
,W/bt-btif ( 2413): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2413): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2413): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection initialized (thread ID: 833)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Entering thread (ID: 833)
,I/jxcore-log( 6583): 2015-12-18T13:41:39.516Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:39.516Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:39.526Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:39.526Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6583): 
D/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 6583): close
D/io.jxcore.node.OutgoingSocketThread( 6583): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 832
D/io.jxcore.node.OutgoingSocketThread( 6583): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 831
D/io.jxcore.node.OutgoingSocketThread( 6583): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 831, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6583): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 6583): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6583): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 832, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 6583): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
,E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 831, name: Sender)
E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 832, name: Receiver)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): onBytesRead: Read 77 bytes successfully (thread ID: 833)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): onBytesWritten: 81 bytes successfully written (thread ID: 833)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): removeThreadFromList: Removing thread with ID 833
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Handshake thread disposed (thread ID: 833)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Exiting thread (ID: 833)
,I/jxcore-log( 6583): 2015-12-18T13:41:39.554Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6583): 
I/jxcore-log( 6583): ---- round done--------
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): do fake peer & start
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): Connect to fake peer: 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:41:39.558Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:41:39.559Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:41:39.559Z SendDataConnector.js: do connect now
I/jxcore-log( 6583): 
,I/io.jxcore.node.ConnectionHelper( 6583): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
,W/io.jxcore.node.ConnectionHelper( 6583): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): connect: [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 6583): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
I/chromium( 6583): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724], created successfully
D/io.jxcore.node.ConnectionHelper( 6583): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 834)
W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/io.jxcore.node.IncomingSocketThread( 6583): Entering thread (ID: 835)
,I/io.jxcore.node.IncomingSocketThread( 6583): Local host address: localhost/127.0.0.1, port: 54023
D/io.jxcore.node.IncomingSocketThread( 6583): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6583): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6583): Exiting thread (ID: 835)
,I/jxcore-log( 6583): 2015-12-18T13:41:39.587Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6583): 
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 836, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 837, name: Receiver)
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
,D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1844","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1844","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1844","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844] already in the list, will not add again
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6583): 2015-12-18T13:41:40.979Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6583): 
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-REQ 2462 0a
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 7 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-REMOVED 7 
,I/jxcore-log( 6583): 2015-12-18T13:41:41.354Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6583): 
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 6583): 2015-12-18T13:41:41.730Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:41.979Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6583): 
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6583): 2015-12-18T13:41:42.230Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6583): 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 8 c0
,D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-ADDED 8 c0
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,W/bt-btif ( 2413): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT8124","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT8124","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT8124","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
,D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] is available
,I/jxcore-log( 6583): 2015-12-18T13:41:42.604Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:42.854Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:43.104Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6583): 
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1403): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-31
,I/wpa_supplicant( 1403): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-34
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  883):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-2ms what=147477 obj=Device: A3-1
D/WifiP2pService(  883):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): InactiveState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  883):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147477 obj=Device: S5-1
D/WifiP2pService(  883):  deviceAddress: ee:1f:72:63:11:86
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -34 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): restart: Restarting...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139307 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
,D/WifiP2pService(  883): InactiveState{ when=0 what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139301 arg2=41 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service request
,D/WifiP2pManager( 6583): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service request added successfully
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  883): InactiveState{ when=0 what=139310 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139310 arg2=42 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState discover services
,I/wpa_supplicant( 1403): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  311): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service discovery started successfully
,I/wpa_supplicant( 1403): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-46
,D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  883):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  883):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -46 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1844","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1844","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1844","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844] already in the list, will not add again
,W/bt-sdp  ( 2413): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
,E/bt-btif ( 2413): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2413): invalid rfc slot id: 23
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 834)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Maximum number of allowed retries (0) reached, giving up... (thread ID: 834)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Exiting thread (thread ID: 834)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
,I/jxcore-log( 6583): 2015-12-18T13:41:44.904Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22] failed
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:44.904Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22] failed
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:41:44.904Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6583): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): shutdown (thread ID: 834)
,I/jxcore-log( 6583): 2015-12-18T13:41:44.944Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 6583): 
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7451c rs_disc_pending=0
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6583): 2015-12-18T13:41:45.321Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6583): 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 02:9a:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 02:9a:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6865","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:02:9a:02:7b:60:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6865","ra":"58:3F:54:73:64:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6865","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865] already in the list, will not add again
,I/jxcore-log( 6583): 2015-12-18T13:41:45.422Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:45.429Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6583): 
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 6583): 2015-12-18T13:41:45.491Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6583): 
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=280, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310901, SEQNUM=4574, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-2, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/jxcore-log( 6583): 2015-12-18T13:41:45.594Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6583): 
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,I/jxcore-log( 6583): 2015-12-18T13:41:45.610Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 6583): 
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=280, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311212, SEQNUM=4576, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-2, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/jxcore-log( 6583): 2015-12-18T13:41:46.005Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:46.036Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 6583): 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT8124","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT8124","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT8124","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] already in the list, will not add again
,I/jxcore-log( 6583): 2015-12-18T13:41:46.113Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:46.368Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:46.416Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 6583): 
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,I/jxcore-log( 6583): 2015-12-18T13:41:46.736Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 6583): 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101] already in the list, will not add again
,I/jxcore-log( 6583): 2015-12-18T13:41:46.916Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:46.921Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:46.926Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:46.933Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:47.033Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:47.169Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:47.173Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:47.178Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 6583): 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6583): 2015-12-18T13:41:47.347Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 6583): 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9453","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:18:8b:78 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9453","ra":"B0:C5:59:3F:75:69"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9453","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453] already in the list, will not add again
,I/jxcore-log( 6583): 2015-12-18T13:41:47.603Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:47.607Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:47.612Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:47.770Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:47.777Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:47.816Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:47.975Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:47.987Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:47.994Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:48.026Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:48.224Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:48.229Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:48.236Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:48.243Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:48.276Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6583): 
,W/bt-btif ( 2413): invalid rfc slot id: 21
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 837, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6583): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 835
D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 837
D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 836
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6583): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 837, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 836, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6583): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 836, name: Sender)
,I/jxcore-log( 6583): 2015-12-18T13:41:48.430Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6583): 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9724","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9724","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9724","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
,I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724] already in the list, will not add again
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7451c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7531c rs_disc_pending=0
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2413): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 2413): RFCOMM_DisconnectInd LCID:0x4c
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2413): onReceive
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: Note4-1
,I/jxcore-log( 6583): 2015-12-18T13:41:49.904Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:49.905Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 8 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-REMOVED 8 
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2413): onReceive
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: G4-1
,D/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 6583): 2015-12-18T13:41:54.907Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:41:54.907Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:41:54.907Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:41:54.908Z SendDataConnector.js: do connect now
I/jxcore-log( 6583): 
I/io.jxcore.node.ConnectionHelper( 6583): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): connect: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 6583): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 839)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6583): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT674","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:76:28 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT674","ra":"08:EC:A9:50:76:27"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT674","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674] already in the list, will not add again
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 9 c0
,D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-ADDED 9 c0
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
,D/TCMD    (  465): Listening for incoming client connection request
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/wpa_supplicant( 1403): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
,D/MDMCTBK (  311): Event received = P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72
,D/WifiP2pService(  883): InactiveState{ when=0 what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT6865], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT6865]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT674]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 5: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): restart: Restarting...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139307 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139307 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState clear service request
,D/WifiP2pService(  883): InactiveState{ when=0 what=139301 arg2=46 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139301 arg2=46 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service request
,D/WifiP2pManager( 6583): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service request added successfully
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/WifiP2pService(  883): InactiveState{ when=0 what=139310 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139310 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState discover services
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service discovery started successfully
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
,D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 9 
,D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-REMOVED 9 
,I/ActivityManager(  883): Waited long enough for: ServiceRecord{1d6c1267 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnectionTimeout: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
I/jxcore-log( 6583): 2015-12-18T13:42:09.916Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] timed out
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:09.917Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] timed out
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:09.917Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6583): 
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [7c:f9:0e:51:18:22]: 7, f, 6109
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3101","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101] already in the list, will not add again
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278] already in the list, will not add again
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT8124","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT8124","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT8124","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] already in the list, will not add again
,I/jxcore-log( 6583): 2015-12-18T13:42:14.918Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:14.918Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1844","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1844","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1844","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
,I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844] already in the list, will not add again
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,D/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 6583): 2015-12-18T13:42:19.919Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:19.920Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:19.921Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:19.921Z SendDataConnector.js: do connect now
I/jxcore-log( 6583): 
I/io.jxcore.node.ConnectionHelper( 6583): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): connect: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 6583): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 841)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6583): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,E/bt-btif ( 2413): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2413): invalid rfc slot id: 24
,W/bt-btif ( 2413): invalid rfc slot id: 25
,D/BluetoothMapService( 2413): onReceive
,W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/wpa_supplicant( 1403): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/wpa_supplicant( 1403): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
D/MDMCTBK (  311): Event received = P2P-DEVICE-LOST p2p_dev_addr=02:9a:02
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  311): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 02:9a:02:7b:60:ac
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): InactiveState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 0a:ec:a9:50:76:28
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=49 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): restart: Restarting...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139307 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139307 arg2=50 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT3101]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
,D/WifiP2pService(  883): InactiveState{ when=0 what=139301 arg2=51 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139301 arg2=51 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service request
D/WifiP2pManager( 6583): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service request added successfully
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 10 c
,D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-ADDED 10 c
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/WifiP2pService(  883): InactiveState{ when=0 what=139310 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139310 arg2=52 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState discover services
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service discovery started successfully
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 10
,D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-REMOVED 10
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT8124","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT8124","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT8124","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] already in the list, will not add again
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2278","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
,I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnectionTimeout: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
,I/jxcore-log( 6583): 2015-12-18T13:42:34.939Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] timed out
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:34.939Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] timed out
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:34.940Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6583): 
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74c1c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,E/bt-rfcomm( 2413): RFCOMM_CreateConnection - already opened state:1, RFC state:1, MCB state:5
E/bt-btif ( 2413): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2413): invalid rfc slot id: 27
,W/bt-btif ( 2413): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2413): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2413): bta_dm_pm_ssr:2, lat:1200
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): shutdown (thread ID: 839)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onSocketConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 841)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): shutdown (thread ID: 841)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 839)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Maximum number of allowed retries (0) reached, giving up... (thread ID: 839)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Exiting thread (thread ID: 839)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Entering thread (ID: 843)
,E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): write: Failed to write to output stream: socket closed
E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): java.io.IOException: socket closed
E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): 	at android.net.LocalSocketImpl$SocketOutputStream.write(LocalSocketImpl.java:132)
E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): 	at android.bluetooth.BluetoothSocket.write(BluetoothSocket.java:447)
E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): 	at android.bluetooth.BluetoothOutputStream.write(BluetoothOutputStream.java:85)
E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): 	at java.io.OutputStream.write(OutputStream.java:82)
E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): 	at org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.write(BluetoothSocketIoThread.java:162)
E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:182)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Exiting thread (thread ID: 841)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Disconnected: socket closed
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): onDisconnected: [null null null] (thread ID: 843)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onConnectionFailed: Socket disconnected
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnectionFailed: Socket disconnected [null null null]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): shutdown (thread ID: 841)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Exiting thread (ID: 843)
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2462 92
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-REQ 2462 92
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74c1c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4486","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4486","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4486","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486] already in the list, will not add again
,W/bt-btif ( 2413): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,E/bt-btif ( 2413): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2413): Entering PendingCommandState State
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2509] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2509] removed
D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2509] not available
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2413): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2413): StableState(): Entering Off State
,D/BluetoothMetrics( 2413): btclass5a020c
,D/Checkin ( 2413): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2413): new conn_srvc id:26, app_id:255
W/bt-btif ( 2413): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2413): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection initialized (thread ID: 844)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Entering thread (ID: 844)
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74c1c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): onBytesRead: Read 77 bytes successfully (thread ID: 844)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): onBytesWritten: 81 bytes successfully written (thread ID: 844)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): removeThreadFromList: Removing thread with ID 844
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Handshake thread disposed (thread ID: 844)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Exiting thread (ID: 844)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2509]
,D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
,D/io.jxcore.node.ConnectionHelper( 6583): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2509] is available
,I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2509], created successfully
D/io.jxcore.node.ConnectionHelper( 6583): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6583): Entering thread (ID: 845)
,I/io.jxcore.node.IncomingSocketThread( 6583): Local host address: localhost/127.0.0.1, port: 54023
,D/io.jxcore.node.IncomingSocketThread( 6583): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6583): 2015-12-18T13:42:37.093Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6583): 
,I/io.jxcore.node.IncomingSocketThread( 6583): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6583): Exiting thread (ID: 845)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 846, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 847, name: Receiver)
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9724","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9724","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState receive service response
I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9724","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724]
I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9724] already in the list, will not add again
,I/jxcore-log( 6583): 2015-12-18T13:42:38.080Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.087Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.092Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.096Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.100Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.104Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.112Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.146Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6583): 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  311): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1844","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1844","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1844","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
,I/io.jxcore.node.ConnectionHelper( 6583): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844] already in the list, will not add again
,I/jxcore-log( 6583): 2015-12-18T13:42:38.218Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.257Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.268Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.368Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.372Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.376Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.407Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.411Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.415Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.446Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.521Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.528Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.567Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.577Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.674Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.706Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.772Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.806Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.871Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.906Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.925Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:38.967Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:39.023Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:39.085Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 6583): 
,I/wpa_supplicant( 1403): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  311): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6583): 2015-12-18T13:42:39.121Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6583): 
,W/bt-btif ( 2413): invalid rfc slot id: 22
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 847, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6583): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2509] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 845
,D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 847
D/io.jxcore.node.IncomingSocketThread( 6583): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 846
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6583): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6583): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 847, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 846, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6583): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2509] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 846, name: Sender)
,I/jxcore-log( 6583): 2015-12-18T13:42:39.244Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6583): 
,I/wpa_supplicant( 1403): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
,D/MDMCTBK (  311): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 11 c
D/MDMCTBK (  311): Event received = CTRL-EVENT-BSS-ADDED 11 c
D/MDMCTBK (  311): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
D/MDMCTBK (  311): Event received = P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2
,D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  883):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy S5)
D/WifiP2pService(  883):  deviceAddress: ee:1f:72:18:8b:78
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=-1ms what=139283 arg2=53 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2278]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4486]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1844]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): restart: Restarting...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139307 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139307 arg2=54 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState clear service request
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74c1c rs_disc_pending=1
W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,D/WifiP2pService(  883): InactiveState{ when=0 what=139301 arg2=55 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139301 arg2=55 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service request
,D/WifiP2pManager( 6583): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Service request added successfully
,--------- beginning of crash
F/libc    ( 1403): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 1403 (wpa_supplicant)
,I/libc    ( 1403): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,E/QC-QMI  (  423): qmuxd: RX on fd=27 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  423): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  423): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
E/QC-QMI  (  423): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
E/QC-QMI  (  423): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f754dc rs_disc_pending=0
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6583): 2015-12-18T13:42:39.941Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:39.941Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2413): onReceive
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-rfcomm( 2413): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 2413): RFCOMM_DisconnectInd LCID:0x45
,D/WifiP2pService(  883): InactiveState{ when=0 what=139310 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=139310 arg2=56 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState discover services
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6583): Failed to start the service discovery, got error code: 3
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2413): onReceive
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: G3s-1
,D/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
,I/jxcore-log( 6583): 2015-12-18T13:42:44.943Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:44.943Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:44.944Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:44.944Z SendDataConnector.js: do connect now
I/jxcore-log( 6583): 
I/io.jxcore.node.ConnectionHelper( 6583): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): connect: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 6583): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 848)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6583): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 2413): new conn_srvc id:26, app_id:1
W/bt-btif ( 2413): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2413): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onSocketConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 848)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): onBytesWritten: 81 bytes successfully written (thread ID: 849)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Outgoing connection initialized (*handshake* thread ID: 849)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Exiting thread (thread ID: 848)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Entering thread (ID: 849)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): onBytesRead: Read 83 bytes successfully (thread ID: 849)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onHandshakeSucceeded: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
,I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Outgoing connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124]
,D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Outgoing socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6583): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Exiting thread (ID: 849)
,D/io.jxcore.node.OutgoingSocketThread( 6583): Entering thread (ID: 850)
,D/io.jxcore.node.OutgoingSocketThread( 6583): Server socket local port: 57795
I/io.jxcore.node.OutgoingSocketThread( 6583): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6583): onListeningForIncomingConnections: Outgoing connection is using port 57795 (peer ID: 7C:F9:0E:51:18:22)
,I/jxcore-log( 6583): 2015-12-18T13:42:47.652Z SendDataConnector.js: CLIENT connected to 57795, error: null
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:47.653Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6583): 
,I/io.jxcore.node.OutgoingSocketThread( 6583): Incoming data from address: /127.0.0.1, port: 57795
,D/io.jxcore.node.OutgoingSocketThread( 6583): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 6583): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6583): Exiting thread (ID: 850)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 852, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 851, name: Sender)
,I/jxcore-log( 6583): 2015-12-18T13:42:47.679Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6583): 
,D/        ( 2413): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6583): 2015-12-18T13:42:48.586Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:48.626Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6583): 
,D/        ( 2413): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 6583): 2015-12-18T13:42:48.719Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6583): 
,D/        ( 2413): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7876
,I/jxcore-log( 6583): 2015-12-18T13:42:48.766Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:49.104Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:49.222Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:49.283Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:49.364Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:49.443Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:49.532Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:49.533Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:49.541Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:49.541Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6583): 
D/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
,I/io.jxcore.node.OutgoingSocketThread( 6583): close
D/io.jxcore.node.OutgoingSocketThread( 6583): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 852
D/io.jxcore.node.OutgoingSocketThread( 6583): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 851
D/io.jxcore.node.OutgoingSocketThread( 6583): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 851, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 6583): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 6583): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 6583): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 852, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 6583): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT8124] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 851, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 852, name: Receiver)
,I/jxcore-log( 6583): 2015-12-18T13:42:49.567Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): ---- round done--------
I/jxcore-log( 6583): 
I/jxcore-log( 6583): do fake peer & start
I/jxcore-log( 6583): 
I/jxcore-log( 6583): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:49.568Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:49.568Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:49.568Z SendDataConnector.js: do connect now
I/jxcore-log( 6583): 
I/io.jxcore.node.ConnectionHelper( 6583): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
,W/bt-btif ( 2413): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 6583): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
,I/chromium( 6583): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:51:18:22 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 853)
W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74c1c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7569c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74c1c rs_disc_pending=0
W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,E/bt-btif ( 2413): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2413): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2413): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2413): StableState(): Entering Off State
,D/BluetoothMetrics( 2413): btclass5a020c
,D/Checkin ( 2413): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2413): new conn_srvc id:26, app_id:1
W/bt-btif ( 2413): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2413): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onSocketConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 853)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): onBytesWritten: 81 bytes successfully written (thread ID: 854)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Outgoing connection initialized (*handshake* thread ID: 854)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Exiting thread (thread ID: 853)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Entering thread (ID: 854)
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74c1c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): onBytesRead: Read 82 bytes successfully (thread ID: 854)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onHandshakeSucceeded: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6583): Exiting thread (ID: 854)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
,I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Outgoing connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453]
,D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
,W/io.jxcore.node.ConnectionHelper( 6583): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6583): onConnected: Outgoing socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6583): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6583): Entering thread (ID: 855)
,D/io.jxcore.node.OutgoingSocketThread( 6583): Server socket local port: 60291
,I/io.jxcore.node.OutgoingSocketThread( 6583): Now accepting connections...
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7569c rs_disc_pending=1
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,I/io.jxcore.node.ConnectionHelper( 6583): onListeningForIncomingConnections: Outgoing connection is using port 60291 (peer ID: B0:C5:59:3F:75:69)
,I/jxcore-log( 6583): 2015-12-18T13:42:51.977Z SendDataConnector.js: CLIENT connected to 60291, error: null
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:51.977Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6583): 
,I/io.jxcore.node.OutgoingSocketThread( 6583): Incoming data from address: /127.0.0.1, port: 60291
,D/io.jxcore.node.OutgoingSocketThread( 6583): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6583): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6583): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6583): Exiting thread (ID: 855)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 857, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6583): Entering thread (ID: 856, name: Sender)
,I/jxcore-log( 6583): 2015-12-18T13:42:52.000Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6583): 
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f74c1c rs_disc_pending=0
W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6583): 2015-12-18T13:42:53.455Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6583): 
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2413): onReceive
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/jxcore-log( 6583): 2015-12-18T13:42:53.588Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:53.724Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:53.783Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:53.837Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:53.875Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:53.938Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:54.034Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:54.224Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:54.401Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:54.402Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:54.411Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:54.411Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6583): 
D/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
,I/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
I/io.jxcore.node.OutgoingSocketThread( 6583): close
D/io.jxcore.node.OutgoingSocketThread( 6583): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 857
D/io.jxcore.node.OutgoingSocketThread( 6583): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6583): doStop: Thread ID: 856
D/io.jxcore.node.OutgoingSocketThread( 6583): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 856, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 6583): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6583): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 6583): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6583): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6583): Either failed to read from the output stream or write to the input stream (thread ID: 857, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6583): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6583): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9453] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
,E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 856, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6583): Exiting thread (ID: 857, name: Receiver)
,I/jxcore-log( 6583): 2015-12-18T13:42:54.436Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): ---- round done--------
I/jxcore-log( 6583): 
I/jxcore-log( 6583): do fake peer & start
I/jxcore-log( 6583): 
I/jxcore-log( 6583): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:54.437Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:54.440Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:54.440Z SendDataConnector.js: do connect now
I/jxcore-log( 6583): 
,I/io.jxcore.node.ConnectionHelper( 6583): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 6583): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 6583): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
I/chromium( 6583): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B0:C5:59:3F:75:69 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 858)
W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2413): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,E/bt-btif ( 2413): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2413): invalid rfc slot id: 31
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 858)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Maximum number of allowed retries (0) reached, giving up... (thread ID: 858)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Exiting thread (thread ID: 858)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/jxcore-log( 6583): 2015-12-18T13:42:55.756Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:42:55.756Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:42:55.757Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6583): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): shutdown (thread ID: 858)
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7569c rs_disc_pending=0
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2413): tBTM_SEC_DEV:0xa6f7585c rs_disc_pending=0
,W/bt-btif ( 2413): bta_dm_check_av:0
,W/bt-btif ( 2413): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2413): onReceive
,I/BTConnectionReceiver( 8420): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8420): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 6583): 2015-12-18T13:43:00.758Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:43:00.758Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 6583): 
,D/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
,E/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 6583): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6583): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
,I/jxcore-log( 6583): 2015-12-18T13:43:05.760Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:43:05.761Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:43:05.761Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:43:05.761Z SendDataConnector.js: do connect now
I/jxcore-log( 6583): 
I/io.jxcore.node.ConnectionHelper( 6583): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 6583): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 6583): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 6583): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 860)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6583): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,E/bt-btif ( 2413): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2413): invalid rfc slot id: 32
,W/BluetoothAdapter( 6583): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2413): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2413): process_service_search_attr_rsp
,E/bt-btif ( 2413): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2413): invalid rfc slot id: 33
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 860)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Maximum number of allowed retries (0) reached, giving up... (thread ID: 860)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): Exiting thread (thread ID: 860)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/jxcore-log( 6583): 2015-12-18T13:43:06.568Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): 2015-12-18T13:43:06.568Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 6583): 
I/jxcore-log( 6583): 2015-12-18T13:43:06.569Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6583): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6583): shutdown (thread ID: 860)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6583): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  883): Waited long enough for: ServiceRecord{181d6e03 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,E/WifiStateMachine(  883): Connection lost, restart supplicant
,E/WifiStateMachine(  883): setWifiState: disabled
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  883): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): handleNetworkDisconnect "NG700" nid=0
,E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  883): failed to set BSSID: any
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  883): do suspend true
,D/WifiP2pService(  883): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,V/AlarmManager(  883): send {1e8d2863, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  883): send {1990f280, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,D/CommandListener(  308): Clearing all IP addresses on wlan0
,D/TCMD    (  465): NL - Read 60 bytes from update socket.
,D/TCMD    (  465): NL - ignore NL message, type = 21
D/TCMD    (  465): Listening for incoming client connection request
,V/NativeCrypto( 1713): Read error: ssl=0xb869d300: I/O error during system call, Connection timed out
,V/AlarmManager(  883): done {1990f280, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [28ms]
,V/NativeCrypto( 1713): SSL shutdown failed: ssl=0xb869d300: I/O error during system call, Broken pipe
,D/ConnectivityService(  883): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): ValidatedState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): setState: RESTARTING
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info<unknown ssid>
,D/WifiP2pService(  883): InactiveState{ when=0 what=139268 arg2=57 target=com.android.internal.util.StateMachine$SmHandler }
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/WifiMetrics(  883): connected time updated 937117
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/jxcore-log( 6583): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 6583): 
,I/jxcore-log( 6583): The Coordinator has disconnected!
I/jxcore-log( 6583): 
,W/Settings( 1713): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): Failed to shutdown P2P device discovery, got error code: 0
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  883): Unexpected BatchedScanResults :null
E/WifiStateMachine(  883): [1,450,446,189,613 ms] noteScanEnd no scan source
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/WifiScanningService(  883): SCAN_AVAILABLE : 1
D/RttService(  883): SCAN_AVAILABLE : 1
D/WifiScanningService(  883): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  883): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiP2pService(  883): InactiveState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
V/AlarmManager(  883): done {1e8d2863, *alarm*:android.intent.action.TIME_TICK} [119ms]
D/WifiP2pService(  883): discovery change broadcast false
D/WifiP2pService(  883): P2pDisablingState
E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/WifiP2pService(  883): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiP2pService(  883): p2p socket connection lost
D/WifiNetworkAgent(  883): NetworkAgent: NetworkAgent channel lost
D/WifiP2pService(  883): P2pDisabledState
E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiP2pService(  883): P2pDisabledState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=58 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): stop: Stopping services
,D/WifiP2pService(  883): P2pDisabledState{ when=0 what=139298 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139298 arg2=59 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  883): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/Nat464Xlat(  883): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  883): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Disconnected - quitting
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524292
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8803 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=8820 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): stop: Stopping P2P device discovery...
,D/ConnectivityService(  883): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiP2pService(  883): P2pDisabledState{ when=0 what=139268 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): DefaultState{ when=0 what=139268 arg2=60 target=com.android.internal.util.StateMachine$SmHandler }
I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6583): setState: NOT_INITIALIZED
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  883): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WifiP2pService(  883): P2pDisabledState{ when=0 what=139307 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139307 arg2=61 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): stopWifiPeerDiscovery: Stopped
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6583): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6583): onP2pDeviceListChanged: 0 device(s) discovered
,D/AndroidRuntime( 6583): Shutting down VM
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): Uncaught exception: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer.onP2pDeviceListChanged(WifiPeerDiscoverer.java:164)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer$MyPeerListListener.onPeersAvailable(WifiP2pDeviceDiscoverer.java:285)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): 	at android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler.handleMessage(WifiP2pManager.java:832)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): 	at android.os.Looper.loop(Looper.java:135)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): 	at java.lang.reflect.Method.invoke(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6583): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,W/ResourcesManager( 8803): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/Tethering(  883): InitialState.processMessage what=4
,D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  0
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
,D/Tethering(  883): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  465): NL - Read 68 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/art     (  883): Explicit concurrent mark sweep GC freed 40500(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.452ms total 148.653ms
,D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/Babel_SMS( 8803): MmsConfig: mnc/mcc: 0/0
,D/TCMD    (  465): NL - Read 444 bytes from update socket.
D/TCMD    (  465): NL - ignore NL message, type = 17
D/TCMD    (  465): Listening for incoming client connection request
I/Babel_SMS( 8803): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8803): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8803): MmsConfig.loadFromDatabase
,D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,E/Babel_SMS( 8803): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8803): MmsConfig.loadFromResources
,E/Babel_SMS( 8803): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 8803): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/TCMD    (  465): NL - Read 444 bytes from update socket.
D/TCMD    (  465): NL - ignore NL message, type = 17
D/TCMD    (  465): Listening for incoming client connection request
,W/ResourcesManager( 8820): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8820): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8820): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/Settings( 8803): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8803): startup - clean
,I/Babel   ( 8803): deleted: false for 0
,W/System  ( 8820): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8820): Installed default security provider GmsCore_OpenSSL
,W/VideoCapabilities( 8803): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8803): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8803): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8803): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8803): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8803): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8803): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8803): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 8803): onServiceConnected
,W/Babel   ( 8803): Attempted to change video mute state without an active call.
,I/MDMCTBK (  311): NetlinkHandler, wifiStateChanged 0
,I/MDMCTBK (  311): MdmCutbackHndler,wifi, new_state =0
,I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
,E/YouTube MDX( 8820): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,W/ResourcesManager( 8820): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8820): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/art     ( 8820): Suspending all threads took: 15.499ms
,I/dex2oat ( 8878): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-551083564.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-551083564.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8820): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/dex2oat ( 8878): dex2oat took 62.846ms (threads: 4)
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8820): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8820): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8820): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 8820): Found 10016
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.youtube/cache/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8820): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  883): Killing 8457:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_8457/cgroup.procs: No such file or directory
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1482): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2522): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8938 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1482): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1482): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2522): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2522): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2522): Registering with Alarm Manager to restart CCE
,D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2522): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2522): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2522): [debug] > CusSM.onRadioDown,
D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2522): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2522): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2522): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2522): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/MusicStore( 8938): Database version: 120
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8938): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8938): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8938): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8938): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8938): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8938): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8938): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8938): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@398fa4c4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8938): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8938): GMSCore installation verified
,I/ConfigStore( 8938): Config Database version: 1
,I/MediaRouter( 8938): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8938): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8983 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8938): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8938): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  883): Killing 8371:com.android.settings/1000 (adj 15): empty #7
,V/Mms     ( 8983): mnc/mcc: 
V/Mms     ( 8983): tag: int value: recipientLimit - 20
,V/Mms     ( 8983): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 8983): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8983): tag: int value: maxSubjectLength - 80
V/Mms     ( 8983): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8983): tag: bool value: enableGroupMms - false
V/Mms     ( 8983):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  883): failed to open /acct/uid_1000/pid_8371/cgroup.procs: No such file or directory
,W/ResourcesManager( 8983): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9010 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 8420:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_8420/cgroup.procs: No such file or directory
,D/PhoneMonitor( 9010): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 9010): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 9010): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 6861): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ActivityManager(  883): Killing 8803:com.google.android.talk/u0a70 (adj 15): empty #7
,I/iu.UploadsManager( 6861): num queued entries: 0
,I/iu.UploadsManager( 6861): num updated entries: 0
I/iu.SyncManager( 6861): NEXT; no task
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_8803/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9028 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  328): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 23.478ms
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 380us total 21.018ms
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.859ms
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9045 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 8820:com.google.android.youtube/u0a101 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10101/pid_8820/cgroup.procs: No such file or directory
,W/ResourcesManager( 9045): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 9045): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 9045): MmsConfig.loadMmsSettings
I/Babel_SMS( 9045): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9045): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9045): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 9045): MmsConfig.loadFromResources
,E/Babel_SMS( 9045): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 9045): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9045): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9045): startup - clean
,I/Babel   ( 9045): deleted: false for 0
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9079 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 9045): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9045): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9045): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9045): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9045): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9045): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9045): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9045): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 9045): onServiceConnected
,W/Babel   ( 9045): Attempted to change video mute state without an active call.
,I/Babel   ( 9045): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  883): Killing 8938:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9079): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 9079): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9079):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9079):   adb logcat -s GAv4
,D/WifiP2pService(  883): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9079): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9079): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9079): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_8938/cgroup.procs: No such file or directory
,W/GAv4    ( 9079): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9079): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9079): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 9079): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9079): Time to load native libraries: 2 ms (timestamps 4678-4680)
I/LibraryLoader( 9079): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9079): Binding Chromium to main looper Looper (main, tid 1) {26b884ef}
,I/LibraryLoader( 9079): Expected native library version number "",actual native library version number ""
,I/chromium( 9079): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9079): Initializing chromium process, singleProcess=true
,W/art     ( 9079): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 9079): ApplicationContext is null in ApplicationStatus
,W/chromium( 9079): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 9079): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 9079): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 9079): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9079): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9079): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9079): Local Branch: 
I/Adreno-EGL( 9079): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9079): Local Patches: NONE
I/Adreno-EGL( 9079): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 9079): Requires BLUETOOTH permission
,I/NSApplication( 9079): Starting up...
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9156 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 8983:com.android.mms/u0a23 (adj 15): empty #7
,D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  0
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
,D/TCMD    (  465): NL - Read 1008 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/TCMD    (  465): NL - Read 1008 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/QsoftapCmd(  308): Got softap fwreload command we are passing on
,D/SoftapController(  308): Softap fwReload - Ok
,D/CommandListener(  308): Setting iface cfg
D/CommandListener(  308): Trying to bring down wlan0
D/CommandListener(  308): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  883): setWifiState: enabling
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_8983/cgroup.procs: No such file or directory
,D/Tethering(  883): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering(  883): InitialState.processMessage what=4
D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  883): ApnList is empty for checkDunConfigured()
,D/Tethering(  883):  upstream interface types: 
,D/Tethering(  883):  0
,D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
,E/WifiStateMachine(  883): Supplicant start successful
D/WifiMonitor(  883): startMonitoring(wlan0) with mConnected = false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,D/Tethering(  883): sendTetherStateChangedBroadcast 0, 0, 0
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/wpa_supplicant( 9174): Successfully initialized wpa_supplicant
I/wpa_supplicant( 9174): Long line in configuration file truncated
I/wpa_supplicant( 9174): rfkill: Cannot open RFKILL control device
,D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
,D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/libmdmdetect( 9174): ESOC framework not supported
,E/Diag_Lib( 9174):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
E/wpa_supplicant( 9174): baseband property is set to [msm]
I/libmdmdetect( 9174): ESOC framework not supported
,E/wpa_supplicant( 9174):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9174): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9174): card_info[i].card_state: 0x0
E/wpa_supplicant( 9174): card_info[i].error_code: 0x0
E/wpa_supplicant( 9174): SIM/USIM not ready
E/wpa_supplicant( 9174): Error while reading SIM card status
,E/wpa_supplicant( 9174): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 9174): card_info[i].card_state: 0x0
E/wpa_supplicant( 9174): card_info[i].error_code: 0x0
E/wpa_supplicant( 9174): SIM/USIM not ready
I/wpa_supplicant( 9174): eap_proxy: Card not ready
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9178 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 9010:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,E/wpa_supplicant( 9174): Line 31: unknown global field 'o'.
,E/wpa_supplicant( 9174): Line 31: Invalid configuration line 'o'.
I/wpa_supplicant( 9174): rfkill: Cannot open RFKILL control device
,D/TCMD    (  465): NL - Read 1004 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,I/art     (  883): Explicit concurrent mark sweep GC freed 20437(1085KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.868ms total 116.364ms
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_9010/cgroup.procs: No such file or directory
,E/wpa_supplicant( 9174): baseband property is set to [msm]
I/libmdmdetect( 9174): ESOC framework not supported
,W/ResourcesManager( 9178): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/wpa_supplicant( 9174):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9174): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9174): card_info[i].card_state: 0x0
,E/wpa_supplicant( 9174): card_info[i].error_code: 0x0
E/wpa_supplicant( 9174): SIM/USIM not ready
E/wpa_supplicant( 9174): Error while reading SIM card status
I/MDMCTBK (  311): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  311): MdmCutbackHndler,wifi, new_state =1
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): wifi_connect_to_supplicant, current pid is = 311
,D/MDMCTBK (  311): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  311): wifi_close_sockets: Exit
E/MDMCTBK (  311): Attach monitor thread
D/MDMCTBK (  311): wifi_ctrl_recv: Exiting
D/MDMCTBK (  311): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  311): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  311): wifi_close_sockets: Exit
E/wpa_supplicant( 9174): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 9174): card_info[i].card_state: 0x0
E/wpa_supplicant( 9174): card_info[i].error_code: 0x0
E/wpa_supplicant( 9174): SIM/USIM not ready
I/wpa_supplicant( 9174): eap_proxy: Card not ready
,I/wpa_supplicant( 9174): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
,E/WifiStateMachine(  883): Supplicant connection established
,E/WifiStateMachine(  883): setWifiState: enabled
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/WifiConfigStore(  883): Loading config and enabling all networks 
E/WifiConfigStore(  883):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  883):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  883): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  883): Setting external_sim to 1
D/WifiStateMachine(  883): Setting OUI to DA-A1-19
W/Settings( 9045): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiNative-HAL(  883): startHal
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2e3889c
D/wifi    (  883): halHandle = 0x0, mVM = 0xb8318310, mCls = 0x201a66
I/WifiNative-HAL(  883): Could not start hal
,E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/wpa_supplicant( 9174): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,I/wpa_supplicant( 9174): CTRL_IFACE: Detach monitor /data/misc/cutback/wpa_ctrl_311-4\x00 that cannot receive messages
,E/native  (  883): do suspend true
,D/WifiP2pService(  883): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  308): Setting iface cfg
,D/CommandListener(  308): Trying to bring up p2p0
D/WifiMonitor(  883): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  883): P2pEnablingState
D/WifiP2pService(  883): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2p socket connection successful
D/WifiP2pService(  883): P2pEnabledState
,D/WifiP2pService(  883): sending p2p connection changed broadcast
,D/WifiNative-HAL(  883): p2pGetDeviceAddress
,D/WifiScanningService(  883): SCAN_AVAILABLE : 3
D/RttService(  883): SCAN_AVAILABLE : 3
D/RttService(  883): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  883): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-HAL(  883): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
I/WifiNative-HAL(  883): startHal
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa480b9cc
D/wifi    (  883): halHandle = 0x0, mVM = 0xb8318310, mCls = 0x101952
I/WifiNative-HAL(  883): Could not start hal
E/WifiScanningService(  883): could not start HAL
D/WifiP2pService(  883): DeviceAddress: 44:80:eb:7b:5a:07
,D/WifiP2pService(  883): MCC mode enabled 0
,D/WifiP2pService(  883): mP2pAutoConnectSupport = 0
,D/WifiP2pService(  883): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  883): InactiveState
,E/WifiStateMachine(  883): set country code US
,D/WifiP2pService(  883): InactiveState{ when=0 what=131222 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): InactiveState{ when=0 what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  883): set frequency band 2
,I/wpa_supplicant( 9174): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9201 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9045:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 9201): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 9028:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2522): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_9045/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_9028/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2522): bindWebServices(): registering our AIDL callback...
I/SundryService( 2522): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2522): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2522): onServiceConnected()
D/GetNotificationsWS( 2522): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2522): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=9225 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 9225): Database version: 120
,D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
,D/TCMD    (  465): Listening for incoming client connection request
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9225): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9225): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9225): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 9225): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 9225): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9225): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9225): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9225): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@398fa4c4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9225): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 9225): GMSCore installation verified
,I/ConfigStore( 9225): Config Database version: 1
,I/MediaRouter( 9225): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 9225): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9257 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 9225): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 9225): Using platform SSLCertificateSocketFactory
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledStateupdate channel list
,I/ActivityManager(  883): Killing 9079:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_9079/cgroup.procs: No such file or directory
,V/Mms     ( 9257): mnc/mcc: 
V/Mms     ( 9257): tag: int value: recipientLimit - 20
,V/Mms     ( 9257): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 9257): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9257): tag: int value: maxSubjectLength - 80
V/Mms     ( 9257): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 9257): tag: bool value: enableGroupMms - false
V/Mms     ( 9257):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 9257): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9291 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9156:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_9156/cgroup.procs: No such file or directory
,D/PhoneMonitor( 9291): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 9291): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 9291): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 9178:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_9178/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9316 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9333 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  883): Killing 9201:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_9201/cgroup.procs: No such file or directory
,W/ResourcesManager( 9333): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  465): NL - Read 56 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,E/WifiStateMachine(  883): [1,450,446,197,503 ms] noteScanEnd no scan source
E/WifiStateMachine(  883): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@37d5ed5c sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  883): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  883):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  883): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  883): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,E/WifiConfigStore(  883): will read network variables netId=0
,E/WifiStateMachine(  883): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  883): will read network variables netId=0
,I/wpa_supplicant( 9174): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  883): didn't find BSSID Trying to associate with SSID 'NG700'
E/wpa_supplicant( 9174): DSDS: eapol_sm_notify_config config->sim_num = 1
E/WifiConfigStore(  883): setLastSelectedConfiguration -1
,E/wpa_supplicant( 9174): PNO: In assoc process
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel_SMS( 9333): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 9333): MmsConfig.loadMmsSettings
,I/Babel_SMS( 9333): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 9333): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9333): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 9333): MmsConfig.loadFromResources
E/Babel_SMS( 9333): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 9333): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9333): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TCMD    (  465): NL - Read 312 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 192 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 1004 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
,D/TCMD    (  465): NL - Read 80 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 80 bytes from update socket.
D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/TCMD    (  465): NL - Read 68 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
I/wpa_supplicant( 9174): wlan0: Associated with c0:ff:d4:d3:aa:48
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
,D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  0
,D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/wpa_supplicant( 9174): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 9174): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,D/TCMD    (  465): NL - Read 1004 bytes from update socket.
,D/TCMD    (  465): NL - message type is RTM_NEWLINK
D/TCMD    (  465): Listening for incoming client connection request
D/Tethering(  883): sendTetherStateChangedBroadcast 1, 0, 0
,I/Babel_Crash( 9333): startup - clean
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  883): Network connection established
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  883): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  883): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
,E/WifiStateMachine(  883): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  883): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 2
E/WifiStateMachine(  883): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  308): Setting iface cfg
E/WifiStateMachine(  883): Start Dhcp Watchdog 3
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  883): do suspend false
,E/wpa_supplicant( 9174): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  883): Unexpected BatchedScanResults :null
E/wpa_supplicant( 9174): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@358619bd target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@358619bd target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel   ( 9333): deleted: false for 0
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9371 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  328): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 20.458ms
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.113ms
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.642ms
,W/VideoCapabilities( 9333): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9333): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9333): Unsupported mime video/mpeg2
,E/DHCPCD  ( 9388): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
I/DHCPCD  ( 9388): version 5.5.6 starting
E/DHCPCD  ( 9388): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 9388): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 9388): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/VideoCapabilities( 9333): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9333): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9333): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9333): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9333): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 9333): onServiceConnected
W/Babel   ( 9333): Attempted to change video mute state without an active call.
D/DHCPCD  ( 9388): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 9388): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 9388): wlan0: sending REQUEST (xid 0xd3f926e3), next in 4.05 seconds
,I/Babel   ( 9333): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  883): Killing 9225:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/GAv4    ( 9371): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9371):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9371):   adb logcat -s GAv4
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9371): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9371): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9371): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9371): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_9225/cgroup.procs: No such file or directory
,W/GAv4    ( 9371): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9371): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9371): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  883): send {25733e97, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/WebViewFactory( 9371): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9371): Time to load native libraries: 1 ms (timestamps 8104-8105)
,I/LibraryLoader( 9371): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9371): Binding Chromium to main looper Looper (main, tid 1) {26b884ef}
,I/LibraryLoader( 9371): Expected native library version number "",actual native library version number ""
I/chromium( 9371): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9371): Initializing chromium process, singleProcess=true
,W/art     ( 9371): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 9371): ApplicationContext is null in ApplicationStatus
,W/chromium( 9371): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9371): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 9371): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 9371): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9371): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9371): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9371): Local Branch: 
I/Adreno-EGL( 9371): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9371): Local Patches: NONE
I/Adreno-EGL( 9371): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 9371): Requires BLUETOOTH permission
,I/NSApplication( 9371): Starting up...
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9446 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9257:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_9257/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9465 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 9291:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_9291/cgroup.procs: No such file or directory
,W/ResourcesManager( 9465): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  883): Explicit concurrent mark sweep GC freed 32543(1589KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.847ms total 115.695ms
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9485 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9333:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_9333/cgroup.procs: No such file or directory
,I/ContactLocale( 9485): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,V/AlarmManager(  883): done {25733e97, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [1051ms]
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9523 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9371:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_9371/cgroup.procs: No such file or directory
,W/ResourcesManager( 9523): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 9523): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 9523): MmsConfig.loadMmsSettings
I/Babel_SMS( 9523): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9523): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9523): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 9523): MmsConfig.loadFromResources
E/Babel_SMS( 9523): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 9523): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9523): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9523): startup - clean
,I/Babel   ( 9523): deleted: false for 0
,W/VideoCapabilities( 9523): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9523): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9523): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9523): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9523): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9523): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9523): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9523): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Killing 6861:com.google.android.gms/u0a16 (adj 15): empty #7
,D/WifiService(  883): Client connection lost with reason: 4
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_6861/cgroup.procs: No such file or directory
,I/vclib   ( 9523): onServiceConnected
W/Babel   ( 9523): Attempted to change video mute state without an active call.
,I/DHCPCD  ( 9388): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 9388): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 9388): wlan0: adding IP address 192.168.1.123/24
,D/DHCPCD  ( 9388): wlan0: adding route to 192.168.1.0/24
,D/DHCPCD  ( 9388): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 9388): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  465): NL - Read 60 bytes from update socket.
D/TCMD    (  465): NL - ignore NL message, type = 20
D/TCMD    (  465): Listening for incoming client connection request
,D/DHCPCD  ( 9388): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend true
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  883): WifiStateMachine DHCP successful
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  883): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  883): Adding iface wlan0 to network 102
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  883): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  883): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  883): Adding Route [fe80::/64 -> :: wlan0] to network 102
D/ConnectivityService(  883): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,D/ConnectivityService(  883): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,E/WifiStateMachine(  883): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  883): Setting Dns servers for network 102 to [/192.168.1.1]
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  883): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  883):    accepting network in place of null
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/CSLegacyTypeTracker(  883): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  883): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1538): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Dec 2015 13:43:21 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450446201128], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450446201109]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Validated
,D/ConnectivityService(  883): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  883): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524290
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1538): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1294): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1538): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/ModemStatsDSDetect( 1538): Inetcondition changed, white->blue
I/SBar.MotoNetworkCtrlr( 1294): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1538): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1294): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1294): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524295
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2522): now: 1023644 ,futureTime: 9223372036854775807
D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2522): now: 1023644 ,futureTime: 9223372036854775807
D/PollingManager( 2522): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2522): now: 1023645 ,futureTime: 9223372036854775807
D/OtaApp  ( 2522): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1482): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=9609 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2522): [debug] > PollingManagerService, now: 1023709 ,futureTime: 78264029
D/Central_PollingManager( 1482): now: 1023709 ,futureTime: 86473089
,D/Central_PollingManager( 1482): Polling alarm set to expire at: 86473089 Current Time: 1023710
D/OtaApp  ( 2522): [debug] > Polling alarm set to expire at: 78264029 Current Time: 1023709
,D/OtaApp  ( 2522): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2522): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2522): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2522): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2522): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
,D/MMApiProvisionService( 2522): isDeviceProvisioned: deviceId = 2072049230914535424
D/OtaApp  ( 2522): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2522): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2522): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2522): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/CCE     ( 2522): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2522): createDeviceIdOrLogin update_device
D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2522): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2522): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2522): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2522): createDeviceIdOrLogin update_device
D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2522): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2522): set mOutstandingReq to true.
I/ Nonce  ( 2522):  Nonce getNonce 
,I/ Nonce  ( 2522):  Nonce Request 
,I/ Nonce  ( 2522):  Nonce execute Request 
,D/MMApiWebService( 2522): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiProvisionService( 2522): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2522): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2522): createDeviceIdOrLogin update_device
D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2522): Not proxy app, so login/provision not allowed
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 5776(278KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 7MB/12MB, paused 581us total 36.910ms
,I/MusicStore( 9609): Database version: 120
,D/MMApiWebService( 2522): generating token using payload instead of using session token
,D/ Nonce  ( 2522):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2522): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9609): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9609): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9609): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 9609): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 9609): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9609): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9609): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9609): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@398fa4c4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9609): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 9609): GMSCore installation verified
,I/ConfigStore( 9609): Config Database version: 1
,I/MediaRouter( 9609): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 9609): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 9609): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 9609): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9656 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 9609): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 9609): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  883): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=9681 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9446:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 9656): mnc/mcc: 
V/Mms     ( 9656): tag: int value: recipientLimit - 20
V/Mms     ( 9656): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 9656): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9656): tag: int value: maxSubjectLength - 80
V/Mms     ( 9656): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 9656): tag: bool value: enableGroupMms - false
V/Mms     ( 9656):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_9446/cgroup.procs: No such file or directory
,W/ResourcesManager( 9681): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9681): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 9681): VM with version 2.1.0 has multidex support
I/MultiDex( 9681): install
I/MultiDex( 9681): VM has multidex support, MultiDex support library is disabled.
,I/art     (  883): Explicit concurrent mark sweep GC freed 19280(942KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.754ms total 127.454ms
,W/ResourcesManager( 9656): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9706 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,V/JNIHelp ( 9681): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PhoneMonitor( 9706): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 9706): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 9706): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  883): Killing 9465:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/ActivityThread( 9681): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 9681): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f880683: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9681): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_9465/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 9485:android.process.acore/u0a7 (adj 15): empty #7
,I/ Nonce  ( 2522):  Nonce Reponse 
D/NativeLibraryUtils( 9681): Install completed successfully. count=14 extracted=0
D/        ( 2522): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"01923b51-be71-4999-b092-4f30dad9d0b4"}
D/MMApiWSBase( 2522): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2522):  Nonce Handle Reponse 
,D/MMApiProvisionService( 2522): mOutstandingReq set to false
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_9485/cgroup.procs: No such file or directory
,D/MMApiProvisionService( 2522):  pTime 1450280700010 sExp 172742 cTime 1450446205263 tTime 1450453442010
,D/MMApiProvisionService( 2522):  No login Required 
,I/CheckinService( 9681): Checkin interval check for package: unspecified last checkin: 1450445429709 min interval config: 0 actual interval: 775561
,I/art     ( 6185): Explicit concurrent mark sweep GC freed 1604(55KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 321us total 24.651ms
,I/CheckinService( 9681): Disabling old GoogleServicesFramework version
,I/CheckinService( 9681): Checking schedule, now: 1450446205336 next: 1450445459692
I/CheckinService( 9681): active receiver: enabled
,I/CheckinService( 9681): Preparing to send checkin request
,I/EventLogService( 9681): Accumulating logs since 1450445426744
,I/iu.SyncManager( 9681): SYNC; picasa accounts
,D/NetworkLogImpl( 9681): Loaded NetworkSpeedPredictor
,I/iu.Environment( 9681): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 9681): num queued entries: 0
,I/iu.UploadsManager( 9681): num updated entries: 0
,I/iu.SyncManager( 9681): NEXT; no task
,I/art     ( 9681): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 9681): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9745 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 9523): connection state changed from UNKNOWN to CONNECTED
,E/MDMCTBK (  311): Unable to attach monitor connection to supplicant on @android:wpa_wlan0
D/MDMCTBK (  311): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  311): wifi_close_sockets: Exit
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9745): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
I/GAv4    ( 9745): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9745):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9745):   adb logcat -s GAv4
W/ContextImpl( 9745): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9745): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 9745): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9745): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 9745): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9745): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/CheckinRequestBuilder( 9681): Checkin reason type: 8 attempt count: 1
,D/WifiService(  883): New client listening to asynchronous messages
,E/ActivityThread( 9681): Failed to find provider info for com.google.android.wearable.settings
,W/DataUsage( 2522): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2522): publish the event [tag = MOT_CCE event name = LOG]
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 9745): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9745): Time to load native libraries: 1 ms (timestamps 5571-5572)
I/LibraryLoader( 9745): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9745): Binding Chromium to main looper Looper (main, tid 1) {32c06285}
I/LibraryLoader( 9745): Expected native library version number "",actual native library version number ""
,I/chromium( 9745): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9745): Initializing chromium process, singleProcess=true
,W/art     ( 9745): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 9745): ApplicationContext is null in ApplicationStatus
,W/chromium( 9745): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9745): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 9745): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 9745): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9745): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9745): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9745): Local Branch: 
I/Adreno-EGL( 9745): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9745): Local Patches: NONE
I/Adreno-EGL( 9745): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  883): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=9800 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/NSApplication( 9745): Starting up...
,W/AudioManagerAndroid( 9745): Requires BLUETOOTH permission
,W/ResourcesManager( 9800): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9800): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 9800): VM with version 2.1.0 has multidex support
,I/MultiDex( 9800): install
I/MultiDex( 9800): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9830 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 9609:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/art     (  328): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 22.262ms
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 19.473ms
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.590ms
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_9609/cgroup.procs: No such file or directory
,V/JNIHelp ( 9800): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9800): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 9800): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3697ca15: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9800): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9850 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 9850): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 9800): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 9800): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  883): Killing 9656:com.android.mms/u0a23 (adj 15): empty #7
,D/NativeLibraryUtils( 9800): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_9656/cgroup.procs: No such file or directory
,D/WVCdm   (  314): Instantiating CDM.
,I/WVCdm   (  314): CdmEngine::OpenSession
I/WVCdm   (  314): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  314): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  314): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  314): Service_Initialize: starts!
D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
E/QSEECOMAPI: (  314): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  314): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
E/QSEECOMAPI: (  314): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  314): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
,D/QSEECOMAPI: (  314): Loaded image: APP id = 3
,D/DrmWidevineDash(  314): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f48000,
E/DrmWidevineDash(  314): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f48000
,D/DrmWidevineDash(  314): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  314): hlos api version =  9
D/DrmWidevineDash(  314): tz api version =  8
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  314): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  314): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  314): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  314): OEMCrypto_OpenSession: starts! SID=0xbea894e0
D/DrmWidevineDash(  314): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  314): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_GetRandom: starts! randomData=0xb8900468, dataLength=8
D/DrmWidevineDash(  314): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  314): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8944990, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  314): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  314): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  314): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  314): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  314): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  314): OEMCrypto_GetDeviceID: starts! deviceID=0xb8a15958, idLength=0xb1339730
,D/DrmWidevineDash(  314): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  314): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  314): hlos api version =  9
D/DrmWidevineDash(  314): tz api version =  8
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  314): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  314): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  314): PrepareKeyRequest: nonce=4195714920
D/DrmWidevineDash(  314): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb89c9ec0
D/DrmWidevineDash(  314): message_length=1591, signature=0xb88e7a30, signature_length=2972948244
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9877 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9316:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,D/DrmWidevineDash(  314): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  314): CdmEngine::CloseSession
D/DrmWidevineDash(  314): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  314): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  314): L3 Terminate.
D/DrmWidevineDash(  314): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  314): Service_Uninitialize: starts!
D/QSEECOMAPI: (  314): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  314): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  314): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_Terminate: ends! returns 0
,I/ContactLocale( 9877): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 9706:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_9316/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2522): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_9706/cgroup.procs: No such file or directory
,I/art     (  883): Explicit concurrent mark sweep GC freed 11004(560KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.543ms total 115.161ms
,D/GetNotificationsWS( 2522): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2522): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2522): onServiceConnected()
D/GetNotificationsWS( 2522): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 2522): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2522): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2522): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2522): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2522): [debug] > In cancelAnyPendingIntentSetPreviously
,I/PushService( 2522): started with background data enabled, making sure notification mechanism is enabled
,I/ActivityManager(  883): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2522): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2522): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2522): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2522): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:32000 mC
,D/WearableService( 1713): callingUid 10016, callindPid: 1713
,D/OtaApp  ( 2522): [debug] > DownloadActivity, FormattedText
,E/MDM     ( 1713): [180] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/OtaApp  ( 2522): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/LocationInitializer( 9681): Restart initialization of location
,D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2522): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2522): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2522): publish the event [tag = MOT_OTA event name = LOG]
,D/AuthorizationBluetoothService( 1713): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=9917 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1713): No location to return for getLastLocation()
,W/FusedLocationProvider( 1713): location=null
,I/dex2oat ( 9916): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/IcingInternalCorpora( 9681): getNumBytesRead when not calculated.
,I/dex2oat ( 9916): dex2oat took 88.781ms (threads: 4)
,I/Adreno-EGL( 9800): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9800): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9800): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9800): Local Branch: 
I/Adreno-EGL( 9800): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9800): Local Patches: NONE
I/Adreno-EGL( 9800): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 9800): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9800): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9800): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9800): Local Branch: 
I/Adreno-EGL( 9800): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9800): Local Patches: NONE
I/Adreno-EGL( 9800): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  883): Killing 9745:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/Adreno-EGL( 9800): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9800): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9800): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9800): Local Branch: 
I/Adreno-EGL( 9800): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9800): Local Patches: NONE
I/Adreno-EGL( 9800): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 9800): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9800): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9800): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9800): Local Branch: 
I/Adreno-EGL( 9800): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9800): Local Patches: NONE
I/Adreno-EGL( 9800): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  314): CdmEngine::OpenSession
,I/WVCdm   (  314): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  314): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_9745/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  314): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  314): Service_Initialize: starts!
D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
E/QSEECOMAPI: (  314): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  314): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
E/QSEECOMAPI: (  314): Error::Cannot open the file /system/etc/firmware/widevine.mdt
,E/QSEECOMAPI: (  314): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  314): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  314): App is not loaded in QSEE
,D/LocationInitializer( 9681): Restart initialization of location
D/AuthorizationBluetoothService( 1713): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1713): [198] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1713): No location to return for getLastLocation()
,W/FusedLocationProvider( 1713): location=null
,D/QSEECOMAPI: (  314): Loaded image: APP id = 3
D/DrmWidevineDash(  314): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  314): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f48000
E/DrmWidevineDash(  314): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f48000
,D/DrmWidevineDash(  314): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  314): hlos api version =  9
D/DrmWidevineDash(  314): tz api version =  8
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  314): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  314): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  314): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  314): OEMCrypto_OpenSession: starts! SID=0xb1339960
D/DrmWidevineDash(  314): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  314): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_GetRandom: starts! randomData=0xb8a0b818, dataLength=8
D/DrmWidevineDash(  314): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8944990, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  314): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  314): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  314): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  314): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  314): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  314): OEMCrypto_GetDeviceID: starts! deviceID=0xb8a15998, idLength=0xb5423730
,D/DrmWidevineDash(  314): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  314): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  314): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  314): hlos api version =  9
D/DrmWidevineDash(  314): tz api version =  8
D/DrmWidevineDash(  314): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  314): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  314): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  314): PrepareKeyRequest: nonce=792614425
,D/DrmWidevineDash(  314): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb89c9ec0
D/DrmWidevineDash(  314): message_length=1626, signature=0xb8902e18, signature_length=3041015572
,D/DrmWidevineDash(  314): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  314): CdmEngine::CloseSession
D/DrmWidevineDash(  314): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  314): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  314): L3 Terminate.
D/DrmWidevineDash(  314): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  314): Service_Uninitialize: starts!
D/QSEECOMAPI: (  314): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  314): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  314): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  314): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 9681): Classify the device as Phone.
,I/CheckinTask( 9681): Sending checkin request (9513 bytes)
,I/CheckinRequestBuilder( 9681): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 9681): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 9681): Classify the device as Phone.
,I/CheckinTask( 9681): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 9681): Checking schedule, now: 1450446209891 next: 1451047346882
I/CheckinService( 9681): active receiver: disabled
,D/CheckinService( 9681): Recording last checkin time for package unspecified as 1450446209904
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=9987 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 9987): Register our PhoneStateListener
,V/SetupWizard( 9987): Connected to Gservices successfully
,I/ActivityManager(  883): Killing 9830:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_9830/cgroup.procs: No such file or directory
,D/GCM     ( 1713): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MDMCTBK (  311): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  311): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  311): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  311): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  311): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
,I/MDMCTBK (  311): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  311): set_property_value, Enter
I/MDMCTBK (  311): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  311): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  311): set_property_value, Exit
I/MDMCTBK (  311): MdmCutbackHndler, setWifiCutback, No Wifi
,I/MDMCTBK (  311): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  311): set_property_value, Enter
I/MDMCTBK (  311): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  311): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  311): set_property_value, Exit
,E/MDMCTBK (  311): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ActivityManager(  883): Killing 9877:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  883): Killing 9850:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_9877/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_9850/cgroup.procs: No such file or directory
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=10013 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3ce7a46c
,I/GCoreNlp( 1713): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1574): Deferring update until onResume
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=10050 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=10072 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9917:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_9917/cgroup.procs: No such file or directory
,W/ResourcesManager( 9523): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9523): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9523): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ContactLocale(10072): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=10094 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 9987:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/System  ( 9523): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9523): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_9987/cgroup.procs: No such file or directory
,I/art     (  883): Explicit concurrent mark sweep GC freed 16597(856KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.884ms total 120.504ms
,W/asset   (10094): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager(10094): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager(10094): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(10094): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 9681): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi(10013): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1574): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2f490a72 new=com.google.android.velvet.VelvetApplication@2f490a72
,I/PackageBroadcastService( 9681): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=10120 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager(10120): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi(10013): UpdateCorporaTask done [took 128 ms] updated apps [took 128 ms] 
,I/Icing   ( 9681): Storage manager: low false usage 1.78MB avail 3.12GB capacity 4.85GB
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=10153 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 9681): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  (10153): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 9681): Internal init done: storage state 0
,I/Icing   ( 9681): Post-init done
,I/Icing   ( 9681): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  (10153): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(10153): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(10153): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  (10153): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  (10153): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     (10153): Skipping gmscore version check
I/ActivityManager(  883): Killing 9800:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_9800/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 10050:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_10050/cgroup.procs: No such file or directory
,D/Finsky  (10153): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  (10153): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:32000 mC
,I/Icing   ( 9681): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 9681): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 9681): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  883): Killing 10094:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_10094/cgroup.procs: No such file or directory
,I/MDMCTBK (  311): NetlinkHandler, subsys is net and action is remove
,I/MDMCTBK (  311): NetlinkHandler, interfaceRemoved
,I/MDMCTBK (  311): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
,I/MDMCTBK (  311): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  311): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  311): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  311): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
,I/MDMCTBK (  311): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  311): set_property_value, Enter
I/MDMCTBK (  311): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  311): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  311): set_property_value, Exit
I/MDMCTBK (  311): MdmCutbackHndler, setWifiCutback, No Wifi
,I/MDMCTBK (  311): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  311): set_property_value, Enter
,I/MDMCTBK (  311): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  311): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  311): set_property_value, Exit
,E/MDMCTBK (  311): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ActivityManager(  883): Killing 9523:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_9523/cgroup.procs: No such file or directory
,I/CheckinService( 9681): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  311): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  311): NetlinkHandler, interfaceAdded
,I/MDMCTBK (  311): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
,E/MDMCTBK (  311): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  311): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  311): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  311): , Wifi = 0
I/MDMCTBK (  311): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  311): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  311): set_property_value, Enter
I/MDMCTBK (  311): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  311): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  311): set_property_value, Exit
I/MDMCTBK (  311): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  311): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  311): set_property_value, Enter
I/MDMCTBK (  311): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  311): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  311): set_property_value, Exit
E/MDMCTBK (  311): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  311): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  311): NetlinkHandler, interfaceAdded
,I/MDMCTBK (  311): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
E/MDMCTBK (  311): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
,I/MDMCTBK (  311): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  311): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  311): , Wifi = 0
I/MDMCTBK (  311): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  311): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  311): set_property_value, Enter
I/MDMCTBK (  311): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  311): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  311): set_property_value, Exit
I/MDMCTBK (  311): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  311): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  311): set_property_value, Enter
I/MDMCTBK (  311): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  311): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  311): set_property_value, Exit
E/MDMCTBK (  311): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310832, SEQNUM=4704, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-36, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {1e8d2863, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {38d93b83, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/LaunchCheckinHandler(  883): cleanup(): cleared. Last call was 84229 ms ago
I/ActivityManager(  883): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=10212 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     (  328): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 24.576ms
,I/art     (  328): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 19.067ms
,I/art     (  328): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 32.496ms
,V/AlarmManager(  883): done {1e8d2863, *alarm*:android.intent.action.TIME_TICK} [153ms]
,I/GAv4    (10212): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    (10212):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    (10212):   adb logcat -s GAv4
,W/GAv4    (10212): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    (10212): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    (10212): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  883): done {38d93b83, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [234ms]
I/ActivityManager(  883): Killing 10013:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_10013/cgroup.procs: No such file or directory
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,E/bt-btif ( 2413): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2413): Entering PendingCommandState State
,I/ActivityManager(  883): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=10256 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 10072:android.process.acore/u0a7 (adj 15): empty #7
,I/BluetoothBondStateMachine( 2413): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2413): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2413): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2413): StableState(): Entering Off State
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_10072/cgroup.procs: No such file or directory
,D/BluetoothMetrics( 2413): btclass5a020c
,D/Checkin ( 2413): publish the event [tag = MOT_BT event name = PAIRING]
,W/ResourcesManager(10256): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a84d39:true
,I/ActivityManager(  883): Killing 10120:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/bt-btif ( 2413): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2413): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2413): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6583): Incoming connection accepted
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_10120/cgroup.procs: No such file or directory
,W/google-breakpad(10286): -----BEGIN BREAKPAD MICRODUMP-----
W/google-breakpad(10286): O A arm 04 armv7l 3.4.42-g48d3b85 #1 SMP PREEMPT Tue Jan 6 18:27:11 CST 2015
W/google-breakpad(10286): S 0 A6119FF0 A6119000 00008000
,W/google-breakpad(10286): S A6119000 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad(10286): S A6119180 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad(10286): S A6119300 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad(10286): S A6119480 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad(10286): S A6119600 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad(10286): S A6119780 000000000000000000000000,000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000687453B8000000002E280000587453B8687453B800000000001000000030A8B40000000000000000B7190000687453B8587453B8C09811A67003000000000000C09811A6E4ADF8B6587453B8809C11A6009D11A6A81481A99BF82FA90B0000000000000002000000F07F11A6000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad(10286): S A6119900 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000008320000000000000000000000000000000D0DDB000000000002000000E00000017000000041200006871406FE0A5E76F90DA2323C0714623C40000006871406FE0A5E76FC071462338A6E76FB06CCCB890DA2323709821A6F07F11A6F09F11A66D2AB2713C2AB27130000FA0F07F11A6041200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001504656200100000000000000000000000000000000000000000000000000000000000000000000D5B2000000000000D0FFFFFF00001582983A0000000000000A510600000010820000000000000000
W/google-breakpad(10286): S A6119A80 00400000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000672F496E7465726E2F7032702F6274636F6E6E6563746F726C69622F7574696C732F426C7565746F6F7468536F636B6574496F546872656100000000000060400C0000000000B03F0000000000000040DF40C7B316B3B0BF000000000000F03F073A9EB598850040EC40C7B316B3603F76B631FC15B360BF13000060000000000000004098C7FBC03465F2C0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad(10286): S A6119C00 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000610AF2F1000000000B000000809C11A6009D11A60000000053F92FA9089B11A10000000004000040386A85B86871406FC40000006871406FE0A5E76FC071462338A6E76FB06CCCB864B4F9B60B0000000000000002000000F07F11A600000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000D0DDB000000000002000000E00000017000000041200006871406FE0A5E76F90DA2323C0714623C40000006871406FE0A5E76FC071462338A6E76FB06CCCB890DA2323709821A6F07F11A6F09F11A66D2AB2713C2AB27130000FA0F07F11A6041200000000000000000000000000000000000000000000
W/google-breakpad(10286): S A6119D80 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001504656200100000000000000000000000000000000000000000000000000000000000000000000D5B2000000000000D0FFFFFF00001582983A0000000000000A51060000001082000000000000000000400000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000672F496E7465726E2F7032702F6274636F6E6E6563746F726C69622F7574696C732F426C7565746F6F7468536F636B6574496F546872656100000000000060400C0000000000B03F0000000000000040DF40C7B316B3B0BF000000000000F03F073A9EB598850040EC40C7B316B3603F76B631FC15B360BF13000060000000000000004098C7FBC0
W/google-breakpad(10286): S A6119F00 3465F2C0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000AD70A0E3AD0090EF6871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611A080 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611A200 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611A380 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611A500 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611A680 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611A800 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611A980 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611AB00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611AC80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611AE00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611AF80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611B100 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611B280 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611B400 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611B580 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611B700 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611B880 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611BA00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611BB80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611BD00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611BE80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611C000 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611C180 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611C300 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611C480 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611C600 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611C780 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611C900 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
,W/google-breakpad(10286): S A611CA80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611CC00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611CD80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611CF00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611D080 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611D200 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611D380 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611D500 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611D680 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611D800 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611D980 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611DB00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611DC80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611DE00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611DF80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611E100 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611E280 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611E400 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611E580 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611E700 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611E880 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611EA00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611EB80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611ED00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611EE80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611F000 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611F180 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611F300 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611F480 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611F600 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611F780 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611F900 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611FA80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611FC00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611FD80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A611FF00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A6120080 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
,W/google-breakpad(10286): S A6120200 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A6120380 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A6120500 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A6120680 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A6120800 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A6120980 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A6120B00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A6120C80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A6120E00 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB271
W/google-breakpad(10286): S A6120F80 6871406F00000000000000000000000000000000000000006871406FE0A5E76FC071462338A6E76F90DA23236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76FC0714623E0A5E76F90DA2323B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F
W/google-breakpad(10286): C 060000406871406FE0A5E76F90DA2323C0714623C40000006871406FE0A5E76FC071462338A6E76FB06CCCB890DA2323709821A6F07F11A6F09F11A66D2AB2713C2AB27130000FA00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad(10286): M B6FAC000 00000000 00003000 E9668E25F5C80EF4F2CC4AB624E387BF0 app_process32
W/google-breakpad(10286): M A0DB3000 00000000 00AB8000 F83F9605A81C561DE740DB94A502D11C0 libjxcore.so
W/google-breakpad(10286): M A480B000 00000000 0000A000 BB53B487721763CEB1E8693EAC1446400 libqservice.so
W/google-breakpad(10286): M A5AD4000 00000000 00452000 1C3C15CCBCD1E8D40558461B307435E60 libsc-a3xx.so
W/google-breakpad(10286): M A5F36000 00000000 00007000 48FE648D1FA5FCBE53FCA043FD7608CB0 libqdutils.so
W/google-breakpad(10286): M A5F3D000 00000000 00005000 BEDF6C78A529DBAC1032A12C9142745E0 libmemalloc.so
W/google-breakpad(10286): M A5F42000 00000000 00005000 7940278696CC504CA766F27B36AC080A0 gralloc.msm8226.so
W/google-breakpad(10286): M A7297000 00000000 0000C000 FE1E24201276FD291234996A311FBB9C0 eglsubAndroid.so
W/google-breakpad(10286): M A7BB7000 00000000 01AE1000 488126E5C3F082244EC0664CC97A94320 libwebviewchromium.so
W/google-breakpad(10286): M ADFB7000 00000000 00003000 932CC9935B065A05D39E38681E0A5F2E0 libwebviewchromium_loader.so
W/google-breakpad(10286): M ADFBA000 00000000 00010000 62690FE7B4748EF8151B01903B27608D0 libandroid.so
W/google-breakpad(10286): M ADFCA000 00000000 0013A000 9C03AF685FCBD8E590150A91E97E640F0 libGLESv2_adreno.so
W/google-breakpad(10286): M AE105000 00000000 00034000 CF692CC2042CC03999A6210A4668E2EF0 libGLESv1_CM_adreno.so
W/google-breakpad(10286): M AE139000 00000000 00027000 13BED457CB8AEE0E8E47FB48F3E826420 libgsl.so
W/google-breakpad(10286): M AE161000 00000000 00029000 C29A639A4A36C88466F1ACCA732D030E0 libEGL_adreno.so
W/google-breakpad(10286): M AE728000 00000000 00018000 0F5D893354D9DF6AC2763E175086C0730 libjavacrypto.so
W/google-breakpad(10286): M AE740000 00000000 00009000 0D2147262F4305E3AED211CB96FC96BA0 librs_jni.so
W/google-breakpad(10286): M AE749000 00000000 00006000 ED6A76B3930E7139A7512B4E28EBAC070 libaudioeffect_jni.so
W/google-breakpad(10286): M AE74F000 00000000 00004000 CDA9BA072D4DECC71C5E63467275E7EE0 libsoundpool.so
W/google-breakpad(10286): M AE753000 00000000 0000E000 D02CB251CF8787A770DE2CFDC52A2B040 libstagefright_amrnb_common.so
W/google-breakpad(10286): M AE761000 00000000 0001B000 F59669C665FE4B073886A8DAAECEA86F0 libvorbisidec.so
W/google-breakpad(10286): M AE77C000 00000000 00004000 9FC00D0B150FE9FC57763A76206D1D550 libstagefright_yuv.so
W/google-breakpad(10286): M AE780000 00000000 0001F000 C2D643DD7028582A8EAF64D04750FE800 libstagefright_omx.so
W/google-breakpad(10286): M AE79F000 00000000 00003000 E11DA546CE9E08D1D647E8E1135DAD810 libstagefright_enc_common.so
W/google-breakpad(10286): M AE7A2000 00000000 00007000 741CC494F5299870A1C62FD71E37AE5F0 libstagefright_avc_common.so
,W/google-breakpad(10286): M AE7A9000 00000000 00005000 D3EA22EB9F383751AB500AE5951F0DB30 libpowermanager.so
,W/google-breakpad(10286): M AE7AE000 00000000 0003C000 F19A7DFF3B6F3AF94EAE23CA21905BAD0 libopus.so
,W/google-breakpad(10286): M AE7EA000 00000000 0001B000 87AFCC5E47ED503148F1AA03777E88590 libdrmframework.so
,W/google-breakpad(10286): M AE805000 00000000 00127000 A7BBF189464222DE263F6ABC36940BBC0 libstagefright.so
,W/google-breakpad(10286): M AE92C000 00000000 00017000 52DC9A344B2F37EBE6D980F419DD79800 libmtp.so
,W/google-breakpad(10286): M AE943000 00000000 0002C000 84F170F995DC0EAD4100002C63E26D090 libexif.so
,W/google-breakpad(10286): M AE96F000 00000000 0003E000 24984B90B04E5F6F6034503CCF81A3530 libmedia_jni.so
,W/google-breakpad(10286): M B0DD1000 00000000 00003000 41762ACB6188785E5EF211BB8F33F0580 memtrack.msm8226.so
,W/google-breakpad(10286): M B24D7000 00000000 00038000 FE4EB304B0639D600DFB5871136831C50 libjavacore.so
,W/google-breakpad(10286): M B254C000 00000000 0000B000 D2AB7418CCD8D2EBF766A47707CC1E530 libjhead.so
,W/google-breakpad(10286): M B256D000 00000000 00003000 8FF5949AE957364C270D0F448DAD4FE20 libjnigraphics.so
,W/google-breakpad(10286): M B2570000 00000000 00008000 F2B1298EE4C6EA0900CDACD17FB5C16B0 libcompiler_rt.so
,W/google-breakpad(10286): M B2578000 00000000 00004000 EB49C798524706CBF3372BB9DFBB92C20 libadreno_utils.so
W/google-breakpad(10286): M B4468000 00000000 00004000 F007D0E8B4B1447628068777E701EBBC0 libwebviewchromium_plat_support.so
W/google-breakpad(10286): M B4E73000 00000000 00009000 CF0326786BDECFB45A519C7005E851000 libbacktrace_libc++.so
W/google-breakpad(10286): M B4E7D000 00000000 0030F000 3DD3B70782F1361DED6013B85580C7EC0 libart.so
,W/google-breakpad(10286): M B51AF000 00000000 00004000 3CBDF0DE27B9554508AD60FDC96CBC620 libusbhost.so
W/google-breakpad(10286): M B51B3000 00000000 00041000 CE3E76CDA5E80C14EBD7C841E8D84F650 libssl.so
,W/google-breakpad(10286): M B51F4000 00000000 000FF000 8DBA0B7AE9FE1796BB2D267C8FA450650 libsqlite.so
,W/google-breakpad(10286): M B52F3000 00000000 0000F000 F954BA248E12C9AF32F54434F977FEF80 libsoundtrigger.so
W/google-breakpad(10286): M B5302000 00000000 0000F000 113A72FAE76EEFA7090E693F3549A3010 libselinux.so
,W/google-breakpad(10286): M B5311000 00000000 00004000 4E6C8C876BA563C3C4B0B3BA562093920 libprocessgroup.so
,W/google-breakpad(10286): M B5315000 00000000 0045B000 83C5B450634DDB5C4FC41CA61A35B3740 libpdfium.so
W/google-breakpad(10286): M B5775000 00000000 00004000 417CB14A7DB4E6A1B990FD8AC53764470 libnetd_client.so
W/google-breakpad(10286): M B5779000 00000000 00007000 F2C71E0D275A5D80BD35EE70ECFD70FD0 libnativehelper.so
W/google-breakpad(10286): M B5780000 00000000 00004000 1DD26A12D05B7F3D88CEF118B5CB04390 libnativebridge.so
,W/google-breakpad(10286): M B5784000 00000000 0000C000 31B45FE1FA6CC789F945332C6FECF9750 libminikin.so
,W/google-breakpad(10286): M B5790000 00000000 00003000 CCA8BE0D07D24523C8D02FEE5F724EA70 libmemtrack.so
,W/google-breakpad(10286): M B5793000 00000000 00015000 60A6E0B998632198B80EB0941121CD710 libstagefright_foundation.so
,W/google-breakpad(10286): M B57A8000 00000000 00051000 6E42AB0836D73C21533C08A98EE7B24C0 libsonivox.so
,W/google-breakpad(10286): M B57FE000 00000000 0000F000 E43E7FA869E4BCDAA3CC9601DF5A6A520 libcommon_time_client.so
,W/google-breakpad(10286): M B580D000 00000000 0000A000 6B713D36804D7F05D55318F859E1E1400 libnbaio.so
,W/google-breakpad(10286): M B5817000 00000000 0009B000 64619D291C1C60AA9DC086C283338A6D0 libmedia.so
,W/google-breakpad(10286): M B58B2000 00000000 0003D000 C38209953DA7DBBD456E5C2897B2FC150 libinputflinger.so
,W/google-breakpad(10286): M B58EF000 00000000 0001B000 74F168449838583071D83A6436D107740 libinput.so
,W/google-breakpad(10286): M B590A000 00000000 0000D000 5B082E821F342B59EB7E98B4A5A1B7D10 libimg_utils.so
,W/google-breakpad(10286): M B5917000 00000000 00032000 89A4F06810290EEAF309C12642A3ECFA0 libjpeg.so
,W/google-breakpad(10286): M B594A000 00000000 00231000 70FC6B965940F66B510A2E7DDA905A3F0 libskia.so
,W/google-breakpad(10286): M B5B80000 00000000 0001D000 FC19A9DAC51914495386BF19318E22EA0 libRScpp.so
,W/google-breakpad(10286): M B5B9D000 00000000 00028000 6E7220E587365DE4D76F850674158CB90 libpng.so
,W/google-breakpad(10286): M B5BC5000 00000000 0005A000 659F1470013A04F7702E4BAB65F034E70 libft2.so
,W/google-breakpad(10286): M B5C1F000 00000000 0003D000 44717FC6883CFF24CB7D5AB323BA6DB00 libbcinfo.so
,W/google-breakpad(10286): M B5C5C000 00000000 00023000 53CBA510148C055D91FC2FE6ABEB7AF80 libbcc.so
W/google-breakpad(10286): M B5C9F000 00000000 00094000 D27BE45ECDACFCE9AD319AFCC4384FDE0 libc++.so
,W/google-breakpad(10286): M B5D35000 00000000 00938000 309278A31B6D547CF87ABF9850B977170 libLLVM.so
,W/google-breakpad(10286): M B6674000 00000000 0003A000 D276EA3D64313AC3429FA50C13E048AD0 libRS.so
,W/google-breakpad(10286): M B66AE000 00000000 0004C000 676E6078730EA64301EE765F510315BD0 libhwui.so
,W/google-breakpad(10286): M B66FA000 00000000 00110000 1B1FD653750DE88B86D7E83095EE37160 libicuuc.so
,W/google-breakpad(10286): M B680E000 00000000 00006000 F4F99E4A6E63BF8C8005D96B2BAC8CEB0 libgabi++.so
,W/google-breakpad(10286): M B6814000 00000000 00167000 237F53C12084A7F42405B410FDE8B4020 libicui18n.so
,W/google-breakpad(10286): M B697B000 00000000 00048000 AC5AE16EC01F4362C8E63DF66565090D0 libharfbuzz_ng.so
,W/google-breakpad(10286): M B69C3000 00000000 00005000 4E8926B7F3B40489DDA2954EC97B8D220 libwpa_client.so
W/google-breakpad(10286): M B69C8000 00000000 00007000 ADCE932B3390EC21752A7A6149AA6DA60 libnetutils.so
,W/google-breakpad(10286): M B69CF000 00000000 00007000 F71457D34715CA9491C2A031B5F4D2DE0 libhardware_legacy.so
,W/google-breakpad(10286): M B69D7000 00000000 00017000 B98E65710C415C83E972EBDC1EB52AC00 libexpat.so
,W/google-breakpad(10286): M B69EE000 00000000 0015E000 00A487ECBEDBE59A4AF1305D7B4C982D0 libcrypto.so
W/google-breakpad(10286): M B6B4F000 00000000 00003000 914425D16565257955F7E1574360B71F0 libhardware.so
,W/google-breakpad(10286): M B6B52000 00000000 0000C000 4C6A07EB894125D1DB41E0E4195358730 libui.so
,W/google-breakpad(10286): M B6B5E000 00000000 00003000 2D9083CB8C22C02E1412DA13B1CA43AE0 libsync.so
,W/google-breakpad(10286): M B6B61000 00000000 0004F000 559E784386AC5E53A9D4D7F9916AA7F90 libgui.so
,W/google-breakpad(10286): M B6BB0000 00000000 00008000 D86968E73262725A4BA707DF821962E60 libcamera_metadata.so
,W/google-breakpad(10286): M B6BB8000 00000000 0003A000 116F763683FB0C7DD45AACC16324410B0 libcamera_client.so
,W/google-breakpad(10286): M B6BF2000 00000000 00006000 AC1D054A26491BE96E8BCCB1E5F2926F0 libspeexresampler.so
,W/google-breakpad(10286): M B6BF8000 00000000 00006000 C7B066E606462D658A4D7A9F2EAA61D80 libaudioutils.so
,W/google-breakpad(10286): M B6BFE000 00000000 0001A000 03AD92B0BEDAA751C0016E97AE374CAE0 libz.so
W/google-breakpad(10286): M B6C18000 00000000 00030000 AC6C388A36224541CD74B35818111B760 libbinder.so
,W/google-breakpad(10286): M B6C48000 00000000 00028000 4369ED7B14428F57EF37081E2AA076720 libandroidfw.so
W/google-breakpad(10286): M B6C70000 00000000 0000B000 E2F67EE50006FD0ED1482E1463C5CCFF0 libGLESv2.so
,W/google-breakpad(10286): M B6C7B000 00000000 00007000 EFE6AB19F4060BCECF8CF0E68958C2F60 libGLESv1_CM.so
W/google-breakpad(10286): M B6C82000 00000000 00004000 C91EAF69D18F0D499BD58532BBA173690 libETC1.so
,W/google-breakpad(10286): M B6C86000 00000000 00004000 7AE0C00FAEDEA3E81109CC784D49A6960 libunwind-ptrace.so
W/google-breakpad(10286): M B6C8A000 00000000 0000E000 EF89B10946BDF6079AAF789F56192FDA0 libunwind.so
W/google-breakpad(10286): M B6CDE000 00000000 00007000 3874D35A672DF92604963290963F44990 libgccdemangle.so
,W/google-breakpad(10286): M B6CE7000 00000000 00008000 45B51BF91D330E793C9142C2617D7A8E0 libbacktrace.so
W/google-breakpad(10286): M B6CF0000 00000000 00018000 4929CACB90B1756D54AABC210956A8720 libutils.so
W/google-breakpad(10286): M B6D08000 00000000 0003B000 2FE003E5119C67BABE1A9FAB459A5A5D0 libstlport.so
,W/google-breakpad(10286): M B6D43000 00000000 0000D000 89C05C3E2CA4C0CEE048FF2C8DBE53BD0 libcutils.so
,W/google-breakpad(10286): M B6D51000 00000000 00071000 A12BAF7D82BE28EC681730452D351E880 libGLES_trace.so
,W/google-breakpad(10286): M B6DC2000 00000000 00068000 924D4C5446BF1132A902C15519E5C4FD0 libEGL.so
,W/google-breakpad(10286): M B6E2D000 00000000 000DD000 ECF593F4D6A605B04E7323D33A3802CE0 libandroid_runtime.so
,W/google-breakpad(10286): M B6F0A000 00000000 00004000 DFCD7772F3A5BD1E84A50C4DBFDE6F570 libstdc++.so
W/google-breakpad(10286): M B6F0E000 00000000 00019000 75E20BCCFF30FFEC047C70BDA7F7144B0 libm.so
W/google-breakpad(10286): M B6F28000 00000000 00007000 8CAFD8BD12AF3E16BE6445415809E8D90 liblog.so
,W/google-breakpad(10286): M B6F30000 00000000 0005A000 11CB106704827A02E2DDB8936FB8C13B0 libc.so
W/google-breakpad(10286): M B6F94000 00000000 00003000 D773C773634B82249E887ECBC5D28C900 libsigchain.so
W/google-breakpad(10286): M B6F9C000 00000000 0000F000 F27F6D6C09C0D8A16DDA00721CEC963C0 linker
,W/google-breakpad(10286): -----END BREAKPAD MICRODUMP-----
,W/google-breakpad( 6583): ### ### ### ### ### ### ### ### ### ### ### ### ###
,W/google-breakpad( 6583): Chrome build fingerprint:
,W/google-breakpad( 6583): 0.0.1
W/google-breakpad( 6583): 18
W/google-breakpad( 6583): 873fd9bc-5759-4679-9dc5-2d671bd0c1b7
W/google-breakpad( 6583): ### ### ### ### ### ### ### ### ### ### ### ### ###
,E/chromium( 6583): ### WebView Version 44.0.2403.90 (code 240309000)
F/libc    ( 6583): Fatal signal 11 (SIGSEGV), code 2, fault addr 0xa6117ff0 in tid 8323 (Thread-789)
,I/DEBUG   (  310): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
I/DEBUG   (  310): Build fingerprint: 'motorola/thea_reteu/thea:5.0.2/LXB22.46-28/27:user/release-keys'
I/DEBUG   (  310): Revision: 'p300'
,I/DEBUG   (  310): ABI: 'arm'
I/DEBUG   (  310): pid: 6583, tid: 8323, name: Thread-789  >>> com.test.thalitest <<<
I/DEBUG   (  310): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xa6117ff0
,I/DEBUG   (  310):     r0 6f407168  r1 6fe7a5e0  r2 2323da90  r3 234671c0
I/DEBUG   (  310):     r4 000000c4  r5 6f407168  r6 6fe7a5e0  r7 234671c0
I/DEBUG   (  310):     r8 6fe7a638  r9 b8cc6cb0  sl 2323da90  fp a6219870
I/DEBUG   (  310):     ip a6117ff0  sp a6119ff0  lr 71b22a6d  pc 71b22a3c  cpsr a00f0030
I/DEBUG   (  310): 
I/DEBUG   (  310): backtrace:
I/DEBUG   (  310):     #00 pc 00091a3c  /system/framework/arm/boot.oat
I/DEBUG   (  310):     #01 pc 00091a6b  /system/framework/arm/boot.oat
,I/DEBUG   (  310): 
I/DEBUG   (  310): Tombstone written to: /data/tombstones/tombstone_03
,I/BootReceiver(  883): Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
,I/WindowState(  883): WIN DEATH: Window{8061db2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  883): Client connection lost with reason: 4
,W/bt-btif ( 2413): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
E/bt-btif ( 2413): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,I/Zygote  (  328): Process 6583 exited due to signal (11)
,I/ActivityManager(  883): Process com.test.thalitest (pid 6583) has died
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310170, SEQNUM=4716, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-39, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2413): onReceive
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=10297 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e3783f5:true
,I/BTConnectionReceiver(10297): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=10331 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/BluetoothClassifier(10297): Bluetooth Device Name: S5-1
,I/ActivityManager(  883): Killing 10153:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_10153/cgroup.procs: No such file or directory
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ActivityManager(  883): Waited long enough for: ServiceRecord{106a0cdf u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/UsageStatsService(  883): User[0] Flushing usage stats to disk
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=269, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311270, SEQNUM=4725, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-14122, POWER_SUPPLY_CHARGE_COUNTER=-80, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311257, SEQNUM=4726, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11919, POWER_SUPPLY_CHARGE_COUNTER=-182, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,I/MDMCTBK (  311): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  311): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  311): checkDefaultInst, current pid is = 311
I/MDMCTBK (  311): checkDefaultInst, pid match
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  311): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  311): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2413): Disconnected process message: 10, size: 0
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,W/bt-btif ( 2413): info:x10
,D/        ( 2413): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2413): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2413): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2413): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  883): send {1e8d2863, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  883): send {5c9c96d, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  883): done {5c9c96d, *walarm*:android.content.syncmanager.SYNC_ALARM} [10ms]
,V/AlarmManager(  883): done {1e8d2863, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=10381 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager(10381): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=10406 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9681:com.google.android.gms/u0a16 (adj 15): empty #7
,I/ContactLocale(10406): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/WifiService(  883): Client connection lost with reason: 4
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_9681/cgroup.procs: No such file or directory
,I/art     (  883): Explicit concurrent mark sweep GC freed 19699(1129KB) AllocSpace objects, 14(3MB) LOS objects, 33% free, 20MB/30MB, paused 2.997ms total 133.913ms
,I/ActivityManager(  883): Killing 10212:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10055/pid_10212/cgroup.procs: No such file or directory
,V/AlarmManager(  883): send {2de4ff48, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,I/ActivityManager(  883): Start proc com.google.android.gms for broadcast com.google.android.gms/.checkin.EventLogService$Receiver: pid=10432 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
V/AlarmManager(  883): send {1990f280, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,W/ResourcesManager(10432): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10432): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex(10432): VM with version 2.1.0 has multidex support
I/MultiDex(10432): install
I/MultiDex(10432): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp (10432): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(10432): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (10432): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f880683: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10432): Installed default security provider GmsCore_OpenSSL
,V/AlarmManager(  883): done {2de4ff48, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [317ms]
,V/AlarmManager(  883): done {1990f280, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [323ms]
,D/WearableService( 1713): callingUid 10016, callindPid: 1713
,E/MDM     ( 1713): [151] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer(10432): Restart initialization of location
,D/AuthorizationBluetoothService( 1713): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (10432): Background sticky concurrent mark sweep GC freed 25480(1332KB) AllocSpace objects, 4(64KB) LOS objects, 9% free, 10MB/11MB, paused 9.265ms total 94.667ms
D/NativeLibraryUtils(10432): Install completed successfully. count=14 extracted=0
,I/art     (10432): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     (10432): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 1555): Explicit concurrent mark sweep GC freed 25529(1223KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 8MB/13MB, paused 765us total 59.379ms
,I/art     (10432): Background partial concurrent mark sweep GC freed 3614(388KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 10MB/17MB, paused 5.331ms total 46.044ms
,W/IcingInternalCorpora(10432): getNumBytesRead when not calculated.
,I/art     ( 1713): Explicit concurrent mark sweep GC freed 62903(3MB) AllocSpace objects, 23(368KB) LOS objects, 40% free, 13MB/22MB, paused 966us total 108.302ms
,E/DataBuffer( 1713): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1c7bf2be)
E/DataBuffer( 1713): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@21b06f1f)
E/DataBuffer( 1713): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2af4f26c)
E/DataBuffer( 1713): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@17b05035)
,E/DataBuffer( 1713): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@c807cca)
,W/GCoreFlp( 1713): No location to return for getLastLocation()
W/FusedLocationProvider( 1713): location=null
,I/EventLogService(10432): Aggregate from 1450446205597 (log), 1450444569326 (data)
,I/ActivityManager(  883): Killing 10256:com.android.settings/1000 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_1000/pid_10256/cgroup.procs: No such file or directory
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  883): send {5c9c96d, *walarm*:android.content.syncmanager.SYNC_ALARM}
V/AlarmManager(  883): done {5c9c96d, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  883): send {1e8d2863, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {1e3108e6, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  883): send {57cd342, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,I/ProcessStatsService(  883): Prepared write state in 18ms
,V/AlarmManager(  883): done {1e3108e6, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [65ms]
,I/ProcessStatsService(  883): Prepared write state in 7ms
,V/AlarmManager(  883): done {1e8d2863, *alarm*:android.intent.action.TIME_TICK} [91ms]
,V/AlarmManager(  883): done {57cd342, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [97ms]
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  883): Pruning old procstats: /data/system/procstats/state-2015-12-17-18-46-40.bin
,I/GoogleURLConnFactory( 1713): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1713): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/PhenotypeConfigurator( 1713): Server returned 404
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  883): send {1e8d2863, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  883): send {2c277031, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  883): done {1e8d2863, *alarm*:android.intent.action.TIME_TICK} [47ms]
,V/AlarmManager(  883): done {2c277031, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [96ms]
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime(10544): 
D/AndroidRuntime(10544): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10544): CheckJNI is OFF
D/AndroidRuntime(10544): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10390 user=-1: uninstall pkg
I/ActivityManager(  883):   Force finishing activity ActivityRecord{331c107f u0 com.test.thalitest/.MainActivity t3}
W/PackageSettings(  883): Skipping PackageSetting{fed9f19 com.example.hello/10377} due to missing metadata
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10390 user=0: pkg removed
I/art     ( 2958): Explicit concurrent mark sweep GC freed 20575(3MB) AllocSpace objects, 40(640KB) LOS objects, 40% free, 7MB/12MB, paused 772us total 44.721ms
I/Keyboard.Facilitator( 1424): resetDictionaries() : en_US
W/GeofencerStateMachine( 1713): Ignoring removeGeofence because network location is disabled.
W/ResourcesManager( 1555): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=10573 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1424): run()
D/VoicemailCleanupService(10406): Cleaning up data for package: com.test.thalitest
I/art     ( 1574): Explicit concurrent mark sweep GC freed 5393(328KB) AllocSpace objects, 7(353KB) LOS objects, 25% free, 13MB/17MB, paused 536us total 156.686ms
I/Decoder ( 1424): createOrResetDecoder
W/asset   (10573): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager(10573): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager(10573): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10573): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  883): Explicit concurrent mark sweep GC freed 24256(1454KB) AllocSpace objects, 6(185KB) LOS objects, 33% free, 20MB/30MB, paused 1.770ms total 219.583ms
I/art     (  883): WaitForGcToComplete blocked for 68.210ms for cause Explicit
I/ConfigService( 1713): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1424): run()
I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=10593 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  883): removeObsoleteFile: deleting file=3_task.xml
I/ActivityManager(  883): Killing 10297:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
I/Launcher( 1574): Deferring update until onResume
I/art     (  883): Explicit concurrent mark sweep GC freed 6567(338KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.079ms total 188.474ms
W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_10297/cgroup.procs: No such file or directory
I/Keyboard.Facilitator.MainLanguageModelLoader( 1424): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loading LM = user
W/ContextImpl(10593): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1424): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1424): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1424): run()
I/StatsUtilsManager( 1424): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1424): shouldRecordStats() = Too Soon
D/PackageBroadcastService(10432): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr(10432): Reading stored module config
D/AccountUtils(10432): Clearing selected account for com.test.thalitest
D/AndroidRuntime(10544): Shutting down VM
D/ChimeraCfgMgr(10432): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr(10432): Loading module APK com.google.android.play.games
I/LocationSettingsChecker(10432): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC(10432): App measurement is starting up, version: 8489
I/GMPM-SVC(10432): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/NetworkScheduler.SchedulerReceiver( 1713): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1713): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase(10432): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase(10432): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase(10432): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase(10432): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase(10432): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase(10432): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase(10432): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase(10432): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase(10432): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase(10432): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase(10432): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase(10432): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase(10432): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=10629 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
W/BaseAppContext(10432): Using Auth Proxy for data requests.
D/ChimeraCfgMgr(10432): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr(10432): Module APK com.google.android.play.games already loaded
E/BaseAppContext(10432): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext(10432): Using Auth Proxy for data requests.
W/Launcher( 1574): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2f490a72 new=com.google.android.velvet.VelvetApplication@2f490a72
I/Icing   (10432): Storage manager: low false usage 1.78MB avail 3.19GB capacity 4.85GB
I/ActivityManager(  883): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=10670 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
W/BaseAppContext(10432): Using Auth Proxy for data requests.
W/BaseAppContext(10432): Using Auth Proxy for data requests.
W/BaseAppContext(10432): Using Auth Proxy for data requests.
D/ConnectivityService(  883): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  883): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  883): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler(10432): CM callback handler got msg 524290
W/BaseAppContext(10432): Using Auth Proxy for data requests.
W/BaseAppContext(10432): Using Auth Proxy for data requests.
W/BaseAppContext(10432): Using Auth Proxy for data requests.
W/BaseAppContext(10432): Using Auth Proxy for data requests.
I/UpdateIcingCorporaServi(10629): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PeopleDatabaseHelper(10432): cleanUpNonGplusAccounts done.
W/DriveInitializer(10432): Awaiting to be initialized
W/DriveInitializer(10432): Background init thread started
I/Icing   (10432): doRemovePackageData com.test.thalitest
E/DocListDatabase(10432): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase(10432): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/DocListDatabase(10432): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase(10432): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase(10432): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase(10432): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase(10432): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase(10432): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase(10432): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase(10432): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/SQLiteLog(10432): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/DriveInitializer(10432): Background init thread ended
I/Process (10432): Sending signal. PID: 10432 SIG: 9
D/ConnectivityService(  883): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@6f9b679)
D/ConnectivityService(  883): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  883): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/GmsClient(10629): service died
E/AppDataSearchHelper(10629): Could not connect to AppDataSearch for onTableChanged, error 8
W/AppDataSearchHelper(10629): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi(10629): UpdateCorporaTask done [took 255 ms] updated apps [took 255 ms] 
I/ActivityManager(  883): Process com.google.android.gms (pid 10432) has died
W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  883): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
I/ActivityManager(  883): Killing 10331:com.google.android.partnersetup/u0a19 (adj 15): empty #7
I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0
W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_10331/cgroup.procs: No such file or directory

```
