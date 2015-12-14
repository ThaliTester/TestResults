#### Test 50650278ec2c976_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,E/global frequency( 2635): no tags to log
D/Checkin ( 2635): publish the event [tag = MOT_CHECKIN event name = LOG]
D/BSUtils ( 2635): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/art     ( 2635): Explicit concurrent mark sweep GC freed 12911(689KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.251ms total 104.781ms
D/BSUtils ( 2635): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2635): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2635): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/art     ( 1480): Explicit concurrent mark sweep GC freed 55724(3MB) AllocSpace objects, 37(1251KB) LOS objects, 39% free, 7MB/12MB, paused 1.044ms total 45.521ms
D/BSUtils ( 2635): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
D/AndroidRuntime( 6598): 
D/AndroidRuntime( 6598): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6598): CheckJNI is OFF
I/BSUtils ( 2635): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2635): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/BSUtils ( 2635): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2635): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/BSUtils ( 2635): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 2635): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2635): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2635): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2635): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2635): publish the event [tag = DEV_ATTRIBS event name = SW]
I/global frequency( 2635): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
D/Checkin ( 2635): publish the event [tag = MOT_CHECKIN event name = LOG]
D/AndroidRuntime( 6598): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  884): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  884): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6621 uid=10365 gids={50365, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6598): Shutting down VM
V/ActivityManager(  884): Display changed displayId=0
W/ContextImpl( 1480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6621): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6621): Time to load native libraries: 12 ms (timestamps 4671-4683)
,I/LibraryLoader( 6621): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6621): Binding Chromium to main looper Looper (main, tid 1) {2bd69f33}
,I/LibraryLoader( 6621): Expected native library version number "",actual native library version number ""
,I/chromium( 6621): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6621): Initializing chromium process, singleProcess=true
,W/art     ( 6621): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6621): ApplicationContext is null in ApplicationStatus
,W/chromium( 6621): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6621): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6621): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6621): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6621): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6621): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6621): Local Branch: 
I/Adreno-EGL( 6621): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6621): Local Patches: NONE
I/Adreno-EGL( 6621): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  884): Message: 20
D/BluetoothManagerService(  884): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e0b21cf:true
,W/ActivityManager(  884): Activity pause timeout for ActivityRecord{b97be18 u0 com.test.thalitest/.MainActivity t3}
,I/art     (  884): Explicit concurrent mark sweep GC freed 24305(1428KB) AllocSpace objects, 2(217KB) LOS objects, 33% free, 20MB/31MB, paused 1.522ms total 127.366ms
,W/art     ( 6621): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6621): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6621): CordovaWebView is running on device made by: motorola
,W/art     ( 6621): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6621): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6621): Render dirty regions requested: true
,D/Atlas   ( 6621): Validating map...
,W/chromium( 6621): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6621): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6621): Enabling debug mode 0
,I/Keyboard.Facilitator( 1418): onFinishInput()
,I/LaunchCheckinHandler(  884): Displayed com.test.thalitest/.MainActivity,cp,ca,1077
,I/ActivityManager(  884): Displayed com.test.thalitest/.MainActivity: +993ms (total +1s77ms)
,W/IInputConnectionWrapper( 6621): showStatusIcon on inactive InputConnection
,V/AlarmManager(  884): send {6cc2878, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  884): done {6cc2878, *walarm*:com.google.android.intent.action.SEND_IDLE} [4ms]
,E/Adreno-ES20( 6621): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6621): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6621): Cannot call determinedVisibility() - never saw a connection for the pid: 6621
,D/JsMessageQueue( 6621): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6621): JniHelper::setJavaVM(0xb87c0310), pthread_self() = -1196091024
D/JX-Cordova( 6621): jxcore cordova android initializing
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,W/jxcore-log( 6621): Initializing JXcore engine
W/jxcore-log( 6621): JXcore engine is ready
,W/jxcore-log( 6621): Starting JXcore engine
,I/art     ( 6621): Background sticky concurrent mark sweep GC freed 38232(3MB) AllocSpace objects, 3(51KB) LOS objects, 14% free, 21MB/25MB, paused 8.842ms total 72.313ms
,W/.test.thalitest( 6621): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10365 path="socket:[7374]" dev="sockfs" ino=7374 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6621): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10365 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6621): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10365 path="socket:[7530]" dev="sockfs" ino=7530 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6621): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10365 path="socket:[29868]" dev="sockfs" ino=29868 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6621): Platform android
W/jxcore-log( 6621): 
W/jxcore-log( 6621): Process ARCH arm
W/jxcore-log( 6621): 
,I/jxcore-log( 6621): JXcore Cordova bridge is ready!
I/jxcore-log( 6621): 
,W/jxcore-log( 6621): JXcore engine is started
I/chromium( 6621): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6621): Toggling radios to true
I/jxcore-log( 6621): 
,D/BluetoothAdapter( 6621): enable(): BT is already enabled..!
,D/WifiService(  884): setWifiEnabled: true pid=6621, uid=10365
E/WifiService(  884): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  884): New client listening to asynchronous messages
,I/jxcore-log( 6621): Radios toggled
I/jxcore-log( 6621): 
,D/BluetoothManagerService(  884): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6621): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6621): 
I/jxcore-log( 6621): Perf Test app loaded loaded
I/jxcore-log( 6621): 
I/jxcore-log( 6621): check test folder
I/jxcore-log( 6621): 
,I/jxcore-log( 6621): found test : ./testFindPeers.js
I/jxcore-log( 6621): 
,I/wpa_supplicant( 1444): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  294):  STA Disconnected !!
D/TCMD    (  471): NL - Read 1004 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/TCMD    (  471): NL - Read 68 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/TCMD    (  471): NL - Read 68 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
I/wpa_supplicant( 1444): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
I/wpa_supplicant( 1444): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): get_property_value, Enter
I/MDMCTBK (  294): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  294): get_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  294): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  294): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  884): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  884): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  884): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  884): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  884): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering(  884): InitialState.processMessage what=4
,W/Settings(  884): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  884): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/Tethering(  884): ApnList is empty for checkDunConfigured()
D/Tethering(  884):  upstream interface types: 
D/Tethering(  884):  1
D/Tethering(  884):  5
,D/Tethering(  884):  7
D/Tethering(  884):  0
E/WifiStateMachine(  884): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  884): do suspend true
D/WifiP2pService(  884): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  884): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1444): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/Tethering(  884): sendTetherStateChangedBroadcast 0, 0, 0
,D/CommandListener(  291): Clearing all IP addresses on wlan0
D/TCMD    (  471): NL - Read 60 bytes from update socket.
D/TCMD    (  471): NL - ignore NL message, type = 21
D/TCMD    (  471): Listening for incoming client connection request
,I/jxcore-log( 6621): found test : ./testSendData.js
I/jxcore-log( 6621): 
,V/NativeCrypto( 1725): Read error: ssl=0xb8afd138: I/O error during system call, Connection timed out
,V/NativeCrypto( 1725): SSL shutdown failed: ssl=0xb8afd138: I/O error during system call, Broken pipe
,D/ConnectivityService(  884): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  884): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  884): setDetailed state send new extra info<unknown ssid>
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname,
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/WifiMetrics(  884): connected time updated 130558
D/ConnectivityService(  884): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  884): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  884): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6689 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  884): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  884): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  884): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Disconnected - quitting
D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  884): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1522): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1522): INET_CONDITION=0 ,activeNet=null
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1522): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1522): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1522): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1522): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  884): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/wpa_supplicant( 1444): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  884): Start Disconnecting Watchdog 1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/wpa_supplicant( 1444): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-STARTED 
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  884): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  884): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  884): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/chromium( 6621): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/WifiStateMachine(  884): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  884): do suspend true
,D/WifiP2pService(  884): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  884): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1444): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  291): Clearing all IP addresses on wlan0
,D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  884): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  884): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  884): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  884): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  884): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  884): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  884): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  884): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  884): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  884): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  884): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
W/ResourcesManager( 6689): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  884): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6715 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 6417:com.google.android.videos/u0a98 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10098/pid_6417/cgroup.procs: No such file or directory
,W/ResourcesManager( 6715): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
,D/MDMCTBK (  294): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  294): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1444): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  294): Event received = Trying to associate with
,D/WifiMonitor(  884): didn't find BSSID Trying to associate with SSID 'NG700'
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  471): NL - Read 56 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
,E/wpa_supplicant( 1444): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiStateMachine(  884): [1,450,109,447,957 ms] noteScanEnd no scan source
,E/WifiStateMachine(  884): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@284c9b37 sup_state=SCANNING debouncing=false
E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  884): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  884): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel_SMS( 6715): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6715): MmsConfig.loadMmsSettings
I/Babel_SMS( 6715): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/TCMD    (  471): NL - Read 312 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
,D/TCMD    (  471): NL - Read 192 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/TCMD    (  471): NL - Read 68 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/TCMD    (  471): NL - Read 1004 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
I/Babel_SMS( 6715): MmsConfig.loadFromDatabase
I/wpa_supplicant( 1444): wlan0: Associated with c0:ff:d4:d3:aa:48
D/Tethering(  884): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  884): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  884): ApnList is empty for checkDunConfigured()
D/Tethering(  884):  upstream interface types: 
D/Tethering(  884):  0
D/Tethering(  884):  1
D/Tethering(  884):  5
D/Tethering(  884):  7
,D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
,D/MDMCTBK (  294): Event received = Associated with c0:ff:d4
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/TCMD    (  471): NL - Read 80 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/TCMD    (  471): NL - Read 80 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
D/TCMD    (  471): NL - Read 68 bytes from update socket.
D/TCMD    (  471): NL - message type is RTM_NEWLINK
D/TCMD    (  471): Listening for incoming client connection request
,D/Tethering(  884): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 1444): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  294): Event received = WPA: Key negotiation com
I/wpa_supplicant( 1444): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
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
D/TCMD    (  471): NL - Read 1004 bytes from update socket.
I/MDMCTBK (  294): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  294): set_property_value, Enter
D/TCMD    (  471): NL - message type is RTM_NEWLINK
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
D/TCMD    (  471): Listening for incoming client connection request
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
I/MDMCTBK (  294): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1198522632
I/MDMCTBK (  294): return from set_get_from_wpa_supplicant
I/MDMCTBK (  294): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  294): set_property_value, Enter
I/MDMCTBK (  294): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  294): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  294): set_property_value, Exit
E/MDMCTBK (  294): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  294): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  294): wifi_set_tx_pwr: SETTXPOWER = 18
E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  884): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/MDMCTBK (  294): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  294): , reply_len: 3, ret: 0
E/MDMCTBK (  294): MdmCutbackHndler, resp=OK
E/MDMCTBK (  294): 
D/MDMCTBK (  294): wifi_set_tx_pwr: Exit
E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  884): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  884): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  884): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  884): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  884): Network connection established
E/WifiStateMachine(  884): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  884): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/ConnectivityService(  884): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  884): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  884): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  884): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  884): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiStateMachine(  884): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  884): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  884): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  884): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  291): Setting iface cfg
E/WifiStateMachine(  884): Start Dhcp Watchdog 2
,E/Babel_SMS( 6715): canonicalizeMccMnc: invalid mccmnc 
,E/WifiStateMachine(  884): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
I/Babel_SMS( 6715): MmsConfig.loadFromResources
E/WifiStateMachine(  884): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
E/Babel_SMS( 6715): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6715): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
E/WifiStateMachine(  884): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  884): do suspend false
,E/wpa_supplicant( 1444): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  884): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1444): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  884): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@258ddb60 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  884): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@258ddb60 target=com.android.internal.util.StateMachine$SmHandler }
,W/art     ( 6715): Suspending all threads took: 5.115ms
,W/Settings( 6715): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6715): startup - clean
,I/Babel   ( 6715): deleted: false for 0
,W/VideoCapabilities( 6715): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6715): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6715): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6715): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6715): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6715): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6715): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6715): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  884): Killing 6495:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,E/DHCPCD  ( 6753): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6753): version 5.5.6 starting
E/DHCPCD  ( 6753): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6753): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6753): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 6753): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6753): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6753): wlan0: sending REQUEST (xid 0x569cc91e), next in 4.60 seconds
,W/libprocessgroup(  884): failed to open /acct/uid_10039/pid_6495/cgroup.procs: No such file or directory
,I/vclib   ( 6715): onServiceConnected
W/Babel   ( 6715): Attempted to change video mute state without an active call.
,I/DHCPCD  ( 6753): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6753): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 6753): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6753): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6753): wlan0: adding default route via 192.168.1.1
,D/DHCPCD  ( 6753): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  471): NL - Read 60 bytes from update socket.
D/TCMD    (  471): NL - ignore NL message, type = 20
D/TCMD    (  471): Listening for incoming client connection request
,D/DHCPCD  ( 6753): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  884): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  884): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  884): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  884): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  (  884): do suspend true
,D/WifiP2pService(  884): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  884): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  884): WifiStateMachine DHCP successful
,E/WifiStateMachine(  884): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  884): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  884): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  884): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  884): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  884): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  884): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  884): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  884): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  884): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  884): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  884): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  884): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Checkin (  884): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/WifiStateMachine(  884): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/Nat464Xlat(  884): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  884): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  884): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  884): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  884):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  884): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  884): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  884): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/ModemStatsDSDetect( 1522): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1522): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1522): onReceive() - done, currentInetCondition=0
,D/ConnectivityService(  884): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  884): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 14 Dec 2015 16:10:50 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450109450182], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450109450163]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  884): Validated
D/ConnectivityService(  884): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  884): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  884): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  884): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524290
,D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1522): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1296): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1522): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1522): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1522): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1296): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1296): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1296): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  884): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1480): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  884): MasterInitialState.processMessage what=3
,W/ContextImpl( 1480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6466): type=WIFI subType= reason=null isConnected=true
,D/Central_PollingManager( 1480): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1480): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,V/MusicLeanback( 6466): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6466): type=WIFI subType= reason=null isConnected=true
,D/OtaApp  ( 2635): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  884): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6827 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2635): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2635): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2635): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2635): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2635): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2635): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2635): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2635): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2635): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2635): [debug] > CusSM.onRadioDown
,V/Mms     ( 6827): mnc/mcc: 
,V/Mms     ( 6827): tag: int value: recipientLimit - 20
,V/Mms     ( 6827): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6827): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6827): tag: int value: maxSubjectLength - 80
,V/Mms     ( 6827): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6827): tag: bool value: enableGroupMms - false
V/Mms     ( 6827):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6827): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6860 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 6258:com.google.android.gms/u0a16 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10016/pid_6258/cgroup.procs: No such file or directory
,D/ConnectivityService(  884): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/PhoneMonitor( 6860): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6860): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6860): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  884): Start proc com.google.android.gms for broadcast com.google.android.gms/.mdm.receivers.ConnectivityReceiver: pid=6879 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 6056:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10032/pid_6056/cgroup.procs: No such file or directory
,W/ResourcesManager( 6879): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6879): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6879): VM with version 2.1.0 has multidex support
,I/MultiDex( 6879): install
,I/MultiDex( 6879): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6879): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6879): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6879): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21863eba: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6879): Installed default security provider GmsCore_OpenSSL
,I/CheckinService( 6879): Checkin interval check for package: unspecified last checkin: 1450109361928 min interval config: 0 actual interval: 89620
,D/NativeLibraryUtils( 6879): Install completed successfully. count=14 extracted=0
,I/CheckinService( 6879): Disabling old GoogleServicesFramework version
,I/CheckinService( 6879): Checking schedule, now: 1450109451614 next: 1450109391499
I/CheckinService( 6879): active receiver: enabled
,I/CheckinService( 6879): Preparing to send checkin request
,I/EventLogService( 6879): Accumulating logs since 1450109358341
,I/iu.SyncManager( 6879): SYNC; picasa accounts
,D/NetworkLogImpl( 6879): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6879): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6879): num queued entries: 0
I/iu.UploadsManager( 6879): num updated entries: 0
,I/iu.SyncManager( 6879): NEXT; no task
,I/art     ( 6879): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6879): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  884): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6926 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6879): Checkin reason type: 8 attempt count: 1
,D/WifiService(  884): New client listening to asynchronous messages
,E/ActivityThread( 6879): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  884): Explicit concurrent mark sweep GC freed 47562(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.611ms total 123.726ms
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  884): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6954 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 6621): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6621): 
,I/ActivityManager(  884): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6973 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 6973): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6973): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6973): VM with version 2.1.0 has multidex support
I/MultiDex( 6973): install
I/MultiDex( 6973): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6973): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6973): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6973): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3473bd14: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6973): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6973): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6973): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel   ( 6715): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  884): Killing 6689:com.motorola.context/u0a8 (adj 15): empty #7
,D/NativeLibraryUtils( 6973): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  884): failed to open /acct/uid_10008/pid_6689/cgroup.procs: No such file or directory
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6954): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
D/WVCdm   (  297): Instantiating CDM.
,I/WVCdm   (  297): CdmEngine::OpenSession
,I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6954): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  280): Returning OperationFailed - no handler for errno 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,W/ContextImpl( 6954): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,V/AlarmManager(  884): send {2b77cb8b, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/GAv4    ( 6954): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6954):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6954):   adb logcat -s GAv4
E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6954): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6954): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe0000
,E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe0000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xbeecc4e0
W/GAv4    ( 6954): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb733b508, dataLength=8
,D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7314480, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb7436f58, idLength=0xb55bb730
,W/GAv4    ( 6954): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
,D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  297): PrepareKeyRequest: nonce=1406876839
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb73eb6c8
D/DrmWidevineDash(  297): message_length=1591, signature=0xb7316368, signature_length=3042686740
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,D/ConnectivityService(  884): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  884): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1480): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1480): now: 206444 ,futureTime: 86473722
D/Central_PollingManager( 1480): Polling alarm set to expire at: 86473722 Current Time: 206444
I/NetworkMonitor( 6466): type=WIFI subType= reason=null isConnected=true
,D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2635): now: 206446 ,futureTime: 9223372036854775807
D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2635): now: 206446 ,futureTime: 9223372036854775807
D/PollingManager( 2635): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2635): now: 206447 ,futureTime: 9223372036854775807
D/OtaApp  ( 2635): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2635): [debug] > PollingManagerService, now: 206448 ,futureTime: 77878804
,D/OtaApp  ( 2635): [debug] > Polling alarm set to expire at: 77878804 Current Time: 206449
,D/MMApiProvisionService( 2635): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2635): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2635): createDeviceIdOrLogin update_device
D/Checkin ( 2635): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2635): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2635): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2635): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2635): createDeviceIdOrLogin update_device
D/Checkin ( 2635): publish the event [tag = MOT_CCE event name = LOG]
,I/WebViewFactory( 6954): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/MMApiProvisionService( 2635): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2635): set mOutstandingReq to true.
I/ Nonce  ( 2635):  Nonce getNonce 
I/ Nonce  ( 2635):  Nonce Request 
I/ Nonce  ( 2635):  Nonce execute Request 
,D/MMApiWebService( 2635): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/LibraryLoader( 6954): Time to load native libraries: 2 ms (timestamps 6541-6543)
I/LibraryLoader( 6954): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6954): Binding Chromium to main looper Looper (main, tid 1) {158a9344}
,I/LibraryLoader( 6954): Expected native library version number "",actual native library version number ""
,I/chromium( 6954): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/art     ( 1480): Explicit concurrent mark sweep GC freed 5119(236KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 901us total 28.957ms
,I/BrowserStartupController( 6954): Initializing chromium process, singleProcess=true
W/art     ( 6954): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6954): ApplicationContext is null in ApplicationStatus
,D/MMApiProvisionService( 2635): isDeviceProvisioned: deviceId = 2072049230914535424
I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,D/CCE     ( 2635): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2635): createDeviceIdOrLogin update_device
D/Checkin ( 2635): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2635): Not proxy app, so login/provision not allowed
D/OtaApp  ( 2635): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2635): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 2635): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2635): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2635): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2635): publish the event [tag = MOT_OTA event name = LOG]
,W/chromium( 6954): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/OtaApp  ( 2635): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2635): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2635): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,E/libEGL  ( 6954): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6954): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6954): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6954): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6954): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6954): Local Branch: 
I/Adreno-EGL( 6954): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6954): Local Patches: NONE
I/Adreno-EGL( 6954): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/OtaApp  ( 2635): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiWebService( 2635): generating token using payload instead of using session token
,D/ Nonce  ( 2635):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2635): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2635): publish the event [tag = MOT_CCE event name = LOG]
,W/AudioManagerAndroid( 6954): Requires BLUETOOTH permission
,I/NSApplication( 6954): Starting up...
,I/ActivityManager(  884): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7050 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 6466:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/dex2oat ( 7048): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  884): failed to open /acct/uid_10080/pid_6466/cgroup.procs: No such file or directory
,E/WifiStateMachine(  884): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  884): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  884): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  884): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  884): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1296): CM callback handler got msg 524295
,I/dex2oat ( 7048): dex2oat took 339.448ms (threads: 4)
,I/Adreno-EGL( 6973): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6973): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6973): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6973): Local Branch: 
I/Adreno-EGL( 6973): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6973): Local Patches: NONE
I/Adreno-EGL( 6973): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  884): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7081 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  884): Killing 6827:com.android.mms/u0a23 (adj 15): empty #7
,I/art     (  310): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 27.305ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 21ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.881ms
,I/Adreno-EGL( 6973): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6973): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6973): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6973): Local Branch: 
I/Adreno-EGL( 6973): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6973): Local Patches: NONE
I/Adreno-EGL( 6973): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  884): failed to open /acct/uid_10023/pid_6827/cgroup.procs: No such file or directory
,W/ResourcesManager( 7081): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ Nonce  ( 2635):  Nonce Reponse 
D/        ( 2635): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"4bf59f25-df48-4797-b93a-c7e586c55a75"}
,D/MMApiWSBase( 2635): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2635):  Nonce Handle Reponse 
,D/MMApiProvisionService( 2635): mOutstandingReq set to false
,I/WVCdm   (  297): CdmEngine::OpenSession
I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe0000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe0000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xb12d0960
D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb733ddb0, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb73191a8, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb7436f98, idLength=0xb13d0730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  297): PrepareKeyRequest: nonce=1566910791
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb73eb6c8
D/DrmWidevineDash(  297): message_length=1626, signature=0xb7314480, signature_length=2973566740
,I/art     ( 2635): Explicit concurrent mark sweep GC freed 16493(986KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.066ms total 72.284ms
,I/ActivityManager(  884): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7114 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,D/MMApiProvisionService( 2635):  pTime 1450100652194 sExp 172742 cTime 1450109454261 tTime 1450273394194
D/MMApiProvisionService( 2635):  No login Required 
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/ContactLocale( 7114): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  884): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7137 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  884): Killing 6926:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/Adreno-EGL( 6973): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6973): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6973): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6973): Local Branch: 
I/Adreno-EGL( 6973): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6973): Local Patches: NONE
I/Adreno-EGL( 6973): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6973): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6973): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6973): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6973): Local Branch: 
I/Adreno-EGL( 6973): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6973): Local Patches: NONE
I/Adreno-EGL( 6973): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  884): Killing 6860:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/DataUsage( 2635): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2635): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  884): failed to open /acct/uid_10088/pid_6926/cgroup.procs: No such file or directory
,W/libprocessgroup(  884): failed to open /acct/uid_10035/pid_6860/cgroup.procs: No such file or directory
,I/MusicStore( 7137): Database version: 120
,I/CheckinRequestBuilder( 6879): Classify the device as Phone.
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7137): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7137): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7137): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     (  884): Explicit concurrent mark sweep GC freed 14324(681KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.649ms total 120.800ms
,W/ResourcesManager( 7137): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7137): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7137): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7137): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7137): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6aeaa3f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7137): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7137): GMSCore installation verified
,I/ConfigStore( 7137): Config Database version: 1
,I/MediaRouter( 7137): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7137): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7137): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7137): type=WIFI subType= reason=null isConnected=true
,I/CheckinTask( 6879): Sending checkin request (9605 bytes)
,I/ActivityManager(  884): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7178 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7137): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7137): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  884): Killing 6715:com.google.android.talk/u0a70 (adj 15): empty #7
,V/Mms     ( 7178): mnc/mcc: 
,V/Mms     ( 7178): tag: int value: recipientLimit - 20
,V/Mms     ( 7178): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7178): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7178): tag: int value: maxSubjectLength - 80
V/Mms     ( 7178): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7178): tag: bool value: enableGroupMms - false
V/Mms     ( 7178):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  884): failed to open /acct/uid_10070/pid_6715/cgroup.procs: No such file or directory
,W/ResourcesManager( 7178): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7208 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 6954:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10081/pid_6954/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7208): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7208): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7208): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  884): Killing 7050:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10052/pid_7050/cgroup.procs: No such file or directory
,I/CheckinService( 6879): Checkin interval check for package: unspecified last checkin: 1450109361928 min interval config: 0 actual interval: 93595
,I/CheckinRequestBuilder( 6879): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  884): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7228 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 6879): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 6218): Explicit concurrent mark sweep GC freed 1609(57KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 426us total 27.686ms
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
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/CheckinRequestBuilder( 6879): Classify the device as Phone.
,I/CheckinTask( 6879): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6879): Checking schedule, now: 1450109455769 next: 1450710592761
I/CheckinService( 6879): active receiver: disabled
,I/CheckinService( 6879): Checking schedule, now: 1450109455784 next: 1450710592761
,I/CheckinService( 6879): active receiver: disabled
,D/CheckinService( 6879): Recording last checkin time for package unspecified as 1450109455787
,I/ActivityManager(  884): Killing 7081:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  884): Killing 7114:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_7081/cgroup.procs: No such file or directory
,W/libprocessgroup(  884): failed to open /acct/uid_10007/pid_7114/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7253 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 7137:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10080/pid_7137/cgroup.procs: No such file or directory
,W/ResourcesManager( 7253): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7253): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7253): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7253): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7253): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7253): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7253): MmsConfig.loadFromResources
,E/Babel_SMS( 7253): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7253): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7253): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7253): startup - clean
,I/Babel   ( 7253): deleted: false for 0
,I/ActivityManager(  884): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7291 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7253): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7253): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7253): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7253): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7253): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7253): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7253): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7253): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7253): onServiceConnected
,W/Babel   ( 7253): Attempted to change video mute state without an active call.
,I/Babel   ( 7253): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  884): Killing 7178:com.android.mms/u0a23 (adj 13): empty #7
,I/GAv4    ( 7291): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7291):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7291):   adb logcat -s GAv4
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7291): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7291): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7291): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7291): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  884): failed to open /acct/uid_10023/pid_7178/cgroup.procs: No such file or directory
,W/GAv4    ( 7291): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7291): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7291): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7291): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7291): Time to load native libraries: 2 ms (timestamps 473-475)
I/LibraryLoader( 7291): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7291): Binding Chromium to main looper Looper (main, tid 1) {158a9344}
,I/LibraryLoader( 7291): Expected native library version number "",actual native library version number ""
,I/chromium( 7291): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7291): Initializing chromium process, singleProcess=true
W/art     ( 7291): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7291): ApplicationContext is null in ApplicationStatus
,W/chromium( 7291): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7291): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7291): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7291): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7291): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7291): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7291): Local Branch: 
I/Adreno-EGL( 7291): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7291): Local Patches: NONE
I/Adreno-EGL( 7291): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7291): Requires BLUETOOTH permission
,I/NSApplication( 7291): Starting up...
,I/ActivityManager(  884): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7364 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 7208:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10035/pid_7208/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7383 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 7228:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10088/pid_7228/cgroup.procs: No such file or directory
,W/ResourcesManager( 7383): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7403 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 7291:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7403): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,E/libprocessgroup(  884): failed to kill 1 processes for processgroup 7291
,I/ActivityManager(  884): Killing 7253:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2635): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  884): failed to open /acct/uid_10070/pid_7253/cgroup.procs: No such file or directory
,I/art     (  884): Explicit concurrent mark sweep GC freed 11506(570KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.391ms total 128.884ms
,D/GetNotificationsWS( 2635): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2635): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2635): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2635): onServiceConnected()
D/GetNotificationsWS( 2635): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2635): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2635): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1725): callingUid 10016, callindPid: 1725
,E/MDM     ( 1725): [199] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6879): Restart initialization of location
,D/AuthorizationBluetoothService( 1725): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  884): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7442 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1725): No location to return for getLastLocation()
,W/FusedLocationProvider( 1725): location=null
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 24.171ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 20.729ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 20.859ms
,W/IcingInternalCorpora( 6879): getNumBytesRead when not calculated.
,E/MDM     ( 1725): [210] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6879): Restart initialization of location
,D/AuthorizationBluetoothService( 1725): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  884): done {2b77cb8b, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [5853ms]
,I/ActivityManager(  884): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7474 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1725): No location to return for getLastLocation()
,W/FusedLocationProvider( 1725): location=null
,I/MusicStore( 7474): Database version: 120
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7474): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7474): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7474): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7474): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7474): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7474): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7474): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7474): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6aeaa3f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7474): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7474): GMSCore installation verified
,I/ConfigStore( 7474): Config Database version: 1
,I/MediaRouter( 7474): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7474): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7474): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7474): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  884): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7510 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7474): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7474): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7510): mnc/mcc: 
V/Mms     ( 7510): tag: int value: recipientLimit - 20
V/Mms     ( 7510): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7510): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7510): tag: int value: maxSubjectLength - 80
V/Mms     ( 7510): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 7510): tag: bool value: enableGroupMms - false
V/Mms     ( 7510):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7510): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7541 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 7364:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10052/pid_7364/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7541): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7541): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7541): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  884): Killing 7383:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_7383/cgroup.procs: No such file or directory
,I/CheckinService( 6879): Checkin interval check for package: unspecified last checkin: 1450109455787 min interval config: 0 actual interval: 3741
,I/CheckinService( 6879): Checkin interval check for package: unspecified last checkin: 1450109455787 min interval config: 0 actual interval: 3745
,I/CheckinService( 6879): Checking schedule, now: 1450109459542 next: 1450109485761
I/CheckinService( 6879): active receiver: disabled
,I/CheckinService( 6879): Checking schedule, now: 1450109459563 next: 1450109485761
I/CheckinService( 6879): active receiver: disabled
,I/ActivityManager(  884): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7566 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7566): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Killing 7403:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10007/pid_7403/cgroup.procs: No such file or directory
,I/Babel_SMS( 7566): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7566): MmsConfig.loadMmsSettings
I/Babel_SMS( 7566): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7566): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7566): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7566): MmsConfig.loadFromResources
,E/Babel_SMS( 7566): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7566): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7566): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7566): startup - clean
,I/Babel   ( 7566): deleted: false for 0
,I/ActivityManager(  884): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7603 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7566): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7566): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7566): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7566): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7566): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7566): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7566): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7566): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7566): onServiceConnected
,W/Babel   ( 7566): Attempted to change video mute state without an active call.
,I/GAv4    ( 7603): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7603):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7603):   adb logcat -s GAv4
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7603): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/Babel   ( 7566): connection state changed from UNKNOWN to CONNECTED
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/GAv4    ( 7603): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 7603): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager(  884): Killing 7474:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7603): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7603): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7603): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7603): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  884): failed to open /acct/uid_10080/pid_7474/cgroup.procs: No such file or directory
,I/art     (  884): Explicit concurrent mark sweep GC freed 11822(567KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.488ms total 110.134ms
,I/WebViewFactory( 7603): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7603): Time to load native libraries: 1 ms (timestamps 4133-4134)
,I/LibraryLoader( 7603): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7603): Binding Chromium to main looper Looper (main, tid 1) {158a9344}
,I/LibraryLoader( 7603): Expected native library version number "",actual native library version number ""
I/chromium( 7603): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7603): Initializing chromium process, singleProcess=true
,W/art     ( 7603): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7603): ApplicationContext is null in ApplicationStatus
,W/chromium( 7603): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7603): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7603): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7603): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7603): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7603): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7603): Local Branch: 
I/Adreno-EGL( 7603): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7603): Local Patches: NONE
I/Adreno-EGL( 7603): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7603): Requires BLUETOOTH permission
,I/NSApplication( 7603): Starting up...
,I/ActivityManager(  884): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7675 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 7510:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10023/pid_7510/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7694 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  884): Killing 7541:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10035/pid_7541/cgroup.procs: No such file or directory
,W/ResourcesManager( 7694): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7714 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 6973:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/ActivityManager(  884): Killing 7442:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ContactLocale( 7714): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/EmailService.MarketingOptInSetter( 2635): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  884): failed to open /acct/uid_10016/pid_6973/cgroup.procs: No such file or directory
,W/libprocessgroup(  884): failed to open /acct/uid_10088/pid_7442/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2635): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2635): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2635): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2635): onServiceConnected()
D/GetNotificationsWS( 2635): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2635): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2635): started with background data enabled, making sure notification mechanism is enabled
D/OtaApp  ( 2635): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2635): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2635): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  884): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1480): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2635): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2635): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2635): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2635): [debug] > cancelling the previous pending intent set for download later
,I/InputReader(  884): Reconfiguring input devices.  changes=0x00000010
,I/OtaApp  ( 2635): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2635): publish the event [tag = MOT_OTA event name = LOG]
,W/ResourcesManager( 1554): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/OtaApp  ( 2635): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2635): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2635): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  884): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7750 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
D/OtaApp  ( 2635): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2635): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2635): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1418): onFinishInput()
,W/IInputConnectionWrapper( 6621): showStatusIcon on inactive InputConnection
,D/PhoneMonitor( 7750): Register our PhoneStateListener
,D/BackupManagerService(  884): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  884): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  884): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/LaunchCheckinHandler(  884): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,222
,V/BackupManagerService(  884): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  884): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@359def
,I/Launcher( 1573): Deferring update until onResume
V/SetupWizard( 7750): Connected to Gservices successfully
,I/ActivityManager(  884): Killing 7566:com.google.android.talk/u0a70 (adj 15): empty #7
,I/GCoreNlp( 1725): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/libprocessgroup(  884): failed to open /acct/uid_10070/pid_7566/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7773 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1725): Explicit concurrent mark sweep GC freed 90409(5MB) AllocSpace objects, 26(439KB) LOS objects, 40% free, 14MB/24MB, paused 1.140ms total 127.276ms
,D/GCM     ( 1725): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/DataBuffer( 1725): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@213e5420)
,E/DataBuffer( 1725): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@15ebc1d9)
E/DataBuffer( 1725): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3147d79e)
E/DataBuffer( 1725): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@17d227f)
,E/DataBuffer( 1725): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3004924c)
,I/ActivityManager(  884): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7797 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 241us total 20.603ms
,I/ActivityManager(  884): Killing 7603:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.583ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 19.617ms
,W/libprocessgroup(  884): failed to open /acct/uid_10081/pid_7603/cgroup.procs: No such file or directory
,W/ResourcesManager( 7797): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7797): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7797): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7797): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7797): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7797): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7797): MmsConfig.loadFromResources
,E/Babel_SMS( 7797): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7797): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7797): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7797): startup - clean
,I/Babel   ( 7797): deleted: false for 0
,D/GCM     ( 1725): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7828 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,W/VideoCapabilities( 7797): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7797): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7797): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7797): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7797): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7797): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7797): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7797): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  884): Killing 7675:com.android.chrome/u0a52 (adj 15): empty #7
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,W/libprocessgroup(  884): failed to open /acct/uid_10052/pid_7675/cgroup.procs: No such file or directory
,I/vclib   ( 7797): onServiceConnected
W/Babel   ( 7797): Attempted to change video mute state without an active call.
,I/ActivityManager(  884): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7856 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7875 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 7694:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_7694/cgroup.procs: No such file or directory
,I/ActivityManager(  884): Killing 7773:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/asset   ( 7875): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7875): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 7875): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7875): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 7797): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7797): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  884): failed to open /acct/uid_10088/pid_7773/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 6879): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 7828): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1573): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2ece4a25 new=com.google.android.velvet.VelvetApplication@2ece4a25
,I/PackageBroadcastService( 6879): Null package name or gms related package.  Ignoreing.
,V/JNIHelp ( 7797): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  884): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7907 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 6879): Storage manager: low false usage 1.81MB avail 3.15GB capacity 4.85GB
,I/UpdateIcingCorporaServi( 7828): UpdateCorporaTask done [took 169 ms] updated apps [took 168 ms] 
,W/System  ( 7797): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7797): Installed default security provider GmsCore_OpenSSL
,I/art     (  884): Explicit concurrent mark sweep GC freed 17169(864KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.619ms total 129.164ms
,W/ResourcesManager( 7907): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  884): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7943 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 6879): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  884): Killing 7750:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10035/pid_7750/cgroup.procs: No such file or directory
,D/Finsky  ( 7943): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 6879): Internal init done: storage state 0
,I/Icing   ( 6879): Post-init done
,I/Icing   ( 6879): updateResources: need to parse f{com.google.android.gms}
,D/TaskPersister(  884): removeObsoleteFile: deleting file=2_task.xml
,D/Finsky  ( 7943): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7943): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7943): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7943): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7943): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7943): Skipping gmscore version check
,D/Finsky  ( 7943): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7943): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  884): Killing 7875:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10027/pid_7875/cgroup.procs: No such file or directory
,I/Icing   ( 6879): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6879): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6879): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  884): Killing 7856:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10019/pid_7856/cgroup.procs: No such file or directory
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=300, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311148, SEQNUM=4487, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10316, POWER_SUPPLY_CHARGE_COUNTER=-748, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2482): Disconnected process message: 10, size: 0
,I/ActivityManager(  884): Killing 7797:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10070/pid_7797/cgroup.procs: No such file or directory
,I/CheckinService( 6879): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:33000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=289, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311514, SEQNUM=4489, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-807, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2482): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2482): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1725): disconnect managed GoogleApiClient
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  884): send {ab315d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): send {37730ef9, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  884): send {e4b5dcb, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  884): done {37730ef9, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [18ms]
,V/AlarmManager(  884): done {e4b5dcb, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [30ms]
,I/CheckinService( 6879): Checkin interval check for package: unspecified last checkin: 1450109455787 min interval config: 0 actual interval: 38860
,V/AlarmManager(  884): done {ab315d, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/CheckinService( 6879): Checking schedule, now: 1450109494673 next: 1450109485761
I/CheckinService( 6879): active receiver: enabled
,I/CheckinService( 6879): Preparing to send checkin request
I/EventLogService( 6879): Accumulating logs since 1450109451840
,I/CheckinRequestBuilder( 6879): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6879): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  884): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8012 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8012): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8012): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8012): VM with version 2.1.0 has multidex support
I/MultiDex( 8012): install
I/MultiDex( 8012): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8012): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8012): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8012): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3473bd14: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8012): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1725): callingUid 10016, callindPid: 1725
,E/MDM     ( 1725): [181] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1725): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6879): Restart initialization of location
,V/GLSActivity( 1725): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1725): No location to return for getLastLocation()
,W/FusedLocationProvider( 1725): location=null
,I/art     ( 8012): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 8012): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8012): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  297): Instantiating CDM.
,I/WVCdm   (  297): CdmEngine::OpenSession
,I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe0000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe0000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xbeecc4e0
,D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb733b608, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb73191a8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb7436f78, idLength=0xb55bb730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  297): hlos api version =  9
D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  297): PrepareKeyRequest: nonce=3045366624
D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb73eb6c8
D/DrmWidevineDash(  297): message_length=1591, signature=0xb7316368, signature_length=3042686740
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8046): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=30 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8046): dex2oat took 85.694ms (threads: 4)
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
,I/WVCdm   (  297): CdmEngine::OpenSession
I/WVCdm   (  297): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  297): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  297): Service_Initialize: starts!
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,E/QSEECOMAPI: (  297): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
E/QSEECOMAPI: (  297): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  297): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  297): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  297): App is not loaded in QSEE
,D/QSEECOMAPI: (  297): Loaded image: APP id = 3
,D/DrmWidevineDash(  297): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe0000
E/DrmWidevineDash(  297): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fe0000
,D/DrmWidevineDash(  297): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  297): hlos api version =  9
,D/DrmWidevineDash(  297): tz api version =  8
D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  297): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  297): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  297): OEMCrypto_OpenSession: starts! SID=0xb12d0960
,D/DrmWidevineDash(  297): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  297): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  297): OEMCrypto_GetRandom: starts! randomData=0xb73eb9a0, dataLength=8
D/DrmWidevineDash(  297): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7364210, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  297): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  297): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  297): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  297): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  297): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: starts! deviceID=0xb7436f98, idLength=0xb13d0730
,D/DrmWidevineDash(  297): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  297): OEMCrypto_SupportsUsageTable: ends! returns 0x0
,D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  297): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  297): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  297): hlos api version =  9
,D/DrmWidevineDash(  297): tz api version =  8
,D/DrmWidevineDash(  297): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  297): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  297): PrepareKeyRequest: nonce=1433657857
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7315d28
D/DrmWidevineDash(  297): message_length=1626, signature=0xb7314ae0, signature_length=2973566740
,D/DrmWidevineDash(  297): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  297): CdmEngine::CloseSession
D/DrmWidevineDash(  297): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  297): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  297): L3 Terminate.
D/DrmWidevineDash(  297): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  297): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  297): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  297): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  297): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  297): OEMCrypto_Terminate: ends! returns 0
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
,I/CheckinRequestBuilder( 6879): Classify the device as Phone.
,I/CheckinTask( 6879): Sending checkin request (9606 bytes)
,I/CheckinRequestBuilder( 6879): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6879): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6879): Classify the device as Phone.
,I/CheckinTask( 6879): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6879): Checking schedule, now: 1450109497803 next: 1450710634797
I/CheckinService( 6879): active receiver: disabled
,D/CheckinService( 6879): Recording last checkin time for package unspecified as 1450109497818
,I/ActivityManager(  884): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8069 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8069): Register our PhoneStateListener
,V/SetupWizard( 8069): Connected to Gservices successfully
,D/GCM     ( 1725): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  884): Killing 7714:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  884): Killing 7828:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #8
,W/libprocessgroup(  884): failed to open /acct/uid_10007/pid_7714/cgroup.procs: No such file or directory
,W/libprocessgroup(  884): failed to open /acct/uid_10039/pid_7828/cgroup.procs: No such file or directory
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/InputReader(  884): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8091 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  884): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  884): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  884): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  884): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  884): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@32deae10
,I/GCoreNlp( 1725): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1573): Deferring update until onResume
,I/art     (  884): Explicit concurrent mark sweep GC freed 22334(1168KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.463ms total 117.929ms
,I/ActivityManager(  884): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8128 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  884): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8145 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  884): Killing 7907:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  884): Killing 7943:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_7907/cgroup.procs: No such file or directory
,W/libprocessgroup(  884): failed to open /acct/uid_10032/pid_7943/cgroup.procs: No such file or directory
,W/ResourcesManager( 8145): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 8145): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8145): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8145): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 8145): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8145): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8145): MmsConfig.loadFromResources
E/Babel_SMS( 8145): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8145): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 8145): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8145): startup - clean
,I/Babel   ( 8145): deleted: false for 0
,I/ActivityManager(  884): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8178 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 21.249ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 19.910ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.201ms
,W/VideoCapabilities( 8145): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8145): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8145): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8145): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8145): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8145): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8145): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8145): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8199 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  884): Killing 8069:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ContactLocale( 8178): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  884): failed to open /acct/uid_10035/pid_8069/cgroup.procs: No such file or directory
,I/vclib   ( 8145): onServiceConnected
W/Babel   ( 8145): Attempted to change video mute state without an active call.
,W/asset   ( 8199): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8199): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8199): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8199): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,W/ResourcesManager( 8145): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8145): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6879): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 6879): Null package name or gms related package.  Ignoreing.
,V/JNIHelp ( 8145): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Launcher( 1573): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2ece4a25 new=com.google.android.velvet.VelvetApplication@2ece4a25
,I/UpdateIcingCorporaServi( 8091): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 6879): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  884): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8232 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/System  ( 8145): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8145): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 8232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8091): UpdateCorporaTask done [took 174 ms] updated apps [took 173 ms] 
,I/ActivityManager(  884): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8258 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  884): Killing 8012:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10016/pid_8012/cgroup.procs: No such file or directory
,D/Finsky  ( 8258): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8258): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8258): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8258): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8258): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8258): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8258): Skipping gmscore version check
,I/ActivityManager(  884): Killing 8128:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10019/pid_8128/cgroup.procs: No such file or directory
,D/Finsky  ( 8258): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8258): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 6879): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6879): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  884): Killing 8199:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10027/pid_8199/cgroup.procs: No such file or directory
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310626, SEQNUM=4507, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-877, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2482): Disconnected process message: 10, size: 0
,I/ActivityManager(  884): Killing 8145:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10070/pid_8145/cgroup.procs: No such file or directory
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1418): run()
,I/Keyboard.Facilitator( 1418): flushDynamicLanguageModels()
,I/ConfigService( 1725): onCreate
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
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
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
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
,I/ConfigService( 1725): onDestroy
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
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
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
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
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311060, SEQNUM=4511, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9314, POWER_SUPPLY_CHARGE_COUNTER=-1048, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2482): Disconnected process message: 10, size: 0
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC

```
