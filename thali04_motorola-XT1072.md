#### Test 56151093f3290d6_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,V/AlarmManager(  880): send {21660367, *walarm*:com.google.android.intent.action.SEND_IDLE}
V/AlarmManager(  880): done {21660367, *walarm*:com.google.android.intent.action.SEND_IDLE} [14ms]
--------- beginning of main
D/AndroidRuntime( 6606): 
D/AndroidRuntime( 6606): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6606): CheckJNI is OFF
D/AndroidRuntime( 6606): Calling main entry com.android.commands.am.Am
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6625 uid=10452 gids={50452, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6606): Shutting down VM
V/ActivityManager(  880): Display changed displayId=0
E/global frequency( 2676): no tags to log
D/Checkin ( 2676): publish the event [tag = MOT_CHECKIN event name = LOG]
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/BSUtils ( 2676): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 55689(3MB) AllocSpace objects, 36(1232KB) LOS objects, 39% free, 7MB/12MB, paused 968us total 56.253ms
,D/BSUtils ( 2676): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2676): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2676): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2676): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2676): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/art     (  880): Explicit concurrent mark sweep GC freed 40018(1932KB) AllocSpace objects, 2(213KB) LOS objects, 33% free, 20MB/30MB, paused 1.474ms total 151.492ms
,D/BSUtils ( 2676): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 4257(177KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 860us total 27.435ms
,D/BSUtils ( 2676): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/BSUtils ( 2676): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2676): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2676): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2676): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2676): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2676): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2676): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/WebViewFactory( 6625): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/global frequency( 2676): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2676): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/LibraryLoader( 6625): Time to load native libraries: 12 ms (timestamps 6614-6626)
I/LibraryLoader( 6625): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6625): Binding Chromium to main looper Looper (main, tid 1) {3181e39}
I/LibraryLoader( 6625): Expected native library version number "",actual native library version number ""
,I/chromium( 6625): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/ActivityManager(  880): Activity pause timeout for ActivityRecord{16230514 u0 com.test.thalitest/.MainActivity t6}
,I/BrowserStartupController( 6625): Initializing chromium process, singleProcess=true
,W/art     ( 6625): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6625): ApplicationContext is null in ApplicationStatus
,W/chromium( 6625): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6625): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6625): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6625): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6625): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6625): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6625): Local Branch: 
I/Adreno-EGL( 6625): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6625): Local Patches: NONE
I/Adreno-EGL( 6625): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@349d09d6:true
,W/art     ( 6625): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6625): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6625): CordovaWebView is running on device made by: motorola
,W/art     ( 6625): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6625): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6625): Render dirty regions requested: true
,D/Atlas   ( 6625): Validating map...
,W/chromium( 6625): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6625): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6625): Enabling debug mode 0
,I/Keyboard.Facilitator( 1416): onFinishInput()
,I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,1236
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +1s86ms (total +1s236ms)
,W/IInputConnectionWrapper( 6625): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6625): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6625): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6625): Cannot call determinedVisibility() - never saw a connection for the pid: 6625
,D/JsMessageQueue( 6625): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6625): JniHelper::setJavaVM(0xb89c7310), pthread_self() = -1193967136
D/JX-Cordova( 6625): jxcore cordova android initializing
,W/jxcore-log( 6625): Initializing JXcore engine
W/jxcore-log( 6625): JXcore engine is ready
,W/jxcore-log( 6625): Starting JXcore engine
,W/.test.thalitest( 6625): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10452 path="socket:[7374]" dev="sockfs" ino=7374 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6625): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10452 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6625): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10452 path="socket:[6672]" dev="sockfs" ino=6672 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6625): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10452 path="socket:[30355]" dev="sockfs" ino=30355 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6625): Platform android
W/jxcore-log( 6625): 
,W/jxcore-log( 6625): Process ARCH arm
W/jxcore-log( 6625): 
,I/jxcore-log( 6625): JXcore Cordova bridge is ready!
I/jxcore-log( 6625): 
,W/jxcore-log( 6625): JXcore engine is started
,I/chromium( 6625): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6625): Toggling radios to true
I/jxcore-log( 6625): 
,D/BluetoothAdapter( 6625): enable(): BT is already enabled..!
,D/WifiService(  880): New client listening to asynchronous messages
,D/WifiService(  880): setWifiEnabled: true pid=6625, uid=10452
,E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6625): Radios toggled
I/jxcore-log( 6625): 
,I/jxcore-log( 6625): My device name is: motorola-XT1072
I/jxcore-log( 6625): 
,I/wpa_supplicant( 1411): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  308): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  308):  STA Disconnected !!
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): get_property_value, Enter
I/MDMCTBK (  308): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  308): get_property_value, Exit
I/MDMCTBK (  308): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  308): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  308): set_property_value, Enter
I/MDMCTBK (  308): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  469): NL - Read 1004 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
D/TCMD    (  469): Listening for incoming client connection request
D/TCMD    (  469): NL - Read 68 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
D/TCMD    (  469): Listening for incoming client connection request
D/TCMD    (  469): NL - Read 68 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
D/TCMD    (  469): Listening for incoming client connection request
I/MDMCTBK (  308): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  308): set_property_value, Exit
I/MDMCTBK (  308): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  308): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  308): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  308): set_property_value, Enter
I/MDMCTBK (  308): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/Tethering(  880): InitialState.processMessage what=4
I/MDMCTBK (  308): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  308): set_property_value, Exit
E/MDMCTBK (  308): MdmCutbackHndler,Airplane Mode Enabled !! =1
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
D/Tethering(  880):  0
D/Tethering(  880): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 1411): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  308): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  308): Event received = CTRL-EVENT-REGDOM-CHANGE
,I/wpa_supplicant( 1411): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  308): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  880): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  880): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  306): Clearing all IP addresses on wlan0
D/TCMD    (  469): NL - Read 60 bytes from update socket.
D/TCMD    (  469): NL - ignore NL message, type = 21
D/TCMD    (  469): Listening for incoming client connection request
,V/NativeCrypto( 1738): Read error: ssl=0xb8cbe820: I/O error during system call, Connection timed out
,V/NativeCrypto( 1738): SSL shutdown failed: ssl=0xb8cbe820: I/O error during system call, Broken pipe
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/WifiMetrics(  880): connected time updated 130379
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  880): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-2ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/ActivityManager(  880): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6711 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  880): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/Nat464Xlat(  880): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  880): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Disconnected - quitting
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  880): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524292
,I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/ConnectivityService(  880): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  880): Start Disconnecting Watchdog 1
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  308): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1411): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  308): Event received = CTRL-EVENT-SCAN-STARTED 
,E/WifiStateMachine(  880): ConnectModeState: Network connection lost 
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  880): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  306): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  880): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  880): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/ResourcesManager( 6711): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6738 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6360:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10057/pid_6360/cgroup.procs: No such file or directory
,W/ResourcesManager( 6738): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  469): NL - Read 56 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
D/TCMD    (  469): Listening for incoming client connection request
,D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  308): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  308): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  308): Event received = WPS-AP-AVAILABLE 
,E/WifiStateMachine(  880): [1,452,862,974,784 ms] noteScanEnd no scan source
I/wpa_supplicant( 1411): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  880): didn't find BSSID Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1411): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  308): Event received = Trying to associate with
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  308): Event received = CTRL-EVENT-STATE-CHANGE 
,E/WifiStateMachine(  880): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3b995edd sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/TCMD    (  469): NL - Read 312 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
D/TCMD    (  469): Listening for incoming client connection request
D/TCMD    (  469): NL - Read 192 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
D/TCMD    (  469): Listening for incoming client connection request
D/TCMD    (  469): NL - Read 68 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
D/TCMD    (  469): Listening for incoming client connection request
D/TCMD    (  469): NL - Read 1004 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
D/TCMD    (  469): Listening for incoming client connection request
,I/wpa_supplicant( 1411): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  469): NL - Read 80 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
D/TCMD    (  469): Listening for incoming client connection request
D/TCMD    (  469): NL - Read 80 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
D/TCMD    (  469): Listening for incoming client connection request
D/TCMD    (  469): NL - Read 68 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
D/TCMD    (  469): Listening for incoming client connection request
,D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  308): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  308): Event received = Associated with c0:ff:d4
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  308): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  880): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  880): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  880): ApnList is empty for checkDunConfigured()
D/Tethering(  880):  upstream interface types: 
D/Tethering(  880):  0
D/Tethering(  880):  1
D/Tethering(  880):  5
D/Tethering(  880):  7
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/Tethering(  880): sendTetherStateChangedBroadcast 1, 0, 0
,D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  308): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1411): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1411): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  469): NL - Read 1004 bytes from update socket.
D/TCMD    (  469): NL - message type is RTM_NEWLINK
D/TCMD    (  469): Listening for incoming client connection request
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  308): Event received = WPA: Key negotiation com
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
,D/MDMCTBK (  308): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  308):  STA Connected !!
E/MDMCTBK (  308): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
,D/MDMCTBK (  308): get_freq !!, resp=2412
I/MDMCTBK (  308): get_freq !!, Strip data
I/MDMCTBK (  308): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): get_property_value, Enter
I/MDMCTBK (  308): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  308): get_property_value, Exit
I/MDMCTBK (  308): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  308): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  308): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  308): set_property_value, Enter
I/MDMCTBK (  308): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  308): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  308): set_property_value, Exit
I/MDMCTBK (  308): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  308): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  308): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): get_property_value, Enter
I/MDMCTBK (  308): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  308): get_property_value, Exit
I/MDMCTBK (  308): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1223119456
I/MDMCTBK (  308): return from set_get_from_wpa_supplicant
I/MDMCTBK (  308): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  308): set_property_value, Enter
I/MDMCTBK (  308): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  308): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  308): set_property_value, Exit
E/MDMCTBK (  308): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  308): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  308): wifi_set_tx_pwr: SETTXPOWER = 18
,E/MDMCTBK (  308): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  308): , reply_len: 3, ret: 0
E/MDMCTBK (  308): MdmCutbackHndler, resp=OK
E/MDMCTBK (  308): 
D/MDMCTBK (  308): wifi_set_tx_pwr: Exit
,E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  880): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  880): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  880): Network connection established
E/WifiStateMachine(  880): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  880): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  880): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): L2ConnectedState "NG700" nid=0
D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  880): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  880): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  880): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  880): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  306): Setting iface cfg
E/WifiStateMachine(  880): Start Dhcp Watchdog 2
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend false
,E/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  880): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1411): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a73fe8e target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a73fe8e target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel_SMS( 6738): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6738): MmsConfig.loadMmsSettings
I/Babel_SMS( 6738): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6738): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6738): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6738): MmsConfig.loadFromResources
,E/Babel_SMS( 6738): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6738): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6738): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6738): startup - clean
,I/Babel   ( 6738): deleted: false for 0
,W/VideoCapabilities( 6738): Unrecognized profile 2130706433 for video/avc
,E/DHCPCD  ( 6777): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6777): version 5.5.6 starting
,E/DHCPCD  ( 6777): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6777): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6777): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/AudioCapabilities( 6738): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6738): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6738): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6738): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6738): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6738): Unrecognized profile 2130706433 for video/avc
,D/DHCPCD  ( 6777): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6777): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6777): wlan0: sending REQUEST (xid 0x9c095fcc), next in 3.46 seconds
W/VideoCapabilities( 6738): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  880): Killing 6398:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6398/cgroup.procs: No such file or directory
,I/vclib   ( 6738): onServiceConnected
,W/Babel   ( 6738): Attempted to change video mute state without an active call.
,I/DHCPCD  ( 6777): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6777): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6777): wlan0: adding IP address 192.168.1.123/24
D/TCMD    (  469): NL - Read 60 bytes from update socket.
D/DHCPCD  ( 6777): wlan0: adding route to 192.168.1.0/24
D/TCMD    (  469): NL - ignore NL message, type = 20
D/TCMD    (  469): Listening for incoming client connection request
D/DHCPCD  ( 6777): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6777): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/DHCPCD  ( 6777): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  880): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  880): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  880): do suspend true
,D/WifiP2pService(  880): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  880): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  880): WifiStateMachine DHCP successful
E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  880): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  880): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  880): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  880): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  880): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  880): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService(  880): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  880): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  880): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  880): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  880): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  880): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880):    accepting network in place of null
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  880): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityService(  880): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/ModemStatsDSDetect( 1533): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=0
E/WifiStateMachine(  880): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/SBar.MotoNetworkCtrlr( 1290): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/Checkin (  880): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/Tethering(  880): MasterInitialState.processMessage what=3
,D/PollingManager( 2676): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2676): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2676): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2676): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6834 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 13:02:57 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452862977491], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452862977465]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Validated
D/ConnectivityService(  880): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1478): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1533): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1290): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1533): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1533): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1533): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1290): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/PollingManager( 2676): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2676): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/PollingManager( 2676): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2676): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
I/SBar.MotoNetworkCtrlr( 1290): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/PollingManager( 2676): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2676): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
I/SBar.MotoNetworkCtrlr( 1290): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/OtaApp  ( 2676): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2676): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/CCE     ( 2676): Registering with Alarm Manager to restart CCE
D/CCE     ( 2676): Registering with Alarm Manager to restart CCE
D/CCE     ( 2676): Registering with Alarm Manager to restart CCE
D/OtaApp  ( 2676): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2676): [debug] > CusSM.onRadioDown
,I/MusicStore( 6834): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6834): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6834): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6834): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6834): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6834): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6834): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6834): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6834): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11e48f25: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6834): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6834): GMSCore installation verified
,I/ConfigStore( 6834): Config Database version: 1
,I/MediaRouter( 6834): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6834): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6834): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6834): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6866 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6834): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6834): Using platform SSLCertificateSocketFactory
,I/art     (  880): Explicit concurrent mark sweep GC freed 44980(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.742ms total 125.494ms
,I/ActivityManager(  880): Killing 6198:android.process.acore/u0a7 (adj 15): empty #7
,V/Mms     ( 6866): mnc/mcc: 
V/Mms     ( 6866): tag: int value: recipientLimit - 20
,V/Mms     ( 6866): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6866): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6866): tag: int value: maxSubjectLength - 80
V/Mms     ( 6866): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6866): tag: bool value: enableGroupMms - false
V/Mms     ( 6866):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/ConnectivityService(  880): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_6198/cgroup.procs: No such file or directory
,W/ResourcesManager( 6866): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6893 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6276:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6893): Register our PhoneStateListener
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_6276/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6893): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6893): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 6738:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6738/cgroup.procs: No such file or directory
,I/CheckinService( 6461): Checkin interval check for package: unspecified last checkin: 1452862891343 min interval config: 0 actual interval: 87715
,I/CheckinService( 6461): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6461): SYNC; picasa accounts
,I/CheckinService( 6461): Checking schedule, now: 1452862979089 next: 1452862921307
I/CheckinService( 6461): active receiver: enabled
,D/NetworkLogImpl( 6461): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6461): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/CheckinService( 6461): Preparing to send checkin request
,I/iu.UploadsManager( 6461): num queued entries: 0
I/iu.UploadsManager( 6461): num updated entries: 0
I/iu.SyncManager( 6461): NEXT; no task
,I/EventLogService( 6461): Accumulating logs since 1452862886521
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6922 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6461): Checkin reason type: 8 attempt count: 1
,D/WifiService(  880): New client listening to asynchronous messages
,E/ActivityThread( 6461): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/chromium( 6625): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  880): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
D/ConnectivityService(  880): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  880): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  880): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,E/WifiStateMachine(  880): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524295
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6949 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6966 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,W/ResourcesManager( 6949): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6966): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6966): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6966): VM with version 2.1.0 has multidex support
I/MultiDex( 6966): install
I/MultiDex( 6966): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6966): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6966): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6966): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d50c042: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6966): Installed default security provider GmsCore_OpenSSL
,I/Babel_SMS( 6949): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6949): MmsConfig.loadMmsSettings
I/Babel_SMS( 6949): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6949): MmsConfig.loadFromDatabase
,I/art     ( 6966): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6966): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/Babel_SMS( 6949): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6949): MmsConfig.loadFromResources
E/Babel_SMS( 6949): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6949): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6949): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6949): startup - clean
,D/NativeLibraryUtils( 6966): Install completed successfully. count=14 extracted=0
,I/Babel   ( 6949): deleted: false for 0
,D/WVCdm   (  311): Instantiating CDM.
,I/WVCdm   (  311): CdmEngine::OpenSession
I/WVCdm   (  311): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  311): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  311): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  311): Service_Initialize: starts!
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
E/QSEECOMAPI: (  311): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
E/QSEECOMAPI: (  311): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
,D/QSEECOMAPI: (  311): Loaded image: APP id = 3
D/DrmWidevineDash(  311): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  311): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa5000
E/DrmWidevineDash(  311): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa5000
,D/DrmWidevineDash(  311): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  311): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  311): OEMCrypto_OpenSession: starts! SID=0xb5577960
D/DrmWidevineDash(  311): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  311): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_GetRandom: starts! randomData=0xb898bdd8, dataLength=8
D/DrmWidevineDash(  311): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb88bd860, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  311): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  311): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  311): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  311): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: starts! deviceID=0xb8997788, idLength=0xbebed2b0
,D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  311): PrepareKeyRequest: nonce=1921443794
D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8978348
D/DrmWidevineDash(  311): message_length=1591, signature=0xb88d1070, signature_length=3200176788
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7005 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6949): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6949): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6949): Unsupported mime video/mpeg2
,D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  311): CdmEngine::CloseSession
D/DrmWidevineDash(  311): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  311): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  311): L3 Terminate.
D/DrmWidevineDash(  311): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  311): Service_Uninitialize: starts!
D/QSEECOMAPI: (  311): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  311): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  311): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_Terminate: ends! returns 0
,I/VideoCapabilities( 6949): Unsupported profile 4 for video/mp4v-es
,D/ConnectivityService(  880): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  880): MasterInitialState.processMessage what=3
D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/Central_PollingManager( 1478): now: 207198 ,futureTime: 86476076
D/Central_PollingManager( 1478): Polling alarm set to expire at: 86476076 Current Time: 207198
,I/NetworkMonitor( 6834): type=WIFI subType= reason=null isConnected=true
,D/PollingManager( 2676): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2676): now: 207205 ,futureTime: 9223372036854775807
D/PollingManager( 2676): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2676): now: 207205 ,futureTime: 9223372036854775807
D/PollingManager( 2676): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2676): now: 207206 ,futureTime: 9223372036854775807
D/OtaApp  ( 2676): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2676): [debug] > PollingManagerService, now: 207208 ,futureTime: 18087730
,W/VideoCapabilities( 6949): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6949): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6949): Unrecognized profile 2130706433 for video/avc
,D/OtaApp  ( 2676): [debug] > Polling alarm set to expire at: 18087730 Current Time: 207209
,W/VideoCapabilities( 6949): Unrecognized profile 2130706433 for video/avc
,D/MMApiProvisionService( 2676): isDeviceProvisioned: deviceId = 2072049230914535424
,I/vclib   ( 6949): onServiceConnected
W/Babel   ( 6949): Attempted to change video mute state without an active call.
,D/CCE     ( 2676): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2676): createDeviceIdOrLogin update_device
D/Checkin ( 2676): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2676): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2676): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2676): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2676): createDeviceIdOrLogin update_device
,D/Checkin ( 2676): publish the event [tag = MOT_CCE event name = LOG]
,I/WVCdm   (  311): CdmEngine::OpenSession
I/WVCdm   (  311): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  311): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/MMApiProvisionService( 2676): isDeviceProvisioned: deviceId = 2072049230914535424
,I/Babel   ( 6949): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 6711:com.motorola.context/u0a8 (adj 15): empty #7
,D/MMApiProvisionService( 2676): set mOutstandingReq to true.
I/ Nonce  ( 2676):  Nonce getNonce 
I/ Nonce  ( 2676):  Nonce Request 
I/ Nonce  ( 2676):  Nonce execute Request 
,D/MMApiWebService( 2676): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/DrmWidevineDash(  311): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  311): Service_Initialize: starts!
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
,E/QSEECOMAPI: (  311): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  311): App is not loaded in QSEE
E/QSEECOMAPI: (  311): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
,D/QSEECOMAPI: (  311): Loaded image: APP id = 3
,D/DrmWidevineDash(  311): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa5000
E/DrmWidevineDash(  311): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa5000
,D/DrmWidevineDash(  311): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  311): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  311): OEMCrypto_OpenSession: starts! SID=0xb5577960
,D/DrmWidevineDash(  311): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  311): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_GetRandom: starts! randomData=0xb898bfc8, dataLength=8
D/DrmWidevineDash(  311): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb88bd860, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  311): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  311): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  311): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  311): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: starts! deviceID=0xb89977c8, idLength=0xbebed2b0
,D/MMApiProvisionService( 2676): isDeviceProvisioned: deviceId = 2072049230914535424
,D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  311): PrepareKeyRequest: nonce=296995990
D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb88c5320
D/DrmWidevineDash(  311): message_length=1626, signature=0xb88d1070, signature_length=3200176788
,D/CCE     ( 2676): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2676): createDeviceIdOrLogin update_device
,D/Checkin ( 2676): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2676): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 2676): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2676): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2676): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/libprocessgroup(  880): failed to open /acct/uid_10008/pid_6711/cgroup.procs: No such file or directory
,D/OtaApp  ( 2676): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2676): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2676): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2676): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2676): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2676): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2676): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/art     ( 2676): Explicit concurrent mark sweep GC freed 13236(755KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 11MB/18MB, paused 1.135ms total 154.611ms
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7005): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7005): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7005): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7005): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7005): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7005):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7005):   adb logcat -s GAv4
,W/GAv4    ( 7005): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  311): CdmEngine::CloseSession
D/DrmWidevineDash(  311): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  311): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  311): L3 Terminate.
,D/DrmWidevineDash(  311): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  311): Service_Uninitialize: starts!
D/QSEECOMAPI: (  311): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  311): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  311): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_Terminate: ends! returns 0
,I/art     (  880): Explicit concurrent mark sweep GC freed 13798(681KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.583ms total 119.329ms
,W/GAv4    ( 7005): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7005): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/MMApiWebService( 2676): generating token using payload instead of using session token
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 3904(169KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 590us total 35.923ms
,D/ Nonce  ( 2676):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2676): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/Checkin ( 2676): publish the event [tag = MOT_CCE event name = LOG]
,I/dex2oat ( 7041): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/WebViewFactory( 7005): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7005): Time to load native libraries: 1 ms (timestamps 7944-7945)
,I/LibraryLoader( 7005): Expected native library version number "",actual native library version number ""
,I/dex2oat ( 7041): dex2oat took 136.065ms (threads: 4)
,V/WebViewChromiumFactoryProvider( 7005): Binding Chromium to main looper Looper (main, tid 1) {241dbdf2}
,I/LibraryLoader( 7005): Expected native library version number "",actual native library version number ""
,I/chromium( 7005): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/Adreno-EGL( 6966): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6966): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6966): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6966): Local Branch: 
I/Adreno-EGL( 6966): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6966): Local Patches: NONE
I/Adreno-EGL( 6966): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/BrowserStartupController( 7005): Initializing chromium process, singleProcess=true
,W/art     ( 7005): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7005): ApplicationContext is null in ApplicationStatus
,W/chromium( 7005): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7005): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7005): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7005): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7005): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7005): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7005): Local Branch: 
I/Adreno-EGL( 7005): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7005): Local Patches: NONE
I/Adreno-EGL( 7005): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7005): Requires BLUETOOTH permission
,I/NSApplication( 7005): Starting up...
,I/Adreno-EGL( 6966): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6966): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6966): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6966): Local Branch: 
I/Adreno-EGL( 6966): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6966): Local Patches: NONE
I/Adreno-EGL( 6966): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7081 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6834:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/art     (  324): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 22.324ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.821ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.705ms
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_6834/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6966): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6966): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6966): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6966): Local Branch: 
I/Adreno-EGL( 6966): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6966): Local Patches: NONE
I/Adreno-EGL( 6966): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7111 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6866:com.android.mms/u0a23 (adj 15): empty #7
,I/Adreno-EGL( 6966): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6966): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6966): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6966): Local Branch: 
I/Adreno-EGL( 6966): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6966): Local Patches: NONE
I/Adreno-EGL( 6966): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_6866/cgroup.procs: No such file or directory
,W/ResourcesManager( 7111): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 6461): Classify the device as Phone.
,I/ Nonce  ( 2676):  Nonce Reponse 
D/        ( 2676): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"903a25e9-750d-43b2-bbd0-43f3311401cd"}
,D/MMApiWSBase( 2676): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2676):  Nonce Handle Reponse 
D/MMApiProvisionService( 2676): mOutstandingReq set to false
,D/MMApiProvisionService( 2676):  pTime 1452855605507 sExp 172742 cTime 1452862982005 tTime 1453028347507
D/MMApiProvisionService( 2676):  No login Required 
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7140 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/CheckinTask( 6461): Sending checkin request (9515 bytes)
,I/ContactLocale( 7140): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7161 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6922:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ActivityManager(  880): Killing 6893:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_6922/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_6893/cgroup.procs: No such file or directory
,I/MusicStore( 7161): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7161): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,W/DataUsage( 2676): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2676): publish the event [tag = MOT_CCE event name = LOG]
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7161): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7161): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7161): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7161): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7161): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7161): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7161): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11e48f25: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7161): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7161): GMSCore installation verified
,I/ConfigStore( 7161): Config Database version: 1
,I/CheckinRequestBuilder( 6461): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6461): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 6426): Explicit concurrent mark sweep GC freed 1554(67KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 533us total 32.274ms
,I/MediaRouter( 7161): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7161): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7161): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7161): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7195 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7161): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7161): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  880): Killing 6949:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_6949/cgroup.procs: No such file or directory
,V/Mms     ( 7195): mnc/mcc: 
,V/Mms     ( 7195): tag: int value: recipientLimit - 20
,I/CheckinRequestBuilder( 6461): Classify the device as Phone.
V/Mms     ( 7195): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7195): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7195): tag: int value: maxSubjectLength - 80
V/Mms     ( 7195): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7195): tag: bool value: enableGroupMms - false
V/Mms     ( 7195):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/CheckinTask( 6461): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6461): Checking schedule, now: 1452862983057 next: 1453464120045
I/CheckinService( 6461): active receiver: disabled
,D/CheckinService( 6461): Recording last checkin time for package unspecified as 1452862983077
,I/art     (  880): Explicit concurrent mark sweep GC freed 7958(403KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.483ms total 121.138ms
,I/ActivityManager(  880): Killing 7081:com.android.chrome/u0a52 (adj 13): empty #7
,I/ActivityManager(  880): Killing 7005:com.google.android.apps.magazines/u0a81 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7081/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7005/cgroup.procs: No such file or directory
,W/ResourcesManager( 7195): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7236 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7140:android.process.acore/u0a7 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7140/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7236): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7236): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7236): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 7111:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7111/cgroup.procs: No such file or directory
,I/CheckinService( 6461): Checkin interval check for package: unspecified last checkin: 1452862983077 min interval config: 0 actual interval: 373
,I/CheckinService( 6461): Checking schedule, now: 1452862983463 next: 1452863013045
,I/CheckinService( 6461): active receiver: disabled
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7258 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7275 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7161:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7161/cgroup.procs: No such file or directory
,W/ResourcesManager( 7275): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7275): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7275): MmsConfig.loadMmsSettings
I/Babel_SMS( 7275): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7275): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7275): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7275): MmsConfig.loadFromResources
,E/Babel_SMS( 7275): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7275): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7275): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7275): startup - clean
,I/Babel   ( 7275): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7307 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7275): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7275): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7275): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7275): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7275): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7275): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7275): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7275): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7275): onServiceConnected
W/Babel   ( 7275): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7307): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7307): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7307):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7307):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7307): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7307): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7307): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7307): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7275): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 7195:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 7307): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7307): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7195/cgroup.procs: No such file or directory
,I/WebViewFactory( 7307): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7307): Time to load native libraries: 2 ms (timestamps 1693-1695)
,I/LibraryLoader( 7307): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7307): Binding Chromium to main looper Looper (main, tid 1) {241dbdf2}
,I/LibraryLoader( 7307): Expected native library version number "",actual native library version number ""
I/chromium( 7307): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7307): Initializing chromium process, singleProcess=true
,W/art     ( 7307): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7307): ApplicationContext is null in ApplicationStatus
,W/chromium( 7307): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7307): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7307): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7307): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7307): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7307): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7307): Local Branch: 
I/Adreno-EGL( 7307): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7307): Local Patches: NONE
I/Adreno-EGL( 7307): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7307): Requires BLUETOOTH permission
,I/NSApplication( 7307): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7378 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7236:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7236/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7401 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7258:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7258/cgroup.procs: No such file or directory
,W/ResourcesManager( 7401): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ProcessCpuTracker(  880): Skipping unknown process pid 7385
,W/ProcessCpuTracker(  880): Skipping unknown process pid 7386
W/ProcessCpuTracker(  880): Skipping unknown process pid 7418
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7424 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  324): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 23.196ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 19.918ms
,I/ActivityManager(  880): Killing 7307:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 21.691ms
,I/ContactLocale( 7424): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Killing 7275:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2676): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7307/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7275/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2676): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2676): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2676): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2676): onServiceConnected()
,D/GetNotificationsWS( 2676): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2676): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7457 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2676): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1738): callingUid 10016, callindPid: 1738
,D/LocationInitializer( 6461): Restart initialization of location
,D/AuthorizationBluetoothService( 1738): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1738): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7485 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1738): No location to return for getLastLocation()
,W/FusedLocationProvider( 1738): location=null
,I/MusicStore( 7485): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7485): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7485): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7485): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7485): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7485): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7485): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7485): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7485): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11e48f25: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7485): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7485): GMSCore installation verified
,I/ConfigStore( 7485): Config Database version: 1
,I/MediaRouter( 7485): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7485): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7485): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7485): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  880): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7519 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7485): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7485): Using platform SSLCertificateSocketFactory
,I/art     (  880): Explicit concurrent mark sweep GC freed 12249(598KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.019ms total 114.598ms
,I/ActivityManager(  880): Killing 7378:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7519): mnc/mcc: 
,V/Mms     ( 7519): tag: int value: recipientLimit - 20
V/Mms     ( 7519): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7519): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7519): tag: int value: maxSubjectLength - 80
,V/Mms     ( 7519): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7519): tag: bool value: enableGroupMms - false
V/Mms     ( 7519):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7378/cgroup.procs: No such file or directory
,W/ResourcesManager( 7519): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7545 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7401:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/PhoneMonitor( 7545): Register our PhoneStateListener
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7401/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7545): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7545): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  880): Killing 7424:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7424/cgroup.procs: No such file or directory
,I/CheckinService( 6461): Checkin interval check for package: unspecified last checkin: 1452862983077 min interval config: 0 actual interval: 4094
,I/CheckinService( 6461): Checkin interval check for package: unspecified last checkin: 1452862983077 min interval config: 0 actual interval: 4097
,I/CheckinService( 6461): Checking schedule, now: 1452862987193 next: 1452863013045
I/CheckinService( 6461): active receiver: disabled
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7565 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 6461): Checking schedule, now: 1452862987244 next: 1452863013045
I/CheckinService( 6461): active receiver: disabled
,W/ResourcesManager( 7565): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7565): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7565): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7565): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7565): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7565): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7565): MmsConfig.loadFromResources
,E/Babel_SMS( 7565): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7565): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7565): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7565): startup - clean
,I/Babel   ( 7565): deleted: false for 0
,I/ActivityManager(  880): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7596 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7565): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7565): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7565): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7565): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7565): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7565): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7565): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7565): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7565): onServiceConnected
W/Babel   ( 7565): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7596): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7596): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7596): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7596): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7596): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7596):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7596):   adb logcat -s GAv4
,W/GAv4    ( 7596): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7565): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  880): Killing 7485:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/GAv4    ( 7596): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7596): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  880): failed to open /acct/uid_10080/pid_7485/cgroup.procs: No such file or directory
,I/WebViewFactory( 7596): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7596): Time to load native libraries: 2 ms (timestamps 5006-5008)
I/LibraryLoader( 7596): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7596): Binding Chromium to main looper Looper (main, tid 1) {241dbdf2}
,I/LibraryLoader( 7596): Expected native library version number "",actual native library version number ""
,I/chromium( 7596): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7596): Initializing chromium process, singleProcess=true
,W/art     ( 7596): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7596): ApplicationContext is null in ApplicationStatus
,W/chromium( 7596): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7596): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7596): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7596): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7596): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7596): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7596): Local Branch: 
I/Adreno-EGL( 7596): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7596): Local Patches: NONE
I/Adreno-EGL( 7596): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7596): Requires BLUETOOTH permission
,I/NSApplication( 7596): Starting up...
,I/ActivityManager(  880): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7667 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 6966:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_6966/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7686 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7519:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10023/pid_7519/cgroup.procs: No such file or directory
,W/ResourcesManager( 7686): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  880): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7706 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7457:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ActivityManager(  880): Killing 7545:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/ContactLocale( 7706): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/EmailService.MarketingOptInSetter( 2676): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7457/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7545/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2676): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2676): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2676): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2676): onServiceConnected()
D/GetNotificationsWS( 2676): onServiceConnected(): Registered for remote service callbacks...
,I/PushService( 2676): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2676): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2676): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2676): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  880): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2676): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2676): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2676): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2676): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7731 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2676): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2676): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2676): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2676): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2676): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2676): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2676): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2676): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2676): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1416): onFinishInput()
W/IInputConnectionWrapper( 6625): showStatusIcon on inactive InputConnection
,D/PhoneMonitor( 7731): Register our PhoneStateListener
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1551): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/LaunchCheckinHandler(  880): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,228
,V/SetupWizard( 7731): Connected to Gservices successfully
I/ActivityManager(  880): Killing 7565:com.google.android.talk/u0a70 (adj 15): empty #7
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7565/cgroup.procs: No such file or directory
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/GCoreNlp( 1738): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1569): Deferring update until onResume
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1d74b13c
,D/GCM     ( 1738): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1738): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7764 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  324): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 241us total 21.131ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 20.350ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.223ms
,D/ChimeraCfgMgr( 6461): Reading stored module config
,D/ChimeraCfgMgr( 6461): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6461): Loading module APK com.google.android.play.games
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:33000 mC
,I/art     (  880): Explicit concurrent mark sweep GC freed 19348(965KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.471ms total 117.220ms
,D/GCM     ( 1738): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GamesSyncServiceMain( 6461): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 6461): Failed to execute periodic sync, missing client context - aborting
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7793 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7596:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10081/pid_7596/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7818 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7835 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  880): Killing 7667:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  880): Killing 7686:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10052/pid_7667/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7686/cgroup.procs: No such file or directory
,W/ResourcesManager( 7835): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7835): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7835): MmsConfig.loadMmsSettings
I/Babel_SMS( 7835): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7835): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7835): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7835): MmsConfig.loadFromResources
,E/Babel_SMS( 7835): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7835): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7835): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7835): startup - clean
,I/Babel   ( 7835): deleted: false for 0
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7868 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/asset   ( 7868): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7868): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7868): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7868): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
W/VideoCapabilities( 7835): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7835): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7835): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7835): Unsupported profile 4 for video/mp4v-es
,D/PackageBroadcastService( 6461): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
W/VideoCapabilities( 7835): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7835): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7835): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7835): Unrecognized profile 2130706433 for video/avc
,I/UpdateIcingCorporaServi( 7793): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2ad5e0fb new=com.google.android.velvet.VelvetApplication@2ad5e0fb
,I/PackageBroadcastService( 6461): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7899 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7835): onServiceConnected
,W/Babel   ( 7835): Attempted to change video mute state without an active call.
,I/Icing   ( 6461): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7899): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7835): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7835): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7793): UpdateCorporaTask done [took 309 ms] updated apps [took 309 ms] 
,I/ActivityManager(  880): Killing 7764:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,V/JNIHelp ( 7835): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7835): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7835): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  880): failed to open /acct/uid_10088/pid_7764/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7934 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 7731:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_7731/cgroup.procs: No such file or directory
,D/Finsky  ( 7934): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7934): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7934): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7934): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7934): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7934): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7934): Skipping gmscore version check
,D/Finsky  ( 7934): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/TaskPersister(  880): removeObsoleteFile: deleting file=5_task.xml
,D/Finsky  ( 7934): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Killing 7818:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_7818/cgroup.procs: No such file or directory
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/Icing   ( 6461): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6461): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6461): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 7868:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_7868/cgroup.procs: No such file or directory
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=294, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311422, SEQNUM=4484, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-474, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,I/ActivityManager(  880): Killing 7793:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_7793/cgroup.procs: No such file or directory
,I/CheckinService( 6461): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=281, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310629, SEQNUM=4488, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-499, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ClearcutLoggerApiImpl( 1738): disconnect managed GoogleApiClient
,V/AlarmManager(  880): send {f8a510a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {10316ccd, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  880): send {2e71fdd5, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  880): done {10316ccd, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [19ms]
,V/AlarmManager(  880): done {2e71fdd5, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [36ms]
,I/CheckinService( 6461): Checkin interval check for package: unspecified last checkin: 1452862983077 min interval config: 0 actual interval: 39606
,V/AlarmManager(  880): done {f8a510a, *alarm*:android.intent.action.TIME_TICK} [56ms]
,I/CheckinService( 6461): Checking schedule, now: 1452863022703 next: 1452863013045
I/CheckinService( 6461): active receiver: enabled
,I/CheckinService( 6461): Preparing to send checkin request
I/EventLogService( 6461): Accumulating logs since 1452862979368
,I/CheckinRequestBuilder( 6461): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6461): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  880): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8012 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8012): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8012): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8012): VM with version 2.1.0 has multidex support
I/MultiDex( 8012): install
I/MultiDex( 8012): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8012): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8012): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8012): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d50c042: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8012): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1738): callingUid 10016, callindPid: 1738
,E/MDM     ( 1738): [152] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1738): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6461): Restart initialization of location
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1738): No location to return for getLastLocation()
W/FusedLocationProvider( 1738): location=null
,I/art     ( 8012): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8012): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8012): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  311): Instantiating CDM.
,I/WVCdm   (  311): CdmEngine::OpenSession
,I/WVCdm   (  311): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  311): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  311): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  311): Service_Initialize: starts!
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
E/QSEECOMAPI: (  311): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
E/QSEECOMAPI: (  311): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
,D/QSEECOMAPI: (  311): Loaded image: APP id = 3
,D/DrmWidevineDash(  311): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
E/DrmWidevineDash(  311): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
,D/DrmWidevineDash(  311): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  311): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  311): OEMCrypto_OpenSession: starts! SID=0xb5577960
,D/DrmWidevineDash(  311): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  311): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_GetRandom: starts! randomData=0xb898c4e8, dataLength=8
D/DrmWidevineDash(  311): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb88bd860, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  311): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  311): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  311): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  311): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: starts! deviceID=0xb89977a8, idLength=0xbebed2b0
,D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  311): PrepareKeyRequest: nonce=3110101662
D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8978348
D/DrmWidevineDash(  311): message_length=1591, signature=0xb88d1070, signature_length=3200176788
,D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  311): CdmEngine::CloseSession
D/DrmWidevineDash(  311): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  311): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  311): L3 Terminate.
D/DrmWidevineDash(  311): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  311): Service_Uninitialize: starts!
D/QSEECOMAPI: (  311): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  311): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  311): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_Terminate: ends! returns 0
,I/WVCdm   (  311): CdmEngine::OpenSession
,I/WVCdm   (  311): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  311): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  311): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  311): Service_Initialize: starts!
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
E/QSEECOMAPI: (  311): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
E/QSEECOMAPI: (  311): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  311): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  311): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  311): App is not loaded in QSEE
,D/QSEECOMAPI: (  311): Loaded image: APP id = 3
,D/DrmWidevineDash(  311): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
E/DrmWidevineDash(  311): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
,D/DrmWidevineDash(  311): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  311): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  311): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  311): OEMCrypto_OpenSession: starts! SID=0xb5577960
D/DrmWidevineDash(  311): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  311): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_GetRandom: starts! randomData=0xb898c6c0, dataLength=8
,D/DrmWidevineDash(  311): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb88bd860, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  311): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  311): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  311): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  311): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  311): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: starts! deviceID=0xb89977c8, idLength=0xb138c730
,D/DrmWidevineDash(  311): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  311): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  311): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  311): hlos api version =  9
D/DrmWidevineDash(  311): tz api version =  8
D/DrmWidevineDash(  311): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  311): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  311): PrepareKeyRequest: nonce=2695080513
D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb88c5320
D/DrmWidevineDash(  311): message_length=1626, signature=0xb88d1070, signature_length=2973288212
,D/DrmWidevineDash(  311): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  311): CdmEngine::CloseSession
,D/DrmWidevineDash(  311): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  311): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  311): L3 Terminate.
D/DrmWidevineDash(  311): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  311): Service_Uninitialize: starts!
D/QSEECOMAPI: (  311): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  311): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  311): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  311): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8051): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8051): dex2oat took 66.012ms (threads: 4)
,I/Adreno-EGL( 8012): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8012): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8012): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8012): Local Branch: 
I/Adreno-EGL( 8012): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8012): Local Patches: NONE
I/Adreno-EGL( 8012): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8012): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8012): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8012): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8012): Local Branch: 
I/Adreno-EGL( 8012): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8012): Local Patches: NONE
I/Adreno-EGL( 8012): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8012): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8012): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8012): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8012): Local Branch: 
I/Adreno-EGL( 8012): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8012): Local Patches: NONE
I/Adreno-EGL( 8012): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8012): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8012): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8012): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8012): Local Branch: 
I/Adreno-EGL( 8012): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8012): Local Patches: NONE
I/Adreno-EGL( 8012): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6461): Classify the device as Phone.
,I/art     (  880): Explicit concurrent mark sweep GC freed 16393(824KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.787ms total 113.083ms
,I/CheckinTask( 6461): Sending checkin request (9521 bytes)
,I/CheckinRequestBuilder( 6461): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6461): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6461): Classify the device as Phone.
,I/CheckinTask( 6461): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6461): Checking schedule, now: 1452863026062 next: 1453464163053
I/CheckinService( 6461): active receiver: disabled
,D/CheckinService( 6461): Recording last checkin time for package unspecified as 1452863026078
,I/ActivityManager(  880): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8071 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8071): Register our PhoneStateListener
,V/SetupWizard( 8071): Connected to Gservices successfully
,D/GCM     ( 1738): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  880): Killing 7899:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  880): Killing 7706:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_7899/cgroup.procs: No such file or directory
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_7706/cgroup.procs: No such file or directory
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8094 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  880): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  880): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  880): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@201990a1
,I/GCoreNlp( 1738): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1569): Deferring update until onResume
,I/art     ( 1738): Explicit concurrent mark sweep GC freed 107246(5MB) AllocSpace objects, 28(448KB) LOS objects, 39% free, 15MB/25MB, paused 1.198ms total 112.176ms
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8127 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8147 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  324): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.483ms
,I/ActivityManager(  880): Killing 7934:com.android.vending/u0a32 (adj 15): empty #7
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.155ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 20.120ms
,W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_7934/cgroup.procs: No such file or directory
,W/ResourcesManager( 7835): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7835): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8147): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8170 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  880): Killing 8071:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10035/pid_8071/cgroup.procs: No such file or directory
,W/asset   ( 8170): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 8170): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8170): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8170): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6461): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6461): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 6461): updateResources: need to parse f{com.google.android.gms}
,W/Launcher( 1569): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2ad5e0fb new=com.google.android.velvet.VelvetApplication@2ad5e0fb
,I/UpdateIcingCorporaServi( 8094): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8197 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8197): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8094): UpdateCorporaTask done [took 124 ms] updated apps [took 124 ms] 
,I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8225 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 8012:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_8012/cgroup.procs: No such file or directory
,D/Finsky  ( 8225): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8225): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8225): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8225): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8225): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8225): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 8225): Skipping gmscore version check
,D/Finsky  ( 8225): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8225): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  880): Killing 8127:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10019/pid_8127/cgroup.procs: No such file or directory
,I/Icing   ( 6461): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6461): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  880): Killing 8170:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10027/pid_8170/cgroup.procs: No such file or directory
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311491, SEQNUM=4506, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-529, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,I/ActivityManager(  880): Killing 7835:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10070/pid_7835/cgroup.procs: No such file or directory
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/Keyboard.Facilitator.LanguageModelFlusher( 1416): run()
I/Keyboard.Facilitator( 1416): flushDynamicLanguageModels()
,I/ConfigService( 1738): onCreate
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ConfigService( 1738): onDestroy
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310721, SEQNUM=4508, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-637, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {f8a510a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {29c57eae, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {29c57eae, *walarm*:android.content.syncmanager.SYNC_ALARM} [11ms]
,V/AlarmManager(  880): done {f8a510a, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310917, SEQNUM=4513, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-802, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310605, SEQNUM=4514, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-895, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/art     (  880): Explicit concurrent mark sweep GC freed 19736(1083KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.472ms total 198.054ms
,D/ConnectivityService(  880): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): DefaultState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Checking http://clients3.google.com/generate_204 on "NG700"
,I/ActivityManager(  880): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8299 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 8299): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 13:09:54 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452863394620], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452863394607]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  880): Validated
,D/ConnectivityService(  880): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  880): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  880): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1290): CM callback handler got msg 524290
,I/Babel_SMS( 8299): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8299): MmsConfig.loadMmsSettings
I/Babel_SMS( 8299): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8299): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8299): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 8299): MmsConfig.loadFromResources
,E/Babel_SMS( 8299): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8299): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8299): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 8299): startup - clean
,I/Babel   ( 8299): deleted: false for 0
,W/VideoCapabilities( 8299): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8299): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8299): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8299): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8299): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8299): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8299): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8299): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  880): Killing 8094:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_8094/cgroup.procs: No such file or directory
,I/vclib   ( 8299): onServiceConnected
W/Babel   ( 8299): Attempted to change video mute state without an active call.
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310609, SEQNUM=4519, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-58, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {f8a510a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {364ef5e, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  880): done {364ef5e, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [13ms]
,V/AlarmManager(  880): done {f8a510a, *alarm*:android.intent.action.TIME_TICK} [44ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310870, SEQNUM=4521, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-104, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=257, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311151, SEQNUM=4522, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-176, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=256, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310848, SEQNUM=4523, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-234, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  880): send {f8a510a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {3f49e8a, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {3f49e8a, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [9ms]
,V/AlarmManager(  880): done {f8a510a, *alarm*:android.intent.action.TIME_TICK} [54ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=254, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310527, SEQNUM=4524, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-49, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  880): send {f8a510a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {339cbf3f, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8345 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  880): done {f8a510a, *alarm*:android.intent.action.TIME_TICK} [84ms]
,I/GAv4    ( 8345): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8345):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8345):   adb logcat -s GAv4
,W/GAv4    ( 8345): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8345): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8345): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  880): done {339cbf3f, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [349ms]
,I/ActivityManager(  880): Killing 8147:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_8147/cgroup.procs: No such file or directory
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=253, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310809, SEQNUM=4529, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-113, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=250, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310771, SEQNUM=4530, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-100, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  880): send {f8a510a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {25bcd00c, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  880): done {f8a510a, *alarm*:android.intent.action.TIME_TICK} [42ms]
,V/AlarmManager(  880): done {25bcd00c, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [93ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  880): send {e106d55, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  880): send {3f49e8a, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {e106d55, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [22ms]
V/AlarmManager(  880): done {3f49e8a, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [22ms]
,I/EventLogService( 6461): Aggregate from 1452863022733 (log), 1452862169998 (data)
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=248, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310462, SEQNUM=4534, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-218, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  880): send {f8a510a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {fc98c36, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ProcessStatsService(  880): Prepared write state in 16ms
,V/AlarmManager(  880): done {fc98c36, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [114ms]
,V/AlarmManager(  880): done {f8a510a, *alarm*:android.intent.action.TIME_TICK} [138ms]
,I/ProcessStatsService(  880): Pruning old procstats: /data/system/procstats/state-2016-01-14-16-50-25.bin
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=248, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310745, SEQNUM=4540, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2724, POWER_SUPPLY_CHARGE_COUNTER=2, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=248, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310741, SEQNUM=4541, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-6, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=248, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310741, SEQNUM=4543, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-7, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2532): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
,V/AlarmManager(  880): send {330d3cdf, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,V/AlarmManager(  880): send {f8a510a, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): send {320b14a4, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  880): send {9d9f20d, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  880): send {1c9a35c2, *walarm*:com.motorola.ccc.cce.alarmintent}
V/AlarmManager(  880): send {162fd3, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,V/AlarmManager(  880): done {330d3cdf, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [35ms]
,V/AlarmManager(  880): done {f8a510a, *alarm*:android.intent.action.TIME_TICK} [48ms]
,V/AlarmManager(  880): done {320b14a4, *walarm*:com.motorola.ccc.cce.alarmintent} [174ms]
,V/AlarmManager(  880): done {9d9f20d, *walarm*:com.motorola.ccc.cce.alarmintent} [188ms]
,V/AlarmManager(  880): done {1c9a35c2, *walarm*:com.motorola.ccc.cce.alarmintent} [203ms]
,V/AlarmManager(  880): done {162fd3, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [207ms]
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1738): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 8427): 
D/AndroidRuntime( 8427): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8427): CheckJNI is OFF
D/AndroidRuntime( 8427): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10452 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 6625:com.test.thalitest/u0a452 (adj 9): stop com.test.thalitest
I/WindowState(  880): WIN DEATH: Window{1ee99486 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  880): Client connection lost with reason: 4
W/PackageSettings(  880): Skipping PackageSetting{1f12c176 com.example.hello/10440} due to missing metadata
I/ActivityManager(  880):   Force finishing activity ActivityRecord{16230514 u0 com.test.thalitest/.MainActivity t6}
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10452 user=0: pkg removed
I/art     ( 3208): Explicit concurrent mark sweep GC freed 12173(2MB) AllocSpace objects, 38(608KB) LOS objects, 39% free, 7MB/12MB, paused 836us total 43.032ms
W/ActivityManager(  880): Spurious death for ProcessRecord{b762440 6625:com.test.thalitest/u0a452}, curProc for 6625: null
I/Keyboard.Facilitator( 1416): resetDictionaries() : en_US
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1738): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8455 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1416): run()
I/art     ( 1569): Explicit concurrent mark sweep GC freed 4948(305KB) AllocSpace objects, 6(297KB) LOS objects, 25% free, 13MB/17MB, paused 491us total 125.523ms
I/Decoder ( 1416): createOrResetDecoder
I/ConfigService( 1738): onCreate
I/art     (  880): Explicit concurrent mark sweep GC freed 25996(1846KB) AllocSpace objects, 11(261KB) LOS objects, 33% free, 20MB/30MB, paused 3.858ms total 185.760ms
I/art     (  880): WaitForGcToComplete blocked for 88.130ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1416): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1416): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1416): run()
I/StatsUtilsManager( 1416): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1416): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 8455): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8480 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  880): removeObsoleteFile: deleting file=6_task.xml
I/ContactLocale( 8455): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  880): Killing 8197:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/art     (  880): Explicit concurrent mark sweep GC freed 5347(281KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.680ms total 166.747ms
I/Launcher( 1569): Deferring update until onResume
I/ThermalEngine(  320): Sensor:xo_therm_pu2:27000 mC
D/AndroidRuntime( 8427): Shutting down VM
W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_8197/cgroup.procs: No such file or directory
W/asset   ( 8480): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8480): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8480): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8480): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8504 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  880): Killing 8225:com.android.vending/u0a32 (adj 15): empty #7
W/ContextImpl( 8504): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_8225/cgroup.procs: No such file or directory
D/PackageBroadcastService( 6461): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 6461): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6461): Module APK com.google.android.play.games already loaded
D/AccountUtils( 6461): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 6461): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1738): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1738): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 6461): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6461): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 6461): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6461): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6461): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6461): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 6461): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6461): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8534 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/gH_CompatibleDatabase( 6461): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/GMPM-SVC( 6461): App measurement is starting up, version: 8489
I/GMPM-SVC( 6461): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
D/gH_CompatibleDatabase( 6461): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6461): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
E/SQLiteLog( 6461): (3850) statement aborts at 25: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] disk I/O error
D/gH_CompatibleDatabase( 6461): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
--------- beginning of crash
E/AndroidRuntime( 6461): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 6461): Process: com.google.android.gms, PID: 6461
E/AndroidRuntime( 6461): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6461): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6461): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 6461): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6461): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6461): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 6461): 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:105)
E/AndroidRuntime( 6461): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
E/AndroidRuntime( 6461): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6461): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6461): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6461): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  880): Can't write: system_app_crash
E/DropBoxManagerService(  880): java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  880): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  880): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  880): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  880): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  880): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  880): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  880): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  880): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  880): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  880): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  880): 	... 5 more
I/Process ( 6461): Sending signal. PID: 6461 SIG: 9
D/WifiService(  880): Client connection lost with reason: 4
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
I/ActivityManager(  880): Process com.google.android.gms (pid 6461) has died
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  880): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms

```
